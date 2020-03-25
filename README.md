# Description

This role configures a [nginx-prometheus-exporter](https://github.com/nginxinc/nginx-prometheus-exporter) service for exporting basic Nginx metrics.

# Configuration

```yaml
nginx_metrics_service_name: 'nginx-metrics'
nginx_metrics_nginx_status_port: 9112
nginx_metrics_listen_host: '0.0.0.0'
nginx_metrics_listen_port: 9113
```

# Example

```
 $ curl -s localhost:9113/metrics | grep '^nginx_' 
nginx_connections_accepted 1352
nginx_connections_active 3
nginx_connections_handled 1352
nginx_connections_reading 0
nginx_connections_waiting 2
nginx_connections_writing 1
nginx_http_requests_total 2606
nginx_up 1
```

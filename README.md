# Description

This role configures a [nginx-prometheus-exporter](https://github.com/nginxinc/nginx-prometheus-exporter) service for exporting basic Nginx metrics.

# Configuration

```yaml
nginx_metrics_service_name: 'nginx-metrics'
nginx_metrics_nginx_status_port: 9112
nginx_metrics_listen_host: '0.0.0.0'
nginx_metrics_listen_port: 9113
```

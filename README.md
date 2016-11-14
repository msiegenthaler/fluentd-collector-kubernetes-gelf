# Fluentd Log Collector For Kubernetes to Graylog

Collects the Kubernetes Logs and sends them to Graylog via GELF.


##Environment variables used by the image:
- `GELF_HOST` - hostname of your graylog instance
- `GELF_PORT` - GELF UDP port.

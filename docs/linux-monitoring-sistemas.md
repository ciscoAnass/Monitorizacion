# 3. Sistemas de Monitorización 📊

![Sistemas de Monitorización](/images/monitoring-systems.png)

## Prometheus 🔥
Sistema de monitorización de código abierto

![Prometheus Logo](/images/prometheus-logo.png)

### Características
- Recolección de métricas en tiempo real
- Almacenamiento de series temporales
- Lenguaje de consultas PromQL
- Alta disponibilidad y escalabilidad

### Ejemplo de Configuración
```yaml
global:
  scrape_interval: 15s
scrapes_configs:
  - job_name: 'node'
    static_configs:
      - targets: ['localhost:9100']
```

![Prometheus Dashboard](/images/prometheus-dashboard.jpg)

## Grafana 📈
Plataforma de visualización de métricas

![Grafana Logo](/images/grafana-logo.png)

### Características
- Dashboards personalizables
- Múltiples fuentes de datos
- Alertas y notificaciones
- Integración con Prometheus

### Dashboard Ejemplo
- Métricas de CPU
- Uso de memoria
- Tráfico de red
- Rendimiento de disco

![Grafana Dashboard](/images/grafana-dashboard.jpg)

## Nagios 🚨
Monitorización de infraestructura

![Nagios Logo](/images/nagios-logo.png)

### Características
- Chequeo de servicios y hosts
- Sistema de plugins extensible
- Alertas por correo/SMS
- Reporting detallado

![Nagios Dashboard](/images/nagios-dashboard.jpg)

[Volver al Índice](/README.md)

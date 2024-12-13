# 3. Sistemas de Monitorización 📊
## Prometheus 🔥
Sistema de monitorización de código abierto

![Prometheus Logo](https://i0.wp.com/unaaldia.hispasec.com/wp-content/uploads/2021/10/prometheus.png?fit=750%2C450&ssl=1)

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

## Grafana 📈
Plataforma de visualización de métricas

![Grafana Logo](/images/main.jpg)

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


## Nagios 🚨
Monitorización de infraestructura

### Características
- Chequeo de servicios y hosts
- Sistema de plugins extensible
- Alertas por correo/SMS
- Reporting detallado

![Nagios Dashboard](https://checkmk.com/application/files/9916/0456/2071/new_USX_blog.png)

[Volver al Índice](/README.md)

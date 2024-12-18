# 4. Mapa Conceptual de Monitorización 🗺️


## Diagrama de Flujo

```mermaid
graph TD
    A[Monitorización Linux] --> B[Comandos Básicos]
    A --> C[Herramientas Avanzadas]
    
    B --> D[ps]
    B --> E[top]
    B --> F[htop]
    B --> G[df]
    
    C --> H[Prometheus]
    C --> I[Grafana]
    C --> J[Nagios]
    
    D --> K[Monitoreo de Procesos]
    E --> K
    F --> K
    
    G --> L[Monitoreo de Disco]
    
    H --> M[Recolección de Métricas]
    I --> N[Visualización]
    J --> O[Alertas]
```


## Relaciones entre Herramientas

1. **Comandos Básicos**: Monitoreo inicial
2. **Herramientas Avanzadas**: Análisis profundo
3. **Integración**: Complemento entre sistemas


[Volver al Índice](/README.md)

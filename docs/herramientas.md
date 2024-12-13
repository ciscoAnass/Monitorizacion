# 2. Herramientas Propias del Sistema 🛠️

![Herramientas de Monitorización](/images/linux-monitoring-tools.png)

## Comandos de Monitorización de Procesos

### ps
```bash
ps aux  # Lista todos los procesos
```
- Muestra información detallada de procesos
- Opciones útiles: `aux`, `ef`


### top
```bash
top  # Monitor de procesos en tiempo real
```
- Vista dinámica de uso de recursos
- Ordenar por CPU, memoria, etc.


### htop
```bash
htop  # Monitor interactivo mejorado
```
- Interfaz más amigable que top
- Colorido y fácil de usar


### atop
```bash
atop  # Monitor avanzado de recursos
```
- Registra histórico de rendimiento
- Análisis detallado de recursos


## Comandos de Sistema de Archivos

### df
```bash
df -h  # Espacio en disco legible
```
- Muestra uso de espacios de disco
- Opción `-h` para formato humano


### du
```bash
du -sh *  # Tamaño de directorios
```
- Calcula espacio usado por directorios
- Resumen con `-sh`


### iostat
```bash
iostat -x  # Estadísticas de I/O extendidas
```
- Rendimiento de dispositivos de almacenamiento


## Comandos de Red

### tcpdump
```bash
tcpdump -i eth0  # Captura tráfico de red
```
- Análisis de paquetes de red
- Filtrado avanzado de tráfico


### netstat
```bash
netstat -tuln  # Conexiones de red
```
- Muestra conexiones y puertos


[Volver al Índice](/README.md)

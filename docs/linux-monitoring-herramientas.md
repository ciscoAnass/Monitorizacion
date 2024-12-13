# 2. Herramientas Propias del Sistema 🛠️

![Herramientas de Monitorización](/images/linux-monitoring-tools.png)

## Comandos de Monitorización de Procesos

### ps
```bash
ps aux  # Lista todos los procesos
```
- Muestra información detallada de procesos
- Opciones útiles: `aux`, `ef`

![Comando ps](/images/ps-command.jpg)

### top
```bash
top  # Monitor de procesos en tiempo real
```
- Vista dinámica de uso de recursos
- Ordenar por CPU, memoria, etc.

![Top Command](/images/top-command.jpg)

### htop
```bash
htop  # Monitor interactivo mejorado
```
- Interfaz más amigable que top
- Colorido y fácil de usar

![htop Command](/images/htop-command.jpg)

### atop
```bash
atop  # Monitor avanzado de recursos
```
- Registra histórico de rendimiento
- Análisis detallado de recursos

![atop Command](/images/atop-command.jpg)

## Comandos de Sistema de Archivos

### df
```bash
df -h  # Espacio en disco legible
```
- Muestra uso de espacios de disco
- Opción `-h` para formato humano

![df Command](/images/df-command.jpg)

### du
```bash
du -sh *  # Tamaño de directorios
```
- Calcula espacio usado por directorios
- Resumen con `-sh`

![du Command](/images/du-command.jpg)

### iostat
```bash
iostat -x  # Estadísticas de I/O extendidas
```
- Rendimiento de dispositivos de almacenamiento

![iostat Command](/images/iostat-command.jpg)

## Comandos de Red

### tcpdump
```bash
tcpdump -i eth0  # Captura tráfico de red
```
- Análisis de paquetes de red
- Filtrado avanzado de tráfico

![tcpdump Command](/images/tcpdump-command.jpg)

### netstat
```bash
netstat -tuln  # Conexiones de red
```
- Muestra conexiones y puertos

![netstat Command](/images/netstat-command.jpg)

[Volver al Índice](/README.md)

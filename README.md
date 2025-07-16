# YANG NETCONF App for Splunk

Esta aplicación contiene dashboards para visualizar métricas recolectadas vía NETCONF/YANG desde routers Cisco.

## Contenido
- Dashboards de CPU, memoria e interfaces
- Visualización de errores, tráfico y disponibilidad
- Basado en datos recolectados con modelos YANG como:
  - Cisco-IOS-XE-process-cpu-oper
  - Cisco-IOS-XE-memory-oper
  - Cisco-IOS-XE-interfaces-oper

## Requisitos
- Splunk Enterprise 9.x
- Tecnología Add-on (TA) correspondiente con sourcetypes `netconf:*`
- Datos indexados en el índice `yang`

## Instalación
Puedes instalar esta app:
1. Desde Splunk GUI (`Manage Apps > Install app from file`)
2. Copiando el directorio en `$SPLUNK_HOME/etc/apps/`
3. Desde Git: `git clone https://github.com/tu_usuario/yang-netconf-app.git`

## Autor
GerardoDLG

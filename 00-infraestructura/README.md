# Fase 00: Infraestructura de Red y Firewall (pfSense)

## Descripción
Implementación de un firewall/router pfSense en VMware Workstation para la segmentación y aislamiento del laboratorio de ciberseguridad.

## Segmentación de Red
- **WAN (em0):** Adaptador NAT con acceso a Internet.
- **LAN (em1):** Subred privada de administración para Kali Linux (192.168.1.1/24).
- **DMZ / OPT1 (em2):** Subred de pruebas aislada para los objetivos (Metasploitable 2) (192.168.2.1/24).

## Archivos en este directorio
- `configs/pfsense-backup.xml`: Respaldo completo de la configuración del firewall.
- `capturas/`: Evidencias del despliegue y estado de las interfaces.

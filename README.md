# cybersecurity-homelab
Laboratorio personal de ciberseguridad para monitoreo, detección de amenazas y análisis de incidentes utilizando Wazuh, pfSense, Ubuntu y Kali Linux.
## Tecnologías Utilizadas

- Wazuh
- pfSense
- Ubuntu
- Kali Linux
- VirtualBox

## Objetivos

- Monitorear eventos de seguridad.
- Detectar actividades sospechosas.
- Simular ataques en un entorno controlado.
- Analizar alertas e incidentes.
- Fortalecer habilidades prácticas en ciberseguridad.

## Arquitectura de Red

```text
                     Internet
                         |
                    WAN Network
                    10.0.2.15/24
                         |
                     pfSense
                ----------------
                |              |
                |              |
     LAN Network           OPT1 Network
   192.168.10.0/24       192.168.20.0/24
                |              |
                |              |
         Ubuntu + Wazuh     Kali Linux
        (Víctima)          (Atacante)
```

### Componentes

#### pfSense

- Segmentación de red.
- Control de tráfico.
- Administración de firewall.

#### Ubuntu + Wazuh

- Máquina víctima.
- Monitoreo de seguridad.
- Recolección y análisis de registros.

#### Kali Linux

- Simulación de ataques.
- Pruebas de seguridad.
- Actividades de reconocimiento.

## Escenarios de Seguridad

1. Escaneo de puertos con Nmap.
2. Ataque de fuerza bruta SSH.
3. Escalada de privilegios.

## Habilidades Desarrolladas

- Monitoreo de Seguridad.
- Detección de Amenazas.
- Análisis de Logs.
- Investigación de Incidentes.
- Segmentación de Redes.
- Administración de Firewall.
- Administración de Linux.

## Estado

Proyecto en desarrollo.

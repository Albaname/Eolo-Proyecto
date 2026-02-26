# EOLO-Proyecto: Sistema de Monitorización Eólica

Este proyecto implementa una infraestructura de microservicios para la captura, almacenamiento y visualización de telemetría de aerogeneradores en tiempo real.

-Arquitectura
El sistema se basa en cuatro componentes principales orquestados con Docker:
1. Python Simulator: Genera datos realistas de velocidad de viento y potencia.
2. InfluxDB: Base de datos de series temporales para almacenamiento.
3. Grafana: Dashboard interactivo para el análisis técnico.
4. Ubuntu Server: Sistema operativo base virtualizado.

-Requisitos Previos
Oracle VM VirtualBox con Ubuntu Server instalado.
Docker y Docker Compose:
  ```bash
  sudo apt update && sudo apt install docker.io docker-compose -y

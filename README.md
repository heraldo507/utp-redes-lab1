# Laboratorio #1: Fundamentos de Redes y Captura de Paquetes (UTP)

Repositorio académico correspondiente a las prácticas iniciales de la **Licenciatura en Ciberseguridad** en la **Universidad Tecnológica de Panamá (UTP)**.

## 1. Propósito del Laboratorio
Comprender el funcionamiento del modelo OSI/TCP-IP mediante la simulación de una red local básica y el análisis de tráfico de paquetes para identificar protocolos comunes (ICMP, ARP, HTTP) y buenas prácticas de seguridad perimetral.

## 2. Topología y Entorno de Prueba
- **Simulador de Red:** Cisco Packet Tracer
- **Analizador de Protocolos:** Wireshark
- **Dispositivos configurados:** 1 Router, 1 Switch Capa 2 y 2 Host finales (PC1 y PC2) en subred `192.168.1.0/24`.

## 3. Procedimiento Realizado
1. Diseño de la topología lógica y asignación de direccionamiento IP estático en los equipos terminales.
2. Verificación de conectividad extremo a extremo mediante pruebas de `ping` (protocolo ICMP).
3. Captura e inspección de tramas para validar el encapsulamiento de datos y descartar tráfico no autorizado.

## 4. Licencia
Este proyecto está distribuido bajo la licencia **MIT** incluida en este repositorio.

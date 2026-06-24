<!-- markdownlint-disable MD033 -->

# ConectaMesa

## Cómo funciona

<p align="center">
  <img src="docs/capturas/servicio/asifuncionaelservicio.png" width="1000">
</p>

**Sistema de gestión operativa para hostelería que combina carta digital, PDA para camareros, TPV y monitor de cocina en una única plataforma.**

Proyecto iniciado como Trabajo Final de DAM y actualmente en evolución.

---

## ¿Qué es ConectaMesa?

ConectaMesa no es únicamente una carta digital ni un TPV.
Es un sistema diseñado para coordinar clientes, camareros, cocina y caja dentro de un mismo flujo operativo.
Su objetivo es mejorar la gestión de pedidos sin perder el control del servicio.

---

## Problema

Durante las pruebas realizadas en establecimientos de hostelería observé un problema común:
Muchos sistemas de autocomanda permiten que los clientes envíen pedidos directamente a cocina.
Cuando varios clientes realizan pedidos simultáneamente aparecen problemas operativos:

- Saturación de cocina
- Acumulación de tickets
- Pérdida de control del servicio
- Errores en pedidos
- Aumento de tiempos de espera

---

## Solución

ConectaMesa mantiene la digitalización del proceso sin eliminar el papel operativo del camarero.

El cliente puede consultar la carta y realizar pedidos desde su dispositivo móvil, pero el sistema incorpora mecanismos de control que regulan cuándo y cómo los pedidos avanzan hacia cocina y barra.

---

## Capturas

### AutoComanda Comensal

<p align="center">
  <img src="docs/capturas/autocomanda/autocomanda.jpeg" width="250">
</p>

### PDA Camarero

<p align="center">
  <img src="docs/capturas/pda/pda_V22.jpg" width="250">
</p>

### TPV

<p align="center">
  <img src="docs/capturas/tpv/tpv.png" width="800">
</p>

---

## Diferenciador

A diferencia de muchos sistemas de autocomanda, ConectaMesa no envía automáticamente los pedidos a cocina.
El cliente puede realizar pedidos desde su dispositivo móvil, pero el personal mantiene el control sobre cuándo una comanda entra en producción.
Este enfoque reduce saturaciones, evita avalanchas de tickets y mejora la coordinación entre sala, cocina y barra.

---

## Ecosistema

| Cliente                      | PDA Camarero           | TPV                      | Cocina y Barra           |
| ---------------------------- | ---------------------- | ------------------------ | ------------------------ |
| Acceso mediante QR           | Gestión de mesas       | Gestión de mesas activas | Recepción de comandas    |
| Gestión mediante PIN de mesa | Gestión de pedidos     | Operaciones de cobro     | Visualización de pedidos |
| Carta digital                | Envío de comandas      | Gestión de pedidos       | Gestión de estados       |
| Creación de pedidos          | Supervisión operativa  | Control del servicio     | Impresión térmica        |
| Consulta de cuenta           | Gestión de incidencias |                          |                          |

--- 
## Arquitectura

### Backend
![Java](https://img.shields.io/badge/Java-17-orange)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-green)
![JPA](https://img.shields.io/badge/JPA-Hibernate-blue)

### Frontend
![Flutter](https://img.shields.io/badge/Flutter-Framework-blue)
![Web](https://img.shields.io/badge/Web-Supported-success)
![Desktop](https://img.shields.io/badge/Desktop-Supported-success)
![Mobile](https://img.shields.io/badge/Mobile-Supported-success)

### Base de Datos
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue)

### Infraestructura
![Docker](https://img.shields.io/badge/Docker-Containerization-blue)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-Orchestration-blue)
![Nginx](https://img.shields.io/badge/Nginx-Reverse_Proxy-green)
---

## Componentes Principales

| Componente            | Responsabilidades                                                                     |
| --------------------- | ------------------------------------------------------------------------------------- |
| Gestión de Mesas   | Apertura de mesa, gestión de comensales, generación de PIN y control de sesión activa |
| Gestión de Pedidos | Creación y gestión de pedidos, líneas de pedido, confirmación y estados de negocio    |
| Gestión Operativa  | Coordinación entre sala, cocina y barra, monitorización y validaciones de servicio    |
| Gestión de Pagos   | Solicitud de cuenta, registro de cobros y liberación de mesa                          |

---


---

## Aspectos Técnicos Trabajados

- Diseño de APIs REST
- Arquitectura cliente-servidor
- Modelado de dominio
- PostgreSQL
- JPA / Hibernate
- Dockerización
- Flutter
- Gestión de estados de negocio
- Integración TPV + PDA + Cliente
- Impresión térmica ESC/POS
- Git y control de versiones

---

## Mi Participación

Proyecto desarrollado como iniciativa personal.

Responsabilidades principales:

- Diseño funcional del producto
- Análisis de necesidades operativas de hostelería
- Arquitectura backend
- Desarrollo de APIs REST
- Diseño de base de datos PostgreSQL
- Desarrollo frontend Flutter
- Dockerización de la plataforma
- Definición de reglas de negocio
- Diseño de flujos operativos

---

## Tecnologías Utilizadas

**Backend:** Java · Spring Boot · Spring Data JPA · Hibernate · Lombok

**Base de Datos:** PostgreSQL

**Frontend:** Flutter · Dart

**Infraestructura:** Docker · Docker Compose · Nginx

**Herramientas:** Git · GitHub · Postman

---

## Repositorio Showcase

Este repositorio es una versión Showcase creada con fines profesionales.

Su objetivo es mostrar la arquitectura, funcionalidades y tecnologías utilizadas en el proyecto sin exponer componentes internos de la plataforma completa.

---

## Contacto

**LinkedIn -**  www.linkedin.com/in/anibal-solano-f

**GitHub -** https://github.com/jav-anibal

---
**Desarrollado por Anibal Solano**
DAM · ASIR · Backend Developer
# 🍽️ ConectaMesa

Sistema de comanda digital y TPV para hostelería desarrollado con Java, Spring Boot, PostgreSQL, Flutter y Docker.
![Funcionamiento](docs/asifuncionaelservicio.png)

> Proyecto desarrollado inicialmente como Trabajo Final de DAM y actualmente evolucionando hacia una plataforma completa para la gestión de bares, cafeterías y restaurantes.

---

# Problema

Muchos negocios de hostelería siguen dependiendo de procesos manuales para la toma de pedidos, gestión de mesas y control de comandas.

Esto provoca:

* Errores en pedidos
* Mayor carga de trabajo para camareros
* Menor velocidad de atención
* Dificultad para escalar operaciones

ConectaMesa nace para digitalizar este flujo de trabajo mediante una plataforma integrada.

---

# Solución

ConectaMesa permite conectar clientes, camareros, cocina y personal de caja dentro de un mismo sistema.

El flujo principal es:

1. El cliente escanea un código QR.
2. Accede a la mesa mediante un PIN.
3. Consulta la carta digital.
4. Realiza pedidos desde su dispositivo.
5. Cocina o barra recibe las comandas.
6. El personal gestiona pedidos y cobros desde TPV o PDA.

---

# Funcionalidades

## Cliente

* Acceso mediante QR
* Unión a mesa mediante PIN
* Carta digital
* Realización de pedidos
* Consulta de cuenta

## Personal

* Gestión de mesas
* Gestión de pedidos
* Control de estados
* PDA para camareros
* TPV para cobros

## Cocina / Barra

* Recepción de comandas
* Gestión de preparación
* Impresión térmica

---

# Arquitectura

## Frontend

* Flutter Web
* Flutter Desktop
* Flutter Mobile

## Backend

* Java 17
* Spring Boot
* Spring Data JPA
* Hibernate

## Base de Datos

* PostgreSQL

## Infraestructura

* Docker
* Docker Compose

---

# Tecnologías utilizadas

| Área                 | Tecnologías                       |
| -------------------- | --------------------------------- |
| Backend              | Java, Spring Boot, JPA, Hibernate |
| Frontend             | Flutter                           |
| Base de Datos        | PostgreSQL                        |
| Infraestructura      | Docker, Docker Compose            |
| Control de versiones | Git, GitHub                       |

---

# Capturas

## Carta digital

![Carta](docs/capturas/carta.png)

## Gestión de mesas

![Mesas](docs/capturas/mesas.png)

## TPV

![TPV](docs/capturas/tpv.png)

## Cocina

![Cocina](docs/capturas/cocina.png)

---

# Evolución del proyecto

Actualmente ConectaMesa continúa evolucionando hacia una solución TPV completa para hostelería.

Líneas de desarrollo:

* Gestión avanzada de usuarios
* Roles y permisos
* Seguridad y autenticación
* Estadísticas de negocio
* Gestión de inventario
* Multiestablecimiento
* Plataforma SaaS

---

# Nota

Este repositorio es una versión Showcase destinada a presentar la arquitectura, funcionalidades y visión del producto.

El código fuente principal permanece privado.

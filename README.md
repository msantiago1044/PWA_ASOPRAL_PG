# Lurepa – PWA para la comercialización de arepas de huevo (ASOPRAL – Luruaco)

Este repositorio contiene el código y la documentación técnica de **Lurepa**, una **Progressive Web Application (PWA)** desarrollada en **Oracle APEX** para la **Asociación de Productoras de Arepas de Huevo (ASOPRAL)** del municipio de Luruaco, Atlántico – Colombia.

El proyecto busca **digitalizar el proceso de comercialización** de la arepa de huevo y productos relacionados, conectando directamente a las productoras con sus clientes finales mediante un canal digital seguro, escalable y fácil de usar.

---

## 🎯 Objetivo del proyecto

**Diseñar, implementar y desplegar** una PWA en Oracle APEX que:

- Optimice la **gestión de pedidos** y productos de ASOPRAL.
- Permita **ampliar el alcance del mercado** más allá del entorno local.
- Contribuya a la **preservación de la tradición gastronómica** de Luruaco mediante la transformación digital.

---

## ✨ Funcionalidades principales

- 👥 **Gestión de usuarios y roles**
  - Cliente
  - Productora
  - Administrador

- 🛒 **Catálogo de productos**
  - Listado de arepas de huevo y productos relacionados.
  - Visualización de precios y descripción básica.

- 🧺 **Carrito de compras**
  - Agregar productos al carrito.
  - Confirmación de pedido.

- 📦 **Gestión de pedidos**
  - Registro de pedidos.
  - Actualización de estados (pendiente, enviado, entregado, cerrado).

- 🔔 **Notificaciones básicas**
  - Confirmación de pedido.
  - Actualización de estado.

- 📱 **Características PWA**
  - Acceso desde navegador móvil y escritorio.
  - Interfaz responsiva.
  - Aplicación instalable desde el navegador (PWA).

---

## 🧱 Tecnologías utilizadas

- **Oracle APEX** (entorno de desarrollo low-code).
- **Oracle Database** (modelo relacional para usuarios, productos, pedidos, bitácoras).
- **PL/SQL** (lógica de negocio y procesos).
- **HTML5 / CSS3 / JavaScript** (interfaz de usuario).
- Enfoque de desarrollo con **metodología ágil XP (Extreme Programming)**.

---

## 🌐 Demo del prototipo funcional

La versión desplegada de la PWA se encuentra en el siguiente enlace:

👉 **Lurepa – PWA ASOPRAL**  
https://oracleapex.com/ords/r/pwa_asopral_col/lurepas/inicio?tz=-5:00

> El acceso y las credenciales pueden estar restringidos según el entorno de pruebas o producción definido para el proyecto.

---

## 🗂 Estructura del repositorio

> _Esta estructura es una guía sugerida; puede ajustarse a la forma final del proyecto._

```text
.
├── db/                 # Scripts de base de datos (tablas, vistas, packages PL/SQL)
├── apex/               # Export(s) de la aplicación Oracle APEX
├── docs/               # Documentación técnica y manuales
├── assets/             # Imágenes, íconos y recursos gráficos
├── scripts/            # Scripts auxiliares (carga inicial, utilidades)
└── README.md           # Este archivo

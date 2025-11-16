# LuruArepa – PWA para la comercialización de arepas de huevo (ASOPRAL – Luruaco)

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

👉 **LuruArepa – PWA ASOPRAL**  
https://oracleapex.com/ords/r/pwa_asopral_col/lurepas/inicio?tz=-5:00

> El acceso y las credenciales pueden estar restringidos según el entorno de pruebas o producción definido para el proyecto.

---

## 📁 Contenido del repositorio

Actualmente el repositorio incluye:

- `README.md`  
  Documento de descripción del proyecto y guía de uso del repositorio.

- `f195700 (3).sql`  
  Archivo **exportado desde Oracle APEX** que contiene la aplicación Lurepa (prototipo funcional).  
  Este archivo se utiliza para **importar la aplicación en otro workspace de Oracle APEX**.

### 🔓 Cómo abrir/descargar `f195700 (3).sql` desde GitHub

GitHub no puede mostrar en pantalla este archivo porque es grande, pero sí permite descargarlo:

1. Ingresar al repositorio:  
   `https://github.com/msantiago1044/PWA_ASOPRAL_PG`
2. En la lista de archivos, hacer clic en **`f195700 (3).sql`**.
3. En la parte central aparecerá un mensaje indicando que el archivo es muy grande.  
   Debajo, hacer clic en **`View raw`**.
4. El navegador descargará el archivo `.sql`.  
   - Guardarlo en su equipo (por ejemplo, en la carpeta `Descargas`).
   - Ese archivo será el que se importará en Oracle APEX.

---
## 🚀 Instalación y despliegue en Oracle APEX

### 1. Clonar o descargar el repositorio (opcional)

Puedes clonar el repositorio o simplemente descargar el archivo `.sql`:

```bash
git clone https://github.com/msantiago1044/PWA_ASOPRAL_PG.git
cd PWA_ASOPRAL_PG

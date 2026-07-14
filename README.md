# Sistema de Inventario CBTIS No. 110

Sistema web desarrollado como proyecto de Estadías Profesionales para el **Centro de Bachillerato Tecnológico Industrial y de Servicios No. 110 (CBTIS 110)**.

La aplicación fue diseñada para optimizar la administración del inventario institucional mediante una plataforma web que permite registrar, organizar y dar seguimiento a los bienes del plantel de forma segura, eficiente y centralizada.

---

## English

**CBTIS No. 110 Inventory System** is a web application developed as a professional internship project to improve institutional inventory management.

The system centralizes asset registration, organization and tracking through a secure and user-friendly platform built with Laravel and MySQL.

---

# Descripción

El proyecto surge como una solución para mejorar el control del inventario dentro del CBTIS No. 110, sustituyendo procesos manuales por una plataforma digital que facilita la administración de equipos, materiales y activos pertenecientes a los distintos talleres del plantel.

El sistema fue desarrollado siguiendo la arquitectura **Modelo-Vista-Controlador (MVC)** utilizando Laravel como framework principal y MySQL como gestor de base de datos.

---

# Características

- Autenticación de usuarios.
- Panel principal de administración.
- Registro de artículos.
- Gestión de categorías.
- Administración de talleres.
- Gestión de usuarios.
- Historial de movimientos.
- Búsqueda de inventario.
- Generación de códigos de barras para la identificación de activos.
- Interfaz responsiva.

---

# Tecnologías utilizadas

| Tecnología | Descripción |
|------------|-------------|
| Laravel 12 | Framework Backend |
| PHP 8.2 | Lenguaje de programación |
| MySQL | Base de datos |
| HTML5 | Estructura de la interfaz |
| CSS3 | Diseño |
| JavaScript | Funcionalidades del cliente |
| Bootstrap 5 | Framework CSS |
| Blade | Motor de plantillas |
| Git | Control de versiones |

---

# Arquitectura

El sistema fue desarrollado utilizando la arquitectura **MVC (Model-View-Controller)**.

```
Usuario
     │
     ▼
 Controladores
     │
     ▼
   Modelos
     │
     ▼
 Base de Datos
     ▲
     │
   Vistas
```

---

# Estructura del proyecto

```
app/
bootstrap/
config/
database/
public/
resources/
routes/
storage/
```

---

# Capturas

Las siguientes imágenes muestran algunas de las principales funciones del sistema.

- Inicio de sesión
- Dashboard
- Inventario
- Registro de artículos
- Categorías
- Talleres
- Usuarios
- Historial
- Código de barras

> Las capturas serán agregadas conforme avance el desarrollo del proyecto.

---

# Instalación

Clonar el repositorio.

```bash
git clone https://github.com/TU-USUARIO/inventario-cbtis110.git
```

Instalar dependencias.

```bash
composer install
```

Copiar el archivo de configuración.

```bash
cp .env.example .env
```

Generar la llave de Laravel.

```bash
php artisan key:generate
```

Ejecutar migraciones.

```bash
php artisan migrate
```

Iniciar el servidor.

```bash
php artisan serve
```

---

# Objetivos del proyecto

- Digitalizar el inventario institucional.
- Mejorar el control de activos.
- Facilitar la administración de bienes.
- Optimizar la organización de talleres.
- Reducir errores en el registro del inventario.
- Automatizar la identificación mediante códigos de barras.

---

# Trabajo futuro

El sistema fue diseñado para permitir futuras ampliaciones, entre ellas:

- Exportación de reportes en PDF y Excel.
- Sistema de préstamos de equipo.
- Estadísticas del inventario.
- Notificaciones automáticas.
- Registro mediante lector de código de barras.
- Respaldo automático de la información.

---

# Sobre el proyecto

Este sistema fue desarrollado como parte de las **Estadías Profesionales** de la carrera de **Tecnologías de la Información**, con el propósito de aportar una solución tecnológica a una necesidad real del CBTIS No. 110.

Durante el desarrollo se aplicaron conceptos de análisis de requerimientos, diseño de bases de datos, arquitectura MVC, desarrollo web y administración de sistemas de información.

---

# Autor

**Dulce Ximena Molina Segovia**

Estudiante de Tecnologías de la Información

Durango, México

---

## Licencia

Este proyecto fue desarrollado con fines académicos y educativos.

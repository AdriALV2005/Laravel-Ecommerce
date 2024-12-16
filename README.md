
# 🎯 Purrfect Shop - Plataforma de E-commerce

  

**Purrfect Shop** es una aplicación de e-commerce desarrollada en Laravel. Diseñada para gestionar productos, categorías, marcas, cupones, órdenes y usuarios de forma eficiente, cuenta con un panel de administración intuitivo para administrar cada aspecto del negocio. 🚀

---

  

## 📸 Capturas de Pantalla

  

¡A continuación puedes ver una vista previa de la aplicación! No olvides añadir tus propias imágenes aquí para mostrar cómo luce:

  
<img src="https://i.ibb.co/mTHgd24/Captura-de-pantalla-2024-12-16-020623.png" alt="Purrfect Shop" style="width: 100%; height: auto;" />
<img src="https://i.ibb.co/wK6Y80R/Captura-de-pantalla-2024-12-16-021056.png" alt="Purrfect Shop" style="width: 100%; height: auto;" />

  

---


## ⚙️ Instalación

### Requisitos Previos

- 🐘 **PHP 8.1 o superior**  
- 🎼 **Composer**  
- 🟢 **Node.js y npm** (para la compilación de assets con Laravel Mix)  
- 🗄️ **MySQL** u otro sistema de base de datos compatible  

### Pasos

1. Clona el repositorio:

   ```bash
   git clone https://github.com/AdriALV2005/Laravel-Ecommerce
1. Navega al directorio del proyecto::

   ```bash
   cd Laravel-Ecommerce
1. Instala las dependencias de PHP:

   ```bash
   composer install
1. Instala las dependencias de Node.js:

   ```bash
   npm install
1. Copia el archivo de entorno y configura las variables necesarias:

   ```bash
   cp .env.example .env
1. Configura las variables de entorno en el archivo .env, incluyendo la conexión a la base de datos:

   ```bash
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=purrfect_shop
    DB_USERNAME=tu_usuario
    DB_PASSWORD=tu_contraseña
1. Genera la clave de aplicación:

   ```bash
   php artisan key:generate
1. Ejecuta las migraciones y seeders:

   ```bash
   php artisan migrate --seed
1. Compila los assets:

   ```bash
   npm run dev

1. Inicia el servidor local:

   ```bash
   php artisan serve

## ✨ Características

  

- 🛍️ Gestión de Productos: Crea, edita y elimina productos, con imágenes y descripciones.
- 🗂️ Categorías y Marcas: Clasifica productos en categorías y gestiona sus marcas.
- 🎟️ Cupones: Aplica descuentos a los pedidos con cupones personalizables.
- 📦 Gestión de Pedidos: Visualiza, actualiza y administra pedidos de clientes.
- 📊 Dashboard Administrativo: Resumen de estadísticas clave del negocio.
- 🔐 Autenticación y Roles: Acceso seguro con roles para administradores y usuarios.
- 📱 Diseño Responsivo: Totalmente optimizado para dispositivos móviles.
  

---

  

## 🛠️ Tecnologías

  

-  **Laravel**: Framework PHP para desarrollo web.

-  **Blade**: Motor de plantillas de Laravel.

-  **MySQL**: Sistema de gestión de bases de datos.

-  **Tailwind CSS**: Framework CSS para diseño rápido.

-  **Intervention Image**: Manejo de imágenes.

-  **Carbon**: Biblioteca de manejo de fechas en PHP.
  

---

  

## 🚀 Uso

### Panel de Administración

1.  Accede al panel administrativo en http://localhost:8000/admin.
2.  Inicia sesión con las credenciales del administrador (definidas en el seeder o manualmente).
3.  Gestiona productos, categorías, marcas, cupones y pedidos desde el panel.
  

### Funciones de Usuario

1.  Los usuarios pueden registrarse e iniciar sesión.
2.  Explora y añade productos al carrito.
3.  Aplica cupones y realiza compras.
  

---

  

## 🗂️ Estructura de Carpetas

  

La estructura del proyecto sigue un diseño modular que facilita el desarrollo y mantenimiento.

```
├── app/Http/Controllers/
│   ├── AdminController.php
│   ├── CartController.php
│   ├── HomeController.php
│   ├── ShopController.php
│   ├── UserController.php
│   └── WishlistController.php
├── database/migrations/
├── public/
├── resources/views/
│   ├── admin/
│   ├── cart/
│   ├── layouts/
│   ├── shop/
│   └── user/
├── routes/
│   └── web.php
└── .env.example

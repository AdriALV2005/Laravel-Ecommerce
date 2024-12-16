
# 🎯 Adri Tasks - Aplicación de Gestión de Tareas

  

**Adri Tasks** es una poderosa aplicación de gestión de tareas construida con Next.js, diseñada para ayudarte a organizar y priorizar tu trabajo de manera eficiente. Con una interfaz moderna y fácil de usar, ¡mejora tu productividad ahora! 🚀

  

🌐 **[Aplicación Desplegada Aquí](https://next-track-three.vercel.app/)**

  

---

  

## 📸 Capturas de Pantalla

  

¡A continuación puedes ver una vista previa de la aplicación! No olvides añadir tus propias imágenes aquí para mostrar cómo luce:

  
<img src="https://i.ibb.co/NKcspXz/Captura-de-pantalla-2024-10-23-160131.png" alt="Adri Tasks" style="width: 100%; height: auto;" />

  

---


## ⚙️ Instalación

### Requisitos Previos

- ⚡ Node.js (versión 14 o superior)
- 📦 npm o yarn

### Pasos

1. Clona el repositorio:

   ```bash
   git clone https://github.com/AdriALV2005/Next-Track.git
1. Navega al directorio del proyecto::

   ```bash
   cd Next-Track
1. Instala las dependencias::

   ```bash
   npm install
1. Crea un archivo `.env.local` y configura tus variables de entorno:

   ```bash
   NEXT_PUBLIC_APP_URL=http://localhost:3000 NEXT_PUBLIC_APPWRITE_ENDPOINT=<tu-endpoint-de-appwrite> NEXT_PUBLIC_APPWRITE_PROJECT=<tu-id-del-proyecto> NEXT_PUBLIC_APPWRITE_DATABASE_ID=<tu-id-de-la-base-de-datos> NEXT_PUBLIC_APPWRITE_WORKSPACES_ID=<tu-id-de-workspaces> NEXT_PUBLIC_APPWRITE_MEMBERS_ID=<tu-id-de-miembros> NEXT_PUBLIC_APPWRITE_PROJECTS_ID=<tu-id-de-proyectos> NEXT_PUBLIC_APPWRITE_TASKS_ID=<tu-id-de-tareas> NEXT_PUBLIC_APPWRITE_IMAGES_BUCKET_ID=<tu-id-del-bucket-de-imágenes> NEXT_APPWRITE_KEY=<tu-clave-appwrite>
1. Ejecuta el servidor de desarrollo:

   ```bash
   npm run dev
## ✨ Características

  

- 🔐 **Autenticación Segura**: Inicio de sesión y registro usando correo electrónico/contraseña, con integración de OAuth (Google, GitHub).

- 📝 **Gestión de Tareas**: Crea, edita y elimina tareas. Organiza tus tareas por proyecto y prioridad.

- 📊 **Analíticas de Proyectos**: Visualiza estadísticas sobre tus tareas, como el total de tareas, tareas completadas, y vencidas.

- 📱 **Diseño Responsivo**: Totalmente optimizado para dispositivos móviles y de escritorio.

- 🌙 **Modo Oscuro**: Cambia entre modo claro y oscuro para tu preferencia visual.

- 🗂️ **Gestión de Proyectos**: Administra múltiples proyectos y sus respectivas tareas.

  

---

  

## 🛠️ Tecnologías

  

-  **Next.js**: Framework de React para renderizado del lado del servidor y generación de sitios estáticos.

-  **React**: Librería JavaScript para construir interfaces de usuario.

-  **TypeScript**: Añade tipos estáticos a JavaScript para mejorar la robustez del código.

-  **Tailwind CSS**: Framework de CSS basado en utilidades para un desarrollo rápido de interfaces.

-  **React Query**: Gestión del estado y de las consultas a la API en aplicaciones React.

-  **Appwrite**: Servidor backend para gestionar autenticación y bases de datos.

-  **Lucide React Icons**: Librería de íconos.

  

---

  

## 🚀 Uso

  

Una vez configuradas las variables de entorno e instaladas las dependencias, puedes ejecutar la aplicación en modo desarrollo o producción, utilizando los comandos adecuados.

  

### Autenticación

  

La aplicación soporta autenticación con Google y GitHub utilizando OAuth, además del registro tradicional con correo electrónico y contraseña.

  

### Analíticas

  

Cada espacio de trabajo y proyecto tiene un panel de analíticas que muestra datos clave como:

  

- 📊 Total de tareas

- 👤 Tareas asignadas

- ✅ Tareas completadas

- ⏰ Tareas vencidas

  

---

  

## 🗂️ Estructura de Carpetas

  

La estructura del proyecto sigue un diseño modular que facilita el desarrollo y mantenimiento.

```
├── components
│   ├── analytics/
│   ├── auth/
│   ├── dashboard/
│   ├── tasks/
│   └── ui/
├── features
│   ├── auth/
│   ├── members/
│   ├── projects/
│   └── tasks/
├── pages
│   ├── api/
│   ├── dashboard/
│   └── sign-in/
├── public/
└── styles/
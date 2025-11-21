# 🚀 Notion Clone – Aplicación Fullstack con Next.js 13, Convex, Tailwind CSS y Clerk

Un clon avanzado de Notion desarrollado con tecnologías modernas del ecosistema JavaScript.  
Este proyecto integra una base de datos en tiempo real, editor estilo Notion, soporte de archivos, autenticación y una interfaz totalmente responsiva y optimizada.

---

## ✨ Características destacadas

- 🔄 **Base de datos en tiempo real** con Convex
- 📝 **Editor inspirado en Notion** (bloques dinámicos y contenido enriquecido)
- 🌗 **Modo claro y oscuro**
- 🌿 **Documentos anidados ilimitados**
- 🗑️ **Papelera con eliminación suave y recuperación**
- 🔐 **Autenticación completa con Clerk**
- 📁 **Subida, eliminación y reemplazo de archivos**
- ⭐ **Iconos personalizables para documentos (sincronización en vivo)**
- 📚 **Sidebar expandible/colapsable**
- 📱 **Diseño responsive para móviles y tablets**
- 🌐 **Publicación de documentos como páginas web**
- 🖼️ **Imágenes de portada para cada documento**

---

## 🛠️ Tecnologías utilizadas

- **Next.js 13** (App Router)
- **React**
- **Convex** (real-time backend)
- **Tailwind CSS**
- **Clerk** (autenticación)
- **Edge Store** (almacenamiento de archivos)

---

## 📋 Requisitos previos

Asegúrate de tener instalada la versión recomendada de Node:

```bash
node -v
# Requiere Node 18.x o superior
```

---

## 📥 Clonar el proyecto

```bash
git clone https://github.com/AntonioErdeljac/notion-clone-tutorial.git
```

> Si este es tu proyecto personal, reemplaza la URL con tu propio repositorio.

---

## 📦 Instalar dependencias

```bash
npm install
```

---

## 🔧 Configuración del archivo `.env`

Crea un archivo `.env` en la raíz del proyecto y define tus claves de Convex, Clerk y Edge Store:

```bash
# Convex
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

# Edge Store
EDGE_STORE_ACCESS_KEY=
EDGE_STORE_SECRET_KEY=
```

---

## ⚙️ Inicialización de Convex

```bash
npx convex dev
```

Esto iniciará el backend en tiempo real para el proyecto.

---

## ▶️ Ejecutar el servidor de desarrollo

```bash
npm run dev
```

La aplicación estará disponible en:

```
http://localhost:3000
```

---

## 📄 Licencia

Este proyecto está destinado para fines educativos y de desarrollo personal.  
Eres libre de modificarlo, extenderlo y adaptarlo a tus necesidades.

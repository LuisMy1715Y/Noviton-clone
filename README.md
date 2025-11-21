# 🚀 Noviton – Clon tipo Notion con Next.js 13, Convex, Tailwind CSS y Clerk

Noviton es un clon moderno inspirado en Notion, desarrollado con tecnologías actuales del ecosistema JavaScript.  
El proyecto integra una base de datos en tiempo real, un editor avanzado, autenticación, manejo de archivos y una interfaz totalmente optimizada.

---

## ✨ Características principales

- 🔄 **Base de datos en tiempo real** (Convex)
- 📝 **Editor tipo Notion** con contenido enriquecido
- 🌗 **Modo claro y oscuro**
- 🌿 **Documentos hijos ilimitados**
- 🗑️ **Papelera con restauración**
- 🔐 **Autenticación con Clerk**
- 📁 **Subida, eliminación y reemplazo de archivos**
- ⭐ **Iconos personalizados en documentos**
- 📚 **Barra lateral expandible y colapsable**
- 📱 **Interfaz completamente responsive**
- 🌐 **Publicación de documentos de forma pública**
- 🖼️ **Imagen de portada por documento**

---

## 🛠️ Tecnologías utilizadas

- **Next.js 13** (App Router)
- **React**
- **Convex**
- **Tailwind CSS**
- **Clerk**
- **Edge Store**

---

## 📋 Requisitos previos

Asegúrate de usar Node.js versión 18 o superior:

```bash
node -v
```

---

## 📥 Clonar el repositorio

```bash
git clone https://github.com/LuisMy1715Y/Noviton-clone.git
```

---

## 📦 Instalación de dependencias

```bash
npm install
```

---

## 🔧 Archivo de entorno `.env`

Crea un archivo `.env` en la raíz del proyecto e incluye tus claves:

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

## ⚙️ Inicializar el backend de Convex

```bash
npx convex dev
```

---

## ▶️ Ejecutar el entorno de desarrollo

```bash
npm run dev
```

Accede a la aplicación en:

```
http://localhost:3000
```

---

## 📄 Licencia

Este proyecto está orientado a aprendizaje y uso personal.  
Eres libre de modificarlo o extenderlo según tus necesidades.

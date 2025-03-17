# 🚀 Proyecto Astro con Tailwind CSS y Vercel  

Este es un proyecto construido con **Astro**, estilizado con **Tailwind CSS**, y desplegado en **Vercel**.  

## 🔧 Tecnologías usadas  

- **[Astro](https://astro.build/)** → Framework optimizado para generar sitios estáticos rápidos.  
- **[Tailwind CSS](https://tailwindcss.com/)** → Framework de utilidades para estilizar rápidamente la UI.  
- **[Vercel](https://vercel.com/)** → Plataforma para desplegar proyectos de frontend de forma rápida y eficiente.  

## 📁 Estructura del proyecto  

```text
/
├── public/            # Archivos estáticos
│   └── favicon.svg
├── src/
│   ├── assets/       # SVGs y PNGs
│   ├── components/    # Componentes reutilizables
│   ├── layouts/       # Plantillas y componentes de diseño
│   │   └── Layout.astro
│   ├── pages/         # Páginas principales del sitio
│   │   └── index.astro
│   ├── scripts/       # Script del cuerpo de la página animada
│   │   └── scroll-reveal.js
│   └── styles/        # Archivos de estilos adicionales
├── astro.config.mjs   # Configuración de Astro
└── package.json       # Dependencias y scripts del proyecto
```

## 🛠️ Instalación y uso  

1️⃣ **Clona el repositorio:**  
```sh
git clone https://github.com/nicoToscano/portfolio.git
cd tu-repo
```

2️⃣ **Instala las dependencias:**  
```sh
npm install
```

3️⃣ **Ejecuta el servidor en local:**  
```sh
npm run dev
```

4️⃣ **Construye la versión de producción:**  
```sh
npm run build
```

## 🚀 Despliegue en Vercel  

El proyecto está desplegado en **Vercel**. Puedes hacer deploy fácilmente con el siguiente comando:  

```sh
npm install -g vercel
vercel
```

O puedes conectarlo a **Vercel** a través de la interfaz web en [vercel.com](https://vercel.com).  

## 🌟 Contribuciones  

Si quieres mejorar el proyecto, siéntete libre de hacer un **fork**, crear una rama y hacer un **pull request**.  

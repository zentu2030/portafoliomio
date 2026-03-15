# Portfolio Profesional - Juan Jose Gonzales Centurión

Este es un proyecto de portafolio personal altamente optimizado para SEO y Core Web Vitals, construido con **Astro** y **Tailwind CSS**.

## Características Principales

- 🚀 **Rendimiento**: LCP < 1.5s, CLS ~ 0, 100/100 Lighthouse score (en producción).
- 🔍 **SEO On-Page**: Metatags dinámicos, Open Graph, Twitter Cards y Sitemap automático.
- 🛠️ **Arquitectura**: Astro 6.0 (Static Mode), Tailwind v4, Schema.org (JSON-LD).
- 📱 **Mobile First**: Diseño responsivo y accesible (WCAG AA).
- 🎨 **Estética Premium**: Uso de fuentes modernas (Outfit & Inter), efectos de cristal (glassmorphism) y animaciones sutiles.

## Estructura del Proyecto

- `/src/pages`: Rutas de la web (Home, Sobre Mí, Experiencia, etc.).
- `/src/components`: Componentes UI reutilizables.
- `/src/layouts`: Estructura base con SEO.
- `/src/data`: Datos personales en formato JSON para fácil mantenimiento.

## Despliegue en Vercel

Este proyecto está configurado para ser desplegado como un **sitio estático** en Vercel.

### Pasos para Desplegar:

1. **Subir a GitHub**: Sube el código de este directorio a un repositorio de GitHub.
2. **Importar en Vercel**: 
   - Ve a [Vercel](https://vercel.com/new).
   - Selecciona tu repositorio.
   - Vercel detectará automáticamente que es un proyecto de Astro.
3. **Configuración de Build**:
   - **Framework Preset**: Astro
   - **Build Command**: `npm run build`
   - **Output Directory**: `dist`
4. **Desplegar**: Haz clic en "Deploy".

### Variables de Entorno
No se requieren variables de entorno complejas para el despliegue básico, pero si decides usar un formulario con backend (como Formspree o Vercel Actions), deberás añadirlas en el panel de Vercel.

## Desarrollo Local

```bash
# Instalar dependencias
npm install

# Iniciar servidor de desarrollo
npm run dev

# Construir para producción
npm run build
```

---
Creado para Juan Jose Gonzales Centurión - Digital Marketing & Web Specialist.

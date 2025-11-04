# Aplicación Todo Angular v1.0

Esta es la versión inicial de la aplicación Todo construida con Angular 17 y TailwindCSS. Configura la estructura básica del proyecto e integra TailwindCSS mediante una configuración manual de PostCSS.

## Características
- Configuración de Angular 17
- TailwindCSS configurado mediante `tailwind.config.js`

## Para comenzar
1. Instalar dependencias:
   ```bash
   npm install
   ```
2. Iniciar el servidor de desarrollo:
   ```bash
   npm start
   ```

## Configuración de TailwindCSS
Tailwind se configura mediante `tailwind.config.js` con las rutas de contenido establecidas en todos los archivos HTML y TypeScript de la carpeta `src`.  
Los estilos se inyectan en `src/styles.css` usando las directivas `base`, `components` y `utilities` de Tailwind.

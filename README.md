# BLL Comercial

Sitio comercial de BLL Servicios y Proyectos Industriales — Astro 5.

## Desarrollo

```bash
npm install
npm run dev
```

## Estructura

- `src/pages/` — Inicio, Servicios, Proyectos, Nosotros, Contacto.
- `src/components/` — Header, Footer, WhatsAppButton, LogoMark, StatBar.
- `src/data/site.ts` — datos de contacto, navegación y cifras. **Contiene
  placeholders marcados con `TODO(BLL)` / `[PENDIENTE]`** (WhatsApp, correo,
  teléfono, dirección y cifras de marketing) que deben confirmarse antes de
  publicar el sitio — búscalos con:

  ```bash
  grep -rn "PENDIENTE\|TODO(BLL)" src/
  ```

- `src/styles/global.css` — sistema de diseño (tokens de color/tipografía,
  animaciones: scroll-reveal, marquee, float, hover-lift).
- `public/images/proyectos/` — fotografía real de obra.
- `public/images/servicios/` — imágenes de categoría de servicio (mismas que
  usa el sistema administrativo interno).

## Build

```bash
npm run build
```

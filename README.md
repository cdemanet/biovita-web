# Biovita — Contenido de Marketing

Este repositorio contiene **únicamente** el contenido de marketing
editado desde el panel de Decap CMS (`/admin/`):

- Productos
- Categorías
- Configuración del sitio (settings)
- Hero de la home

El código de la aplicación Astro vive en un repositorio separado.
Este repo es la fuente de verdad para el contenido.

## Estructura

```
src/content/
  products/       # un JSON por producto
  categories/     # un JSON por categoría
  settings.json   # configuración global del sitio
  homeHero.json   # contenido del hero de la home
```

## Edición

Entrar a `/admin/`, iniciar sesión con GitHub, editar y guardar.
Decap hace commit y push automático al branch `main` de este repo.

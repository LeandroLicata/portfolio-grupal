# Portfolio Grupal

Somos un equipo de estudiantes apasionados por el desarrollo web y la tecnología. Este portfolio reúne algunos de nuestros proyectos, habilidades y experiencias, reflejando nuestro aprendizaje, creatividad y trabajo en equipo.

Proyecto desarrollado para la materia **Práctica Profesionalizante I**.

## Tecnologías

- **HTML5** — estructura del contenido
- **CSS3** — estilos propios ([css/styles.css](css/styles.css))
- **Bootstrap 5** — diseño responsive y componentes (vía CDN, no requiere instalación)
- **Bootstrap Icons** — iconografía (vía CDN)

> No usa frameworks de JS ni proceso de build. Solo se incluye el bundle JS de Bootstrap (CDN) para que funcionen el navbar responsive, dropdowns, etc.

## Estructura del proyecto

```
portfolio-grupal/
├── index.html              # Home: CV del equipo (acordeón) + grilla de proyectos
├── css/
│   └── styles.css          # Estilos propios (sobre Bootstrap)
├── assets/
│   └── img/                # Imágenes (placeholders SVG por ahora)
└── proyectos/
    ├── proyecto1.html      # Páginas de detalle de cada miniproyecto
    ├── proyecto2.html
    └── proyecto3.html
```

## Cómo verlo

Abrí [index.html](index.html) directamente en el navegador (doble clic). No necesita servidor local.

## Cómo completarlo (para el equipo)

1. **CV del equipo:** en [index.html](index.html), sección `#cv`, cada integrante tiene un ítem de acordeón con su currículum. Completar los campos marcados con `⚠️` y los placeholders entre paréntesis: identificación, contacto, idiomas, título más alto, perfeccionamiento certificado, habilidades (blandas/técnicas/transversales) y antecedentes laborales.
2. **Proyectos:** por cada miniproyecto, actualizar la card correspondiente en `#proyectos` (título, descripción, badges de tecnología) y editar su página en `proyectos/`.
3. **Agregar más proyectos:** copiar `proyectos/proyecto3.html` → `proyecto4.html`, editar el contenido y agregar una nueva card en el home apuntando a esa página.
4. **Imágenes:** reemplazar los placeholders de [assets/img/](assets/img/) por fotos del equipo y capturas reales (mantener los mismos nombres de archivo o actualizar los `src`).
5. **Contacto:** completar el email y links del footer en `#contacto`.

## Convención de trabajo en equipo (sugerida)

- Trabajar en ramas separadas y abrir Pull Requests para integrar cambios.
- Que cada integrante se haga cargo de su tarjeta de equipo y de al menos un proyecto.

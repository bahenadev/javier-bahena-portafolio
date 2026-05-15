# Javier Bahena Ocampo — Portafolio

Portafolio personal como Desarrollador Java Full Stack. Construido con Astro y Tailwind CSS.

## Stack

- [Astro 6](https://astro.build) — Framework web estático
- [Tailwind CSS v4](https://tailwindcss.com) — Estilos utilitarios
- [pnpm](https://pnpm.io) — Gestor de paquetes

## Desarrollo

```sh
pnpm install        # Instalar dependencias
pnpm dev            # Servidor local en localhost:4321
pnpm build          # Generar sitio estático en dist/
pnpm preview        # Previsualizar build de producción
```

## Estructura

```
src/
├── components/     # Componentes reutilizables
│   ├── Hero.astro
│   ├── Tech.astro
│   ├── Projects.astro
│   ├── CV.astro
│   ├── Contact.astro
│   ├── Nav.astro
│   └── Footer.astro
├── layouts/        # Layout base con SEO
│   └── Layout.astro
├── pages/          # Rutas del sitio
│   ├── index.astro
│   └── 404.astro
└── styles/         # Estilos globales
    └── global.css
```

## Deploy

El sitio se despliega en Netlify con deploy manual de la carpeta `dist/`. Incluye `netlify.toml` con configuración de Forms para el formulario de contacto.

```sh
pnpm build          # Genera dist/
# Subir carpeta dist/ a Netlify (sin comprimir)
```

## Contacto

- Email: javierbahenadev@gmail.com
- LinkedIn: [linkedin.com/in/bahenadev](https://linkedin.com/in/bahenadev)
- GitHub: [github.com/bahenadev](https://github.com/bahenadev)

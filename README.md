# Spade Beauty Center — Sitio Web

Proyecto construido con **Astro** + **Tailwind CSS**.

## Requisitos

- Node.js 18+
- npm o pnpm

## Instalación

```bash
npm install
```

## Desarrollo local

```bash
npm run dev
```

Abre http://localhost:4321 en tu navegador.

## Build para producción

```bash
npm run build
```

Los archivos listos para subir quedan en la carpeta `dist/`.

## Preview del build

```bash
npm run preview
```

## Estructura del proyecto

```
spade-beauty/
├── public/
│   └── images/          # Fotos de servicios y logo
├── src/
│   ├── components/      # Nav, Hero, About, Services, Contact, Footer, WaFloat
│   ├── layouts/         # Layout base HTML
│   ├── pages/           # index.astro (página principal)
│   └── styles/          # global.css (Tailwind + estilos custom)
├── astro.config.mjs
├── tailwind.config.mjs
└── package.json
```

## Personalización

- **Servicios y precios**: edita `src/components/Services.astro`
- **Colores**: edita las variables en `src/styles/global.css` y `tailwind.config.mjs`
- **WhatsApp**: busca `WA_LINK` en cualquier componente para cambiar el número
- **Fotos**: reemplaza las imágenes en `public/images/`

## Despliegue recomendado

- [Netlify](https://netlify.com) — arrastra la carpeta `dist/` o conecta el repositorio
- [Vercel](https://vercel.com) — importa el repositorio directamente
- [Cloudflare Pages](https://pages.cloudflare.com) — conecta el repositorio

## Contacto del negocio

- WhatsApp: 310 516 4565
- Instagram: @spadebeautycenter
- Dirección: Cra 7A No 26-74 Local No 2, Girardot, Colombia

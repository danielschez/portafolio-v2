# danielschez.dev — Portfolio

Portafolio personal construido con **Astro 4** + **React**.

## 🚀 Inicio rápido

```bash
# 1. Instala dependencias
npm install

# 2. Inicia el servidor de desarrollo
npm run dev

# 3. Abre http://localhost:4321
```

## 📁 Estructura

```
portfolio/
├── public/
│   ├── favicon.svg
│   └── me.jpg          ← AGREGA TU FOTO AQUÍ
├── src/
│   ├── components/
│   │   ├── Hero.astro
│   │   ├── Experience.astro
│   │   ├── Projects.astro
│   │   ├── About.astro
│   │   └── Contact.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## 📸 Tu foto

Agrega tu foto en `public/me.jpg`.
- Tamaño recomendado: **800×1000px** (vertical)
- Formato: JPG o WebP
- La foto aparece en el Hero y en la sección Sobre mí

## 📬 Formulario de contacto

El formulario usa [Formspree](https://formspree.io):
1. Crea una cuenta gratis en formspree.io
2. Crea un nuevo formulario
3. Copia el ID (ej: `xpzgvkqw`)
4. En `src/components/Contact.astro`, reemplaza:
   ```
   action="https://formspree.io/f/YOUR_FORM_ID"
   ```
   con tu ID real.

## 🌐 Deploy en Vercel / Netlify

```bash
# Build
npm run build

# Preview local del build
npm run preview
```

Sube la carpeta `dist/` o conecta tu repo directamente a Vercel/Netlify.

## ✏️ Personalización rápida

- **Colores**: edita las variables CSS en `src/styles/global.css` (`:root { ... }`)
- **Experiencia**: edita el array `jobs` en `src/components/Experience.astro`
- **Proyectos**: edita el array `projects` en `src/components/Projects.astro`
- **Correo**: busca `daniel@danielschez.dev` y reemplaza con el tuyo

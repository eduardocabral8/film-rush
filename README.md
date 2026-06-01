# 🎬 FilmRush

Catálogo de películas y series para descubrir, puntuar y reseñar — rápido, responsive y sin vueltas.

🔗 **Demo:** https://examen-fullstack-rho.vercel.app/

---

## Qué es esto

FilmRush es un sitio web para amantes del cine y las series. Podés explorar un catálogo, ver la información de cada título, leer opiniones destacadas y dejar tu propia reseña a través de un formulario de contacto.

Lo construimos en equipo como proyecto integrador, con foco en una experiencia simple y un rendimiento alto: Astro genera el sitio de forma estática, así que carga al instante y anda bien en cualquier dispositivo.

---

## Funcionalidades

- 🎥 **Catálogo** de películas y series con información detallada de cada título.
- ⭐ **Sistema de puntuación** por título.
- ✍️ **Reseñas** escritas por usuarios.
- 📝 **Lista personalizada** para guardar tus favoritos.
- 📨 **Formulario de contacto** para enviar tu propia reseña.
- 📱 **Diseño responsive**, pensado mobile-first.

---

## Stack

| Capa | Tecnología |
|------|------------|
| Framework | Astro 5 |
| Lenguajes | HTML5, CSS, JavaScript |
| Deploy | Vercel (`@astrojs/vercel`) |
| Formato | Prettier + plugin de Astro |

---

## Estructura

```
film-rush/
└── src/
    ├── pages/         # index, movies, series, reviews
    ├── layouts/       # layout base
    ├── components/    # card de película/serie
    ├── data/          # catálogo de películas y series
    └── styles/        # tema y estilos globales
```

---

## Levantar el proyecto

### Requisitos

- Node.js v18+
- pnpm (o npm)

### Pasos

```bash
# 1. Instalar dependencias
pnpm install

# 2. Servidor de desarrollo
pnpm dev          # http://localhost:4321

# 3. Build de producción
pnpm build

# 4. Previsualizar el build
pnpm preview
```

---

## Integrantes

Proyecto integrador de IntegrarTEC, hecho en equipo:

- Agustín Luján
- Valentina Gallo
- Eduardo Emanuel Cabral Figueredo

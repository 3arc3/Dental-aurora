# Clínica Dental Aurora — Web

Web estática (HTML + CSS + JS puro, sin build) para la clínica dental.

## Archivos

- `index.html` — estructura y contenido de todas las secciones.
- `estilos.css` — todos los estilos.
- `script.js` — menú móvil, iconos y animaciones al hacer scroll.

No hay dependencias que instalar ni paso de compilación: son 3 archivos que funcionan tal cual en cualquier navegador.

## Datos a revisar antes de publicar

Algunos datos son inventados/orientativos y conviene sustituirlos por los reales:

- Nombre, teléfono, email, Instagram y dirección (sección `#contacto` en `index.html`).
- Horario de atención.
- Nombres y roles del equipo (`#equipo`).
- Precios de servicios (`#servicios`) — son orientativos.
- Fotos de la galería (`#galeria`): ahora mismo son imágenes de muestra (`picsum.photos`). Sustitúyelas por fotos reales de la clínica subiendo tus imágenes a una carpeta `img/` y cambiando el `src` de cada `<img>`.
- Reseñas (`#resenas`): son de ejemplo, cámbialas por reseñas reales de pacientes.

## Cómo subirlo a GitHub

1. Crea un repositorio nuevo en GitHub (puede estar vacío).
2. En tu ordenador, dentro de esta carpeta:
   ```bash
   git init
   git add .
   git commit -m "Primera versión de la web"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/TU-REPO.git
   git push -u origin main
   ```

## Cómo publicarlo en Vercel

1. Entra en [vercel.com](https://vercel.com) e inicia sesión con tu cuenta de GitHub.
2. Pulsa **Add New → Project** y selecciona el repositorio que acabas de subir.
3. Framework: elige **Other** (es HTML estático, no necesita configuración de build).
4. Deja "Build Command" y "Output Directory" vacíos y pulsa **Deploy**.
5. En un par de minutos tendrás una URL pública (algo como `tu-repo.vercel.app`).

## Alternativa: GitHub Pages

Si prefieres GitHub Pages en lugar de Vercel:
1. En el repositorio, ve a **Settings → Pages**.
2. En "Source" selecciona la rama `main` y la carpeta `/ (root)`.
3. Guarda y espera a que te dé la URL pública.

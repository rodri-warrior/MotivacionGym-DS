---
name: motivacion-gym-design-system
description: Sistema visual de Motivación Gym para piezas de redes (feed 4:5, 1:1, historias 9:16). Usalo para diseñar flyers, publicaciones, carruseles e historias del gimnasio.
---
Leé primero `README.md` (identidad, voz, color, tipografía, composición, logo) y `2-plantillas.md` (qué familia usar).
- Colores y tipografías: `colors_and_type.css` (tokens) y `tokens.json`. Fuentes en `fonts/`.
- Logo: `assets/logos/` (blanco sobre negro/gris, negro sobre amarillo; sobre foto, en placa negra). Nunca redibujarlo.
- Íconos: `assets/iconos/` (trazo 4 px, grilla 48).
- Componentes y plantillas: `components/<Nombre>/<Nombre>.html` con su guía `<Nombre>.prompt.md`. El motor `_ds_bundle.js` expone `window.MG` (`MG.render(id, 'v'|'s'|'h', opciones)`).
- Piezas a 1080 px de ancho. Voseo rioplatense, sin culpa ni promesas de resultados. Datos comerciales siempre como [PLACEHOLDER] hasta tener los reales.

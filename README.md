Sistema operativo de diseño para las redes de **Motivación Gym**: colores, tipografías, componentes y 12 familias de plantillas listas para flyers, publicaciones, carruseles e historias. Está pensado para que cualquier persona del equipo arme una pieza nueva sin reinventar colores, jerarquías ni composiciones.

**Cómo se usa, en una línea:** elegí una plantilla (sección *Plantillas*), abrí el **Estudio MG** (el archivo `estudio-mg.html` que acompaña este sistema), cambiá textos y foto, y descargá el PNG a 1080 px. La guía paso a paso está en *Guía de uso y exportación*.

## Identidad

| | |
|---|---|
| Nombre | Motivación Gym |
| Slogan | Siempre Motivados |
| Hashtag | #siempremotivados (siempre en minúsculas, discreto, en el pie o en la franja) |
| Actividades | Fitness general, musculación y crossfit |
| Público | Personas de todas las edades, experiencias y condiciones físicas |
| Valores | Motivación, comunidad, constancia, superación, autenticidad y energía |
| Personalidad | Enérgica, cercana, inclusiva, directa y auténtica: fuerza y movimiento sin intimidar a quien recién empieza |

## Organización del sistema

- **Vista general** (esta página): identidad y reglas básicas.
- **Fundamentos**: Color, Tipografía, Retícula, Recursos gráficos, Iconografía, Fotografía y Logo (tarjetas en *Componentes › 1 · Fundamentos*).
- **Componentes**: 17 piezas reutilizables (encabezado, título, datos, tabla de horarios, CTA, pie…).
- **Plantillas**: 12 familias × 3 formatos × 3 líneas, con variantes.
- **Ejemplos aplicados**: cada familia con contenido de muestra, más un carrusel de 5 slides.
- **Guía de uso y exportación**, **Voz, captions y CTA**, **Decisiones del sistema** y **Control de calidad** (secciones de este libro).

**Nombres.** Todo se nombra de mayor a menor: `MG / Plantilla / Horarios / Feed vertical / Amarillo`. Los archivos exportados usan el mismo orden con guiones bajos: `MG_Plantilla_Horarios_FeedVertical_Amarillo.png` (y `_01`, `_02`… para slides).

## Voz

Hablamos en **español rioplatense con voseo**: *vení, entrená, sumate, arrancá, consultá, escribinos*. Motivamos desde la invitación, no desde la culpa.

- Sí: “CADA ENTRENAMIENTO SUMA”, “TU PRIMER DÍA EMPIEZA ACÁ”, “Andá de a poco”, “Preguntá siempre: el staff está para ayudarte”.
- No: “No hay excusas”, “Sin dolor no hay ganancia”, “Quemá lo que comiste”, “Cuerpo de verano en 30 días”. Nada de castigo, culto al dolor, comparaciones de cuerpos ni resultados físicos garantizados.
- Sin consejos médicos. Cuando corresponda: “consultá al staff” o “consultá con tu médico”.
- Títulos en MAYÚSCULAS (Bebas Neue); bajadas y cuerpo en oración normal. Sin emojis dentro de las piezas (en la descripción, con moderación).
- Tildes y signos de apertura siempre: ¿…? ¡…!

## Color

Paleta del manual: `amarillo` #F5C518, `negro` #0D0D0D, `gris` #2A2A2A, `blanco` #FFFFFF. Proporción global de marca, **mirando el feed completo y no cada pieza**: 60% negro · 25% amarillo · 10% blanco · 5% gris.

Usá los roles, no los hexadecimales: `fondo-oscuro`, `fondo-campana`, `superficie`, `texto-sobre-oscuro`, `texto-sec-sobre-oscuro`, `texto-sobre-amarillo`, `acento`, `divisor`, `cta-fondo`, `cta-texto`.

| Combinación | Contraste | Uso |
|---|---|---|
| Blanco sobre negro | 19,4:1 | ✔ Todo texto |
| Negro sobre amarillo | 11,9:1 | ✔ Todo texto |
| Amarillo sobre negro | 11,9:1 | ✔ Títulos, datos, acentos, CTA |
| `gris-texto` sobre negro | 9,8:1 | ✔ Texto secundario |
| Gris sobre amarillo | 8,8:1 | ✔ Texto secundario sobre amarillo |
| Blanco sobre gris | 14,4:1 | ✔ Texto en paneles |
| Amarillo sobre blanco | 1,6:1 | ✘ Nunca para información |
| Blanco sobre amarillo | 1,6:1 | ✘ Nunca |
| Gris sobre negro | 1,35:1 | ✘ Solo superficies, nunca texto |
| Texto directo sobre foto | variable | ✘ Siempre sobre superficie sólida o `velo-foto` |

## Tipografía

Tres familias, cada una con un trabajo: **Bebas Neue** (`display-xl`, `display-l`, `display-m`, `display-s`) para títulos en mayúsculas; **Barlow Condensed** (`bajada`, `dato-clave`, `dato`, `etiqueta`, `pie`) para subtítulos, etiquetas y datos; **Barlow** (`cuerpo`, `cuerpo-s`, `cita`, `legal`) para leer.

- Los tamaños son para piezas de 1080 px de ancho y están calculados para leerse en un teléfono (la pieza se ve a ~36%): `cuerpo` 38 px ≈ 14 pt en pantalla. **Piso absoluto: 26 px (`legal`)**, y solo para letra chica.
- Cada estilo tiene un largo máximo (ver Tipografía). **Si un texto no entra: 1) acortalo; 2) pasá el detalle a la descripción; 3) dividilo en un carrusel.** Un título puede bajar un solo paso de la escala; nunca se sigue achicando.
- Destacá como máximo 1–2 palabras por título con *asteriscos* en el Estudio: se pintan de `acento` (sobre amarillo, barra negra con texto amarillo).

## Composición

- Márgenes: `margen-vertical` 80/80/72/80, `margen-cuadrado` 64/72/60/72, `margen-historia` 288/80/340/80. Retícula de 6 columnas con medianil `esp-3`.
- Alineación a la izquierda por defecto. Centrado solo en piezas de una frase (motivacional).
- Las **zonas de interfaz** (`zona-historia-arriba`, `zona-historia-abajo`, `recorte-portada-4x5`) son otra capa: allí puede haber fondo o foto, nunca texto. El Estudio las muestra con “Márgenes y zonas de interfaz”.
- Adaptar = **reacomodar**. Del 4:5 al 1:1 la foto pasa al costado y el texto se compacta; del 4:5 al 9:16 se agrega aire y la foto crece hacia arriba. Nunca estirar ni recortar a ciegas.

## Recursos gráficos

Hay cinco, y una pieza usa **como máximo dos** además del logo: la **franja lateral** (`franja-ancho`, con #siempremotivados en vertical), el **separador barra** (motivo de la barra del logo: dos tramos y dos bloques), la **barra inclinada** (−14°, movimiento, solo en campaña), la **trama** diagonal (solo en contenedores sin foto) y las **etiquetas** (`radio-s`). Radios: `radio-0` en todo lo demás.

## Iconografía

Un solo estilo: **trazo de 4 px en grilla de 48, puntas rectas, esquinas en inglete, sin relleno**. 18 íconos en *Iconos* (reloj, calendario, ubicación, chat, arroba…). Van en `acento` sobre negro y en negro sobre amarillo, siempre acompañando un texto. No se usan logos de apps (WhatsApp, Instagram): se usan `chat` y `arroba`.

## Fotografía

Fotos **reales del gym y de su comunidad**, con permiso de quienes aparecen. Luz del lugar, gente entrenando de verdad, planos medios y detalles de esfuerzo; sin poses de catálogo, sin cuerpos como trofeo. Tratamiento natural (contraste +4%); blanco y negro solo sobre la línea Amarillo. El texto nunca va directo sobre la foto: va en un panel sólido o sobre `velo-foto`. Cada plantilla con foto tiene su versión **sin foto** equivalente (trama + palabra en contorno), y el placeholder dice `[FOTO DEL GYM]` con la indicación de encuadre.

## Logo

Usá los archivos de *Logos* (vectorizados del PNG original): `mg-logo-blanco` sobre negro y gris, `mg-logo-negro` sobre amarillo. Nunca se redibuja, deforma, recolorea fuera de la paleta ni se le agregan efectos. Espacio de protección: ¼ de la altura del logo por lado. Ancho `logo-ancho` 150 px en el encabezado, mínimo 120 px. Sobre fotografía, siempre dentro de una **placa negra sólida**. En las plantillas amarillas va la versión negra, chica, en el encabezado: presencia discreta que no compite con el título.

## Niveles de intensidad y líneas

| Nivel | Para qué | Línea típica | Cómo se ve |
|---|---|---|---|
| Informativo | Horarios, feriados, avisos, normas | Oscuro | Tabla y datos protagonistas, un solo acento, sin foto o foto chica |
| Comunidad y educación | Actividades, consejos, staff, testimonios, primera visita, carruseles | Oscuro con franja / Oscuro con foto | Equilibrado, foto real, cuerpo de texto legible |
| Campaña | Propuestas, eventos, motivacionales | Amarillo / Oscuro con foto a sangre | Título grande, barra inclinada, un solo CTA |

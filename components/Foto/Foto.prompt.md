# MG / Componente / Contenedor de fotografía

Encuadra la foto del gym con recorte controlado; si no hay foto, muestra el placeholder con indicación de encuadre o la versión gráfica.

**Variantes:** Con foto (natural) · B/N (solo sobre amarillo) · Placeholder [FOTO DEL GYM] · Sin foto (trama + palabra en contorno) · Con velo inferior.

**Campos editables:** Imagen, punto de foco (horizontal/vertical), palabra de la versión sin foto.

**Largo recomendado:** Palabra sin foto: 1 palabra, máx. 12 caracteres.

**Reglas de combinación:** Nunca texto directo sobre la foto: panel sólido o velo. Logo sobre foto solo en placa. Una foto por pieza (más la mini de testimonio).

**En código:** `MG.foto({ src, foco: '50% 30%', tratamiento: 'natural'|'byn', sinFoto, palabra, velo, w, h })`

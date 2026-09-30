# MG / Componente / Fila de horario y tabla semanal

Presenta horarios en filas de tres columnas: día, horario y actividad.

**Variantes:** Tabla estándar (4:5 y 9:16) · Tabla compacta (1:1) · Fila destacada (empezá el día con ! en el Estudio).

**Campos editables:** Filas con formato `DÍA | HORARIO | ACTIVIDAD`, una por línea; cabeceras.

**Largo recomendado:** Máx. 7 filas. Día completo (Miércoles), horario máx. 13 caracteres (07:00 a 22:00), actividad máx. 24.

**Reglas de combinación:** Más de 7 filas o más de una franja horaria por día: dividí en dos piezas (mañana/tarde) o en un carrusel. Nunca achicar la letra de la tabla.

**En código:** `MG.tablaSemanal({ filas: 'Lunes | [HORARIO] | [ACTIVIDAD]\n…', compacta })`

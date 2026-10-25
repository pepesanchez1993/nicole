# NICOLEGYM

PWA personal de gimnasio y pilates. Un solo `index.html` autocontenido, sin servidor ni build, 100 % offline e instalable.
Los datos se guardan en `localStorage` (clave `nicolegym-v2`) y se pueden exportar/importar desde **Plan → Tus datos**.

## Tres pestañas

- **Hoy**: registrar el entreno del día. Tira de la semana arriba; «Cambiar» cambia la sesión solo de ese día.
- **Plan**: elegir cada día de la semana (Gimnasio + rutina · Pilates + modalidad · Descanso) y editar las rutinas.
- **Progreso**: racha de actividad, mejor racha, semana/mes, calendario, récords con gráfica y últimas sesiones.

## Cada entreno tiene siempre los mismos 5 bloques

1. Calentamiento (checks) · 2. Fuerza (o Clase de pilates de 60 min: suelo, reformer o silla) · 3. Core 15 min · 4. Cardio 10 min (check) · 5. Estiramiento (checks)

- Rutinas de gym: Pierna y glúteo · Pecho, hombro y tríceps · Espalda y bíceps (se pueden añadir más).
- Cada ejercicio: 3 series + fila **PR** (mejor peso y repeticiones del día).
- Todo es editable en Plan: añadir, renombrar, reordenar y quitar ejercicios, calentamientos y estiramientos; core, cardio y duración del pilates.
- Racha: días seguidos con actividad; los descansos planificados no la rompen.

## Migración

Al abrir por primera vez, los registros de la versión anterior (`nicolegym-v1`) se importan solos al nuevo formato y la copia antigua se deja intacta.

# Actividad Integradora - Unidad 2
## Caso B: PostgreSQL vs. MongoDB

Inferencia estadística y toma de decisiones en ingeniería.
Materia: Fundamentos de Ciencia de Datos - TecNM / ITZ

Integrantes: Jesús Alejandro Moreno Vargas, Santiago Ocampo Castro
Docente: Ramos Palencia Celia

## Estructura del repositorio
- data/: dataset original y versión depurada (.csv)
- notebooks/: cuaderno Caso_B.ipynb ejecutado y documentado
- docs/: reporte técnico en PDF

## Resumen
Se compara el tiempo de ejecución por transacción (ms) entre PostgreSQL y MongoDB
con datos sintéticos (300 observaciones por motor). Se aplican estadística descriptiva,
remuestreo (TCL), intervalos de confianza y prueba t. Resultado: se rechaza H0
(p = 0.0148); PostgreSQL es ~1.2 ms más rápido, con un efecto pequeño.

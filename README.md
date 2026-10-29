# Investigathon Y-Hat 2026

Material del problema **"Conectividad crítica para la sincronización global en el modelo de Kuramoto, y su equivalencia con un problema de completación de matrices"**.

| Documento | PDF | Fuente |
|---|---|---|
| Propuesta del problema | [propuesta_kuramoto_mc.pdf](propuesta_kuramoto_mc.pdf) | `propuesta_kuramoto_mc.tex` |
| Charla corta (introducción) | [charla_corta_kuramoto.pdf](charla_corta_kuramoto.pdf) | `charla_corta_kuramoto.tex` |
| Charla larga (1 hora) | [charla_kuramoto_mc.pdf](charla_kuramoto_mc.pdf) | `charla_kuramoto_mc.tex` |

## Compilar

- Propuesta y charla larga: `pdflatex` (dos pasadas).
- Charla corta: `lualatex` (dos pasadas), porque `header.tex` usa `fontspec`.

Las dos charlas usan el tema de beamer de `tema_luciernagas.tex`.

Los videos que muestra la charla corta (`videos/`) no están en el repositorio: la charla compila igual, pero para reproducirlos hay que agregarlos en esa carpeta.

# Semiología C3 — Sistema nervioso

Sitio de estudio del Certamen 3 de Semiología (Medicina, UBB 2026-2): cuatro guías construidas
desde las diapositivas de clase, una por clase, más un banco de preguntas.

Publicado en https://kraksiplus.github.io/semio-c3-nervioso/ con GitHub Pages.

## Contenido

| Página | Clase | Diapositivas |
|---|---|---|
| [01 — Anamnesis y razonamiento localizador](01_Anamnesis_y_Razonamiento_Localizador.html) | 1 | 41 |
| [02 — Del síntoma al síndrome](02_Del_Sintoma_Al_Sindrome.html) | 2 | 42 |
| [03 — Examen motor, sensitivo y reflejos](03_Examen_Motor_Sensitivo_Reflejos.html) | 3 | 74 |
| [04 — Integración y síndromes neurológicos](04_Integracion_Sindromes_Neurologicos.html) | 4 | 49 |

`preguntas/05_Banco_Preguntas_C3.json` — 40 preguntas de 5 alternativas en formato QuestApp.

## Cómo está hecho

- Texto extraído por página con `pdftotext -layout`; las 81 diapositivas sin capa de texto se
  resolvieron con OCR `tesseract -l spa` y se listan al final de cada guía.
- Cada afirmación clínica lleva una cita `[diapo N]`, donde N es el número de diapositiva del PDF.
- No se agrega contenido ausente de las diapositivas; cuando un tema no aparece, la guía lo dice.
- HTML autocontenido (CSS y JS embebidos, sin dependencias externas): funciona offline.

## Notas

- `clase 3 parte I.pdf` está contenido en `clase 3 parte II.pdf`; se usa la parte II.
- Los PDF originales de clase no se distribuyen en este repositorio.
- Material de estudio, no una recomendación clínica.

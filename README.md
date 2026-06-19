# TP Integrador — Comunicación de Datos 2025
**UTN La Plata** · Ingeniería aplicada a la comunicación de datos

## Propuestas desarrolladas
- **Propuesta 2** — Conversor de Audio Analógico a Digital (Afinador de Guitarra)
- **Propuesta 4** — Transmisión Digital de Señales y Compresión

## Descripción
Aplicación web que integra ambas propuestas en una sola interfaz:

- Captura audio en tiempo real desde el micrófono (44100 Hz, 32 bits float)
- Detecta la frecuencia fundamental de cada cuerda mediante autocorrelación + FFT (4096 puntos)
- Muestra la nota detectada, desviación en cents y espectro de frecuencias
- Simula transmisión digital con codificación PCM / ADPCM / MP3, control de error de canal y visualización de señal TX vs RX reconstruida

## Tecnologías
- Web Audio API — captura, muestreo y análisis
- Canvas API — espectro FFT y ondas TX/RX
- JavaScript ES2022 vanilla — autocorrelación, cuantización, simulación de errores
- HTML5 + CSS3 — sin frameworks, sin dependencias externas

## Cómo ejecutar
1. Abrir `afinador_guitarra.html` en Chrome, Firefox o Edge
2. Permitir acceso al micrófono
3. Seleccionar una cuerda y tocar la guitarra

No requiere instalación ni servidor.

## Archivos
| Archivo | Descripción |
|---|---|
| `afinador_guitarra.html` | Aplicación completa (ejecutable) |
| `TP_Etapa1_ComunicacionDatos.docx` | Documento Etapa 1 — Diseño y planificación |

## Etapas
- ✅ Etapa 1 — Diseño y planificación
- ✅ Etapa 2 — Desarrollo y defensa
- ⬜ Etapa 3 — Fin del proyecto

# Banco de preguntas · Mediación (MAES)

Aplicación estática para practicar la asignatura de Mediación.

## Banco inicial

- **147 preguntas** del recopilatorio Word: 123 asociadas al manual y 24 del artículo AA1.
- **44 preguntas** adicionales del HTML anterior, conservando las explicaciones originales.
- **191 preguntas en total**.
- Se excluyen únicamente seis duplicidades claras acordadas (preguntas 7, 21, 27, 36, 41 y 49 del HTML). Se conservan las coincidencias conceptuales que se decidió mantener.

No se ha realizado una auditoría académica de las respuestas; se importan como aparecen en los materiales de origen. La pregunta 19 del Word queda marcada como ambigua, según la advertencia del propio recopilatorio.

## Funcionalidad

- Filtros por origen y capítulo.
- Selección de 10, 20, 40, todas o cantidad personalizada.
- Mezcla independiente de preguntas y opciones (activada por defecto).
- Práctica con feedback inmediato y simulacro con revisión final.
- Penalización configurable por error; las preguntas en blanco no penalizan.
- Buscador sobre enunciados, opciones, explicaciones y procedencia.
- Banco completo con respuestas correctas y origen de cada pregunta.
- Las claves utilizan identificadores estables; las letras A–D se asignan después de mezclar.

## Ejecutar en local

Desde la carpeta del proyecto: `python -m http.server 8000` y abrir `http://localhost:8000`.

## Entornos

- `main`: producción en la raíz del sitio.
- `develop`: pruebas en `/test/`.
- GitHub Actions combina ambas ramas en cada despliegue para mantener simultáneamente producción y pruebas.
- Primera configuración: en **Settings → Pages**, seleccionar **GitHub Actions** como origen de publicación, si aún no está habilitado.

# Banco de preguntas · Mediación (MAES)

Proyecto independiente para practicar la asignatura de Mediación.

## Entornos

- `main`: producción.
- `develop`: pruebas.

## Banco inicial

- 147 preguntas del recopilatorio Word.
- 44 preguntas adicionales del HTML (6 duplicados claros excluidos).
- Total previsto: 191 preguntas.

## Estructura prevista

- `index.html`: aplicación del test.
- `data/questions.json`: banco de preguntas con opciones, clave interna, explicación y procedencia.
- `test/`: despliegue de pruebas.
- `.github/workflows/`: despliegues automatizados.

La clave correcta se guardará por identificador de opción, nunca por letra. Las letras A–D se asignarán después de mezclar las opciones.
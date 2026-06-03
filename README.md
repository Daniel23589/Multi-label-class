# Multi-label Class

Proyecto de **clasificación multietiqueta de imágenes** orientado al reconocimiento de alimentos. La finalidad es permitir que una misma imagen pueda asociarse con varias etiquetas o atributos relacionados.

## Objetivo

Experimentar con modelos de visión artificial capaces de reconocer información complementaria en una imagen, por ejemplo el plato y su grupo alimenticio.

## Archivos principales

- `mlclass.py`: código para clasificación multietiqueta.
- `slclass.py`: código de clasificación de una sola etiqueta utilizado como referencia o comparación.

## Conjunto de datos

Dentro de `MAFood121/` se organiza el conjunto de datos:

- `annotations/`: anotaciones de platos, grupos alimenticios y divisiones de entrenamiento, validación y prueba.
- `images/`: imágenes agrupadas por clases.

## Puesta en marcha

1. Crea un entorno de Python.
2. Instala las dependencias importadas por los scripts.
3. Comprueba que las rutas hacia `MAFood121/` coinciden con tu entorno local.
4. Ejecuta el script multietiqueta:

```bash
python mlclass.py
```

## Recomendaciones

Para mejorar la reproducibilidad, sería conveniente añadir un archivo `requirements.txt`, documentar los hiperparámetros y guardar los resultados de cada ejecución en una carpeta separada.

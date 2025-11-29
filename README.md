# Prueba sostenibilidad

## Sobre este repositorio

- Los datos de entrada están comprimidos en el archivo `SostenibilidadEmpresarial.zip` y descomprimidos en `SostenibilidadEmpresarial/`.
- En `output/` están los archivos obtenidos como resultado de la prueba.
- `Prueba_técnica.ipynb` es el notebook con el código del ETL y con los comentarios y justificaciones sobre los pasos realizados y las decisiones tomadas en el desarrollo del mismo.

## Instrucciones

El notebook fue elaborado en Google Colab y se puede acceder a él mediante este [enlace](https://colab.research.google.com/drive/1mtMrZfJhFqGWHn7NPQfMwJn9yicLjH-M?usp=sharing). Para la reproducción del resultado basta con subir el archivo comprimido `SostenibilidadEmpresarial.zip` y ejecutar todas las celdas. La salida aparecerá en una nuevo directorio `output/` con la estructura típica de Spark:
- Un subdirectorio `output/impacto_ambiental_empresas` con el .csv de Impacto Ambiental Empresas.
- Un subdirectorio `output/beneficios_proyectos_energeticos` con el .csv de Beneficios Proyectos Energéticos.
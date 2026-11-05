# Predicción del rendimiento académico en matemáticas

Este repositorio reúne la base de datos y los resultados de predicción utilizados en una tesis de maestría sobre el desarrollo de un modelo de aprendizaje automático mediante una red neuronal densa.

## Objetivo

Desarrollar un modelo de aprendizaje automático que permita predecir el rendimiento académico en matemáticas de estudiantes de secundaria de colegios públicos de Trujillo, en el contexto del estudio correspondiente a 2024.

## Archivos

- **Estudiantes_rendimiento_academico_GITHUB.csv:** base de datos utilizada en la investigación.
- **Rendimiento_academico_predicho.xlsx:** resultados de las predicciones generadas por el modelo.

Se incorporarán el cuestionario de investigación, el diccionario de variables y el código del modelo para facilitar la revisión del procedimiento.

## Descripción de los datos

La base contiene 10 000 registros y 30 factores considerados para la predicción. Incluye las columnas `InstitucionEducativa` y `Estudiante` como identificadores; estas no se utilizan como entradas de la red neuronal.

La variable objetivo es binaria:

- **0:** desaprobación.
- **1:** aprobación.

## Documentación metodológica

La documentación complementaria precisará el origen de los registros, el procedimiento de recolección y procesamiento, la correspondencia entre el cuestionario y la codificación, y la obtención de las calificaciones.

## Resultados

El archivo de predicciones permite consultar las salidas del modelo para los registros procesados. La evaluación del desempeño debe distinguir los conjuntos de entrenamiento, validación y prueba; las predicciones sobre toda la base no equivalen a una evaluación independiente.

## Uso

Los archivos se presentan como material complementario de la investigación. Para interpretar los resultados, deben consultarse la metodología y las limitaciones descritas en la tesis.

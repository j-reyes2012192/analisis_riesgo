Análisis del Riesgo de Prestatarios

Este repositorio contiene el proyecto Análisis del Riesgo de Prestatarios, cuyo objetivo es analizar datos históricos proporcionados por una división de préstamos de un banco para identificar patrones y factores clave que impactan el riesgo de incumplimiento de los prestatarios. Este análisis ayudará a crear una puntuación de crédito que permita evaluar la capacidad de pago de futuros clientes.

Preguntas a Resolver

El proyecto busca responder las siguientes preguntas:

¿Hay alguna conexión entre tener hijos y pagar un préstamo a tiempo?

¿Existe una conexión entre el estado civil y el pago a tiempo de un préstamo?

¿Existe una conexión entre el nivel de ingresos y el pago a tiempo de un préstamo?

¿Cómo afectan los diferentes propósitos del préstamo al reembolso a tiempo del préstamo?

Datos Utilizados

El dataset incluye las siguientes columnas:

children: Número de hijos en la familia

days_employed: Experiencia laboral en días

dob_years: Edad del cliente en años

education: Nivel educativo del cliente

education_id: Identificador del nivel educativo

family_status: Estado civil

family_status_id: Identificador del estado civil

gender: Género del cliente

income_type: Tipo de empleo

debt: Indicador de deuda previa en el pago de un préstamo

total_income: Ingreso mensual

purpose: Propósito del préstamo

Estructura del Proyecto

Inicialización y Exploración de Datos: Se cargan las librerías necesarias y se realiza un análisis inicial del dataset.

import pandas as pd
df = pd.read_csv('/datasets/credit_scoring_eng.csv')

Procesamiento de Datos: Limpieza, transformación y análisis estadístico de los datos.

Visualización y Resultados: Presentación de hallazgos clave y patrones identificados en los datos.

Conclusiones y Recomendaciones: Resumen de los factores que influyen en el riesgo de incumplimiento y recomendaciones basadas en los resultados.

Requisitos

Para ejecutar este proyecto, necesitas:

Python 3.x

Bibliotecas: pandas, numpy, matplotlib, seaborn

Jupyter Notebook (opcional, pero recomendado para reproducir los análisis)

Uso

Clona este repositorio:

git clone https://github.com/tuusuario/analisis-riesgo-prestatarios.git

Instala las dependencias necesarias.

Abre y ejecuta el archivo Jupyter Notebook incluido en el repositorio para explorar los análisis paso a paso.

Contribuciones

Si deseas contribuir a este proyecto, crea un fork del repositorio, realiza tus cambios y envía un pull request.

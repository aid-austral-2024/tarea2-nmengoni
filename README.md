# Trabajo Práctico 2 - Análisis Inteligente de Datos
**Maestría en Ciencias de Datos - AUSTRAL**

## Descripción
El objetivo de este desarrollo es optimizar el tiempo dedicado a la limpieza y procesamiento de los datos provenientes de Mercosur Online. A través de la automatización de estos procesos, se facilita un análisis inteligente del mercado de productos de diagnóstico de laboratorio, lo que permite evaluar la demanda, identificar patrones de competencia y tomar decisiones estratégicas más informadas sobre precios y posicionamiento.
El enfoque principal de este desarrollo es mejorar los procesos laborales, transformando tareas manuales en flujos automáticos más eficientes. El trabajo se lleva a cabo en dos fases principales:

**Análisis Exploratorio de Datos (EDA):**
En esta fase se identifican tendencias y relaciones clave en el mercado, que sirven como base sólida para la toma de decisiones estratégicas.

**Análisis Ad Hoc:** (en proceso)
Esta fase responde a preguntas específicas sobre el comportamiento del mercado y las estrategias de precios, proporcionando insights detallados que guían las decisiones estratégicas de la empresa.
*Nota 1: Una vez aprobado el EDA, se avanzara en la nueva etapa.*

## Fuente de Datos
Los datos utilizados en este análisis provienen de la plataforma Mercosur Online, una fuente confiable que proporciona información detallada sobre las importaciones. 
Debido a la naturaleza desorganizada de los archivos descargados, se requiere un proceso de limpieza y estructuración de los datos antes de proceder con el análisis.

## Estructura de los Archivos
La estructura de los archivos para este proyecto es la siguiente:
  - Carpeta de datos: MERCOSUR_ONLINE. Contiene los archivos descargados desde Mercosur Online.
  - index.qmd: Documento en formato Quarto, que contiene el código y la descripción del análisis.
  - index.html: Documento HTML generado a partir de index.qmd, que presenta el informe de los resultados.

## Tecnologías y Herramientas Utilizadas
Este proyecto fue realizado utilizando R, un lenguaje de programación y entorno para el análisis de datos. A continuación, se detallan los principales paquetes de R utilizados:
- readxl, readr, haven: Para la lectura de archivos de datos en diferentes formatos.
- dplyr, tidyr, purrr: Para la manipulación y transformación de datos.
- ggplot2: Para la visualización de datos.
- lubridate: Para el manejo y análisis de fechas.
- stringr, stringr: Para manipulación de texto.
- skimr, knitr, kableExtra: Para la presentación de resultados y creación de informes.
- scales, ggrepel: Para mejorar la visualización y el etiquetado en gráficos.

## Uso
El objetivo de este análisis es optimizar el tiempo de los analistas, permitiéndoles enfocarse en tareas estratégicas y no en el trabajo operativo. Esto se logra mediante la automatización de un proceso manual que actualmente forma parte del flujo laboral. Al automatizar las etapas de limpieza y transformación de los datos, se busca no solo reducir significativamente los tiempos de procesamiento, sino también mejorar la precisión y eficiencia de los resultados. De este modo, los analistas pueden centrarse en la interpretación de los datos y en la toma de decisiones más informadas y basadas en insights precisos.

*Nota 2: Este análisis tiene en cuenta la confidencialidad de los datos, por lo que los archivos han sido modificados y filtrados para cumplir con las normativas de privacidad y seguridad.*
*Nota 3: Debido al peso y la cantidad de archivos, solo se tomó una muestra representativa de los archivos necesarios para el análisis, ya que no era posible cargar todos en GitHub.*

## Contribución
Este repositorio está abierto a comentarios y mejoras. Se aceptan contribuciones de usuarios que deseen sugerir optimización de procesos o aportar nuevas ideas. 

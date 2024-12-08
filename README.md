# Trabajo Práctico 2 - Análisis Inteligente de Datos
**Maestría en Ciencias de Datos - AUSTRAL**

## Descripción
El objetivo de este desarrollo es optimizar el tiempo dedicado a la limpieza y procesamiento de datos de importación provenientes de Mercosur Online. A través de este proceso, se facilita un análisis inteligente del mercado de productos de diagnóstico de laboratorio, con el fin de evaluar la demanda, identificar patrones de competencia y tomar decisiones estratégicas informadas sobre precios y posicionamiento. Este enfoque busca mejorar los procesos laborales, transformando tareas manuales en flujos automáticos más eficientes.
Mediante un proceso de estructuración de datos desorganizados, se logran generar insights clave que optimizan las decisiones empresariales.

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
El análisis se centra en la automatización de un proceso manual que actualmente se realiza en el ambiente laboral. Con el uso de este análisis, se ha logrado optimizar el proceso de limpieza y transformación de los datos, reduciendo tiempos y mejorando la precisión de los resultados.
El trabajo se realiza en dos fases principales:
**Análisis Exploratorio de Datos (EDA):**
Identificación de tendencias y relaciones clave en el mercado, que sirven como base para la toma de decisiones.
**Análisis Ad Hoc:**
Responde a preguntas específicas sobre el comportamiento del mercado y las estrategias de precios, proporcionando insights más detallados que guían las decisiones estratégicas de la empresa.
*Nota: Este análisis tiene en cuenta la confidencialidad de los datos, por lo que los archivos han sido modificados y filtrados para cumplir con las normativas de privacidad y seguridad.*

## Contribución
Este repositorio está abierto a comentarios y mejoras. Se aceptan contribuciones de usuarios que deseen sugerir optimización de procesos o aportar nuevas ideas. Si deseas contribuir:
Haz un fork de este repositorio.
- Crea una nueva rama (git checkout -b nombre-de-tu-rama).
- Realiza tus cambios y haz un commit (git commit -am 'Descripción de los cambios').
- Haz push a la rama (git push origin nombre-de-tu-rama).
- Abre un pull request para integrar tus cambios.
Este proyecto está en constante mejora y cualquier aporte será bienvenido.

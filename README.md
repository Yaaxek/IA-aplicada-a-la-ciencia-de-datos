# IA aplicada a Data Science: Utilizando IA en la construcción de visualizaciones de datos

Este cuaderno documenta un proyecto de análisis de datos para **Zoop**, una gran minorista de e-commerce en México. El objetivo principal es generar visualizaciones clave y obtener *insights* estratégicos sobre la facturación, el perfil del cliente y el rendimiento de las ventas a lo largo de 2023.

## 🚀 Objetivos del Proyecto

Como analista de datos de Zoop, el desafío es:

1.  **Extraer y consolidar datos** de clientes y ventas de e-commerce.
2.  **Explorar y comprender** la estructura y el contenido de los datos.
3.  **Construir visualizaciones significativas** que respondan a preguntas de negocio clave.
4.  **Aplicar técnicas de *storytelling*** en las visualizaciones para mejorar la comunicación de resultados.
5.  **Utilizar la Inteligencia Artificial (IA)**, específicamente ChatGPT, como asistente para guiar el proceso de análisis exploratorio y la creación de gráficos.
6.  **Utilizar la Inteligencia Artificial (IA)**, específicamente Gamma App, como asistente para crear el informe final.


## 📊 Datos Utilizados

Se utilizan tres conjuntos de datos, obtenidos de repositorios de GitHub:

-   `clientes_zoop.csv`: Información detallada de los clientes (ID de compra, ID de cliente, ubicación, edad, sexo biológico, participación en cashback, calificación de compra).
-   `ventas_zoop.csv`: Datos de ventas (ID de compra, fecha, hora, categoría, precio unitario, cantidad, envío, método de pago).
-   `zoop_pay.csv`: (Utilizado en el desafío) Clientes pre-registrados en Zoop Pay, la billetera digital de la empresa.

## 🛠️ Metodología

El proyecto sigue un enfoque paso a paso:

1.  **Carga y Estandarización de Datos**: Lectura de los CSVs y normalización de los nombres de columnas.
2.  **Consolidación de Datos**: Unificación de las bases de `ventas` y `clientes` en un único DataFrame (`df`), y posterior unión con `zoop_pay` para el desafío.
3.  **Exploración de Datos (EDA)**: Análisis inicial de la estructura, tipos de datos, estadísticas descriptivas y valores únicos de ambos DataFrames (`clientes` y `ventas`).
4.  **Definición de Visualizaciones**: Identificación de los tipos de gráficos más adecuados para responder a preguntas específicas de negocio, con el apoyo de sugerencias de ChatGPT.
5.  **Construcción de Visualizaciones (Versión Inicial)**: Creación de 7 gráficos básicos para abordar las siguientes preguntas:
    -   Métodos de pago más utilizados en 2023.
    -   Facturación por categoría en 2023.
    -   Ventas a lo largo de los meses en 2023.
    -   Venta por trimestre por método de pago.
    -   Proporción de clientela en el programa de cashback.
    -   Distribución de las evaluaciones del producto.
    -   Distribución del público por edad y sexo biológico.
6.  **Aplicación de *Storytelling***: Refinamiento de las visualizaciones mediante la personalización de colores (siguiendo la paleta de Zoop), adición de títulos, etiquetas, rótulos, anotaciones y elementos visuales para mejorar la claridad y el impacto de los *insights*.
7.  **Exportación de Visualizaciones**: Conversión de los gráficos a funciones para facilitar su exportación como imágenes PNG.

## ✨ Visualizaciones Clave Refinadas

Se han refinado 7 visualizaciones, aplicando la identidad de marca de Zoop y técnicas de *storytelling*:

1.  **Métodos de pago más utilizados en 2023** (Gráfico de barras con texto informativo).
2.  **Facturación por categoría de producto en 2023** (Gráfico de barras horizontales con *insights* destacados).
3.  **Ventas totales mensuales en 2023** (Gráfico de líneas con puntos destacados de eventos clave).
4.  **Ventas por Trimestre y Método de Pago en 2023** (Gráfico de barras apiladas con cuadrícula).
5.  **Proporción de usuarios en el programa de Cashback** (Gráfico de dona con porcentajes y colores de marca).
6.  **Distribución de las evaluaciones de las compras en 2023** (Histograma con anotaciones sobre promedio y moda).
7.  **Distribución de la Edad por Sexo Biológico de los clientes** (Boxplot con anotaciones de cuartiles).

## 💻 Tecnologías Utilizadas

-   **Python**
-   **Pandas** para manipulación y análisis de datos.
-   **Matplotlib** para la creación de gráficos.
-   **Seaborn** para visualizaciones estadísticas mejoradas.
-   **ChatGPT** para asistencia en la generación de código y *brainstorming* de visualizaciones.
-   **Gamma app** para asistencia en la generación del informe.

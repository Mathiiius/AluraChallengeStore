# Análisis de Ventas y Rendimiento de Tiendas Alura Store

**Descripción**

Este proyecto tiene como objetivo ayudar al Sr. Juan a decidir cuál tienda de la cadena Alura Store debería vender para iniciar un nuevo emprendimiento. A través del análisis de datos de ventas, ingresos, productos, calificaciones de clientes y costos de envío de las cuatro tiendas, se identifica la tienda menos eficiente.

# Estructura del Proyecto

1. Importación de Datos
Se cargaron los datos de las cuatro tiendas desde archivos CSV alojados en URLs, utilizando pandas para manipulación y análisis de datos.

2. Análisis de Facturación
Se calculó el ingreso total de cada tienda sumando los valores de la columna Precio. Esto permite comparar el desempeño comercial en términos de ingresos brutos.

3. Ventas por Categoría
Se analizó la cantidad de productos vendidos por categoría para cada tienda, identificando las categorías más y menos populares. Se presentó un desglose por tienda para facilitar la comparación.

4. Calificación Promedio de Clientes
Se calculó la calificación promedio dada por los clientes para cada tienda, lo que da una medida de satisfacción y calidad percibida.

5. Productos Más y Menos Vendidos
Se identificaron los productos con mayor y menor cantidad de ventas en cada tienda, evidenciando qué productos impulsan o limitan las ventas.

6. Costo de Envío Promedio
Se calculó el costo de envío promedio para cada tienda, para evaluar el impacto de los costos logísticos en la rentabilidad y competitividad.

# Visualizaciones

Para cada análisis se generaron gráficos diferentes que facilitan la interpretación visual de los datos:

* Análisis de facturación: Gráfico de barras verticales mostrando ingresos totales por tienda.

* Ventas por categoría: Gráfico de líneas comparando la cantidad vendida por categoría y tienda.

* Calificación promedio: Gráfico de pastel mostrando la distribución de calificaciones promedio.

* Productos más y menos vendidos: Tabla resumen con productos destacados y sus ventas.

* Costo de envío promedio: Gráfico de dispersión con costos de envío por tienda.

# Resultados Clave

* La Tienda 1 es la que genera mayores ingresos, aunque con la calificación promedio más baja.

* Las categorías de productos más vendidas se mantienen constantes en todas las tiendas, con “Muebles” y “Electrónicos” liderando.

* La Tienda 3 tiene la mejor calificación promedio, seguida por Tienda 2 y Tienda 4.

* El costo de envío más bajo corresponde a la Tienda 4, aunque esta tienda también tiene los menores ingresos.

* La Tienda 4 presenta un rendimiento general más bajo en comparación con las demás.

# Conclusión

Con base en el análisis de todos los factores mencionados, se recomienda que el Sr. Juan venda la Tienda 4, que es la menos eficiente en ingresos y ventas, aunque mantiene un costo de envío más bajo. Esto permitirá concentrar esfuerzos en las tiendas con mejor desempeño para maximizar el éxito del nuevo emprendimiento.

# Tecnologías Utilizadas

* Python 3.x

* Pandas

* Matplotlib

* Seaborn

# Cómo ejecutar el proyecto

1. Asegúrate de tener Python y las librerías pandas, matplotlib y seaborn instaladas.

2. Ejecuta el código paso a paso en un Jupyter Notebook o Google Colab.

3. Revisa los gráficos y tablas generadas para comprender el análisis.

4. Lee el informe final para conocer la recomendación basada en los datos.

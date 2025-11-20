# Análisis de Desempeño de Tiendas para Decisión de Venta

## Introducción
Este proyecto tiene como objetivo analizar el desempeño de cuatro tiendas (`tienda1`, `tienda2`, `tienda3`, `tienda4`) con el fin de proporcionar una recomendación fundamentada al Sr. Juan sobre cuál de estas tiendas sería la más conveniente para vender, maximizando el beneficio y el potencial de negocio.

El análisis se basa en diversas métricas clave obtenidas de los datos de ventas de cada tienda, incluyendo ingresos, categorías de productos, satisfacción del cliente, productos estrella y de bajo rendimiento, y aspectos logísticos como los costos de envío. Además, se realizó un análisis geográfico para identificar patrones de ventas en diferentes ubicaciones.

## Fuentes de Datos
Los datos para este análisis provienen de cuatro archivos CSV distintos, cada uno correspondiente a una tienda:
*   `tienda_1.csv`
*   `tienda_2.csv`
*   `tienda_3.csv`
*   `tienda_4.csv`

Cada archivo contiene información detallada sobre las transacciones, incluyendo `Producto`, `Categoría del Producto`, `Precio`, `Costo de envío`, `Fecha de Compra`, `Vendedor`, `Lugar de Compra`, `Calificación`, `Método de pago`, `Cantidad de cuotas`, `lat` (latitud) y `lon` (longitud).

## Análisis Realizados
Se llevaron a cabo los siguientes análisis para evaluar el rendimiento de cada tienda:

1.  **Análisis de Facturación (Ingresos Totales):** Se calculó el ingreso total generado por cada tienda para identificar cuál tiene el mayor volumen de ventas.
2.  **Ventas por Categoría:** Se determinó la cantidad de productos vendidos por cada categoría en cada tienda, mostrando las categorías más populares y su distribución.
3.  **Calificación Promedio de Clientes:** Se calculó la calificación promedio de los clientes para cada tienda, proporcionando una medida de la satisfacción general.
4.  **Productos Más y Menos Vendidos:** Se identificaron los 5 productos con mayor y menor volumen de ventas en cada tienda para comprender las preferencias de los clientes y el rendimiento individual de los productos.
5.  **Costo de Envío Promedio:** Se calculó el costo de envío promedio para cada tienda, un factor importante considerando que este costo es asumido por el cliente.
6.  **Análisis Geográfico de Ventas:** Se mapearon las ventas de cada tienda utilizando datos de latitud y longitud, visualizando la distribución geográfica de los productos vendidos e identificando áreas con mayor concentración de ventas.

## Herramientas Utilizadas
*   **Python:** Lenguaje de programación principal para el análisis de datos.
*   **Pandas:** Biblioteca para manipulación y análisis de datos.
*   **Matplotlib:** Biblioteca para la creación de gráficos estáticos.
*   **Folium:** Biblioteca para la creación de mapas interactivos.

## Hallazgos Clave y Recomendación

### Hallazgos:
*   **Ingresos:** La Tienda 1 presenta los ingresos totales más altos, seguida de cerca por la Tienda 2. La Tienda 4 tiene los ingresos más bajos.
*   **Categorías de Productos:** 'Muebles' y 'Electrónicos' son consistentemente las categorías más vendidas en todas las tiendas.
*   **Calificación de Clientes:** La Tienda 3 tiene la calificación promedio más alta (4.05), lo que indica una mayor satisfacción del cliente.
*   **Productos (Ejemplos):** Se observaron variaciones interesantes; por ejemplo, 'Microondas' es un top-seller en Tienda 1 y 2, pero un low-seller en Tienda 3.
*   **Costo de Envío:** La Tienda 1 tiene el costo de envío promedio más alto, mientras que la Tienda 4 tiene el más bajo.
*   **Distribución Geográfica:** El mapa interactivo de Folium muestra clústeres de ventas, permitiendo identificar zonas de alta actividad por tienda.

### Recomendación para el Sr. Juan:
Basándonos en un análisis integral que busca equilibrar ingresos, satisfacción del cliente y eficiencia operativa, **se recomienda al Sr. Juan vender la Tienda 3.**

#### Justificación:
Aunque la Tienda 1 lidera en ingresos, la **Tienda 3 se destaca por su excepcional satisfacción del cliente** (la calificación promedio más alta). Una alta satisfacción del cliente es un activo invaluable que impulsa la retención, la lealtad y el crecimiento sostenible a largo plazo, factores cruciales para cualquier adquirente. Además, sus ingresos son muy competitivos y presenta **costos de envío eficientes**.

Las debilidades menores, como el bajo rendimiento de ciertos productos en la Tienda 3, son problemas manejables mediante estrategias de marketing específicas o ajustes de inventario, lo cual es más sencillo de optimizar que mejorar una baja satisfacción general del cliente o altos costos operativos sistémicos.

La Tienda 1, a pesar de sus altos ingresos, enfrenta desafíos en la satisfacción del cliente y costos de envío elevados, lo que podría implicar una inversión significativa para mejorar su reputación y eficiencia. La Tienda 2 es una opción sólida, pero la Tienda 3 ofrece un diferenciador clave en la experiencia del cliente que es fundamental para el éxito continuo y el valor a largo plazo.

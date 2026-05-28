# Taller N°2 usando Pandas

## Inteligencia Artificial

**Estudiantes:** Brayan David Riascos Murillo  
**Materia:** Inteligencia Artificial  
**Universidad:** Universidad del pacifico  
**Docente:** Wilman Quiñones 


---

# Introducción

En este taller se trabajó con la librería Pandas de Python utilizando Google Colab.

Durante la actividad se realizaron diferentes ejercicios relacionados con manejo y organización de datos utilizando productos tecnológicos y de oficina como ejemplo.

A lo largo del desarrollo se practicaron temas como:

- Creación de DataFrames.
- Operaciones matemáticas entre columnas.
- Cálculo de porcentajes.
- Estadística descriptiva.
- Filtrado y organización de información.

Además, los ejercicios permitieron comprender mejor cómo Pandas facilita el trabajo con datos de manera más sencilla y organizada.

---

# Objetivo del Taller

Comprender el funcionamiento básico de la librería Pandas mediante ejercicios prácticos que permitieran trabajar, organizar y analizar información utilizando Python.

---

# Herramientas Utilizadas

- Python
- Pandas
- Google Colab
- GitHub

---

# Desarrollo del Taller

## Punto 1 - Creación y exploración del DataFrame

En esta sección se creó el DataFrame `df_productos` utilizando información de 60 productos relacionados principalmente con tecnología y oficina.

Posteriormente se realizó una exploración inicial de los datos utilizando funciones como:

- `head()`
- `tail()`
- `dtypes`
- `shape`
- `describe()`

Esto permitió conocer la estructura general del conjunto de datos y verificar que la información estuviera correctamente organizada.

---

## Punto 2 - Operaciones matemáticas entre columnas

En este punto se realizaron diferentes operaciones utilizando columnas del DataFrame.

Se crearon nuevas variables como:

- `Total_Venta`
- `Costo_Total`

Además, se calculó:

- El promedio general de ventas.
- El producto con mayor valor de inventario.
- El producto con menor valor de inventario.

Estas operaciones permitieron analizar el comportamiento económico de los productos dentro del inventario.

---

## Punto 3 - Porcentajes y análisis

En esta sección se realizaron cálculos relacionados con impuestos, ganancias, pérdidas y porcentajes de participación.

Se crearon las siguientes columnas:

- `IVA`
- `Ganancia_Estimada`
- `Perdida_Estimada`
- `Porcentaje_Participacion`

También se aplicó un filtro para identificar productos con una participación superior al 15% dentro del total de ventas.

---

## Punto 4 - Estadística descriptiva

En este punto se calcularon diferentes medidas estadísticas utilizando las columnas del DataFrame.

Se trabajó con:

- Media
- Mediana
- Moda
- Desviación estándar
- Valores máximos
- Valores mínimos

Estas métricas permitieron obtener una visión más clara del comportamiento de los datos relacionados con precios, cantidades y ventas.

---

## Punto 5 - Filtrado y ordenamiento de datos

Finalmente, se realizó un filtrado utilizando únicamente los productos pertenecientes a la categoría `Tecnología`.

Después de aplicar el filtro, los datos fueron ordenados de mayor a menor según el valor de `Total_Venta`.

Esto permitió identificar rápidamente cuáles productos tecnológicos representan mayor impacto económico dentro del inventario.

---

# Interpretación y Análisis de Resultados para la Toma de Decisiones

## Participación de productos en ventas

Al aplicar el filtro de participación superior al 15%, no se encontraron productos que alcanzaran dicho porcentaje.

El producto con mayor participación fue **Laptop Gamer** con aproximadamente $6.94\%$ del total de ventas.

Este resultado indica que las ventas se encuentran distribuidas entre múltiples productos y no dependen únicamente de uno solo.

Desde el punto de vista empresarial, esto representa un portafolio más equilibrado y menos riesgoso, ya que una caída en las ventas de un producto específico no afectaría de forma extrema el inventario completo.

---

## Desviación estándar de cantidades

La desviación estándar obtenida para la columna `Cantidad` fue de aproximadamente $4.42$ unidades.

Esto indica que las cantidades de productos almacenadas en inventario no presentan variaciones exageradas entre sí.

Desde una perspectiva logística, este comportamiento puede interpretarse como una distribución relativamente estable del stock, facilitando el control de inventario y reduciendo riesgos de sobreabastecimiento o escasez extrema.

---

## Producto con mayor valor de inventario

El valor máximo encontrado en `Total_Venta` fue de:

$\$27,500,000.00$

correspondiente a un producto de la categoría Tecnología.

Este resultado demuestra que ciertos productos representan una inversión importante dentro del inventario y requieren mayor seguimiento administrativo y logístico.

En términos empresariales, productos con valores altos necesitan:

- Mayor control de stock.
- Seguimiento constante.
- Estrategias de protección y rotación.
- Supervisión de pérdidas o daños.

---

## Producto con menor valor de inventario

El valor mínimo encontrado en `Total_Venta` fue de:

**$900,000.00**

Esto indica que algunos productos tienen una participación económica mucho menor dentro del inventario general.

Aunque representan menos impacto financiero, siguen siendo importantes para mantener variedad y complementar el portafolio de productos ofrecidos.

---

## Filtrado de productos tecnológicos

Después de aislar la categoría `Tecnología` en el DataFrame `df_tecnologia`, se realizó un ordenamiento de mayor a menor según `Total_Venta`.

Este análisis permitió identificar rápidamente cuáles productos tecnológicos generan mayores valores de venta y cuáles tienen menor impacto económico.

Desde el punto de vista empresarial, este tipo de organización facilita:

- Priorización de productos.
- Planeación de compras.
- Gestión de inventario.
- Estrategias comerciales.
- Análisis de rentabilidad.

---

# Conclusiones

- Durante el desarrollo del taller permitio entender como funciona la librería Pandas y cómo puede utilizarse para trabajar información de manera más organizada.

- La creación de DataFrames permitió manipular datos relacionados con inventarios de una forma más sencilla y visual.

- Las operaciones matemáticas entre columnas facilitaron el cálculo automático de valores como ventas, costos, ganancias e impuestos sin necesidad de realizar operaciones manuales producto por producto.

- Las medidas estadísticas ayudaron a interpretar mejor el comportamiento de los datos, especialmente en aspectos relacionados con precios, cantidades y valores de venta dentro del inventario.

- Los filtros y ordenamientos permitieron identificar productos específicos y analizar cuáles generan un mayor impacto económico dentro de la categoría Tecnología.

- Este taller también permitió entender cómo Python y Pandas pueden utilizarse como herramientas útiles para el análisis básico de datos y apoyo en la toma de decisiones.

---

# Notebook en Google Colab

Enlace al Notebook desarrollado en Google Colab:

[Abrir Notebook en Google](https://colab.research.google.com/drive/1U0K0L3HbeAatfE5TSIFolbKKjWibRYwl?usp=sharing)

---

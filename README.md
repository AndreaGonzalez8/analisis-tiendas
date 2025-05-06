## Proyecto de Análisis de Tiendas – Alura Store

Este informe corresponde al trabajo realizado durante el reto de ciencia de datos propuesto por **Alura Latam**, dentro del curso de Introducción a Python. El análisis tiene como finalidad brindar una recomendación objetiva al **Sr. Juan**, quien planea vender una de sus tiendas para invertir en un nuevo emprendimiento.

---

## Objetivo General

El propósito de este estudio es **evaluar el rendimiento de las 4 tiendas de Alura Store** con base en datos reales de ventas, satisfacción del cliente y costos logísticos, para tomar una decisión informada sobre cuál de ellas debería ser vendida.

---

## Criterios Analizados

Durante el desarrollo del proyecto, se exploraron y visualizaron los siguientes indicadores clave:

-  **Ingresos generados por tienda**  
-  **Categorías más y menos populares en ventas**  
-  **Calificaciones promedio otorgadas por los clientes**  
-  **Productos con mayor y menor rotación**  
-  **Costo promedio de envío por tienda**

---

##  Organización del Proyecto

- **Carga y exploración de los datos:** Importación de archivos CSV y limpieza básica.  
- **Análisis exploratorio:** Uso de `pandas`, `matplotlib` y `seaborn` para extraer insights.  
- **Visualización de datos:** Creación de gráficos representativos para cada métrica.  
- **Conclusión final:** Recomendación sobre la tienda a vender basada en datos objetivos.

---

##  Principales Visualizaciones e Interpretaciones

###  Ingresos por Tienda
Un gráfico de barras muestra claramente que la **Tienda 1** lidera en ingresos, mientras que la **Tienda 4** genera el menor valor acumulado.

###  Ventas por Categoría de Producto
Las categorías de **"Muebles"** y **"Electrónica"** concentran la mayoría de las ventas, siendo las más rentables. **Tienda 4** muestra bajo rendimiento incluso en estas categorías.

###  Calificaciones de Clientes
Aunque todas las tiendas tienen un promedio cercano a 4 sobre 5, las tiendas con mayor volumen presentan ligeras caídas, posiblemente por mayor carga operativa.

###  Productos Más Vendidos
Los productos más populares pertenecen a las categorías líderes. **Tienda 1** tiene mayor variedad en el top de productos vendidos.

###  Productos Menos Vendidos
Libros y artículos musicales figuran entre los menos vendidos, afectando la rotación y rentabilidad.

### Costo de Envío Promedio
Las tiendas con más pedidos tienen mayores costos logísticos. **Tienda 4**, con pocas ventas, presenta el costo más bajo, pero refleja menor actividad general.

>  **Conclusión de análisis parcial:** Tienda 4 destaca negativamente en casi todos los aspectos evaluados, lo que la posiciona como la opción más lógica para ser vendida.

---

##  ¿Cómo usar este notebook?

1. Abre el archivo `proyecto_alura_store.ipynb` en Google Colab.  
2. Verifica que los enlaces a los archivos `.csv` estén activos.  
3. Ejecuta cada celda secuencialmente para reproducir el análisis.  
4. Observa los gráficos generados y consulta las conclusiones al final del documento.

---

## ✅ Recomendación Final

Tras un análisis integral, se recomienda que el **Sr. Juan considere vender la Tienda 4**, ya que:

- Tiene los **menores ingresos** registrados.
- Muestra **baja participación** en las categorías más rentables.
- **No sobresale en calificaciones** ni en volumen de ventas.
- Su **rotación de productos es limitada**, lo cual puede estancar su crecimiento.
- El **costo de envío bajo** responde a la baja cantidad de transacciones, no a una operación eficiente.

Vender esta tienda permitirá optimizar el portafolio del negocio, liberar recursos y canalizarlos hacia unidades con mejor desempeño.

---

##  Autoría

**Desarrollado por:** *Paula Andrea González Sepúlveda*  
**Curso:** *Formación en Ciencia de Datos – Alura Latam*  
**Herramientas utilizadas:** `Python`, `Pandas`, `Matplotlib`, `Seaborn`, `Google Colab`

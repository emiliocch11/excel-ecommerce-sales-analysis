# E-commerce Sales Analysis | Ecuador

**Data Analytics con Excel, Power Query y Power Pivot**  
**Proyecto académico | Data Analyst Expert · Ciencia de Datos Ecuador · 2026**

## Descripción

Este proyecto analiza un conjunto de datos **sintéticos** de ventas online de una tienda ecuatoriana, generado con apoyo de inteligencia artificial para simular errores habituales de registros comerciales. El trabajo se desarrolló en dos entregas: (1) preparación y análisis de datos y (2) desarrollo de un dashboard interactivo en Excel.

**Herramientas:** Microsoft Excel, Power Query, Power Pivot, tablas dinámicas, gráficos dinámicos y segmentadores.

## Problema de negocio

Los datos de ventas presentaban formatos de fechas inconsistentes, textos no normalizados, precios con formatos distintos, valores erróneos y registros duplicados. Estas inconsistencias dificultaban interpretar el desempeño comercial, comparar ciudades y monitorear el estado de los pedidos.

El objetivo fue preparar una base de análisis y convertirla en visualizaciones que permitan explorar ventas, ingresos y seguimiento logístico.

## Datos

- **Fuente:** dataset sintético de ventas online de Ecuador, elaborado con apoyo de IA; no representa ventas reales de una compañía.
- **Dataset original según presentación:** 191 registros y 12 columnas.
- **Archivo final revisado:** 164 registros de pedidos y 13 columnas visibles, incluida `Correo_Valido`.
- **Variables:** identificador del pedido, fecha, cliente, correo electrónico, ciudad, país, categoría, producto, cantidad, precio unitario, medio de pago y estado del pedido, entre otras.

> La diferencia entre 191 registros originales y 164 finales no demuestra por sí sola que se hayan eliminado exactamente 27 duplicados. La presentación describe varios pasos de depuración, pero no incluye una conciliación detallada de exclusiones.

## Metodología

### Entrega 1 · Preparación, transformación y análisis

1. Importación del dataset en Excel.
2. Limpieza y transformación con **Power Query**: tipos de datos, estandarización de texto, corrección de formatos y eliminación de filas vacías o duplicadas.
3. Uso del editor avanzado y lenguaje **M**, con apoyo de IA para tratar inconsistencias en fechas y correos.
4. Construcción de un modelo de análisis con **Power Pivot**.
5. Elaboración de tablas dinámicas para cantidades, ingresos, distribución trimestral y estados de pedidos.
6. Exploración mediante filtros y segmentadores.

### Entrega 2 · Dashboard interactivo

1. Reutilización del dataset preparado.
2. Configuración de una consulta y conexión en Excel mediante **Power Query**.
3. Construcción de visualizaciones y segmentadores para explorar indicadores.
4. Organización del dashboard en una hoja dedicada.

**Nota sobre actualización:** el archivo contiene una conexión de consulta y objetos de análisis, pero **no se ha verificado** que pueda actualizarse de extremo a extremo en otra computadora al agregar nuevos datos. Para reproducir esa funcionalidad se debe revisar el origen de datos y probar **Datos → Actualizar todo** en Excel de escritorio.

## Principales hallazgos

Los siguientes hallazgos aparecen en la presentación final del proyecto y corresponden a un **escenario simulado**, no a resultados comerciales reales.

| Indicador | Resultado |
| --- | ---: |
| Ciudad con mayores ingresos | Santo Domingo: **USD 153.048,16** |
| Ciudad con mayor cantidad de unidades | Guayaquil: **41 unidades** |
| Pedidos en proceso | **53 de 164** |
| Pedidos entregados | **35 de 164** |
| Pedidos devueltos | **30 de 164** |
| Pedidos cancelados | **27 de 164** |
| Pedidos pendientes | **19 de 164** |
| Mayor ingreso trimestral reportado | T3 2024: **USD 199.211,52** |
| Menor ingreso trimestral reportado | T4 2025: **USD 134,96** |

**Interpretación:** las diferencias entre volumen e ingresos por ciudad sugieren revisar la mezcla de productos y los valores promedio de venta. El elevado número de pedidos en proceso motiva investigar posibles retrasos operativos. La disminución de ingresos hacia finales de 2025 merece un análisis de causas antes de concluir que existe una caída estructural de la demanda.

> En la presentación original se utilizan de forma intercambiable “pedidos” y “unidades” para comparar ciudades. Aquí se usa **unidades** para el indicador de cantidad, consistente con el campo `Cantidad` del Excel.

## Archivos del proyecto

| Archivo | Contenido |
| --- | --- |
| [`data/entrega-1-limpieza-analisis.xlsx`](data/entrega-1-limpieza-analisis.xlsx) | Datos preparados, tablas y análisis de la primera entrega |
| [`data/entrega-2-dashboard.xlsx`](data/entrega-2-dashboard.xlsx) | Dashboard y análisis de la segunda entrega |
| [`presentation/analisis-ventas-online.pptx`](presentation/analisis-ventas-online.pptx) | Presentación del proceso y hallazgos |

## Cómo explorar el proyecto

1. Descarga `data/entrega-2-dashboard.xlsx` y ábrelo en **Microsoft Excel de escritorio**.
2. Abre la hoja `DASHBOARD` para explorar las visualizaciones.
3. Revisa la hoja `Datos_Ventas_Online` para observar los datos preparados.
4. Si quieres probar la actualización de datos, revisa primero la configuración de **Datos → Consultas y conexiones**, ya que la fuente original podría necesitar vincularse nuevamente.
5. Consulta la presentación para conocer la interpretación y las conclusiones.

## Alcance y limitaciones

- Los datos son simulados y se usan con fines de aprendizaje y demostración técnica.
- Los resultados son descriptivos; las recomendaciones no establecen causalidad.
- No se incluye aquí una auditoría completa de registros eliminados ni una prueba independiente de actualización automática con una nueva fuente.
- Las consultas, conexiones, segmentadores y gráficos están guardados en los archivos de Excel, por lo que su uso completo requiere una versión compatible de Excel de escritorio.

## Autor

**Emilio Caldas**  
[LinkedIn](https://www.linkedin.com/in/emiliocaldas/) · [Correo](mailto:emiliocch11@gmail.com)

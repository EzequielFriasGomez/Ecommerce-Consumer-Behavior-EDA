# Análisis de Ventas y Estacionalidad: Sector Electrónica

**Contexto del Proyecto** Este repositorio contiene el código y los resultados de un análisis exploratorio (EDA) basado en un dataset de e-commerce simulado. El objetivo principal fue limpiar los datos crudos y encontrar patrones reales de compra para optimizar el presupuesto publicitario. 

**El Problema Comercial** La empresa estaba invirtiendo en marketing de forma generalizada. Necesitábamos responder dos preguntas básicas para dejar de perder plata: ¿Quién nos compra realmente? y ¿En qué momento del año lo hacen?

**El Proceso** Utilizando Python y Pandas, tomé el archivo crudo y armé un pipeline de limpieza:
- Conversión y estandarización de valores monetarios.
- Segmentación de los clientes en rangos etarios lógicos.
- Mapeo de fechas para agrupar las compras por estación del año.
- Exportación del modelo limpio para su visualización en Power BI.

**Lo que dicen los datos** Al cruzar las variables, el tablero expuso dos realidades muy marcadas:
1. **El público joven no sostiene el rubro:** La franja de 18 a 25 años genera la mitad de ingresos que el segmento de 35 a 50 años. La electrónica de alto valor requiere poder adquisitivo, y nuestro cliente fuerte es el adulto.
2. **El verano es una temporada muerta:** Las ventas caen a su punto más bajo durante el verano ($2.46k), mientras que el otoño concentra el pico absoluto de demanda ($4.08k).

**Decisión Estratégica** Con estos números en la mesa, la recomendación comercial es clara: hay que recortar fuertemente la publicidad dirigida a jóvenes y el gasto de pauta en verano. Ese presupuesto debe reasignarse a campañas agresivas a principios de otoño, apuntando directamente a la franja de 35 a 50 años.

**Herramientas:** Python (Pandas) | Power BI
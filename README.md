# Explicativo Power BI Buenas Prácticas de Plantas :rotating_light:

El siguiente explicativo contiene algunas consideraciones a tener para interpretar de manera óptima el dashboard desarrollado.

El encabezado de cada página, tiene por finalidad realizar todos los filtros necesarios para obtener las mediciones para cierto subconjunto de datos recopilados. Por ejemplo, se puede realizar un filtro por compañía, por fecha, zona geofráfica, etc.
Notar, por ejemplo, que para una mayor facilidad en el uso de los filtros, conviene primero filtrar por compañía, y posteriormente por alguna de sus gerencias/SI o zonas geográficas.

El Power BI presenta en total 14 páginas:
* 1 a modo de resumen. Esta página contiene un cuadro para cada una de las 13 prácticas, a las cuales se puede acceder presionando CTRL + Click Izquierdo en la respectiva imagen o ícono.
* 13 representando una para cada práctica y entregando un mayor detalle de estas.

## Consideraciones

 El cumplimiento de cada práctica tiene asociado un color: 
- Rojo para un desempeño deficiente (0 - 79%) :heavy_minus_sign:
- Amarillo para un desempeño intermedio (80-89%) :monocle_face:
- Verde para un desempeño bueno (90-99%) :heavy_plus_sign:

Respecto al cálculo de las métricas:

* La métrica *Total Repuestas Válidas* y *Verificaciones Válidas*, representa el número total de preguntas respondidas con *Cumple / No cumple*, sin considerar aquellas con respuesta *No aplica*.

* El cumplimiento general y de cada práctica es calculado a partir del porcentaje de respuestas *Cumple* obtenidas del total de respuestas válidas, es decir, respuestas que Aplican. Por ende, se toma la suma de todas las preguntas de cada práctica, y se divide por el total de preguntas respondidas.

# 🏘️ MODELO DE EXPOSICIÓN

El modelo de exposición (también conocido como inventario de edificios y habitantes) para Santiago de los Caballeros, puede utilizarse junto con modelos de múltiples amenazas naturales y tecnológicas, y modelos de vulnerabilidad física y social, en el análisis de riesgo catastrófico.

Para Santiago se recopilaron más de 10 conjuntos de datos diferentes, incluido el conjunto de datos de referencia del uso del suelo de la ciudad que presenta el propósito económico del suelo por lote. Se recopilaron conjuntos de datos adicionales que contenían el año de construcción, el material de construcción predominante y el número promedio de pisos por cuadra de la ciudad. De estas fuentes se obtuvo toda la información requerida para modelar la exposición. 
 

## Variables básicas para la clasificación de edificaciones
Se identificaron múltiples variables para la clasificación de las edificaciones. Las siguientes figuras muestran ejemplos de la distribución de las carácteristicas constructivas en la ciudad, tales como: año de construcción, material predominante de las paredes exteriores, costo por lote por m2 y calidad de la construcción.

<p >
  <img src="../Mapas/exposicion/SDC_Ano.png" alt="Modelo de exposición - Modelo de exposición - Periodo de construccion" width="500">

  <img src="../Mapas/exposicion/SDC_Material_Paredes.png" alt="Modelo de exposición - Material de paredes" width="500">

  <img src="../Mapas/exposicion/SDC_costos.png" alt="Modelo de exposición - Costo por lote por m2" width="500">

  <img src="../Mapas/exposicion/SDC_calidad.png" alt="Modelo de exposición - Calidad de la construcción" width="500">
</p>

## Información en las bases de datos de exposición
El modelo de exposición hace referencia a:
- **Material constructivo:** es el material predominante del sistema constructivo de la edificación. Los más comunes son la mampostería y sus variantes (confinada, reforzada, simple o sin refuerzo), el concreto reforzado y otras tipologías en menor proporción (madera, adobe, bahareque).
- **Sistema resistente a las cargas laterales:** es el sistema que resiste la acción de las fuerzas sísmicas. Los más comunes son los muros de cortante y los marcos o pórticos.
- **Número de pisos:** esta veriable se encuentra directamente en la base de datos.
- **Ductilidad esperada de la edificación:** hace referencia a la capacidad de la estructura a soportar cargas laterales sin perder su integridad o poner en riesgo la vida de los ocupantes, los componentes y sus contenidos. A mayor ductilidad, mejor el desempeño de la estructura durante un sismo. Por lo general una estructura se clasifica con baja, mediana o alta ductilidad. Esta variable se asocia con el cumplimiento de las disposiciones del código sísmico o la formalidad de la construcción.
- **Uso de la edificación (ocupación):** se refiere al uso, ocupación o destino de la edificación, por ejemplo, residencial, comercial, industrial, institucional, educativo y médico o de salud.
- **Valor del costo de reemplazo:** es el valor económico de la estructura y sus componentes estructurales y no estructurales. Excluye el valor del lote. Este valor puede ser mayor al costo actual de la edificación, si esta debe construirse de nuevo teniendo en cuenta nuevas previsiones de calidad constructiva y sismo-resistente.

Para la clasificación de las estructuras se utiliza la taxonomía de GEM, la cual cuenta con un [glosario en línea](https://taxonomy.openquake.org/) el cual facilita el entendimiento de los códigos utilizados para la clasificación de la exposición y vulnerabilidad.


## Referencias
Detalles adicionales sobre la metodología pueden encontrarse en el reporte [Evaluación del riesgo sísmico para Santiago de los Caballeros](./TREQ_Deliverable_D262_Riesgo_Sismico_Santiago.pdf)
# 🏘️ MODELO DE EXPOSICIÓN

El modelo de exposición (también conocido como inventario de edificios y habitantes) para Santiago de los Caballeros, puede utilizarse junto con modelos de múltiples amenazas naturales y tecnológicas, y modelos de vulnerabilidad física y social, en el análisis de riesgo catastrófico.

Se utilizaron un total de 29 conjuntos de datos para definir el modelo de exposición. Estos incluyen el censo oficial de población y hogares (proyectado a 2020), la base de datos catastral de la ciudad (2020), el conjunto de datos de uso de suelo (2016) y el desarrollo histórico del límite urbano de la ciudad desde 1760 hasta 2015. Adicionalmente, la Pontificia Universidad Católica del Ecuador (PUCE), contribuyó con el estudio y levantamiento de más de 2.000 edificaciones en el centro histórico de la ciudad. Como aporte fundamental para el estudio de la exposición en la ciudad, esta información hace parte del modelo de exposición a nivel de edificación, además de ser utilizado para evaluar la calidad de las bases de datos con la información constructiva de la ciudad.
 

## Variables básicas para la clasificación de edificaciones
Se identificaron múltiples variables para la clasificación de las edificaciones. Las siguientes figuras muestran ejemplos de la distribución de las carácteristicas constructivas en la ciudad, tales como: año de construcción, material predominante de las paredes exteriores, costo por lote por m2 y calidad de la construcción.

<p >
  <img src="../Mapas/exposicion/SDC_Ano.png" alt="Modelo de exposición - Modelo de exposición - Periodo de construccion" width="350">

  <img src="../Mapas/exposicion/SDC_Material_Paredes.png" alt="Modelo de exposición - Material de paredes" width="350">

  <img src="../Mapas/exposicion/SDC_costos.png" alt="Modelo de exposición - Costo por lote por m2" width="350">

  <img src="../Mapas/exposicion/SDC_calidad.png" alt="Modelo de exposición - Calidad de la construcción" width="350">
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

## Incertidumbres en el modelo
Para incorporar la incertidumbre epistémica asociadas al modelo, la metodología propuesta genera cuatro posibles modelos de exposición a partir de esquemas de clasificación (criterio de expertos) que relacionan las variables de la base de datos con la tipología constructiva. Los modelos resultantes y sus correspondientes relaciones con la vulnerabilidad están disponibles en esta carpeta. 

## Uso del modelo de exposición
Para el uso del modelo, es decisión del analista cómo incorporar la incertidumbre asociada de acuerdo con los modelos generados. Es posible asignar diferentes pesos a los diferentes modelos.


## Referencias
Detalles adicionales sobre la metodología pueden encontrarse en el reporte [Evaluación del riesgo sísmico para Santiago de los Caballeros](./TREQ_Deliverable_D262_Riesgo_Sismico_Santiago.pdf)
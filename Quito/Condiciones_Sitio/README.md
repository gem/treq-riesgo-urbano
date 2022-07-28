# CONDICIONES DE SITIO

Los archivos de esta carpeta incluyen diferentes condiciones de sitio para la ciudad, en formato compatible con OpenQuake.

- **site_model_uniform_grid_ampcodes.csv :** valores para usar con las funciones de amplificación (AFs)
- **site_model_uniform_grid_rock.csv :** valores para condiciones en roca
- **site_model_uniform_grid_vs30_USGS.csv :** valores para la Vs30 sugerida por el USGS (Servicio Geológico de los Estados Unidos)
- **soil_amplification_model_20210825_sigaf03.csv :** funciones de amplificación (AFs) para cada zona homogénea considerada en el estudio de la microzonificación sísmica de referencia

```Vs30: Velocidad de la onda de corte medida a 30m de profundidad```


## Microzonificación sísmica de referencia
ERN Consorcio (2012): Microzonificación sísmica del Distrito Metropolitano de Quito: Estudio de la amenaza sísmica a nivel local.

<p align="left">
  <img src="../Mapas/Quito_Microzonificacion.png" alt="Quito_Microzonificacion" width="500">
</p>

## Funciones de amplificación
La siguiente figura presenta el modelo de respuesta del suelo, dónde se grafican las [funciones de amplificación](./soil_amplification_model_20210825_sigaf03.csv) (AF) medias en cada zona homogénea de la microzonificación para diferentes períodos. La zona “noaf” se usa para edificaciones fuera de las microzonas para lo que se asigna un AF=1 (sin amplificación) y en su lugar se usa un Vs30 inferido.

<p align="left">
  <img src="./Funciones_Amplificacion.png" alt="Quito_Funciones_Amplificacion" width="700">
</p>

El reporte [D2.2.4 Análisis de la amenaza sísmica a escala urbana](https://www.globalquakemodel.org/proj/treq-es?tab=publications))presenta en detalle los datos y metodología para el desarrollo de las funciones de amplificación.

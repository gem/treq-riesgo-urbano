# 🗺️ SIG - SISTEMA DE INFORMACIÓN GEOGRÁFICA

Esta carpeta referencia las capas utilizadas para generar los mapas de los resultados.

El archivo `mapas_Cali.qgz` puede abrirse con el software QGIS. El proyecto de QGIS contine capas de información generada durante el proyecto, incluyendo: exposición, rupturas de escenarios sísmicos y resultados de riesgo.

## Metadatos
Las capas geográficas contienen los siguientes metadatos:
| Metadato en la capa | Métrica de Riesgo |
| ----- | ------ |
| number | Número de edificios expuestos |
| rc_usd | Valor económico de reemplazo expuesto (USD) |
| night | Número de ocupantes expuesto |
| collapsed | Número de estructuras colapsadas |
| fatalities | Número de fatalidades |
| losses | Pérdidas económucas en USD |
| str_lr | Índice de pérdidas económicas (pérdidas por valor expuesto) |
| col_lr | Índice de colapsos (colapsos por edificios expuestos) |
| occ_lr | Índice de fatalidades (muertes por 100 mil habitantes) |
| hom_lr | Índice de desplazados (desplazados por 100 mil habitantes) |
| inj_lr | Índice de heridos de gravedad (heridos por 100 mil habitantes) |
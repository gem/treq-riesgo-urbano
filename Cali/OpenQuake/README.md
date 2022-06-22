# <img src="https://raw.githubusercontent.com/gem/oq-infrastructure/master/logos/oq-logo.png" alt="OpenQuake" width="200"/> OPENQUAKE - ARCHIVOS DE CONFIGURACIÓN

Cada carpeta incluye los archivos de configuración para realizar cálculos en [OpenQuake](https://github.com/gem/oq-engine) (`*.ini`).

Para el caso de los escenarios sísmicos, los características específicas de las rupturas están en la carpeta [Rupturas_Sismicas](../Rupturas_Sismicas/).
También se incluyen archivos de entrada para realizar cálculos de licuefacción y deslizamientos inducidos por terremotos.

## Ejecutar cálculos con OpenQuake
Recuerda usar versiones de OpenQuake 3.14 o superior.

### Ejecutar riesgo probabilístico (Event_Based)
`oq engine --run job.ini`

### Ejecutar escenarios sísmicos (Scenarios, Landslides, Liquefaction)
`oq engine --run ini_rupture_code.ini`<br/>
`oq engine --run exe_rupture_code.ini --hc -1`

## Comienza a usar OpenQuake
[OpenQuake](https://github.com/gem/oq-engine) es un software gratuito y de código de fuente abierto.

Talleres en línea de OpenQuake:
https://www.training.openquake.org/

Videos para aprender a usar OpenQuake: <br/>
[Español](https://youtube.com/playlist?list=PL08aqbvcszvT6YG353CnIyL9d7gdZblBX),
[Ingles](https://youtube.com/playlist?list=PL08aqbvcszvQxT_HMoSk0XisLw1twc3V4)
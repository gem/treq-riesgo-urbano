
# DISTRITO METROPOLOTANO DE QUITO, ECUADOR 🇪🇨 <br /> Evaluación del riesgo sísmico a nivel urbano


## 📂 En este repositorio  

En este repositorio se puede encontrar los modelos desarrollados y resultados obtenidos para la evaluación del riesgo sísmico en la ciudad.

- **Amenaza:** Incluye información relativa al modelo de amenaza sísmica de referencia utilizado en los cálculos probabilísticos y para la selección de los escenarios sísmicos
- **Condiciones_Sitio:** Archivos con los modelos de las condiciones de sitio en formato compatible con OpenQuake
- **Exposicion:** Archivos con el modelo de exposición para la ciudad y los esquemas de clasificación que relacionan las tipologías constructivas y su vulnerabilidad (taxonomy_mapping) en formato compatible con OpenQuake.
- **GIS:** Capas georeferenciadas con los mapas de la ciudad con diferentes niveles administrativos
- **Mapas:** Mapas e imágenes con los modelos o resultados para la ciudad
- **OpenQuake:** Archivos de configuración para realizar los escenarios de riesgo o los cálculos probabilísticos
- **Riesgo:** Resultados del análisis de riesgo usando OpenQuake y perfiles para la ciudad
- **Rupturas_Sismicas:** Rupturas de los escenarios de riesgo sísmico seleccionados en formato compatible con OpenQuake


## Vistazo de los resultados de riesgo sísmico

El reporte [Evaluación del riesgo sísmico para el DMQ](./TREQ_Deliverable_D262_Riesgo_Sismico_Quito.pdf) presenta los detalles de los modelos utilizados y resultados obtenidos.

### Perfiles de mitigación del riesgo sísmico (mediano y largo plazo)
<p align="center">
  <img src="./Riesgo/perfil_mitigacion.png" alt="Perfiles de escenarios de riesgo" width="700">
</p>


### Perfiles de respuesta (escenarios sísmicos)
<p align="center">
  <img src="./Riesgo/perfiles_escenarios.gif" alt="Perfiles de escenarios de riesgo" width="700">

| Descripción                                              | Magnitud (Mw) | Profundiad (km) |
|----------------------------------------------------------|---------------|-----------------|
| Falla de Quito, Evento Mw6.5 en el centro de la ciudad   | 6.5           | 8               |
| Falla de Quito, Evento Mw6.5 en el norte de la ciudad    | 6.5           | 8               |
| Falla de Quito, Evento Mw7.0 en el centro de la ciudad   | 7             | 8               |
| Falla de Quito, Evento Mw6.5 al sur de la ciudad         | 6.5           | 8               |
| Falla de Quito, Evento Mw6.5 al oeste de la ciudad       | 6.5           | 8               |
| Nazca, Terremoto de 1906 Subducción de la Placa de Nazca | 8.8           | 20              |
| Manabí, Terremoto de Muisne de 2016                      | 7.8           | 20              |

</p>


## 📚 Publicaciones

Los siguientes entregables (Deliverables) del proyecto TREQ son relevantes para el análisis de riesgo urbano en la ciudad, los cuales se encuentran disponibles en la página web [www.globalquakemodel.org/proj/treq-es](https://www.globalquakemodel.org/proj/treq-es?tab=publications):

| | Evaluación de la amenaza sísmica |
| :----: | ---- |
| D2.2.1 | Description of the compiled datasets and the selected seismic hazard models. <br/>_[Descripción de las bases de datos recopiladas y los modelos de amenaza sísmica seleccionados]_|
| D2.2.3  | Seismic hazard results (rock and soil conditions). <br/>_[Resultados de amenaza sísmica (condiciones en roca y en suelo)]_ |
| D2.2.4  | Seismic hazard analysis at the urban scale. <br/>_[Análisis de la amenaza sísmica a escala urbana]_ |

| | Evaluación del riesgo sísmico |
| :----: | ---- |
| D2.3.1 | Technical report with description of building classes identified in each city. <br/>_[Reporte sobre tipologías constructivas en las ciudades del Proyecto TREQ]_ |
| D2.3.2 | Geo-referenced exposure database of population and residential, industrial and commercial buildings, and where available, other occupancy classes. One database per city. <br/>_[Base de datos de exposición georreferenciada de población y edificios residenciales, industriales y comerciales, y donde esté disponible, otras clases de ocupación. Una base de datos por ciudad]_ |
| D2.3.3 | Database of fragility and vulnerability functions for each building class present in the exposure model. <br/>_[Base de datos de funciones de fragilidad y vulnerabilidad para cada clase de edificio presente en el modelo de exposición]_ |
| D2.3.4 | Maps and risk metrics generated for each city. <br/>_[Mapas y métricas de riesgo para cada ciudad]_ |
| D2.3.5 | An executive summary report with findings and highlights of the exposure, vulnerability and risk models. <br/>_[Resumen ejecutivo con hallazgos y aspectos destacados de los modelos de exposición, vulnerabilidad y riesgo]_ |


## 🌟 Colaboradores 
<div align='right'>

  <img src="https://metrodequito.gob.ec/wp-content/uploads/2018/01/noticia-logo-nuevo.jpg" alt="Alcaldía de Quito" width="100"/>

  <img src="https://cacmq.gob.ec/sistemas/operativos/images/logos/sgsg.png" alt="Quito, Secretaría de seguridad" width="150"/>

  <img src="https://seeklogo.com/images/E/epmaps-agua-de-quito-logo-876095CBC6-seeklogo.com.png" alt="EPMAPS" width="150"/>

  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTV5b8jCxkKvXjdyFUe5ie7rNcu9HythoOLtQ&usqp=CAU" alt="PUCE" width="150"/>
  
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5b/Global_Earthquake_Model_Logo.png/440px-Global_Earthquake_Model_Logo.png" alt="GEM Foundation" width="150"/>

  <img src="https://upload.wikimedia.org/wikipedia/commons/1/17/USAID-Identity.svg" alt="USAID" width="150"/>
</div>

Agradecemos a las instituciones y colaboradores que participaron en el desarrollo de las actividades del proyecto TREQ en la ciudad. Esto incluye la facilitación de la información de entrada, desarrollo de los modelos y revisión de la información.

En particular, queremos agradecer a la Alcaldía de el DMQ por su aporte, a través de las oficinas de Planeación Municipal y de la Secretaría de Gestión del Riesgo de Emergencias y Desastres.


| NOMBRE                         | INSTITUCIÓN                                                 |
|--------------------------------|-------------------------------------------------------------|
| Alejandro Calderón Carpio | Fundación GEM |
| Catalina Yepes Estrada | Fundación GEM |
| Carlos Andrés Celi Sánchez | Pontificia Universidad Católica del Ecuador (PUCE) |
| Fausto Alarcón | Empresa Pública Metropolitana de Agua Potable y Saneamiento de Quito (EPMAPS)  |
| Hugo Yepes | Oficina de la Alcaldía |
| Irwin Álvarez | Dirección Metropolitana de Gestión del Riesgo (DMGR) |
| Jorge Ordóñez | Dirección Metropolitana de Gestión del Riesgo (DMGR) |
| Jose Marrero | Oficina de la Alcaldía |
| Kishor Jaiwal | United States Geological Survey (USGS) |
| Marco Pagani | Fundación GEM |
| Robert Chase | United States Geological Survey (USGS) |
| Robin Gee | Antiguo miembro de la Fundación GEM |
| Richard Styron | Fundación GEM |
| Shreyasvi Chandrasekhar | Fundación GEM |


# Licencia
Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

Esta trabajo está bajo una
[Licencia Creative Commons Atribución-CompartirIgual 4.0 Internacional][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: https://creativecommons.org/licenses/by-sa/4.0/deed.es
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

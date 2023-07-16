# PI2_Camila_Criado
Este Repositorio contiene el **Proyecto Individual 2** de la Carrera Data Science Part Time 01 de Henry. 
El mismo perseguía los siguientes objetivos; 

**Se pedía simular un informe a un Cliente del Rubro TELECOMUNICACIONES,a través del Análisis de 16 Datasets**

Este informe se realiza por partes y en etapas:

1. Análisis de todos los Datasets y elección de aquellos con los que se trabajaría en profundidad. 
2. Análisis Exploratorio de Datos (EDA) de los datasets elegidos. 
3. Confección de 3 Kpis funcionales al negocio.
4. Presentación del Informe y conclusiones en un DashBoard Interactivo para contar la historia. 

Tal como fue explicado en los párrafos anteriores, como primer paso se decidió realizar un OverView de cada uno de los datasets. 
Se observó que los datos proporcionados en varios de ellos podían obtenerse con el resto, por lo tanto se decidió profundizar puntualmente en los datasets
que contengan datos Provinciales. 

**Particularmente, se analizaron los datasets con info. sobre:**
- La cantidad de conexiones cada 100 hogares
- Conexión Banda Ancha o Dial Up.
- Tecnología utilizada.
- Velocidad Media de Bajada
- Rangos de Velocidad.

Los análisis fueron hechos con python y a nivel Nacional y Provincial mayormente, dejándose para la etapa del Dashboard, la utilización de los datasets con info. de 
localidades. Esto es porque se considera más útil y amigable la creación de mapas y filtros interactivos en una herramienta de visualización, tal como Power Bi. 

**En el presente repositorio encontrarás los siguientes archivos**

Carpeta Datasets: Contiene los datasets que fueorn analizados. 
Carpeta EDA: Contiene una notebook con el EDA y una carpeta (DataSets_limpios) con los datasets que derevivaron de la limpieza de datos y algunas transformaciones.
Estos serán utilizados para la creación del DashBoard. 

**Del EDA, surgieron las siguientes conclusiones principales**

En primer lugar, se ha analizado la **Cantidad de conexiones cada 100 hogares**, obteniendose las siguientes conclusiones:

- Se observa un marcado incremento en la Cantidad de Accesos por cada 100 hogares en el período analizado 2014-2022.

- Se observa que la Cantidad de Accesos en el Trimestre 2, ha tenido un aumento levemente superior al resto de los Trimestres durante el periodo    2014-2022, en particular a partir del año 2018. 

- Las 5 Provincias con más Accesos al Trimestre 3 del año 2022 fueron: Capital Federal, Tierra del Fuego, La Pampa, San Luis y Córdoba. 

- Las 5 Provincias con menos Accesos al Trimestre 3 del año 2022 fueron: Formosa, San Juan, Santa Cruz, Mendoza y Chaco.

                                                            ................
En segundo lugar, se ha analizado el tipo de conexión: **Banda Ancha o Dial Up**. Al respecto, se han obtenido las siguientes conclusiones:

- Se observa una clarísima supremasía de las Conexiones con Banda Ancha sobre las Dial Up. Estas últimas representan solamente el 0,1% de las conexiones del país. Esta misma distribución se mantiene a niveles Provinciales. 

- Las conexiones con *Banda Ancha* muestran un crecimiento marcado durante todo el período analizado, mientras que en el caso del Dial Up, se observa un decrecimiento entre el 2014 y el 2020. Para el 2021 cambió la tendencia y tuvo un crecimiento del 8% respecto al año anterior. 

- La tendencia por Trimestre es similar a la anual. En el caso de Banda Ancha, se observa en todos los casos un crecimiento constante. Para el Dial Up, se identifica una caída entre 2014 y 2020 y luego comienza un período de crecimiento leve. 

- La distribución trimestral se observa homogenea en ambos tipos de conexión, durante todos los años analizados, salvo en el Trimestre 4 del año 2019, donde se ve una caída en la cantidad de Conexiones de Dial Up, comparándolo con los trimestres anteriores. 

- En cuanto a la cantidad de conexiones por Provincia, Buenos Aires es por lejos la Provincia con más conexiones, tanto con Banda Ancha como con Dial Up. Capital Federal y Mendoza también ocupan los primeros puestos en ambos tipos de conexiones, aunque muy por debajo de Buenos Aires. 

                                                        ......................

En tercer lugar, se ha analizado el tipo de tecnología utilizada. Se destaca lo siguiente: 

- La tecnología ADSL viene con tendencia negativa desde el 2016, aunque la pendiente se hace más pronunciada a partir del 2017, lo que significa que la caída es más rápida año a año. 
- La Fibra Óptica comenzó su crecimiento en 2017 y desde ese momento ha estado creciendo. Aparentemente es la tecnología que actualmente está crecimiento. De hecho, aún sin contar con los datos del Trimestre 4 del 2022, los números del 2022 ya superan a los del 2021. Sin dudas es la tecnología en Auge. 
- Wireless se mantiene en niveles bajos durante todo el período analizado. 

- Al 2022, se observa aun una fuerte presencia del Cablemodem rondando el 60%. El segundo lugar lo ocupa la conexión a la Fibra Optica que está tomando mucha fuerza, y probablemente se convierta en la tecnologia puntera en un par de años. En Tercer lugar, se encuentra el ADSL

- Las 5 Provincias con más presencia de Fibra Óptica son:
    Buenos Aires, que supera ampliamente al resto de las Provincias y se encuentra en el orden de las 4M, mientras que el resto de las Provinciacs que le siguen, no alcanzan el 1M.   Le siguen las siguientes provincias: Cordoba, Santa Fe, Mendoza y Tucumán. Capital Federal ocupa el Sexto Lugar. 

                                                        ........................

En cuarto lugar, se analizó un dataset que proporciona la **Velocidad Media de Bajada**. En este caso, se decidió tomar los últimos datos disponibles (Trimestre 3 del 2022)

Se observa una distribucion multimodal. 

Por un lado, hay 7 Provincias con Velocidades Medias entre 10 y 20 Mbps: Tiera del Fuego, Santa Cruz, Chubut, San Juan, Santiago del Estero, La Pampa, y San Luis. 

Por otro lado, hay 11 Provincias que tienen velocidades entre 30 Mbps y aprox 50 Mbps: Misiones, Neuquen, Corrientes, Santa Fe, La Rioja, Entre Rios, Salta, Rio Negro, Mendoza, Jujuy y Formosa. 

Entre 50 y 100 Mbps se encuentran Buenos Aires, Catamarca, Cordoba, Tucuman y Chaco

Por Último, Solamente Capital Federal Supera la Media de 100 Mbps. 

                                                       ........................

Por último, se analizó el dataset que proporciona datos sobre los **rangos de velocidades**. En este caso también se consideraron los últimos datos disponibles (Trimestre 4 - 2022)

- El rango de velocidad con mayor frecuencia a nivel Nacional corresponde a la categoría +30 Mbps. 
- En cuanto a la distribución provincial, Buenos Aires es la Provincia con más conexiones en el Rango de MAS 30 Mbps. 

    Le siguen, en orden: Capital Federal, Córdoba, Santa Fe y Tucumán, Mendoza y Entre Ríos, todas superando las 100.000 Conexiones. 
    El resto de las provincias se encuentra por debajo de este número. 
    Entre las Provincias con muy pocas conexiones a este velocidad se encuentran: Santiago del Estero, Santa Cruz, Tierra del Fuego y San Luis. 

-----------------------------------------------------------------------------------------------------------------------------------------------------------------
**Por último se analizan los KPIS Sugeridos**


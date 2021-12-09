# La brecha migratoria de Madrid
## Con barrios con una población extranjera de más del 30% sobre el total, la población migrante se concentra en el sur de la capital

![Porcentaje-de-poblacio-n-extranjera-en-los-barrios-de-madrid](https://user-images.githubusercontent.com/90325763/143934255-697b9079-4186-43f5-b179-63e3c95a9178.png)

- Un eje este-oeste divide Madrid en dos mitades. En el norte, la mayoría de los barrios de los distritos de Chamartín, Moncloa-Aravaca, el Pardo y Hortaleza acogen en su interior a alrededor de un 10% de población extranjera. Valdeacederas, Berruguete y Bellas Vistas son, no obstante, la excepción a la regla. Con una población migrante superior al 20%, los tres pequeños barrios del distrito norteño de Tetúan manchan de azul el plano verdoso de la capital.

- En el sur, como vemos, la situación cambia. La media de población extranjera sube diez puntos y se sitúa en torno al 20%. Puente de Vallecas, Usera, Villaverde y Carabanchel se muestran como los distritos donde a más migrantes se acoge. Los barrios de San Diego (31.7%), san Cristóbal (35.9%) y Pradolongo (37%) son, junto a Sol (32.3%), las regiones de Madrid con mayor porcentaje de población extranjera.

- FUENTE DE LA IMAGEN: Elaboración propia vía https://app.datawrapper.de/archive#/5ktch

- PROCESO DE ELABORACIÓN: Tras descargar los datos demográficos de la página web (https://www.epdata.es/datos/poblacion-inmigrantes-emigrantes-otros-datos-habitantes-cada-municipio/3/madrid/4245) abrí la herrmanienta OpenRefine y eliminé las filas y columnas que no necesitaría después en la elaboración de la visualización de datos. Puesto que no había creado ningún mapa con anterioridad, decidí hacer uno con los porcentajes de población migrante de la ciudad de Madrid. Sorprendentemente, el proceso fue muy sencillo. Solo tuve que importar los datos y corregir algunos de los nombres de los barrios que Datawrapper había confundido.

- DESCRIPCIÓN: En el mapa se pueden observar, gracias a los distintos colores empleados, las diferencias en los porcentajes de población extranjera dependiendo del barrio madrileño en el que nos encontramos. Mientras que en Valderribas, El Pardo, Estrella y Mirasierra los migrantes no llegan al 5% de la población, en barrios como Pradolongo, San Cristóbal, Sol y san Diego superan el 30% del total.

## ¿Está relacionado el porcentaje de población migrante con el nivel de renta de los hogares de Madrid?

![jEUlI-renta-media-por-familia-2017-](https://user-images.githubusercontent.com/90325763/144118372-0f1e976d-8a9f-42e7-ba75-0f4f6ac40cd2.png)

- DESCRIPCIÓN: La división norte-sur vuelve a repetirse. San Cristóbal, San Diego y Amposta son los barrios de Madrid con un nivel de renta más bajo. El patrón se mantiene.

- Después de haber terminado el mapa decidí dar un paso más allá y comprobar si, como hipotetizaba, los barrios con un mayor porcentaje de población migrante se relacionaban de algún modo con el nivel de renta de sus habitantes. Descargué "Indicadores de renta media según  Distritos, Barrios y Secciones censales" en la web del Ayuntamiento de Madrid (https://www.madrid.es/portales/munimadrid/es/Inicio/El-Ayuntamiento/Estadistica/Areas-de-informacion-estadistica/Economia/Renta/Urban-Audit/?vgnextfmt=default&vgnextoid=6d40393c7ee41710VgnVCM2000001f4a900aRCRD&vgnextchannel=ef863636b44b4210VgnVCM2000000c205a0aRCRD) y elaboré un nuevo mapa con los datos encontrados. Los filtré con OpenRefine dejando únicamente la columna de "Renta media por hogar en 2017", por lo que tuve que eliminar el resto de columnas y dividir la de los barrios debido a que esta se encontraba numerada. 

- El nuevo mapa, creado también con Datawrapper, parecía corroborar mi hipótesis. Para asegurarme, no obstante, decidí elaborar una última gráfica en la que se mezclaran ambas variables. Este es el resultado:

![4JxLz-relaci-n-entre-la-renta-media-por-hogar-y-la-poblaci-n-migrante-en-los-barrios-de-madrid](https://user-images.githubusercontent.com/90325763/144118379-2c2ce963-9fe3-42ec-b6cc-cb4251496776.png)

DESCRIPCIÓN: Como se observa en la gráfica, la relación entre ambas variables es clara. Los barrios con una menor renta son, a su vez, los barrios con un mayor porcentaje de población extranjera. Y viceversa.
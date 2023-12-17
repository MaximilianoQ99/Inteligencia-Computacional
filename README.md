Los anteriores codigos corresponden a Maximiliano Quintero Y Tomás Apablaza, En este proyecto, nos enfrentamos al desafío de clasificar series de tiempo astronómicas,
específicamente las curvas de luz de estrellas periódicas pertenecientes al catálogo Earth Resources Observation and Science (EROS). Con alrededor de 57,000 curvas de luz disponibles,
abarcando Eclipses Binarias, Cefeidas y RR Lyrae, el objetivo es implementar un sistema de
clasificación supervisada. Sin embargo, se destaca un desbalance significativo en la cantidad
de curvas de luz de cada clase.
El proceso implica la inspección, visualización y preprocesamiento de los datos, seguido
de la extracción de características de cada curva de luz. Una vez obtenidas estas características, propondremos un modelo supervisado para clasificar las estrellas periódicas en sus
respectivas clases. La estrategia para entrenar y evaluar el modelo debe abordar el contexto
de desbalance, lo que implica considerar cuidadosamente el manejo de clases minoritarias.
Este proyecto se apoya en referencias importantes, como el trabajo de Martínez Palomera
sobre la clasificación automática de objetos variables y el artículo de Sánchez-Sáez sobre
la clasificación de alertas para el sistema ALeRCE Broker. Además, se incorporan otras
referencias valiosas, como FATS (Feature Analysis for Time Series) y el libro de Catelan y
Smith sobre estrellas pulsantes. Estas fuentes enriquecerán nuestra comprensión y enfoque
en el desarrollo de este proyecto.

El orden con el que ejecutamos el codigo es el siguiente 
1) " "... Modelo propuesto Obtención de datos
2) " "... Doblar Curvas y Interpolación Kernel
3) Extractor Iterativo Final
4) Proyecto 4B ...

Finalmente La metodologia alternativa corresponde a un Anexo

Saludos!

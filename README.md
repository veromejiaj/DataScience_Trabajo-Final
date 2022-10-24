# Trabajo-Final

Se han cargado las dos bases de datos empleadas para el analisis. Las cuales fueron extraidas de: 
1. ICAEN – Instituto Catalán de Energía     https://analisi.transparenciacatalunya.cat/es/Transport/Matriculacions-mensuals-de-vehicles-electrificats-/eds6-562k
2. Idescat – Estadística oficial de Cataluña   https://www.idescat.cat/indicadors/?id=aec&n=15917&lang=es
3. DGT – Dirección General de Trafico    https://sedeapl.dgt.gob.es/WEB_IEST_CONSULTA/subcategoria.faces
Una vez descargadas las bases de datos, se pocedió a analizarlas: 

A. Regresion general

Con los datos provenientes del DGT en el que se obtienen las matriculaciones mensuales a nivel de codigo postal. Se hace el siguiente analisis en el que se contrasta la evolucion de las matriculacion de los vehiculos en general y la de los vehiculos electricos. 

https://github.com/veromejiaj/Trabajo-Final/blob/main/Regresion.ipynb

B. Cluster por comarcas - series temporales 

Se continua con la identificacion de cluster en relacion a los datos de las matriculaciones mensuales de los vehiculos electricos extraidos del ICAEN. Aqui encuestras los datos de las matriculaciones unicamente de los vehiculos electricos con una periocidad mensual. Se ha empleado como unidad territorial la comarcas puesto que así se obtienen datos equiparables entre territorios. 

Una vez realizado los cluster, se incorporan los datos socioeconomicos del IDESCAT. Así, se contrasta los cluster con datos de renta, densidad y población. 

https://github.com/veromejiaj/Trabajo-Final/blob/main/Cluster%20catalu%C3%B1a.ipynb

# Laboratorio Bioinformática 3 (29-08-2017)



# Bruno Romero




-----



# Parte 1: El artículo genoma



----


#### Cuántos genomas han sido depositados en GOLD? ¿Son los mismos de GENBANK?
	
  
__R:__


+ `En la sección 'Sequencing projects' se detallan 11,598 genomas completos y 53,156 genomas incompletos. Hay 80.576 proyectos secuenciados entre ambas bases de datos.` 


#### ¿Cuál es la distribución de procariontes y eucariontes secuenciados?


__R:__


+ `En procariontes hay 249.701 genomas depositados (bacterias) y en eucariontes hay 18.241 genomas depositados. Es decir, una relación de 14:1 respectivamente.`




#### ¿Qué es el N50, L50, NG50?


__R:__


+ `+ N50: Este valor significa una estimación de la calidad del secuenciamiento en relación al largo de los contigs (o de los fragmentos). Luego, se suman todos los contigs/reads de mayor longitud a menor longitud, hasta que se llegue a la suma de la mitad del genoma. Luego, el último valor que está dentro del rango de la mitad del genoma, es el valor de N50.`

+ `L50: Número de contigs que se necesitaron para cubrir la mitad del genoma.`

+ `NG50: Es el N50 ajustado a la longitud total del genoma.`


#### ¿Cuál es el propósito de calcular estas estadísticas?


__R:__



+ `Estimar la calidad de la secuenciación midiendo el largo de los reads/contigs/scaffolds en relación al largo de la secuencia original.`


#### ¿Cuál es el genoma que escogiste? Adjunta la referencia.



__R:__



+ `El genoma escogido es Brachypodium distachyon Brachypodium_distachyon_v2.0 [1].`


+ El estudio es: https://www.nature.com/nature/journal/v463/n7282/full/nature08747.html



#### ¿Cuál es el N50 del genoma que escogiste? ¿Y el NG50?
	
	
	
__R:__


![Valores](https://github.com/CapitanFlint/Laboratorio3bioinfo29-08-2017/blob/master/N50.png)



__IMAGEN 1:__ Valores de N50 y L50 en relación a scaffolds y contigs.
	
	
	
	
	
#### ¿Qué tipo de tecnología se uso para secuenciar el genoma que escogiste?



__R:__



+ `ABI 3730 xl instruments.`
 



#### ¿Qué organismo escogiste, cuántos cromosomas tiene tu organismo y cuál es su tamaño?



__R:__



+ `Brachypodium distachyon [1], posee 5 cromosomas y su longitud total es de 271,77 Mpb. `


# Parte 2: Predicción de genes


-----



#### ¿Cuántos ORF o genes encontró ORFfinder?


__R:__


+ `La secuencia entregó 7 open reading frames.`



![orfs](https://github.com/CapitanFlint/Laboratorio3bioinfo29-08-2017/blob/master/ORF.png)



__IMAGEN 2:__ Resultados obtenidos en OFFfinder.


#### ¿Cuántos ORF o genes encontró Glimmer?


__R:__


+ `- `



#### ¿Alguno de los genes predichos por estas herramientas coinciden?


__R:__


+ `- `



#### ¿En qué hebra están codificados?


__R:_


+ ` `


#### ¿Qué tipo de programa es GLIMMER? ¿Ab initio o por homología?



__R:__




+ ` -`



# Bibliografía

 
[1] https://www.ncbi.nlm.nih.gov/genome/?term=txid15368[Organism:noexp]





# INFORME-DE-TAREA-9

### 1. OBJETIVOS
#### Objetivos generales

Determinar los metódos ya estudiados anteriormente y analizar las aplicaciones de Circuitos RLC y Filtros Pasivos mediante la lectura y comprensión de temas del Libro de Floyd "Principios de Circuitos Eléctricos" para resolver los ejercicios planteados en cada capitulo.

#### Objetivos especificos

- Determinar la impedancia de un circuito RLC en serie

- Analizar circuitos RLC en serie y resonancia en serie

- Determinar la impedancia de un circuito RLC en paralelo

- Analizar circuitos RLC en paralelo y resonancia en paralelo

- Analizar la operación de filtros pasabajas y pasaaltas RC y RL

- Analizar la operación de filtros pasabanda y rechazabanda

### 2. MARCO TEORICO

## Cicuitos RLC y Resonancia (Capitulo 17)

#### Circuitos en Serie

Un circuito RLC en serie contiene resistencia, inductancia y capacitancia. Como la reactancia inductiva y la reactancia capacitiva tienen efectos opuestos en el ángulo de fasedel circuito, la reactancia total es menor que cualquier reactancia individual.

![image](https://user-images.githubusercontent.com/105259381/187109712-25a0e03f-fd21-4717-b1f6-35ed14765ebf.png)

#### Circuitos en Paralelo

La impedancia total se calcula utilizando el método del recíproco de la suma de recíprocos, exactamente como se hizo para circuitos con resistores en paralelo.

![image](https://user-images.githubusercontent.com/105259381/187110035-6ce693f0-8324-45a6-a393-af5b17dc083f.png)

![image](https://user-images.githubusercontent.com/105259381/187110899-4ec8197a-af61-421d-a9e4-195c1fd2ee3a.png)

En circuitos RLC en paralelo a frecuencias bajas, la reactancia inductiva es menor que la reactancia capacitiva; por consiguiente, el circuito es inductivo. Conforme se incrementa la frecuencia, XL aumenta y XC disminuye hasta alcanzar un valor donde XL = XC. Éste es el punto de resonancia en paralelo. A medida que la frecuencia aumenta un poco más, XC se vuelve más pequeña que XL, y el circuito se vuelve capacitivo.

![image](https://user-images.githubusercontent.com/105259381/187213389-6858b487-d21c-48c1-a142-e9665a7a559b.png)

#### Circuitos en Serie - Paralelo

![image](https://user-images.githubusercontent.com/105259381/187218600-fb1b8e20-4f23-4a07-9c6f-78aacc492a15.png)


## Filtros Pasivos (Capitulo 18)

#### Filtros pasabajas

Un filtro pasabajas deja pasar señales de bajas frecuencias desde la entrada hasta la salida mientras rechaza las frecuencias altas.

![image](https://user-images.githubusercontent.com/105259381/187287822-82bf2bbb-b2ee-49a7-8f65-ac7164339a94.png)

#### Filtros pasaaltas

Un filtro pasaaltas deja pasar señales de alta frecuencia desde la entrada hasta la salida en tanto que rechaza las señales de baja frecuencia.

La frecuencia considerada como el extremo inferior de la banda de paso se llama frecuencia crítica. Al igual que en el filtro pasabajas, es la frecuencia a la cual la salida es el 70.7% de la frecuencia máxima, como indica la figura.

![image](https://user-images.githubusercontent.com/105259381/187288478-b748a11f-a776-4957-982f-665ecca682f3.png)

Filtro RC pasaaltas

En la figura se muestra un filtro RC pasaaltas. Advierta que el voltaje de salida se toma a través del resistor.

Cuando la frecuencia de entrada alcanza su valor crítico, XC = R y el voltaje de salida es de 0.707Vent, como en el caso del filtro pasabajas. Conforme la frecuencia de entrada se incrementa por encima de la frecuencia crítica, XC disminuye y, por consiguiente, el voltaje de salida aumenta y tiende a un valor igual a Vent. La expresión para la frecuencia crítica del filtro pasaaltas es la misma que para el filtro pasabajas

![image](https://user-images.githubusercontent.com/105259381/187288643-bc6687e3-0b00-4bf4-8b98-e1461f8182d7.png)

![image](https://user-images.githubusercontent.com/105259381/187289006-70dceb69-a9de-4982-a7cc-fd6a2248d3dd.png)

#### Filtros pasabanda

Un filtro pasabanda deja pasar cierta banda de frecuencias y atenúa o rechaza todas las frecuencias por debajo y por encima de la banda de paso.

El ancho de banda de un filtro pasabanda es el intervalo de frecuencias dentro del cual la corriente, y por tanto el voltaje de salida, es igual o mayor que el 70.7% de su valor en la frecuencia de resonancia.

Como se sabe, el ancho de banda a menudo se abrevia AB y se calcula como:

![image](https://user-images.githubusercontent.com/105259381/187289287-cd4764c8-2bdd-4e11-8fe3-b98810a9f9e4.png)

donde fc1 es la frecuencia de corte baja y fc2 es la frecuencia de corte alta.

Filtro pasabajas / pasaaltas.

Se puede utilizar la combinación de un filtro pasabajas y un filtro pasaaltas para formar un filtro pasabanda, como se observa en la figura. El efecto de carga del segundo filtro sobre el primero debe ser tomado en cuenta.

![image](https://user-images.githubusercontent.com/105259381/187289631-fe5d1c86-28e7-4696-b234-e1bad60334c2.png)

Si la frecuencia crítica del filtro pasabajas, fc(l), es más alta que la frecuencia crítica del filtro pasaaltas, fc(h), las respuestas se traslapan.

![image](https://user-images.githubusercontent.com/105259381/187289799-d63a3765-9661-4852-b8ec-d84c434aa4f9.png)

#### Filtros Rechazabanda

Un filtro rechazabanda es, en esencia, lo opuesto de un filtro pasabanda en función de las respuestas. Un filtro rechazabanda deja pasar todas las frecuencias excepto aquellas que quedan dentro de cierta banda de rechazo.

Curva general de respuesta rechazabanda.

![image](https://user-images.githubusercontent.com/105259381/187290183-97474972-9ca8-4a6f-9d7c-dc8b39a4b115.png)

![image](https://user-images.githubusercontent.com/105259381/187291295-802a4331-4d24-404b-84ba-1d9daa21b888.png)

### 3. EXPLICACIÓN O RESOLUCIÓN DE EJERCICIOS O PROBLEMAS

## Resolucion de los ejercicios Capitulo 17

#### PARTE 1: CIRCUITOS EN SERIE

#### SECCIÓN 17–1 Impedancia de circuitos RLC en serie

2. Determine la impedancia en la figura 17-59 y exprésela en forma polar. 

![image](https://user-images.githubusercontent.com/105259381/187293195-90f333c5-afc3-4e8e-a268-370120a79591.png)

![image](https://user-images.githubusercontent.com/105259381/187293099-6a4c9f7b-0c0f-456d-9ab6-75c46f77b14e.png)

4. Para el circuito de la figura 17-59, determine la reactancia neta que hará que la magnitud de la impedancia sea igual a 100 Ω

![image](https://user-images.githubusercontent.com/105259381/187293436-80cd7b15-b0e2-46a2-87f0-e65153506c17.png)

![image](https://user-images.githubusercontent.com/105259381/187293561-c7399e61-4893-403e-8f83-b6b373eb9b13.png)

#### SECCIÓN 17–2 Análisis de circuitos RLC en serie

6. Trace el diagrama fasorial de voltaje para el circuito de la figura 17-59.

![image](https://user-images.githubusercontent.com/105259381/187293436-80cd7b15-b0e2-46a2-87f0-e65153506c17.png)

![image](https://user-images.githubusercontent.com/105259381/187294227-fc224942-863a-4013-b10d-f28e37063856.png)

Diagrama fasorial:

![image](https://user-images.githubusercontent.com/105259381/187294356-5777d1ab-d4d7-41e9-a067-fadcadf0b8ac.png)

#### SECCIÓN 17–3 Resonancia en serie

8. Para el circuito de la figura 17-59, ¿es la frecuencia resonante más alta o más baja que el valor indicado por los valores de reactancia?

![image](https://user-images.githubusercontent.com/105259381/187293436-80cd7b15-b0e2-46a2-87f0-e65153506c17.png)

![image](https://user-images.githubusercontent.com/105259381/187294677-537d4125-0da1-4123-b909-68c4103b1f3e.png)

10. En la figura 17-61, determine XL, XC, Z e I a la frecuencia resonante.

![image](https://user-images.githubusercontent.com/105259381/187294832-6b94e076-deb3-4c0b-a6e0-622c085f41f8.png)

![image](https://user-images.githubusercontent.com/105259381/187295583-f0ba2a72-e60d-4ab2-b5cb-6f505315a1d3.png)

12. Para el circuito RLC de la figura 17-62, determine la frecuencia resonante.

![image](https://user-images.githubusercontent.com/105259381/187295760-a145166e-9050-4818-b150-6d5315ac246d.png)

![image](https://user-images.githubusercontent.com/105259381/187295838-faeb26fa-7aa8-4715-8416-3d3be7e3f609.png)

14. En la figura 17-62, determine el ángulo de fase entre el voltaje aplicado y la corriente a las frecuencias
críticas. ¿Cuál es el ángulo de fase en condición de resonancia?

![image](https://user-images.githubusercontent.com/105259381/187295760-a145166e-9050-4818-b150-6d5315ac246d.png)

![image](https://user-images.githubusercontent.com/105259381/187295909-f549fde5-83d3-405c-95b0-859df36f11b2.png)

#### PARTE 2: CIRCUITOS EN PARALELO

#### SECCIÓN 17–4 Impedancia de circuitos RLC en paralelo

16. Exprese en forma polar la impedancia del circuito de la figura 17-63.

![image](https://user-images.githubusercontent.com/105259381/187296207-09eec268-cd1e-4e2e-a40b-7dee578de617.png)

![image](https://user-images.githubusercontent.com/105259381/187296052-719581ef-0775-440e-8c52-6f96d6b55baa.png)

18. ¿A qué frecuencia el circuito de la figura 17-63 cambia su característica reactiva (de inductiva a capacitiva o viceversa)?

![image](https://user-images.githubusercontent.com/105259381/187296422-f83cf5bf-ee23-4cc4-8f28-e87d17dc65fe.png)

![image](https://user-images.githubusercontent.com/105259381/187296708-b4e1a71a-8584-4cb3-b0a5-8bd9dd5217c4.png)

#### SECCIÓN 17–5 Análisis de circuitos RLC en paralelo

20. Determine la impedancia total del circuito de la figura 17-63 a 50 kHz. 

![image](https://user-images.githubusercontent.com/105259381/187296422-f83cf5bf-ee23-4cc4-8f28-e87d17dc65fe.png)

![image](https://user-images.githubusercontent.com/105259381/187296936-b57a4378-1488-4644-92a1-15fadcda5083.png)

#### SECCIÓN 17–6 Resonancia en paralelo

22. ¿Cuál es la impedancia de un circuito resonante ideal dispuesto en paralelo (sin resistencia en las ramas)?

![image](https://user-images.githubusercontent.com/105259381/187297149-53095977-1dc9-4e7d-b307-dd1c768a9c76.png)

24. ¿Cuánta corriente se extrae de la fuente de la figura 17-64 en condición de resonancia? ¿Cuáles son las corrientes inductiva y capacitiva en la frecuencia resonante?

![image](https://user-images.githubusercontent.com/105259381/187297346-7f95cb21-1695-42c9-9e64-3c7e18fa2e89.png)

![image](https://user-images.githubusercontent.com/105259381/187298063-5629c63f-0613-4739-b9b0-2d5452f6548b.png)

#### PARTE 3: CIRCUITOS EN SERIE-PARALELO

#### SECCIÓN 17–7 ANÁLISIS DE CIRCUITOS RLC EN SERIE-PARALELO

26. Encuentre la impedancia total para cada circuito de la figura 17 - 65

![image](https://user-images.githubusercontent.com/105259381/187298283-00c1d094-6929-46ac-b537-f388568c8477.png)

Para el literal a

![image](https://user-images.githubusercontent.com/105259381/187298516-2c1e84d0-850f-4fe5-a044-c85d63e2defe.png)

Para el literal b

![image](https://user-images.githubusercontent.com/105259381/187298690-3d96a657-9828-4ee9-a721-0434eec462b5.png)

28. Determine el voltaje entre las terminales de cada elemento mostrado en la figura 17-66, y expréselo en forma polar. 

![image](https://user-images.githubusercontent.com/105259381/187298893-24bf4680-23af-4029-a6c8-d847d0d673cd.png)

![image](https://user-images.githubusercontent.com/105259381/187298820-55344b49-81fc-401f-820e-1900b60315b7.png)

30. ¿Cuál es la corriente a través de R2 en la figura 17-67?

![image](https://user-images.githubusercontent.com/105259381/187298992-9181c38e-6dd3-4bb0-80cf-cadf844eee39.png)

![image](https://user-images.githubusercontent.com/105259381/187299713-29c40bca-25d7-44a9-bad3-bf86077b0b2d.png)

32. Determine la resistencia y la reactancia totales en la figura 17-68.

![image](https://user-images.githubusercontent.com/105259381/187300022-4f603043-9584-494d-b0a4-a253ec913c26.png)

![image](https://user-images.githubusercontent.com/105259381/187300184-f59e3738-f5db-4d81-a8b5-abb246f6301e.png)

34. Determine si existe un valor de C que hará Vab = 0 V en la figura 17-69. Si no lo hay, explique la razón.

![image](https://user-images.githubusercontent.com/105259381/187300286-44dc996d-7baa-4185-b414-a8c55560d4f7.png)

![image](https://user-images.githubusercontent.com/105259381/187300657-617f568f-a95a-4221-a5ac-2b874ea56981.png)

![image](https://user-images.githubusercontent.com/105259381/187301353-c55be53d-124b-4449-982e-c9cf68ae96df.png)

36. ¿Cuántas frecuencias resonantes hay en el circuito de la figura 17-70 ¿Por qué?

![image](https://user-images.githubusercontent.com/105259381/187301551-1baf4602-1d1b-4c39-8069-40ed25682de1.png)

![image](https://user-images.githubusercontent.com/105259381/187301843-2d378137-4a85-41d8-b784-abc653c4ec41.png)

38. Diseñe un red resonante en paralelo usando una sola bobina y capacitores seleccionables mediante un interruptor para producir las siguientes frecuencias resonantes: 8 MHz, 9 MHz, 10 MHz, y 11 MHz. Suponga una bobina de 10 μH con resistencia de devanado de 5 Ω

![image](https://user-images.githubusercontent.com/105259381/187302232-85b7e5cd-6e52-4fc5-a8d4-cd432f3155ee.png)

#### PARTE 4: TEMAS ESPECIALES

#### SECCIÓN 17–8 Ancho de banda de circuitos resonantes 

40. Si la frecuencia crítica baja es de 2400 Hz y la frecuencia crítica alta es de 2800 Hz, ¿cuál es el ancho de banda? ¿Cuál es la frecuencia resonante?

![image](https://user-images.githubusercontent.com/105259381/187303345-f055e1e9-b8be-4343-9498-6642ead751fc.png)

42. En un circuito tanque, ¿qué valores de L y C deberán utilizarse para obtener una frecuencia resonante de 8 kHz? El ancho de banda debe ser de 800 Hz. La resistencia de devanado del circuito es de 10 Ω.

![image](https://user-images.githubusercontent.com/105259381/187303391-40a0beb5-bbc1-4a6b-9694-f6292558e048.png)

## Resolucion de los ejercicios Capitulo 18

#### SECCIÓN 18–1 Filtros pasabajas

2. Un filtro pasabajas tiene frecuencia crítica de 3 kHz. Determine a cuáles de las siguientes frecuencias se les permite pasar y cuáles son rechazadas:

![image](https://user-images.githubusercontent.com/105259381/187304212-443bd406-79f0-414e-a1fa-b9fd4a0fba2b.png)

4. ¿Cuál es fc para cada filtro mostrado en la figura 18-38? Determine el voltaje de salida a fc en cada caso cuando Vent = 5 V.

![image](https://user-images.githubusercontent.com/105259381/187304359-2b3acf13-21bf-4561-9918-ad482e8b3b47.png)

![image](https://user-images.githubusercontent.com/105259381/187304654-b1813daf-9492-4e92-ad53-30e68808f69b.png)

6. Determine la frecuencia crítica en cada una de las posiciones del interruptor en la red de filtros conmutados de la figura 18-40.

![image](https://user-images.githubusercontent.com/105259381/187304864-944e768d-4638-40b4-8334-117a60ebc98f.png)

![image](https://user-images.githubusercontent.com/105259381/187305227-8693b883-e0b7-41af-9a13-a2943f2eb5de.png)

8. En cada uno de los casos siguientes, exprese la relación de voltaje en dB:

![image](https://user-images.githubusercontent.com/105259381/187305329-a4a678ca-9045-4051-9667-d119dba21f7a.png)

10. Para cada filtro RC pasabajas, determine el voltaje de salida en dB con respecto a una entrada de 0 dB en las siguientes frecuencias (fc = 1 kHz):

![image](https://user-images.githubusercontent.com/105259381/187305611-4db9f3f6-206f-4704-b324-6b835e698269.png)

#### SECCIÓN 18–2 Filtros pasaaltas

12. La frecuencia crítica de un filtro pasaaltas es de 50 Hz. Determine a cuáles de las siguientes frecuencias se les permite pasar y cuáles son rechazadas:

![image](https://user-images.githubusercontent.com/105259381/187305862-4715f9d0-5406-4a43-95cd-ed6ec47f8c6d.png)

14. ¿Cuál es fc para cada filtro de la figura 18-41? Determine el voltaje de salida a fc en cada caso (Vent = 10 V).

![image](https://user-images.githubusercontent.com/105259381/187306056-0e6d521f-48fb-419a-8f20-7b66c33a26ba.png)

![image](https://user-images.githubusercontent.com/105259381/187306336-baaf76aa-71a7-4f9d-9737-007c4fd64da1.png)

16. Determine fc para cada una de las posiciones del interruptor en la figura 18-42.

![image](https://user-images.githubusercontent.com/105259381/187306523-72cce80d-d100-4eaa-8a53-a6eea5d9adf2.png)

![image](https://user-images.githubusercontent.com/105259381/187306768-8dfcf225-63bd-4d96-ba9d-2cd255bc3a5d.png)

#### SECCIÓN 18–3 Filtros pasabanda

18. Suponiendo que la resistencia de devanado de las bobinas mostradas en la figura 18-43 es de 10 Æ, determine el ancho de banda para cada filtro.

![image](https://user-images.githubusercontent.com/105259381/187307112-ed20aa96-f58a-4481-be1f-a56564508cba.png)

![image](https://user-images.githubusercontent.com/105259381/187307495-2856335d-6afe-4a5c-85bc-35546811d4d5.png)

20. Para cada filtro mostrado en la figura 18-44, determine la frecuencia central de la pasabanda. Ignore RW

![image](https://user-images.githubusercontent.com/105259381/187307666-ea26eac8-e358-4046-97ff-5b8a8032d807.png)

![image](https://user-images.githubusercontent.com/105259381/187307803-04d19cf6-27a0-414c-8f2f-b2667f6ee8de.png)

22. Determine la separación de las frecuencias centrales en todas las posiciones del interruptor de la figura 18-45. ¿Se traslapan algunas de las respuestas? Suponga que RW = 0 Ω para cada bobina.

![image](https://user-images.githubusercontent.com/105259381/187307971-8399f303-d506-45c4-89fb-d8bb3d9f5259.png)

![image](https://user-images.githubusercontent.com/105259381/187309261-5d2b17a3-b1db-408c-bc51-28a183b5bc25.png)

![image](https://user-images.githubusercontent.com/105259381/187309290-261fab5c-f5fc-4fde-abc8-e4ba19384ba0.png)

#### SECCIÓN 18–4 Filtros Rechazabanda

24. Determine la frecuencia central para cada filtro mostrado en la figura 18-46.

![image](https://user-images.githubusercontent.com/105259381/187309523-ec2ff24b-d90b-429e-9df3-fc1356572496.png)

![image](https://user-images.githubusercontent.com/105259381/187309630-ab19bbf4-1aeb-4ab8-9327-fd31d72de42a.png)

26. Si la resistencia de las bobinas de la figura 18-47 es de 8 Ω, ¿cuál es el voltaje de salida en condición de resonancia cuando Vent = 50 V?

![image](https://user-images.githubusercontent.com/105259381/187309781-d4cfbc35-0eba-4a4c-a1c6-5d7eb6ee78f1.png)

![image](https://user-images.githubusercontent.com/105259381/187310252-f14ce518-6bd5-4021-90f2-9ad44e7f1bd5.png)

### 4. CONCLUSIONES

Se analizó que los circuitos que tienen tanto inductancia como capacitancia exhiben la propiedad de resonancia, la cual es importante en muchos tipos de aplicaciones. La resonancia es la base de la selectividad de frecuencia en sistemas de comunicaciones.

La capacidad de un receptor de radio o de televisión para seleccionar cierta frecuencia transmitida por una estación particular y, al mismo tiempo, eliminar las frecuencias de otras estaciones está basada en el principio de resonancia. En este capítulo se abordan las condiciones que producen resonancia en circuitos RLC y las características de los circuitos resonantes

Los filtros pasabajas permiten el paso de una banda de frecuencias que va desde CD hasta una cierta frecuencia mientras que los filtros pasaaltas permiten el paso de frecuencias mayores que una frecuencia baja (FL)

Un filtro pasa bajas permite el paso de una banda especifica de frecuencias, esta banda de frecuencias es llamada banda de paso, en el caso del filtro pasa bajas, esta frecuencia es desde DC (cero hertz.) hasta una frecuencia FH. En frecuencias superiores a FH, se tiene una atenuación en el voltaje de salida, pero a una frecuencia especificada como FS, definida como banda de paro, debe de existir una atenuación mínima.

### 5. VIDEO



### 6. BIBLIOGRAFIA

Floyd, TL (2007). Principios de circuitos electricos. Monterrey: Pearson Educación.

Reyes, L. G. (22 de noviembre de 2007). https://lc.fie.umich.mx. Obtenido de https://lc.fie.umich.mx/~jfelix/InstruII/PB/PB.htm

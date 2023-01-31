1. ##### ¿Qué se entiende por hediondez del código? Pon al menos 5 ejemplos.

   Es síntoma en el código fuente que indica posiblemente un problema más profundo.Usualmente no son bug de programación (errores): no son técnicamente incorrectos y en realidad no impiden que el programa funcione correctamente. Indica deficiencias en el diseño que puede ralentizar el desarrollo o aumentan el riesgo de errores o fallos en el futuro.

   Ejemplos:

   - Código duplicado
   - Método grande
   - Clase grande
   - Demasiados parameteros
   - Envidia de caracteristicas
   - Intimidad inadecuada

   ------

2. ##### ¿Qué tipo de herramienta utilizamos para hacer análisis estático del código?

   Utilizamos analizadores estaticos como pueden ser los linters y sitios web para inspección de código como es el Continuous Inspection.

   ------

3. ##### ¿Qué sitios web nos permiten hacer análisis estático del código o **Continuous Inspection**?

   Los sitios web que nos permiten hacer análisis estático del código son:

   - lint: C  
   - sonar: Java
   - JSLint, ESLint: Javascript 

   Para hacer Continuos Inspection tenemos:

   - Scrutinizer
   - SonarQube

   ------

4. ##### Instala en Netbeans el plugin **FindBugs**, si no lo tienes aún instalado.

![](/home/albertoromero/Imágenes/Capturas de pantalla/Captura desde 2023-01-24 09-59-49.png)

------

5. ##### Realiza **análisis estático de código** para las clases del proyecto *miapp*. Consulta el siguiente enlace: [análisis estático con FindBugs](https://github.com/jamj2000/DAW1-ED-Pruebas-Ejemplo1#análisis-estático-de-código-con-findbugs-en-netbeans)

   ![](/home/albertoromero/Imágenes/Capturas de pantalla/Captura desde 2023-01-25 08-59-06.png)

   Nos encontramos con un bug infinito donde no parara de poner "no acabare nunca!"

   ------

6. ##### Indica al menos un `code smell` relevante de cada clase. Explica cómo podría solucionarse.

   El code smell se encuentra en el if que es lo que hace que se repita tantas veces.

   Para poder solucionar este code smell podriamos poner un return para que así solo suceda una sola vez.

   ------

7. ##### ¿Qué es la refactorización?

   Es el proceso de reestructurar un código fuente, alterando su estructura interna sin cambiar su comportamiento externo. 

   ------

8. ##### ¿Qué técnicas se utilizan a menudo a la hora de refactorizar?

   - Renombrado de variables

   - Pasar código duplicado a funciones

   - Eliminación de código inalcanzable

   - Eliminación de código redundante 

   - Eliminación de código muerto

   ------
## Plan de transporte de sedimentos
Keywords: `Sediment transport` 

### Creación del plan de transporte de sedimentos para flujo cuasi-no permanente

En las actividades anteriores creamos el archivo de geometría, el archivo de caudales y el archivo de sedimentos, ahora solo nos falta crear el plan de transporte de sedimentos que relacione los tres archivos y permita ejecutar el modelo.

<div align="center">
    <img src="./Img/3_1.png" Height="400px">
</div>

Vamos a crear el plan de transporte de sedimentos seleccionando el botón indicado en la siguiente figura.

<div align="center">
    <img src="./Img/3_2.png">
</div>

Se abrirá la ventana _Sediment Transport Analysis_, en esa ventana se escogen los archivos de geometría, caudal y sedimentos que se van a utilizar en el plan.

<div align="center">
    <img src="./Img/3_3.png" Height="300px">
</div>

Se guarda el plan, se le asigna un nombre y un identificativo más corto:

<div align="center">
    <img src="./Img/3_4.png" Height="450px">
</div>

Se debe establecer una fecha de inicio y fin para la simulación, es importante que la información de las series de caudales, temperatura, sedimentos, ect. que se hayan creado sean lo suficientemente extensas para abarcar toda la ventana de tiempo de la simulación. En el caso de estudio vamos a realizar la simulación de un año, empezando el 01Jan2010 0000 y finalizando el 31Dec2010 0000.

<div align="center">
    <img src="./Img/3_5.png" Height="300px">
</div>

Con esta información ya se podría ejecutar el modelo de transporte de sedimentos, sin embargo, antes vamos a modificar las opciones de los resultados (_Sediment Output Options_).

<div align="center">
    <img src="./Img/3_6.png" Height="300px">
</div>

Primero vamos a revisar las tres primeras opciones:

<div align="center">
    <img src="./Img/3_7.png" Height="500px">
</div>

* **Output Level**: puede ser un valor del 1 al 6, mientras mayor sea el número mayor será la cantidad de información y parámetros que se muestren en los resultados. El _Output Level_ 3 es el valor por defecto, la diferencia entre el nivel 3 y el 4 básicamente es que la información se muestra por cada intervalo de clase de la granulometría. En el siguiente link se encuentra detallado cada una de las variables de los niveles de resultado [Output Level](https://www.hec.usace.army.mil/confluence/rasdocs/rassed1d/1d-sediment-transport-user-s-manual/simulating-sediment-transport/sediment-output-options-and-tolerances/output-level).
* **Mass or Volume?**:
* **Output Increment**: 


### Licencia, cláusulas y condiciones de uso

M.TSED es de uso libre para fines académicos, conoce nuestra licencia, cláusulas, condiciones de uso y como referenciar los contenidos publicados en este repositorio, dando [clic aquí](https://github.com/mflatouche/M.TSED/wiki/License).


| [Anterior](../3_Sedimentos) | [:house: Inicio](../../README.md) | [:beginner: Ayuda]() | [Siguiente](../3_Resultados) |
|------------------|-----------------------------------|----------------------|-------------------|

[^1]: Federal Agency Stream Restoration Working Group. (2001). _Stream Corridor Restoration: Principles, Processes, and Practices_. FISRWG.

[^2]: Gibson, S. (5 de Junio de 2019). _Intro HEC-RAS Sediment Demo (Part 1 of 3 - Quasi-Unsteady Flow)_. Obtenido de https://www.youtube.com/watch?v=d416442IC4c

[^3]:Gibson, S. (5 de Junio de 2019). _Intro HEC-RAS Sediment Demo (Part 2 of 3 - Sediment Transport Data)_. Obtenido de https://www.youtube.com/watch?v=9YiL3Men9as&t=609s

[^4]:Gibson, S. (10 de Junio de 2019). _Intro to HEC-RAS Sediment Demo (Part 3 of 3 - Simulation and Output)_. Obtenido de https://www.youtube.com/watch?v=X9xikwi0v-U&t=225s
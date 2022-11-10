## Limitaciones
Keywords: `HEC-RAS 1D` `Model limitations`

### Limitaciones del modelo HEC-RAS 1D

Se debe tener en consideración las siguientes limitaciones del modelo de transporte de sedimentos unidimensional en HEC-RAS:

* HEC-RAS 1D es un modelo a escala de _tramo_. No es recomendable realizar análisis sobre los resultados de los cambios en secciones transversales individuales.
* HEC-RAS 1D es un modelo a escala _decadal_. No es recomendable realizar análisis sobre eventos individuales.
* En el modelo se utilizan algoritmos _empíricos_, por lo cual el modelo de transporte de sedimentos debe ser calibrado para producir resultados confiables.
* Es un modelo unidimensional, por lo tanto, no se tiene tan buen desempeño en el análisis de: zonas de amortiguamiento, derivaciones de flujo, procesos de sedimentación en las llanuras.
* Análisis de flujos newtonianos, aquellos con concentraciones de sólidos menor al 5-10%.
* Información de campo. La información de sedimentos normalmente es escasa.
* Para realizar el modelo de transporte de sedimentos se debe tener previamente un buen modelo hidráulico calibrado.

### Licencia, cláusulas y condiciones de uso

M.TSED es de uso libre para fines académicos, conoce nuestra licencia, cláusulas, condiciones de uso y como referenciar los contenidos publicados en este repositorio, dando [clic aquí](https://github.com/mflatouche/M.TSED/wiki/License).


| [Anterior]() | [:house: Inicio](../../README.md) | [:beginner: Ayuda]() | [Siguiente]() |
|--------------|-----------------------------------|----------------------|---------------|

[^1]: Australian Water School. (22 de Agosto de 2019). _Sediment transport modelling. Too hard for Einstein?_ Obtenido de https://www.youtube.com/watch?v=76FjruCW4KA&list=LL&index=9&t=2462s

[^2]: Gibson, S. (10 de Junio de 2019). _Intro to HEC-RAS Sediment Demo (Part 3 of 3 - Simulation and Output)_. Obtenido de https://www.youtube.com/watch?v=X9xikwi0v-U&t=225s

[^3]: Hydrologic Engineering Center. (s.f.). Hydrologic Engineering Center's (CEIWR-HEC) River Analysis System (HEC-RAS). Obtenido de 1D Sediment Transport Technical Reference Manual: https://www.hec.usace.army.
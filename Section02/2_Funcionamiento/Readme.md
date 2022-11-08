## Funcionamiento del modelo de HEC-RAS 1D
Keywords: `Sediment transport` 

### Acoplamiento entre las características hidráulicas y de sedimentos

HEC-RAS es un modelo acoplado explícito, el cual, para cada incremento computacional ($\Delta t$) realiza el tránsito hidráulico y de sedimentos en todo el tramo en estudio.

En primer lugar, el modelo calcula las características hidráulicas del sistema desde aguas abajo hacia aguas arriba para cada sección transversal. Luego, utilizando las ecuaciones de transporte de sedimentos y las características hidráulicas determinadas previamente, realiza el tránsito de sedimentos desde aguas arriba hacia aguas abajo. Por último, el modelo actualiza las secciones transversales del cauce y comienza otra vez el ciclo para el siguiente incremento computacional. 

<div align="center">
  <img src="./Img/2_1.png">
</div>

### Licencia, cláusulas y condiciones de uso

M.TSED es de uso libre para fines académicos, conoce nuestra licencia, cláusulas, condiciones de uso y como referenciar los contenidos publicados en este repositorio, dando [clic aquí](https://github.com/mflatouche/M.TSED/wiki/License).


| [Anterior]() | [:house: Inicio](../../README.md) | [:beginner: Ayuda]() | [Siguiente]() |
|--------------|-----------------------------------|----------------------|---------------|

[^1]: Australian Water School. (2019, Agosto 22). _Sediment transport modelling. Too hard for Einstein?_ Retrieved from https://www.youtube.com/watch?v=76FjruCW4KA&list=LL&index=9&t=2462s

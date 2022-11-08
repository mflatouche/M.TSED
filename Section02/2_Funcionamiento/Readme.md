## Funcionamiento del modelo de HEC-RAS 1D
Keywords: `Sediment transport` 

### Acoplamiento entre las características hidráulicas y de sedimentos

HEC-RAS es un modelo acoplado explícito, el cual, para cada incremento computacional $(\Delta t)$ realiza el tránsito hidráulico y de sedimentos en todo el tramo en estudio.

En primer lugar, el modelo calcula las características hidráulicas del sistema desde aguas abajo hacia aguas arriba para cada sección transversal. Luego, utilizando las ecuaciones de transporte de sedimentos y las características hidráulicas determinadas previamente, realiza el tránsito de sedimentos desde aguas arriba hacia aguas abajo. Por último, el modelo actualiza las secciones transversales del cauce y comienza otra vez el ciclo para el siguiente incremento computacional[^1]. 

<div align="center">
  <img src="./Img/2_1.png">
</div>

### Continuidad de sedimentos

Para realizar el tránsito de sedimentos, HEC-RAS resuelve la ecuación de Exner, la cual es una ecuación de conservación de la masa (o continuidad) que se aplica a los sedimentos de un sistema fluvial.

<div align="center">
  $\left ( 1-\lambda _{p} \right )B\frac{\delta \eta }{\delta t}=-\frac{\delta Q_{s}}{\delta x}$
</div>

Donde:

$B$ = Ancho del canal

$η$ = Elevación del canal

$λ_{p}$ = Porosidad de la capa activa

$t$ = Tiempo

$x$ = Distancia

$Q_{s}$ = Carga de sedimentos transportada

La ecuación expresa que la diferencia entre el caudal sólido que sale del volumen de control y el caudal sólido que ingresa a este en un intervalo de tiempo es igual al volumen de material sólido acumulado o perdido en el interior, el cual se convierte en un ascenso o descenso de la elevación del fondo del cauce[^2]. Entonces, la ecuación de continuidad de sedimentos también se puede escribir como:

<div align="center">
  $Q_{S (in)}-Q_{S (out)}=\frac{\Delta V}{\Delta t}=(1-\lambda _{p})B\frac{\Delta \eta }{\Delta t}$
</div>

Donde:

$Q_{S (in)}$ = Caudal sólido ingresando al volumen de control

$Q_{S (out)}$ = Caudal sólido saliendo del volumen de control

$V$ = Volumen de material sólido

<div align="center">
    <img src="./Img/2_2.png" width="600px">
</div>

HEC-RAS resuelve la ecuación de continuidad de sedimentos calculando una capacidad de transporte de sedimentos para el volumen de control $(Q_{S (out)})$ asociada a cada sección transversal, comparándola con el caudal de sedimentos $(Q_{S (in)})$ que entra en el volumen de control desde aguas arriba. Si la capacidad de transporte es mayor que el caudal sólido ingresando al volumen de control, HEC-RAS satisface el déficit mediante la erosión de los sedimentos del lecho. Si la oferta supera la capacidad, HEC-RAS deposita el excedente de sedimentos[^3].

### Licencia, cláusulas y condiciones de uso

M.TSED es de uso libre para fines académicos, conoce nuestra licencia, cláusulas, condiciones de uso y como referenciar los contenidos publicados en este repositorio, dando [clic aquí](https://github.com/mflatouche/M.TSED/wiki/License).


| [Anterior]() | [:house: Inicio](../../README.md) | [:beginner: Ayuda]() | [Siguiente]() |
|--------------|-----------------------------------|----------------------|---------------|

[^1]: Australian Water School. (2019, Agosto 22). _Sediment transport modelling. Too hard for Einstein?_ Retrieved from https://www.youtube.com/watch?v=76FjruCW4KA&list=LL&index=9&t=2462s
[^2]: Martín V., J. P. (2009). _Ingeniería de ríos_. Barcelona: Univ. Politèc. de Catalunya.
[^3]: Hydrologic Engineering Center. (s.f.). Hydrologic Engineering Center's (CEIWR-HEC) River Analysis System (HEC-RAS). Obtenido de 1D Sediment Transport Technical Reference Manual: https://www.hec.usace.army.

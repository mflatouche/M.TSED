## Movimiento Incipiente
Keywords: `Shear stress` `Shields` 

### Objetivos

### Requerimientos

### Alcance

### Definición. Análisis de fuerzas

Para el estudio del transporte de sedimentos, es necesario analizar el comienzo del movimiento de las partículas o _movimiento incipiente_. Si se supone una partícula de sedimento de forma esférica sobre el fondo del lecho de un cauce aluvial, con una pentiende longitudinal muy pequeña tal que se pueda despreciar la componente del peso en la dirección del movimiento, se presentan las siguientes fuerzas actuando sobre la partícula[^1].

$F_{L}$ = Fuerza ascensional, producida por las componentes verticales de la velocidad

$F_{D}$ = Fuerza de arrastre, producida por las componentes horizonatles de la velocidad

$W_{S}$ = Peso sumergido de la partícula

$F_{R}$ = Fuerza de resistencia, producida entre la frontera fija y las partículas en movimiento

<div align="center">
  <img src="https://raw.githubusercontent.com/mflatouche/M.TSED/main/Section01/1_MovimientoIncipiente/Img/1_1.png" width="600px">
</div>

Cuando la partícula se encuentra en estado de movimiento incipiente se cumple algunas de estas condiciones:

<div align="center">
  $F_{L}=W_{S}$
  
  $F_{D}=F_{R}$
  
  $M_{0}=M_{R}$
</div>

Donde:

$M_{0}$ = Momento del movimiento producido por  $F_{D}$ y $F_{R}$ 

$M_{R}$ = Momento resistente al movimiento debdio a $F_{L}$ y $W_{S}$ 

La determinación del movimiento incipiente de las partículas o la condición _crítica_ de arrastre es de gran importancia en la ingeniería fluvial, debido a que permite inferir las condiciones que originarían el transporte de partículas del material del lecho o las condiciones que favorecerían su depositación [^2]. Los criterios más utilizados para determinar el movimiento incipiente toman como referencia los esfuerzos cortantes.

### Aproximación de esfuerzos cortantes

#### Aproximación de Shields
El arrastre de materiales no cohesivos con granulometría uniforme se ha estudiado desde hace varios siglos[^2], para esto se han efectuado muchos experimentos de laboratorio, entre los que destacan los resultados presentados por Shields[^1].

Shields realizó sus experimentos en un canal de laboratorio utilizando flujo turbulento completamente desarrollado y materiales con distintas densidades, pero con granulometría uniforme, partiendo siempre de la condición de fondo plano y considerando como condición crítica de arrastre aquella en la que existe movimiento generalizado de las partículas, pero el transporte de ellas o el _caudal sólido_ es muy pequeño y el fondo permanece plano[^2]. 

Los resultados de sus experimentos los presentó en el "Diagrama de Shields" como función de dos parámetros adimensionales:


La ecuación propuesta por Maza de la curva de shields en función del Número de Reynolds de corte es:

<div align="center">
  Si $R_{*}> 1500$ entonces $T=0.06$
  <br> 
  <br>
  Si $R_{*}\leq 1500$ entonces $T=\frac{0.097}{R_{*}}+0.077 exp\left \{- (\frac{19.58}{R_{*}})^{0.3191} \right \}$
</div>

Se definió una función en Python para calcular el esfuerzo cortante adimensional utilizando la ecuación de Maza:

```
def T_shields(Rc):
    if Rc <= 1500:
        T=(0.097/Rc)+0.077*np.exp(-((19.58/Rc)**0.3191))
    else:
        T=0.06
    return T
```

### Licencia, cláusulas y condiciones de uso

M.TSED es de uso libre para fines académicos, conoce nuestra licencia, cláusulas, condiciones de uso y como referenciar los contenidos publicados en este repositorio, dando [clic aquí](https://github.com/mflatouche/M.TSED/wiki/License).


| [Actividad anterior]() | [Inicio](https://github.com/mflatouche/M.TSED/wiki) | [Actividad siguiente]()  |
|------------------------|----------------------------------------------------|----------------------------------------------------------------------------------------|


[^1]: Rodríguez Díaz, H. A. (2010). _Hidráulica Fluvial. Fundamentos y aplicaciones. Socavación_. Colombia: Editorial Escuela Colombiana de Ingeniería.
[^2]: Camargo, J., & Franco, V. (1999). _Manual de Ingeniería de Ríos_. México: Universidad Autónoma de México Instituto de Ingeniería.

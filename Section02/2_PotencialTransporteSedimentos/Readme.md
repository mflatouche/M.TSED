## Cuantificación del potencial de transporte de sedimentos
Keywords: `Sediment transport` 

### Objetivos

### Requerimientos

### Alcance

### Potencial de transporte de sedimentos

El _potencial de transporte de sedimentos_ es la máxima cantidad de sedimentos que se podrían transportar con base en las características hidráulicas dadas de una sección transversal [^1]. Entonces, el potencial de transporte de sedimentos siempre será mayor o igual al transporte real de sedimentos debido a que no tiene en cuenta la cantidad de sedimentos disponibles para el transporte.

Las ecuaciones de transporte de sedimentos son ecuaciones o algortimos empíricos que determinan el potencial de transporte de sedimentos con base en la hidrodinámica de la sección transversal en estudio [^1]. Sin embargo, cada ecuación fue desarrollada para condiciones partículares, las cuales deben ser consideradas y con el objetivo de escoger la ecuación que mejor se adapte a las características del sistema analizado.

En general, las ecuaciones de transporte de sedimentos se basan en aproximaciones de [esfuerzos cortantes](https://github.com/mflatouche/M.TSED/tree/main/Section01/1_MovimientoIncipiente) o de la [potencia de la corriente](https://github.com/mflatouche/M.TSED/tree/main/Section01/1_Potencia)[^1]. En los siguientes módulos se presentarán algunas de las ecuaciones utilizadas para cuantificar el transporte de sedimentos.

### Transporte de sedimentos por cuantificar según el caso de estudio

En la literatura existe una gran cantidad de ecuaciones para determinar el potencial de transporte de sedimentos según el modo de transporte (arrastre, suspensión o total), siendo los métodos más completos aquellos que permiten determinar la carga total de sedimentos, sin embargo, no en todos los casos de estudio es necesario determinar el transporte total. Por ejemplo, si se necesita determinar el tiempo en el que se colmata el tramo aguas arriba de una presa derivadora, se tendría que calcular el transporte por arrastre. Por otro lado, si se necesita determinar la pérdida de capacidad del embalse de una gran presa se necesita cuantificar el transporte total, ya que aún las partículas más finas se depositan dentro del embalse [^2].

En la siguiente tabla se indican algunos estudios y el transporte de sedimentos requerido para resolverlos:

| Estudio | Transporte por cuantificar |
|---|---|
| Tiempo de llenado de una pequeña presa derivadora | $G_{B}$ |
| Tiempo de llenado de una presa derivadora | $G_{B}$ o $G_{BT}$ |
| Tiempo de llenado de una gran presa | $G_{T}$ |
| Erosión aguas abajo de grandes presas | $G_{BT}$ |
| Estabilidad de cauces y rectificaciones | $G_{B}$ o $G_{BT}$ |
| Derivaciones en ríos hacia canales de riego | $G_{BS}$ |
| Obras de defensa contra inundaciones |  |
|           Bordos de protección | $G_{BT}$ |
|           Desvíos temporales | $G_{BS}$ y $G_{L}$  |
|           Cauces de alivio | $G_{BS}$ |
| Bombeo directo de un río | $G_{BS}$ |
| Tanques de sedimentación | $G_{B}$ o $G_{BT}$ |
| Desvíos para acuacultura en lagunas costeras o estanques | $G_{BS}$ o $G_{L}$  |
| Entubamiento de arroyos en su paso por centros urbanos | $G_{BT}$ |
| Diseño de canales sin arrastre | $G_{B}=0$ (condición crítica de arrastre) |
| Estudios de erosión y sedimentación de tramso de ríos | $G_{B}$ o $G_{BT}$ |

> Fuente: Instituto de Ingeniería UNAM. (1999)[^2]

### Licencia, cláusulas y condiciones de uso

M.TSED es de uso libre para fines académicos, conoce nuestra licencia, cláusulas, condiciones de uso y como referenciar los contenidos publicados en este repositorio, dando [clic aquí](https://github.com/mflatouche/M.TSED/wiki/License).


| [Actividad anterior]() | [Inicio](https://github.com/mflatouche/M.TSED/wiki) | [Actividad siguiente]()  |
|------------------------|----------------------------------------------------|----------------------------------------------------------------------------------------|


[^1]: Hydrologic Engineering Center. (s.f.). Hydrologic Engineering Center's (CEIWR-HEC) River Analysis System (HEC-RAS). Obtenido de 1D Sediment Transport Technical Reference Manual: https://www.hec.usace.army.mil/confluence/rasdocs/rassed1d/1d-sediment-transport-technical-reference-manual
[^2]: Instituto de Ingeniería UNAM. (1999). _Manual de Ingeniería de Ríos_. México: Universidad Autónoma de México.
[^3]:Rodríguez Díaz, H. A. (2010). _Hidráulica Fluvial. Fundamentos y aplicaciones. Socavación_. Colombia: Editorial Escuela Colombiana de Ingeniería.


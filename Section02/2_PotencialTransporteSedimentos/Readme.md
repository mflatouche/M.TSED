## Cuantificación del transporte de sedimentos
Keywords: `Sediment transport` 

### Carga de lavado y carga del material del lecho

Como se había explicado en capítulos anteriores, la carga de sedimentos de un cauce se puede caracterizar en función del origen del material transportado. La carga total de sedimentos en un cauce, en cualquier momento y lugar, se divide en dos partes: la carga de lavado y la carga de lecho. La fuente principal de la carga de lavado es la cuenca hidrográfica, producto de procesos de erosión. La fuente de la carga de material del lecho es principalmente el propio lecho del río[^1].

La carga de lavado se compone de las partículas de sedimento más finas transportadas y la turbulencia del flujo las mantiene en suspensión. La concentración de la carga de lavado es esencialmente independiente de las condiciones hidráulicas de la corriente y, por lo tanto, no puede ser calculada usando parámetros hidráulicos medidos o estimados $(V$ o $Q)$. La concentración de la carga de lavado es generalmente función de la disponibilidad de sedimentos; es decir, la corriente puede transportar tanto sedimento como la cuenca y las riberas puedan aportar (para concentraciones de sedimentos por debajo de aproximadamente 3000 mg/l)[^1].

La carga de material del lecho se mueve a lo largo del lecho del río rodando, deslizándose o en saltación, y puede ser arrastrada periódicamente al flujo por la turbulencia, donde se convierte en una parte de la carga suspendida. La carga de material del lecho está controlada hidráulicamente y puede calcularse utilizando las ecuaciones de transporte de sedimentos[^1] que se presentarán en las siguientes actividades.

### Potencial de transporte de sedimentos

El _potencial de transporte de sedimentos_ es la máxima cantidad de sedimentos que se podrían transportar con base en las características hidráulicas dadas de una sección transversal[^2]. Entonces, el potencial de transporte de sedimentos siempre será mayor o igual al transporte real de sedimentos debido a que no tiene en cuenta la cantidad de sedimentos disponibles para el transporte.

Las ecuaciones de transporte de sedimentos del material del lecho son ecuaciones o algortimos empíricos que determinan el potencial de transporte de sedimentos de una corriente en función de sus características hidráulicas y de las características geométricas y granulométricas del cauce[^3]. Sin embargo, cada ecuación fue desarrollada para condiciones partículares, las cuales deben ser consideradas y con el objetivo de escoger la ecuación que mejor se adapte a las características del sistema analizado.

En general, las ecuaciones de transporte de sedimentos se basan en aproximaciones de [esfuerzos cortantes](./Section01/1_MovimientoIncipiente) o de la [potencia de la corriente](./Section01/1_Potencia)[^2]. En los siguientes módulos se presentarán algunas de las ecuaciones utilizadas para cuantificar el transporte de sedimentos.

### Transporte de sedimentos por cuantificar según el caso de estudio

En la literatura existe una gran cantidad de ecuaciones para determinar el potencial de transporte de sedimentos según el modo de transporte (arrastre, suspensión o total), siendo los métodos más completos aquellos que permiten determinar la carga total de sedimentos, sin embargo, no en todos los casos de estudio es necesario determinar el transporte total. Por ejemplo, si se necesita determinar el tiempo en el que se colmata el tramo aguas arriba de una presa derivadora, se tendría que calcular el transporte por arrastre. Por otro lado, si se necesita determinar la pérdida de capacidad del embalse de una gran presa se necesita cuantificar el transporte total, ya que aún las partículas más finas se depositan dentro del embalse[^4].

En la siguiente tabla se indican algunos estudios y el transporte de sedimentos requerido para resolverlos:

<div align="center">

| Estudio                                                    | Transporte por cuantificar                |
|------------------------------------------------------------|-------------------------------------------|
| Tiempo de llenado de una pequeña presa derivadora          | $G_{B}$                                   |
| Tiempo de llenado de una presa derivadora                  | $G_{B}$ o $G_{BT}$                        |
| Tiempo de llenado de una gran presa                        | $G_{T}$                                   |
| Erosión aguas abajo de grandes presas                      | $G_{BT}$                                  |
| Estabilidad de cauces y rectificaciones                    | $G_{B}$ o $G_{BT}$                        |
| Derivaciones en ríos hacia canales de riego                | $G_{BS}$                                  |
| Obras de defensa contra inundaciones: Bordos de protección | $G_{BT}$                                  |
| Obras de defensa contra inundaciones: Desvíos temporales   | $G_{BS}$ y $G_{L}$                        |
| Obras de defensa contra inundaciones: Cauces de alivio     | $G_{BS}$                                  |
| Bombeo directo de un río                                   | $G_{BS}$                                  |
| Tanques de sedimentación                                   | $G_{B}$ o $G_{BT}$                        |
| Desvíos para acuacultura en lagunas costeras o estanques   | $G_{BS}$ o $G_{L}$                        |
| Canalización de arroyos en su paso por centros urbanos     | $G_{BT}$                                  |
| Diseño de canales sin arrastre                             | $G_{B}=0$ (condición crítica de arrastre) |
| Estudios de erosión y sedimentación de tramos de ríos      | $G_{B}$ o $G_{BT}$                        |

</div>

> Fuente: Instituto de Ingeniería UNAM. (1999)[^4]

### Licencia, cláusulas y condiciones de uso

M.TSED es de uso libre para fines académicos, conoce nuestra licencia, cláusulas, condiciones de uso y como referenciar los contenidos publicados en este repositorio, dando [clic aquí](https://github.com/mflatouche/M.TSED/wiki/License).


| [Anterior]() | [:house: Inicio](../../README.md) | [:beginner: Ayuda]() | [Siguiente]() |
|--------------|-----------------------------------|----------------------|---------------|

[^1]: Federal Agency Stream Restoration Working Group. (2001). _Stream Corridor Restoration: Principles, Processes, and Practices_. FISRWG.
[^2]: Hydrologic Engineering Center. (s.f.). Hydrologic Engineering Center's (CEIWR-HEC) River Analysis System (HEC-RAS). Obtenido de 1D Sediment Transport Technical Reference Manual: https://www.hec.usace.army.mil/confluence/rasdocs/rassed1d/1d-sediment-transport-technical-reference-manual
[^3]: Martín V., J. P. (2009). _Ingeniería de ríos_. Barcelona: Univ. Politèc. de Catalunya.
[^4]: Instituto de Ingeniería UNAM. (1999). _Manual de Ingeniería de Ríos_. México: Universidad Autónoma de México.
[^5]:Rodríguez Díaz, H. A. (2010). _Hidráulica Fluvial. Fundamentos y aplicaciones. Socavación_. Colombia: Editorial Escuela Colombiana de Ingeniería.


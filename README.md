# Optimización para la Localización de Plantas de Reciclaje

Este repositorio contiene la resolución de un problema de diseño de redes de cadena de suministro (Supply Chain Network Design) aplicado al ámbito municipal. El objetivo principal es optimizar la localización de centros de acopio y la asignación óptima de flujos de transporte de material reciclable, minimizando los costos anuales de operación bajo restricciones de capacidad, regulatorias y ambientales.

El desarrollo fue estructurado e implementado en **Python** utilizando programación lineal entera mixta (**MILP**).

##  Tecnologías y Librerías Utilizadas
- **Python 3.10+**
- **PuLP 2.9.0** (Modelamiento de optimización matemática)
- **CBC Solver** (Motor de resolución Branch and Bound)
- **Pandas** & **NumPy** (Procesamiento y estructuración de datos)
- **Matplotlib** (Visualización espacial de redes y flujos)

##  Modelos Implementados
1. **Modelo Base (P1):** Minimización del costo total (Costo Fijo de activación + Costo de Transporte anualizado) sujeto a balances de masa y límites de capacidad.
2. **Escenario Normativo (P2):** Inclusión de restricciones de exclusión espacial (protección de zonas húmedas protegidas) y condiciones contractuales de uso operativo mínimo (50% de capacidad).
3. **Análisis de Sensibilidad (P4):** Evaluación del comportamiento y reorganización óptima de la red ante un incremento del 50% en los costos de combustible/transporte.

##  Características del Proyecto
- **Enfoque de Negocio:** Toma de decisiones informada basada en datos cuantitativos y restricciones reales del entorno.

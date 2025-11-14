# MEO – Metaheurística Basada en Gasto Metabólico

Este proyecto implementa un algoritmo de optimización basado en la ecuación de movimiento metabólico y regeneración adaptativa (MEO). El algoritmo es evaluado usando varios benchmarks comunes en problemas de optimización, como el benchmark de *Rastrigin*, *Sphere*, *Rosenbrock*, *Ackley* y *Griewank*.

## Descripción

El objetivo del proyecto es optimizar un conjunto de funciones utilizando un enfoque basado en la simulación de un comportamiento metabólico con regeneración adaptativa. La optimización se realiza mediante un algoritmo que adapta los parámetros de la población durante el proceso de búsqueda.

El código incluye varias funciones de benchmark, un algoritmo de optimización personalizado, y herramientas para gestionar los límites del espacio de búsqueda y las actualizaciones de la población.

## Instrucciones

Para personalizar el experimento, modifica los valores de `benchmark` (elige entre 'sphere', 'rastrigin', 'rosenbrock', 'ackley', 'griewank') y `config` (elige entre 'C1', 'C2', 'C3', 'C4') dentro de la función `ejecutar_testeo()` en el código.


## Requisitos

Este proyecto requiere Python 3.6 o superior y las siguientes librerías:

- `numpy` para cálculos numéricos
- `matplotlib` para visualización

Instalar las dependencias:

```bash
pip install numpy matplotlib




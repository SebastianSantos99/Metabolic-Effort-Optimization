# MEO – Metaheurística Basada en Gasto Metabólico

Este proyecto implementa un algoritmo de optimización basado en la ecuación de movimiento metabólico y regeneración adaptativa (MEO). El algoritmo es evaluado usando varios benchmarks comunes en problemas de optimización, como el benchmark de *Rastrigin*, *Sphere*, *Rosenbrock*, *Ackley* y *Griewank*.

## Descripción

El objetivo del proyecto es optimizar un conjunto de funciones utilizando un enfoque basado en la simulación de un comportamiento metabólico con regeneración adaptativa. La optimización se realiza mediante un algoritmo que adapta los parámetros de la población durante el proceso de búsqueda.

El código incluye varias funciones de benchmark, un algoritmo de optimización personalizado, y herramientas para gestionar los límites del espacio de búsqueda y las actualizaciones de la población.

## Instrucciones

Para personalizar el experimento, simplemente debes modificar los valores de `benchmark` y `config` en la función `ejecutar_testeo()` del código de cada algoritmo. A continuación te explico cómo hacerlo:

## 1. Valores de Benchmark:
Puedes elegir entre los siguientes benchmarks (funciones de optimización) que se utilizarán en el experimento:
- `'sphere'`
- `'rastrigin'`
- `'rosenbrock'`
- `'ackley'`
- `'griewank'`

Cada uno de estos benchmarks tiene diferentes características y puede ser adecuado para evaluar el rendimiento del algoritmo en diferentes tipos de funciones.

## 2. Configuraciones (config):
Las configuraciones disponibles son las siguientes:
- `'C1'`: Población de 50, 1000 generaciones.
- `'C2'`: Población de 100, 500 generaciones.
- `'C3'`: Población de 200, 250 generaciones.
- `'C4'`: Población de 400, 125 generaciones.

Estas configuraciones controlan el tamaño de la población y el número de generaciones para cada experimento. Puedes elegir la configuración que mejor se adapte a tu escenario de prueba.

## 3. Cómo Ejecutar Cada Algoritmo

`python PSO.py <benchmark> <config>`
  Ejemplo de ejecucion
  
`python PSO.py griewank C1`



## Requisitos

Este proyecto requiere Python 3.6 o superior y las siguientes librerías:

- `numpy` para cálculos numéricos
- `matplotlib` para visualización

Instalar las dependencias:

```bash
pip install numpy matplotlib




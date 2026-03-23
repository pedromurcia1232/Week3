# Week 3 - Backpropagation y Funciones de Activación

## Objetivo
Implementar una red neuronal básica desde cero con NumPy para evidenciar el proceso de aprendizaje mediante backpropagation y comparar dos funciones de activación en la capa oculta.

## Qué se implementó
- Red neuronal de una capa oculta entrenada con descenso por gradiente.
- Forward propagation, función de pérdida Binary Cross Entropy y backpropagation manual.
- Comparación entre activaciones **Sigmoid** y **ReLU** manteniendo constante el dataset y la configuración base.
- Gráficas de evolución de `loss` y `accuracy`, tabla de métricas y conclusiones en Markdown.

## Activaciones comparadas
- Sigmoid
- ReLU

## Resultados principales
En esta ejecución, **ReLU** logró mejor desempeño final que **Sigmoid**, con menor `loss` y mayor exactitud de prueba. La comparación fue válida porque solo cambió la activación de la capa oculta.

## Cómo ejecutar el notebook
1. Abrir `backprop_activaciones_week3.ipynb` en Google Colab.
2. Ejecutar todas las celdas en orden.
3. Verificar las gráficas, la tabla de resultados y las conclusiones finales.

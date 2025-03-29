# Simulación de Colas

Este proyecto realiza simulaciones de sistemas de colas utilizando el método de Monte Carlo para modelar el comportamiento de un sistema con servidores. El código simula el comportamiento de las colas tanto con un servidor como con múltiples servidores, utilizando diferentes distribuciones de probabilidad (exponencial y normal) para los tiempos entre llegadas y tiempos de servicio.

## Descripción

El código simula la llegada y salida de clientes en un sistema de colas, y calcula métricas clave como el tiempo promedio en cola, el tiempo promedio en el sistema, la longitud promedio de la cola y la utilización de los servidores. Las simulaciones permiten comparar el rendimiento del sistema al variar el número de servidores.

### Características del proyecto:
- **Simulación de colas con un servidor**: Utiliza distribuciones exponenciales y normales para los tiempos de llegada y de servicio.
- **Simulación de colas con múltiples servidores**: Evalúa el rendimiento del sistema con hasta 5 servidores.
- **Cálculo de métricas**: Incluye métricas como el tiempo de espera en cola, el tiempo en el sistema, la longitud de la cola y la utilización de los servidores.
- **Visualización**: Los resultados de las simulaciones se muestran a través de gráficos de líneas, barras e histogramas utilizando Matplotlib y Seaborn.

## Requisitos

- Python 3
- Pandas
- Numpy
- Matplotlib
- Seaborn

## Ejecución

1. Clona este repositorio:
   ```bash
   git clone https://github.com/usuario/simulacion_colas.git

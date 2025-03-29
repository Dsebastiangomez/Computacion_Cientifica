# Simulación de Colas

Este proyecto realiza simulaciones de sistemas de colas utilizando el método de Monte Carlo para modelar el comportamiento de un sistema con servidores. El código simula el comportamiento de las colas tanto con un servidor como con múltiples servidores, utilizando diferentes distribuciones de probabilidad (exponencial y normal) para los tiempos entre llegadas y tiempos de servicio.

## Descripción

El código simula la llegada y salida de clientes en un sistema de colas, y calcula métricas clave como el tiempo promedio en cola, el tiempo promedio en el sistema, la longitud promedio de la cola y la utilización de los servidores. Las simulaciones permiten comparar el rendimiento del sistema al variar el número de servidores.

### Características del proyecto:
- **Simulación de colas con un servidor**: Utiliza distribuciones exponenciales y normales para los tiempos de llegada y de servicio.
- **Simulación de colas con múltiples servidores**: Evalúa el rendimiento del sistema con hasta 5 servidores.
- **Cálculo de métricas**: Incluye métricas como el tiempo de espera en cola, el tiempo en el sistema, la longitud de la cola y la utilización de los servidores.
- **Visualización**: Los resultados de las simulaciones se muestran a través de gráficos de líneas, barras e histogramas utilizando Matplotlib y Seaborn.

## Resultados

Tiempo en cola con un servidor. Cola markoviana

![Tiempo_cola_MM1](https://github.com/user-attachments/assets/a8ba91ce-38c5-46f1-b33e-bbfe674afa9c)


Entidades en cola y probabilidad de n entidades en sistema. Cola con tiempos de servicio normales

![Entidades_cola_MG1](https://github.com/user-attachments/assets/1d07b0f6-e1e8-4080-928a-1becb8a4031c)

![Entidades_sistema_MG1](https://github.com/user-attachments/assets/59e0ff1a-39af-4102-96c8-66ad41999427)

Comparativo de métricas de desempeño para múltiples servidores

![Metricas_multiples_servidores](https://github.com/user-attachments/assets/2eabc855-efa8-4e31-9d29-2721d858c62d)

## Ejecución

1. Clona este repositorio:
   ```bash
   git clone https://github.com/usuario/simulacion_colas.git

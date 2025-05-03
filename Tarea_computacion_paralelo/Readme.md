# Resolución del Problema del Viajero (TSP) con Computación en Paralelo y CPLEX

Este repositorio contiene una serie de scripts en Python diseñados para resolver el clásico problema del viajero (TSP) utilizando diferentes enfoques computacionales:

- Fuerza bruta en ejecución secuencial (serie)
- Fuerza bruta con computación en paralelo (`multiprocessing`)
- Optimización exacta mediante el solver IBM CPLEX y la librería `docplex`

Recuerde cargar el archivo de Excel con las coordenadas de ciudades.

![image](https://github.com/user-attachments/assets/fbaa174f-2e0c-4cef-a01b-6e9d3eeeb8b8)



Para el problema del viajero con 10 ciudades, se tiene que:

- El método en serie es significativamente más lento, con un tiempo de cómputo de 141,052 segundos, lo que demuestra su ineficiencia para problemas con un gran número de ciudades.
- El uso de multiprocessing mejora notablemente el tiempo de cómputo, reduciéndolo a 123,5711 segundos, gracias a la paralelización del trabajo en múltiples núcleos.
- CPLEX ofrece una solución mucho más eficiente, con un tiempo de cómputo de 0,27 segundos, destacándose por su rapidez en la resolución de problemas complejos como el TSP.

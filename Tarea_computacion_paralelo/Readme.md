# Resolución del Problema del Viajero (TSP) con Computación en Paralelo y CPLEX

Este repositorio contiene una serie de scripts en Python diseñados para resolver el clásico problema del viajero (TSP) utilizando diferentes enfoques computacionales:

- Fuerza bruta en ejecución secuencial (serie)
- Fuerza bruta con computación en paralelo (`multiprocessing`)
- Optimización exacta mediante el solver IBM CPLEX y la librería `docplex`

Recuerde cargar el archivo de Excel con las coordenadas de ciudades.

![image](https://github.com/user-attachments/assets/fbaa174f-2e0c-4cef-a01b-6e9d3eeeb8b8)


A continuación (tabla \ref{tab:tiempos_computo}), se muestran los tiempos de cómputo para el problema de optimización, con el método de fuerza bruta con cálculos en serie y paralelo, además del tiempo de solución con Cplex.
$$
\begin{table}[h!]
\centering
\begin{tabular}{|c|c|}
\hline
\textbf{Método} & \textbf{Tiempo de Cómputo (segundos)} \\
\hline
\textbf{Serie} & 141,3052 \\
\hline
\textbf{Multiprocessing} & 123,5711 \\
\hline
\textbf{CPLEX} & 0,27 \\
\hline
\end{tabular}
\caption{Comparación del tiempo de cómputo para el TSP.}
\label{tab:tiempos_computo}
\end{table}
$$

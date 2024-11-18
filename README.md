# Laberinto-Reiforcement-Learning

Este proyecto implementa un agente inteligente que aprende a resolver un laberinto utilizando el algoritmo **Q-Learning**, un método de aprendizaje por refuerzo. El laberinto se genera aleatoriamente, y el agente aprende a encontrar la mejor ruta hacia la meta.

---

## Características
1. **Generación de laberintos aleatorios**:
   - El laberinto se representa como una matriz bidimensional donde:
     - `1`: Pared.
     - `0`: Camino.
     - `2`: Meta.

2. **Algoritmo Q-Learning**:
   - El agente explora el laberinto y aprende a tomar decisiones para maximizar la recompensa.
   - Parámetros ajustables:
     - **Tasa de aprendizaje (α)**.
     - **Factor de descuento (γ)**.

3. **Visualización del proceso**:
   - Usa `matplotlib` para mostrar el laberinto y la posición actual del agente durante el entrenamiento.

4. **Resolución del laberinto**:
   - Una vez entrenado, el agente utiliza la tabla Q para encontrar la mejor ruta hacia la meta.

---

## Requisitos

Instalar los siguientes paquetes de Python:
- `numpy`
- `matplotlib`


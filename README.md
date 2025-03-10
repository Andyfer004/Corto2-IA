# 🚀 Entrenamiento y Evaluación del Agente con Q-learning en Frozen Lake

[![Abrir en Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Andyfer004/Corto2-IA/blob/main/Corto2.ipynb)

Este repositorio contiene un **notebook** en Python donde se entrena un agente utilizando **Q-learning** en el entorno de **Frozen Lake** de Gymnasium con `slippery=True`.

## 📌 Descripción

El notebook implementa un agente basado en **aprendizaje por refuerzo** con los siguientes pasos:

1. **Inicialización de la Q-table**: Se utiliza una matriz Q para almacenar los valores de acción-estado.
2. **Definición de la política ε-greedy**: Se implementa un mecanismo de exploración con **ε** decreciente.
3. **Actualización con la ecuación de Bellman**: Se ajustan los valores de Q usando la regla de actualización estándar.
4. **Evaluación del agente**: Se ejecutan **100 episodios de prueba**, donde el agente toma la mejor acción según la Q-table aprendida.

## 📊 Visualización de Resultados

El notebook genera dos gráficas principales:

- **Recompensa promedio móvil** 📈: Muestra cómo mejora el agente con el tiempo.
- **Decaimiento de ε** 📉: Visualiza la reducción de exploración a medida que el agente aprende.

## 🔧 Requisitos

Para ejecutar el código localmente, necesitas instalar las siguientes dependencias:

```bash
pip install gymnasium numpy matplotlib
```

## ▶️ Ejecución

Puedes correr el notebook en **Google Colab** o en tu entorno local. Para ejecutarlo en Colab, simplemente haz clic en el badge de arriba ☝️.

Para correrlo en local:

```bash
jupyter notebook Corto2.ipynb
```



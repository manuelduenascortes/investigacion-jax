# Investigación sobre JAX - Máster en Inteligencia Artificial y Big Data

## Descripción del Proyecto
Este repositorio contiene una actividad de investigación y prueba de concepto sobre **JAX**, la librería desarrollada por Google para computación numérica de alto rendimiento y aprendizaje automático.

El objetivo de este proyecto es analizar las diferencias arquitectónicas de JAX frente a frameworks tradicionales como TensorFlow y PyTorch, así como demostrar sus capacidades de aceleración (XLA) y diferenciación automática mediante ejemplos prácticos de código.

## Contenido del Repositorio
El repositorio se estructura de la siguiente manera:

* **`investigacion_jax.ipynb`**: Es el archivo principal del proyecto. Este Cuaderno Jupyter integra tanto la documentación teórica como la implementación práctica. Incluye:
    * Introducción a JAX y su ecosistema (Flax, Haiku, Optax).
    * Comparativa técnica frente a PyTorch y TensorFlow.
    * Ejemplos de código ejecutables de las transformaciones clave: `grad` (diferenciación), `jit` (compilación Just-In-Time) y `vmap` (vectorización).
    * Visualización gráfica de derivadas automáticas.
    * Conclusiones finales sobre el rendimiento y usabilidad.

* **`requirements.txt`** (Opcional): Fichero de dependencias necesarias para reproducir el entorno de ejecución.

## Tecnologías Utilizadas
* **Lenguaje:** Python 3
* **Librería Principal:** JAX (jax, jaxlib)
* **Librerías Auxiliares:** NumPy, Matplotlib (para visualización de datos).

## Instrucciones de Ejecución
Para visualizar y ejecutar el código contenido en este repositorio:

1.  Clonar el repositorio o descargar los archivos.
2.  Instalar las dependencias necesarias:
    ```bash
    pip install jax jaxlib matplotlib jupyter
    ```
3.  Abrir el archivo `investigacion_jax.ipynb` utilizando Jupyter Notebook, Jupyter Lab o Google Colab.

## Bibliografía y Recursos
Para la elaboración de la documentación y los ejemplos técnicos se han consultado las siguientes fuentes oficiales:

* **

# Calidad del Vino Rojo y Blanco
El proyecto se planteo con la finalidad de predecir la calidad de vinos rojos y blancos conociendo las características fisicoquímicas y la calidad de distintas muestras.

Las etapas del proyecto se dividen de la siguiente manera: preprocesamiento, entrenamiento & selección de modelos y evaluación.

Se implementaron modelos de aprendiza supervisado de regresión, clasificación y métodos de ensamble.

**Índice**  

[Instalación](#id_instalacion)  
[Tecnologías usadas](#id_tecnologias)  
[Autores](#id_autores)  
[Creditos](#id_creditos)

## Archivos
1.	**winequality-red.csv**: Dataset con las propiedades fisicoquímicas y puntajes de calidad de muestras de vinos rojos.
1.	**winequality-white.csv**: Dataset con las propiedades fisicoquímicas y puntajes de calidad de muestras de vinos blancos.
1.	**Exploración.ipynb**: Notebook que contiene una exploración básica de los datasets como boxplots y matrices de correlación.
1.	**Classif_red.ipynb**: Notebook que contiene todos los modelos de clasificación entrenados para el dataset de vinos rojos, con sus respectivas métricas de error y matrices de confusión.
1.	**Classif_white.ipynb**: Notebook que contiene todos los modelos de clasificación entrenados para el dataset de vinos blancos, con sus respectivas métricas de error y matrices de confusión.
1.	**Regg_red.ipynb**: Notebook que contiene todos los modelos de regresión entrenados para el dataset de vinos rojos, con sus respectivas métricas de error.
1.	**Regg_white.ipynb**: Notebook que contiene todos los modelos de regresión entrenados para el dataset de vinos blancos, con sus respectivas métricas de error.
1.	**Conclusiones.ipynb**: Notebook que explica los mejores modelos y donde se selecciona el modelo final.


## Instalación<a name="id_instalacion"></a>
1. En la pagina inicial del repositorio de GitHub seleccionar la pestaña `Code` y presionar la opción `Download ZIP` ó
2. Clonar el repositorio utilizando la consola de comandos de GIT
```
git clone https://github.com/camilotobon18/wine_quality_ML/
```
3. Abrir el sistema de gestión de paquetes `Anaconda`
4. Dentro de `Anaconda` abrir la aplicación `Jupyter Notebook` Donde se encuentra
5. Buscar la carpeta del proyecto y abrir el archivo `.ipynb`
6. En la pestaña `Kernel` seleccionar la opción `Restart & Run All`

## Tecnologías usadas<a name="id_tecnologias"></a>

Lenguaje de programación y librerías utilizadas en el desarrollo del proyecto
* [Python](https://www.python.org/): Versión 3.8.5
* [Pandas](https://pandas.pydata.org/): Versión 1.1.3
* [Numpy](https://numpy.org/): Versión 1.19.2
* [Matplotlib](https://matplotlib.org/): Versión 3.4.1
* [Seaborn](https://seaborn.pydata.org/): Versión 0.11.0
* [Scikit-learn](https://scikit-learn.org/stable/): Versión 0.24.1
* [SciPy](https://www.scipy.org/): Versión 1.5.2
* [Collections](https://docs.python.org/3/library/collections.html): Versión 3.3.
* [Imblearn](https://pypi.org/project/imblearn/): Versión 0.8.0

## Autores<a name="id_autores"></a>

* Alejandro Velásquez Arango - [Perfil de GitHub](https://github.com/alejo963) - [Perfil de LinkedIn](https://www.linkedin.com/in/alejandro-velasquez-arango-984bb71b2/)
* Camilo Andrés Tobón Florez - [Perfil de GitHub](https://github.com/camilotobon18) - [Perfil de LinkedIn](www.linkedin.com/in/camilo-andrés-tobón-florez-4390851ba)
* Hugo Vega - [Perfil de GitHub](https://github.com/hevega95) - [Perfil de LinkedIn](http://linkedin.com/in/hugo-vega-66b08a181)

## Creditos<a name="id_creditos"></a>

El proyecto fue llevado a cabo gracias a los conocimientos adquiridos en el diplomado de `Machine Learning` dictado por la Universidad EAFIT, agradecemos a la institución en especial a los docentes Ana María López Moreno, Isabel Cristina Hernández Mona y Esteban López Aguirre. 

# TFG
<p align="center">
  <img width="360" height="100" src="Memoria/portada/imagenes/logo.png">
</p>
Repositorio del trabajo fin de grado realizado por María Victoria Granados Pozo del Doble Grado de Ingeniería Informática y Matemáticas de la Universidad de Granada.

En este trabajo se ha implementado un algoritmo criptográfico resistente a ordenadores cuánticos, denominado UOV, para la firma de bloques. Posteriormente se ha realizar un prototipo de cadena de bloques para probar el algoritmo y se integrado en la blockchain ARK.

Este repositorio consta de varias carpetas:
* En la carpeta *Memoria* se puede encontrar la memoria, con un manual de usuario. Se compila con `pdflatex proyecto.tex`.
* La carpeta *Presentación* contiene el código fuente y el pdf utilizado para la presentación. Se compila con `xelatex main.tex`. La plantilla que se ha utilizado para la presentación la publicó [@CharlieLeee][repo] y es la plantilla [BIT_school_Template][plantilla]
* La carpeta *src* contiene el código del algoritmo UOV en python, con una implementación de la aritmética del cuerpo de 2⁷ elementos. Se puede ejecutar con `python3 uov.py`. Además se incluye la implementación en SageMath, para abrirlo ejecutar `sage -n jupyter`.

[repo]:https://github.com/CharlieLeee
[plantilla]:https://github.com/CharlieLeee/My_Beamer_Template/tree/master/BIT_school_Template

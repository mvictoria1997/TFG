# TFG

Repositorio del trabajo fin de grado.

En este trabajo se ha implementado un algoritmo criptográfico resistente a ordenadores cuánticos, denominado UOV, para la firma de documentos, y posteriormente se ha integrado en la blockchain ARK.

* En la carpeta Memoria se puede encontrar la memoria, con un manual de usuario. Se compila con `pdflatex proyecto.tex`
* La carpeta Presentación contiene el código fuente y el pdf utilizado para la presentación. Se compila con `xelatex main.tex`
* La carpeta src contiene el código del algoritmo UOV en python, con una implementación de la aritmética del cuerpo de *2^7* elementos. Se puede ejecutar con `python3 uov.py`. Además se incluye la implementación en SageMath, para abrirlo ejecutar `sage -n jupyter`.

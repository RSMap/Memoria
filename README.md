# Documento del trabajo de Fin de Grado: "RSMap"

Si no dispone de las herramientas para construir el PDF, puede descargarlo desde [aquí](https://github.com/RSMap/TFG/raw/master/project.pdf).

## Importante:
Tanto la estructura de éste repositorio, como la automatización para generar el documento en LaTeX ha sido definida por [Germán Martínez Maldonado](https://github.com/germaaan) localizada en el repositorio [TFG](https://github.com/germaaan/TFG).


### Autor: José Manuel Luque Burgos
### Tutor: Juan Julián Merelo Guervós


Documentación realizada con LaTeX, para generar el archivo PDF introducir las siguientes órdenes:

#### Distribuciones basadas en Debian
```
sudo apt-get install texlive texlive-latex-extra texlive-lang-spanish xzdec
tlmgr init-usertree
tlmgr install xcolor
./makePDF.sh
```

#### ArchLinux
```
yaourt -S texlive-core texlive-latex-extra
./makePDF.sh
```

## Tecnologías usadas

Las herramientas utilizadas de forma global en el proyecto se detallan [aquí](https://github.com/RSMap/RSMap#tecnolog%C3%ADas-usadas).

Las tecnologías usadas para la detección de vehículos se encuentra descritas [aquí](https://github.com/RSMap/RSMapPi#technologies).

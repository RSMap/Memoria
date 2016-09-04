# Documento del trabajo de Fin de Grado: "RSMap"

## Importante:
Tanto estructura de éste repositorio, como la automatización para generar el documento en LaTeX sido definida por [Germán Martínez Maldonado](https://github.com/germaaan) localizada en el repositorio [TFG](https://github.com/germaaan/TFG).


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

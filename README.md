<!-- LTeX: language=es -->

# Plantilla de presentación en LaTeX-beamer

Código fuente en LaTeX (beamer) para presentaciones, como plantilla.

## Autor
* Dr.-Ing. Alan Wilson (<alan.wilson@usm.cl>)


## Contenido de las carpetas
* [conf](./conf) Archivos de configuración del documento LaTeX (paquetes, macros, configuración de estilos, etc.).

* [img](./img) Imágenes pre-generadas (.pdf, .jpg, etc.) para insertar en el documento.

* [frame](./frame) Código fuente con el contenido de las diapositivas (frames).

* [glos](./glos) Definiciones de glosario utilizando `\usepackage{glossaries}`
* [bib](./bib) Archivos de bibliografía para LaTeX/BibTeX.

* [texfig](./texfig) Archivos fuente LaTeX para generar gráficos (PGF-TikZ, PGFplots, circuitikz, etc.), incluyendo "wrapper" en `.tex` para usarse con `\usepackage{standalone}`.

	* [texfig/data](./texfig/data) Archivos de datos tipo `.csv` usados por PGFplots.


## Cómo usar LaTeX localmente

1. Instalar una distribución de LaTeX, como por ejemplo [MikTeX](https://miktex.org/).
1. Instalar un editor de texto LaTeX, como por ejemplo [TeXStudio](https://www.texstudio.org/), o [Visual Studio Code](https://code.visualstudio.com/) junto con el [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) para Visual Studio Code.
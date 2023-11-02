<!-- LTeX: language=es -->

# Plantilla de presentación en LaTeX-beamer

Código fuente en LaTeX (beamer) para presentaciones, como plantilla.

## Autor
* Dr.-Ing. Alan Wilson (<alan.wilson@usm.cl>)


## Contenido de las carpetas y archivos
* [conf](./conf) Archivos de configuración del documento LaTeX (paquetes, macros, configuración de estilos, etc.).
	* [conf/CONF_usepackage_beamer.tex](./conf/CONF_usepackage_beamer.tex): Archivo con los paquetes LaTeX.
	* [conf/CONF_beamer_elo_utfsm.tex](./conf/CONF_beamer_elo_utfsm.tex): Archivo de estilo del dpto. de electrónica UTFSM.
	* [conf/CONF_beamer_ac3e.tex](./conf/CONF_beamer_ac3e.tex): Archivo de estilo del AC3E.

* [img](./img) Imágenes pre-generadas (.pdf, .jpg, etc.) para insertar en el documento.

* [frame](./frame) Código fuente con el contenido de las diapositivas (frames).

* [glos](./glos) Definiciones de glosario utilizando `\usepackage{glossaries}`
* [bib](./bib) Archivos de bibliografía para LaTeX/BibTeX.

* [texfig](./texfig) Archivos fuente LaTeX para generar gráficos (PGF-TikZ, PGFplots, circuitikz, etc.), incluyendo "wrapper" en `.tex` para usarse con `\usepackage{standalone}`.

	* [texfig/data](./texfig/data) Archivos de datos tipo `.csv` usados por PGFplots.

* [textab](./textab) Archivos fuente LaTeX para generar tablas.

## Cómo usar LaTeX localmente

1. Instalar una distribución de LaTeX, como por ejemplo [MikTeX](https://miktex.org/).
1. Instalar un editor de texto LaTeX, como por ejemplo [TeXStudio](https://www.texstudio.org/), o [Visual Studio Code](https://code.visualstudio.com/) junto con el [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) para Visual Studio Code.
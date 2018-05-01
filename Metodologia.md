# Metodologia de la Investigacion
Un ejemplo de lo que se puede hacer con Bookdown.
# Bookdown
Introduccion Los libros usualmente suelen escribirse con LaTex o en archivos de Microsoft, pero desafortunadamente no son herramientas de uso integral, pues cuando se usa el primero, el resultado siempre estará en PDF y cuando se crea en el segundo, las funciones se quedan cortas. Al combinar R Markdown con Pandoc, se hace posible el desarrollo de documentos en varios formatos simultáneamente (HTML, EPUB y Word, etc), tan solo dependerá de la forma en que se exporten al ser guardados en el ordenador. Las interfaces son más dinámicas y pueden modificarse según algunos parámetros de programación.
# Paquetes necesarios para el uso de R Markdown
- R and R packages
    - El primer paso es comprobar que se tenga la versión actualizada de R para poder proceder a instalar los paquetes adicionales. Puede hacerse según se consideren necesarios o todos en la misma descarga. Para probar la versión de desarrollo de bookdown en GitHub se debe instalar devtools.
> "install.packages ("bookdown", dependencias = TRUE)"
- Pandoc
    - Cuando se compila un documento de Bookdown, no es necesario instalar knitr o rmarkdown pues son paquetes requeridos por la función que se descargan automáticamente. Sin embargo, cuando se trata de Pandoc, si es necesario activar la librería si no se está usando RStudio.

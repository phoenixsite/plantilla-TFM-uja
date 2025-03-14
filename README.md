# Plantilla TFG y TFM

## Introducción
Este repositorio contiene una plantilla para la elaboración de un TFG o TFM mediante LaTex siguiendo las directrices de la [Escuela Politécnica Superior de Jaén](https://eps.ujaen.es/sites/centro_epsj/files/uploads/documents/grados/TFG/criteriosYestilo_TFG.pdf).

## Opciones de la plantilla
La plantilla hace uso de la clase `scrbook` del paquete `KOMA-Script` que normalmente viene instalado por defecto en las distribuciones de TeX más usuales. Dicha plantilla tiene las siguientes características:
- Tamaño de impresión: a4.
- Tipografía: Arial e [Inconsolata](http://www.tug.dk/FontCatalogue/inconsolata/) (monospace). 

El fichero principal de la plantilla es `tft.tex`. Al inicio del mismo (entre las líneas 13-32) es necesario modificar los datos del TFT: título, autor, grado, facultad y tutores mediante los comandos `\miTitulo`, `\miNombre`, `\miGrado`, `\miFacultad`, `\miUniversidad`, `\miTutor` y `\miTutorDepar`.

En el fichero `tft.pdf` se puede encontrar más información sobre la estructura de la plantilla y ejemplos de su uso.

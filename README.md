# Webscraping Páginas.

## Para el código del WebscrapingNature.ipynb
El siguiente jupyter permite extrar el abstract de las publicaciones relacionadas a la frase o palabra buscada en la revista "Nature" y descargar un archivo de texto delimitado, que contiene:
 * El título de la publicación.
 * Página web.
 * Abstract si existe en formato html.
 * link para descargar el archivo.

Sólo es necesario cambiar la **frase** con la frase que se desea buscar.

El archivo se descarga con el nombre de la frase y separado por pipe.

## Para el código del WebscrapingImagenGoogle.ipynb
Este jupyter permite descargar las imágenes relacionadas con la frase o palabra buscada, la cual debe ser ingresada en **search_terms**, en tu cuenta de google drive.

Este código fue modificado a partir de https://github.com/Ladvien/deep_arcane, donde se le adiciona:
  * Guardar las imágenes en google drive.
  * Utilizar selenium en colab.
  * Guardar en un excel el nombre del archivo, url y la breve descripción (caption) de la imagen asociada.



*Sigue en desarrollo implementar otras páginas*


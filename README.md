# Clasificador de cáncer de esofágo

Se utiliza Perceptrón lineal para realizar una clasificación binaria de un subconjunto de imágenes provenientes del [Data Challenge by Mauna Kea](https://challengedata.ens.fr/login/?next=/participants/challenges/11).
Para este clasificador se utilizaron solamente las imágenes de tejido sano y las imágenes de tejido con displasia/cáncer. De manera que el conjuntode datos está formado por 1,469 imágenes de tejido sano _(clase 0)_ y 3,594 imágenes de displasia/cáncer _(clase 1)_.

Las imágenes originales fueron escaladas de 519x521 pixeles a 260x260 para reducir el tiempo y la memoria requeridos para el procesamiento. El conjunto de imágenes utilizadas están disponibles en el archivo comprimido [CarpetaImagenes.zip](https://drive.google.com/drive/u/1/folders/1MZEeVNbAfketqcfrEO-Rse__vynKKyRu), fuera de este repositorio.

Por su parte, el archivo ClasesImagenes.csv, que se ubica en la carpeta Datos de éste repositorio, contiene una tabla donde se identifica el nombre de cada imagen y la clase a la que pertenece.

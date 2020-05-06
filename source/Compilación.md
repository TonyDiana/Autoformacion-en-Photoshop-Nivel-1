# Proceso de compilación y montaje de la documentación

##Proceso de exportación dentro de eXeLearning

- Revisar que el versionado se ha realizado.
- Modificación de la versión y fecha de la misma en el archivo **README.md** de la raíz.
- Exportar a la carpeta `packages` en formato sitio web comprimido al archivo `Moodle.zip`.
- Exportar a la carpeta `packages` en formato sitio web carpeta auto-contenida.
    + Debe realizarse en la carpeta `docs/manual`.
    + Creará una subcarpeta de nombre `Autoformacion_en_Photoshop_Nivel_1`.
    + Trasladar el contenido de esa subcarpeta a la carpeta `docs/manual` y eliminar la subcarpeta sobrante.
- En la carpeta `packages` hay un archivo denominado `Autoformación Photoshop Nivel 1.rar`. Sustituir en su contenido la carpeta `manual` por la carpeta `docs/manual` (Debe de llamarse `manual` dentro del comprimido).
- Exportar a la carpeta `packages` en formato ePub al archivo `Autoformacion en Photoshop Nivel 1.epub`.
- Salir de eXeLearning.


##Mejorado del ePub

- Importar a Calibre y añadir la portada, archivo `source\imágenes\Portada.png`.
- Proceso de Modificar libro:
    + Realizar proceso automático de añadir portada.
    + Eliminar en archivo `cover.xhtml`.
    + Corregir el HTML de todos los archivos.
    + Herramienta mejorar la puntuación.
    + Comprimir las imágenes sin pérdidas, pero no comprimir los `jpg`.
    + Modificar el índice arrastrando los niveles segundos hacia abajo, fuera del índice, para que queden en nivel 1º.
    + **NO MODIFICAR LOS CSS DE FORMA AUTOMÁTICA NUNCA**.
    + Salir del editor.
- Metadatear según el gusto.
- Exportar de Calibre hacia la carpeta `packages`.
- Será necesario cambiar el nombre al ePub.


##Otras posibilidades adicionales

- Ubicar en el repositorio de GitHub.
- Comprimir en la carpeta original.

# GS2CSV

Este programa está pensado para facilitar la vida a los administradores de Moodle en los centros educativos. Lo más común es encontrarse con un formulario de Google, creando una Hoja de Cálculo con las respuestas en Google Drive.

Este programa automatiza la creación de un archivo CSV con el nombre, apellidos y correo electrónico de los alumnos para su posterior importación en Moodle.

Además, actualiza con el mismo color de texto en la marca temporal al último alumno o alumna para evitar duplicados a la hora de la importación en Moodle.

Requisitos

- Java 8
- Gradle

Cuando se ejecute por primera vez, la instrucciones a seguir son las siguientes:

1) Deberemos ir al siguiente enlace https://developers.google.com/sheets/api/quickstart/java?authuser=2 y seguir las instrucciones del paso 1.
2) Descargaremos el fichero "credentials.json"
3) Ejecutaremos la aplicación
4) Seleccionaremos el fichero "credentials.json" y rellenaremos los campos requeridos (SheetID y SpreadsheetID)
5) Pulsaremos el botón "Generar CSV"
6) Debemos iniciar sesión con la cuenta de Google donde se encuentra el formulario.
7) En la carpeta de descargas se generará un archivo llamado "import2CSV.csv".

En las siguientes ejecuciones:

Cuando lo ejecutemos por segunda vez, el programa ya no nos pedirá seleccionar el fichero "credentials.json", ni el SpreadsheetId, ni el sheetId. Simplemente, pulsamos el botón de "Generar CSV", creándose así el archivo "import2CSV.json" en la carpeta de descargas.

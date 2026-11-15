Libro interactivo: Don Quijote de la Mancha

Este proyecto es un minilibro educativo. Presenta a Miguel de Cervantes, los personajes principales de Don Quijote de la Mancha y el lenguaje que se usa en la obra. Al final hay una actividad de tres preguntas con un máximo de tres intentos.

 Cómo ejecutar el programa

1. Descargá y descomprimí `LibroInteractivoTarea.zip`.
2. En Apache NetBeans, elegí File → Open Project y abrí la carpeta que contiene el archivo `pom.xml`.
3. Hacé clic en Run Project para iniciar el programa.

 Clases principales

- `Libro` guarda y organiza las páginas del libro.
- `Pagina` es la clase base de `PaginaInformativa`, que contiene las lecturas, y `PaginaActividad`, que contiene las preguntas.
- `Evaluacion` cuenta los aciertos y guarda el historial de intentos.
- `VistaLibro`, `Vista_Actividad` y `Vista_Resultados` muestran la lectura, las preguntas y los resultados.
- `ControladorLibro` conecta los botones con la navegación y la evaluación.

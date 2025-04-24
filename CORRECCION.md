# CORRECCIÓN DE MALA PRÁCTICA

**1. ¿Qué mala práctica identificaste?**  
Detecté que el código incluía estilos CSS incrustados directamente en el archivo HTML y que tanto el HTML como el CSS contenían fragmentos de código innecesarios o redundantes.

**2. ¿Por qué es considerada una mala práctica?**  
Incorporar CSS directamente en el HTML va en contra del principio de separación de responsabilidades, dificultando el mantenimiento, la reutilización y la escalabilidad del proyecto. Además, la presencia de código superfluo puede generar confusión, reducir el rendimiento y entorpecer la comprensión por parte de otros desarrolladores.

**3. ¿Cómo la solucionaste?**  
Externalicé todos los estilos a un archivo CSS independiente. Apliqué la metodología BEM (Block Element Modifier) para mejorar la organización semántica de las clases CSS y definí variables globales utilizando `:root` para una mejor gestión de colores, sombras y transiciones. También realicé una limpieza del HTML, asegurándome de que solo se incluyeran elementos relevantes, eliminando etiquetas duplicadas, código redundante y estilos embebidos innecesarios. Finalmente, vinculé correctamente el archivo `index.css` desde el HTML.

**4. ¿Qué beneficios aporta tu solución?**  
Esta mejora optimiza la organización del proyecto, facilita la lectura y el mantenimiento del código, permite reutilizar estilos en otras páginas y reduce la posibilidad de errores. Además, al aplicar buenas prácticas como BEM y CSS modularizado, el código es más escalable, limpio y profesional, mejorando el rendimiento general y facilitando el trabajo colaborativo.

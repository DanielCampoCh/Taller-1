# Repsuestas Readme

1. ¿Qué es HTML y cuál es su función?
HTML (HyperText Markup Language) es el lenguaje de marcado estándar de la web. Su función es definir la estructura y el contenido de una página (títulos, párrafos, imágenes, enlaces) mediante etiquetas que el navegador interpreta y muestra.

2. ¿Qué es una etiqueta HTML y las más comunes?
Es el elemento que marca un contenido e indica cómo interpretarlo; normalmente va en pares de apertura y cierre (<p>...</p>). Comunes: <html>, <head>, <body>, <h1>–<h6>, <p>, <a>, <img>, <div>, <span>, <ul>, <li>, <table>.

3. ¿Qué es un atributo y los más comunes?
Es información adicional dentro de la etiqueta de apertura que modifica su comportamiento, con formato nombre="valor". Comunes: href, src, alt, id, class, style, title, width, height.

4. ¿Qué es CSS y cómo se usa?
CSS (Cascading Style Sheets) describe la presentación visual del HTML: colores, fuentes, tamaños, espaciado y distribución. Se puede aplicar en línea (atributo style), interno (<style> en el <head>) o externo (archivo .css vinculado con <link>); el externo es el recomendado.

5. ¿Qué es una propiedad en CSS y las más comunes?
Es la característica del elemento que se quiere modificar, escrita como propiedad: valor;. Comunes: color, background-color, font-size, font-family, text-align, margin, padding, width, border, display.

6. ¿Qué es un selector y qué tipos existen?
Es el patrón que indica a qué elementos se aplican los estilos. Tipos: de etiqueta (p), de clase (.nombre), de id (#nombre), universal (*), de atributo ([type="text"]), combinadores/descendientes (div p) y pseudo-clases/pseudo-elementos (:hover, ::before).

7. ¿Qué es JavaScript y cómo añade interactividad?
Es un lenguaje de programación que se ejecuta en el navegador y hace las páginas dinámicas. Responde a eventos (clics, teclado), modifica el HTML y el CSS en tiempo real (manipulación del DOM), valida formularios y consume datos.

8. ¿Tipos de datos primitivos en JavaScript?
string, number, boolean, undefined, null, bigint y symbol.

9. ¿Cómo funcionan if, else, switch y bucles?
if/else ejecutan un bloque según se cumpla o no una condición. switch compara una expresión contra varios case y ejecuta el que coincide (default para el resto). Los bucles (for, while, do...while) repiten un bloque mientras se cumpla una condición, útiles para recorrer listas o repetir tareas.

10. ¿Por qué usar nombres significativos?
Porque hacen el código legible y fácil de mantener: se entiende qué hace cada parte sin descifrarla, se reducen errores y se facilita el trabajo en equipo.

11. ¿Qué es una variable de entorno y por qué importa?
Es un valor guardado fuera del código (a nivel del sistema o entorno de ejecución) que la aplicación lee al ejecutarse: claves de API, URLs de bases de datos, configuraciones. Importan porque permiten configurar la app sin tocar el código, mantener datos sensibles fuera del repositorio y manejar distintos entornos (desarrollo, producción).

12. ¿Qué son las DevTools de Chrome y cómo se accede?
Son utilidades integradas para inspeccionar, depurar y analizar páginas web. Se accede con F12, con Ctrl+Shift+I (Cmd+Opt+I en Mac) o clic derecho → "Inspeccionar".

13. ¿Qué se puede hacer en el panel "Elements"?
Ver y editar en vivo el HTML (DOM) y el CSS: modificar texto, atributos y estilos de forma temporal para probar cambios, y revisar el box model y problemas de maquetación.

14. ¿Cómo se usa el panel "Console"?
Muestra mensajes, advertencias y errores de JavaScript, y permite ejecutar código JS directamente. Es útil para depurar, probar y mostrar salidas con console.log().

15. ¿Qué información da el panel "Network"?
Muestra todas las peticiones de la página (HTML, CSS, JS, imágenes, llamadas a APIs) con su estado, tamaño y tiempo de carga. Importa para analizar el rendimiento, detectar recursos lentos o fallidos y depurar la comunicación con el servidor.


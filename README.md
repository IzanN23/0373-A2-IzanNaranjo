# 0373-A2-IzanNaranjo
## Evaluación inicial

1. __¿Qué es una página web?__

Una página web es algo que ves en Internet, pero no estoy seguro de cómo explicarlo bien. Es como un documento que tiene información, imágenes y a veces videos, creo que se hace con algo llamado HTML, que es como una especie de código, cuando escribes una dirección web en el navegador accedes a esa página.

2. __¿Qué es un servidor web?__

Un servidor web es un ordenador que almacena páginas de Internet y las envía a otros dispositivos cuando se les solicita. 

3. __¿Qué son los lenguajes de marcas? ¿Cuántos conoces?.__

Los lenguajes de marcas son herramientas que usamos para organizar y dar formato a documentos, especialmente en la web.

| Nombre | Enlace a Documentación |
|--------------------------------| |------------------------------------|
| HTML | [Documentación HTML](https://developer.mozilla.org/es/docs/Web/HTML) |
|XML | [Documentación XML](https://www.w3.org/TR/xml/) |
| Markdown | [Documentación Markdown](https://www.markdownguide.org/) |
| LaTeX | [Documentación LaTeX](https://ondiz.github.io/cursoLatex/Contenido/01.Introduccion.html) |

4. __¿Qué es HTML ? ¿Sabes cómo se estructura?__

HTML (HyperText Markup Language) es el lenguaje utilizado para crear páginas web. Usa etiquetas para estructurar el contenido, para encabezados y para párrafos.

![Imagen Estructura HTML](https://github.com/IzanN23/0373-A2-IzanNaranjo?tab=readme-ov-file "Titulo opcional")

**_Figura 1: Estructura de código HTML_**

5. __¿Qué es CSS?__

CSS (Cascading Style Sheets) es un lenguaje utilizado para definir el estilo y la presentación de las páginas web. Mientras que HTML se encarga de la estructura del contenido, CSS controla aspectos como colores, fuentes, márgenes y disposición de los elementos.

6. __¿Sabes cómo funciona un navegador web? Describe brevemente el proceso que se sigue para visualizar una página web.__

    Sí, el funcionamiento de un navegador web es bastante interesante. Cuando quieres visualizar una página web, el proceso sigue varios pasos:
    1. __Escritura de la URL__: Escribes la dirección web (URL) en la barra de direcciones del navegador.
    2. **Resolución del nombre de dominio**: El navegador envía una solicitud a un servidor DNS para traducir el nombre de dominio a una dirección IP, que es la dirección real del servidor donde está alojada la página.
    3. **Solicitud HTTP**: Una vez que tiene la dirección IP, el navegador envía una solicitud HTTP al servidor web para obtener el contenido de la página.
    4. **Recepción de la respuesta**: El servidor procesa la solicitud y envía de vuelta el código HTML, junto con otros archivos necesarios, como CSS y JavaScript.
    5. **Renderizado**: El navegador recibe estos archivos y comienza a renderizar la página. Primero, interpreta el HTML para estructurar el contenido, luego aplica el CSS para estilizarlo y, finalmente, ejecuta cualquier JavaScript para añadir interactividad.
    6. **Visualización**: Una vez que todo está procesado, el navegador muestra la página en la pantalla, permitiéndote interactuar con ella.

![Esquema de peticiones HTML](https://github.com/IzanN23/0373-A2-IzanNaranjo?tab=readme-ov-file "Titulo opcional")

**_Figura 2: Esquema de peticiones HTML_**
# **Capítulo 7: Dibujo Asistido por Ordenador**

Hasta ahora hemos aprendido a crear planos precisos utilizando instrumentos de dibujo tradicionales. Sin embargo, hoy en día es muy común usar **programas de ordenador que permiten realizar y modificar planos** de forma mucho más fácil y rápida. Estos programas se conocen como **CAD** (Diseño Asistido por Ordenador).

Uno de los programas CAD que vamos a utilizar es **LibreCAD**, una aplicación gratuita disponible para Windows, Mac y Linux. Aunque existen muchos programas de diseño, la interfaz de LibreCAD es muy intuitiva y fácil de usar.

## **7.1. La Interfaz de LibreCAD: Nuestro Espacio de Trabajo**


Cuando abres LibreCAD, te encuentras con un espacio de trabajo organizado en varias zonas:

*   **Barra de menú:** En la parte superior, con las opciones típicas (Archivo, Editar, Ver...).
*   **Barra de herramientas:** Contiene los comandos más habituales (líneas, círculos, rectángulos, etc.).
*   **Cuadro de capas:** Es una ventana, normalmente a la derecha, donde gestionamos las capas de nuestro dibujo.
*   **Barra de estado:** ¡Esta es muy importante! Se encuentra en la parte inferior de la ventana y te va diciendo qué es lo que el programa espera que hagas a continuación (por ejemplo, "especificar primer punto"). Para que el resultado en CAD sea preciso, el diseñador debe ser muy riguroso, y leer esta barra es fundamental.

## **7.2. Conceptos Fundamentales: Entidades y Capas**

Antes de empezar a dibujar, debemos entender dos ideas clave:

*   **Entidad:** Es cada elemento que dibujamos y que el programa "conoce". Por ejemplo, un segmento de línea, un arco o un texto. Cada entidad tiene sus propias características: su forma, su posición, sus atributos (color, grosor) y la capa a la que pertenece.
*   **Capas:** Son como "hojas transparentes" virtuales que se apilan unas sobre otras. Cada capa contiene una parte del dibujo. Por ejemplo, es muy conveniente usar una capa para los **contornos** de la pieza, otra para los **ejes** y otra para las **cotas** (dimensiones). Al verlas todas juntas, forman el plano completo.

La gran ventaja de las capas es que puedes hacerlas invisibles, bloquearlas para no modificarlas por error o borrarlas sin afectar al resto del dibujo. Siempre hay una única capa activa, que es sobre la que estás trabajando en cada momento.

## **7.3. El Proceso para Dibujar en LibreCAD**

Como regla general, para construir cualquier elemento (entidad) en LibreCAD, seguiremos estos pasos:

1.  **Posicionarse sobre la capa de trabajo** donde queremos dibujar.
2.  **Definir los atributos** (color, grosor, tipo de trazo...).
3.  **Elegir la naturaleza** del elemento: recta, círculo, texto, etc.
4.  **Indicar las condiciones de conexión**: si empieza en un extremo, en un centro, en una intersección, etc.

***

Ahora que conocemos la interfaz y la importancia de las capas, si tuvieras que dibujar las tres vistas (alzado, planta y perfil) de una pieza y luego acotarlas...

¿Qué capas crearías primero y qué dibujarías en cada una para mantener tu trabajo lo más organizado posible?
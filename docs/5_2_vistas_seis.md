# Las seis vistas de un objeto

Aunque el **Alzado, la Planta y el Perfil (izquierdo o derecho)** son las tres vistas más importantes, un objeto tiene en realidad **seis caras** (piensa en un dado 🎲). Por tanto, podemos obtener hasta **seis vistas diferentes**, que se nombran de la siguiente manera:

``` mermaid
graph TD
  A[**VISTAS**]-->B[ALZADOS]
  B -- Vista de frente --> C[1. Alzado anterior]
  B -- Vista desde atrás --> D[2. Alzado posterior]
  A[VISTAS]-->E[PLANTAS]
  E -- Vista desde arriba--> F[3. Planta superior]
  E -- Vista desde abajo--> G[4. Planta inferior]
  A[VISTAS]-->H[PERFILES]
  H -- Vista desde la izquierda--> I[5. Perfil izquierdo]
  H -- Vista desde la derecha--> J[6. Perfil derecho]
```
  
Sin embargo, casi nunca es necesario dibujar las seis vistas. La razón es que, con las tres vistas principales (alzado, planta y perfil izquierdo), la mayoría de los objetos ya quedan perfectamente definidos y se entiende su forma y medidas sin ninguna duda.

![vistas](media/vistas5.jpg){ align=left width=100% }


## La colocación de las vistas 

![vistas](./media/pieza-102-sistema-europeo-3.webp){align=right width=30%}

Para que todos los dibujos técnicos se puedan interpretar de la misma forma, la posición de las vistas sigue una norma internacional (UNE 1032 en España). Es como si metiéramos el objeto en una caja de cristal y luego desplegáramos sus caras.

Debajo se pueden ver las vistas desde la representación isométrica a la representación ortogonal en el Sistema Europeo.

![vistas](media/vistas1.jpg)


La colocación es siempre la siguiente:

1.  **El Alzado (vista de frente) es la vista principal** y se toma como referencia. Se coloca en el centro del área de dibujo.
2.  **La Planta (vista desde arriba)** se dibuja siempre **debajo** del alzado.
3.  **El Perfil Izquierdo (lo que vemos desde la izquierda)** se dibuja a la **derecha** del alzado.

Aplicando esta misma lógica de "desplegar la caja", las otras tres vistas se colocarían así:

*   **La Planta Inferior (vista desde abajo)** se dibujaría **encima** del alzado.
*   **El Perfil Derecho (lo que vemos desde la derecha)** se dibujaría a la **izquierda** del alzado.
*   **La Vista Posterior (lo que vemos desde atrás)** se dibujaría a la derecha del perfil izquierdo.

Normalmente, con las tres vistas principales (alzado, planta y perfil izquierdo) es suficiente para definir un objeto.
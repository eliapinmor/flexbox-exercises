# FLEXBOX EXERCISES

## Contenido del proyecto
Consta de 3 partes: Flexbox, Grid y Animación. Se trata de usar el css para distribuir los elementos a nuestro gusto y que nos ayude a que la experiencia del usuario sea mejor.
### Flexbox
Aquí he usado `display: flex` para distribuir elementos, centrar divs de manera vertical y horizontal. Además de `flex-direction` para controlar la dirección, o `flex-wrap` para controlar que no se rompa visualmente la web dependiendo del número de elementos.

<img width="883" height="357" alt="image" src="https://github.com/user-attachments/assets/8de73cda-8a75-4fae-95cd-0b79b42efc60" />

### Grid
En esta parte he usado grid, ordenando de manera uniforme los elementos o desardenandolos a nuestro gusto
### Animación
En este apartado he usado distintos elementos de csspara hacer animaciones, como por ejemplo hovers, crear movimientos (desplazarse, rebotar, rotar, zoom...) con `@keyframe`:
```bash
@keyframes moverYCambiarColor {
            0% {
                transform: translateX(0);
                background-color: coral;
            }

            50% {
                transform: translateX(300px);
                background-color:
                    lightcoral;
            }

            100% {
                transform: translateX(0);
                background-color: coral;
            }
```
## ¿Cómo arrancar este proyecto?
Para desplegar este proyecto he usado el servidor local de Visual Studio Code, descargandome la extensión de Live Server. Por tanto, lo único necesario será clonarte este repositorio (`https://github.com/eliapinmor/flexbox-exercises`) y arrancar el servidor local. Una vez arrancado, podemos acceder a http://127.0.0.1:5500/ex1/parte-1.html para ver el primer ejercicio de la primera parte.
 



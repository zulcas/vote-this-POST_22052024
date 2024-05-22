# Votación de película

Hemos creado una aplicación Web que permite puntuar diversas series del 1 al 10. Esta puntuación se puede hacer des de diveross dispositivos: Web, aplicación móvil, e incluso des de el menú de navegación del Smart TV.

Por ello, hemos creado un _endpoint_ que recibe las votaciones de todos los dispositivos. Además, devuelve al cliente el total de votaciónes y la valoración media.

[Demo Completa](https://omiras.github.io/vote-this-POST/)

## Iteración 1

Completa el código para que, al hacer clic en Enviar Votación, aparezca tu puntuación en el apartado "Tu votación"

<img src="https://oscarm.tinytake.com/media/1630d11?filename=1716392974927_TinyTake22-05-2024-05-49-19_638519897739083121.png&sub_type=thumbnail_preview&type=attachment&width=1200&height=695" title="Powered by TinyTake Screen Capture"/><br><a href="https://www.tinytake.com">Powered by TinyTake Screen Capture</a>

## Iteración 2

Envia los datos de la puntuación mediante el método POST a **https://votes-api-sjv2.onrender.com/send-score**
Muestra por consola la respuesta de la API para verificar que todo ha ido bien

<img src="https://oscarm.tinytake.com/media/1630d13?filename=1716393034595_TinyTake22-05-2024-05-50-24_638519898339257603.png&sub_type=thumbnail_preview&type=attachment&width=1199&height=576" title="Powered by TinyTake Screen Capture"/><br><a href="https://www.tinytake.com">Powered by TinyTake Screen Capture</a>

## Iteración 3

Usa los datos que devuelve la API para rellenar los apartados "Valoración media:" y "Número total de votos recibidos"

## BONUS

Intenta _engañar_ a la API. Modificar el control de rango para poderle enviar un valor mayor de 10. ¿que sucede?

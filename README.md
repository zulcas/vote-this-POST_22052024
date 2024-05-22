# Votación de película

Hemos creado una aplicación Web que permite puntuar diversas series del 1 al 10. Esta puntuación se puede hacer des de diveross dispositivos: Web, aplicación móvil, e incluso des de el menú de navegación del Smart TV.

Por ello, hemos creado un _endpoint_ que recibe las votaciones de todos los dispositivos. Además, devuelve al cliente el total de votaciónes y la valoración media.

## Iteración 1

Completa el código para que, al hacer clic en Enviar Votación, aparezca tu puntuación en el apartado "Tu votación"

## Iteración 2

Envia los datos de la puntuación mediante el método POST a **https://votes-api-sjv2.onrender.com/send-score**
Muestra por consola la respuesta de la API para verificar que todo ha ido bien

## Iteración 3

Usa los datos que devuelve la API para rellenar los apartados "Valoración media:" y "Número total de votos recibidos"

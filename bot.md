# Bot con Pandorabots

## Alumnos
    * Lucas Segarra Fernández
    * Sergio Semedi Barranci

## Contendido

#### Bot molesto
* *Molesto* es un bot diseñado para hablar sobre futbol.  El bot entonces esta preparado para tener una conversación básico con un aficionado al futbol.  Para la construcción de este básico bot se han usado los siguientes conceptos:
    * Uso de variables, almacenamiento básico de información.
    * Preprocesado básico de entradas (Normalization).
        * Además del sustito básico de palabras también trabaja con contracciones (WANNA -> WANT TO)
        * Elimina puntiaciones innecesarias.
    * Usa categorias.
    * Uso de variables, almacenamiento básico de información.
    * Uso de Wildcards:
        Las más básicas como puede ser * para capturar cualquier cosa que pueda decir el usuario y poder reconocer patrones.

    * Recursión y Redución:
        Las plantillas pueden llamar a otras categorias de esta forma el bot mira en diferentes categorias dependiendo del jugador por el que le preguntes.
    * Sets:
        A modo de información ya guardada por la que responderá el bot.
        En nuestro caso tenemos por ejemplo una lista de players de futbol, el usuario podrá preguntar si alg es un equipo de futbol.
    * Maps:
        Para poder tener una memoria clave -> valor.
        Tenemos un mapa que nos emparejará nuestro sets de jugadores con equipos.


### Estadisticas:
![Stats](https://github.com/softportal/Pandorabot_example/blob/master/staistics.png?raw=true)
---
---
---



### Ejemplo Interacción:
![Conver00](https://github.com/softportal/Pandorabot_example/blob/master/merge.jpg?raw=true)






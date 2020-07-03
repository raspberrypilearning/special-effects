## Noche de tormenta

+ Elija un búfer vacío para crear el siguiente efecto especial.

+ Para empezar, añade la muestra `:ambi_swoosh`.
    
    ![captura de pantalla](images/effects-storm-sample.png)

+ Presione 'Run' para probar tu muestra y ver cómo suena.

+ Si reduces la velocidad de la muestra, escucharás que suena como una tormenta.
    
    ![captura de pantalla](images/effects-storm-rate.png)

+ También puedes añadir una muestra `:misc_crow`, que se reproduce al mismo tiempo.
    
    ![captura de pantalla](images/effects-storm-crow.png)

+ Pon la muestra `:misc_crow` en un loop, por lo que se reproduce 4 veces con 1 pulso `sleep` cada vez que se reproduce.
    
    ![captura de pantalla](images/effects-storm-crow-repeat.png)

+ En lugar de agregar un sonido sleep cada vez, puedes usar `rrand` a lo que le dará un número aleatorio entre los 2 valores en paréntesis.
    
    ![captura de pantalla](images/effects-storm-crow-rand.png)

+ La **amplitud** de un sonido es el tamaño de la onda de sonido. Cambiando la amplitud de una onda de sonido cambia su **volumen**.
    
    ![amplitud](images/effects-amplitude.png)
    
    Puedes usar `amp` para hacer que una muestra se reproduzca a un volumen diferente. Un número menor a 1 reproducirá una muestra más silenciosa.
    
    ![captura de pantalla](images/effects-storm-crow-amp.png)
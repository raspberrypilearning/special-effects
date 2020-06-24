## Suspenso

Comencemos creando un sonido para mostrar que el peligro se está acercando.

+ Para crear el primer efecto especial, debes agregar la muestra `: ambi_choir` a un búfer vacío.
    
    ![captura de pantalla](images/effects-suspense-sample.png)

+ Puedes cambiar el **rate** en la que se reproduce una muestra. Un `valor` de ` 1 ` es la velocidad normal de la muestra y el uso de ` rate` de menos de 1 hará la muestra más lenta.
    
    ![captura de pantalla](images/effects-suspense-rate-low.png)

+ Presione 'Run' para escuchar su muestra reproducida lentamente. ¿Cómo suena la muestra?

+ Un ` rate ` mayor a 1 acelera la muestra.
    
    ![captura de pantalla](images/effects-suspense-rate-high.png)

+ Vuelve a probar tu muestra. ¿Cómo suena ahora?

+ Puedes repetir la muestra varias veces poniéndola en un loop. También tendrás que añadir un `sleep` después de reproducir la muestra.
    
    ![captura de pantalla](images/effects-suspense-repeat.png)
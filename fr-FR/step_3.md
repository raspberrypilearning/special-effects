## Nuit orageuse

+ Choisis un tampon vide pour créer le prochain effet spécial.

+ Pour commencer, ajoute l'échantillon `:ambi_swoosh`.
    
    ![capture d'écran](images/effects-storm-sample.png)

+ Appuie sur « Run » pour tester ton échantillon et voir comment il sonne.

+ Si tu ralentis l'échantillon, tu entendras que cela ressemble à un orage.
    
    ![capture d'écran](images/effects-storm-rate.png)

+ Tu peux également ajouter un échantillon `:misc_crow` qui est joué en même temps.
    
    ![capture d'écran](images/effects-storm-crow.png)

+ Mets l'échantillon `:misc_crow` dans une boucle, de sorte qu'il soit joué 4 fois avec un battement `sleep` à chaque fois qu'il est joué.
    
    ![capture d'écran](images/effects-storm-crow-repeat.png)

+ Au lieu d'un sleep de 1 battement à chaque fois, tu peux utiliser `rrand` qui te donnera un nombre aléatoire entre les 2 valeurs entre parenthèses.
    
    ![capture d'écran](images/effects-storm-crow-rand.png)

+ L' **amplitude** d'un son est la taille de l'onde sonore. Changer l'amplitude d'une onde sonore change son **volume**.
    
    ![amplitude](images/effects-amplitude.png)
    
    Tu peux utiliser `amp` pour faire un échantillon de lecture à un volume différent. Un nombre inférieur à 1 jouera un échantillon plus silencieux.
    
    ![capture d'écran](images/effects-storm-crow-amp.png)
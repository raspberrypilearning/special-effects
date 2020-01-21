## Stürmische Nacht

+ Wähle einen leeren Puffer, um den nächsten Spezialeffekt zu erstellen.

+ Füge zuerst das `:ambi_swoosh` Sample hinzu.
    
    ![screenshot](images/effects-storm-sample.png)

+ Klicke auf "Run", um dein Sample zu testen und zu sehen, wie es klingt.

+ Wenn Du das Sample langsamer machest, hörst Du, dass es wie ein Sturm klingt.
    
    ![screenshot](images/effects-storm-rate.png)

+ Du kannst auch ein `:misc_crow` (crow ist Englisch für Krähe) Sample hinzufügen, das gleichzeitig abgespielt wird.
    
    ![screenshot](images/effects-storm-crow.png)

+ Setze das `:misc_crow` Sample in eine Schleife, so dass es 4-mal, mit jeweils 1 Beat `sleep` dazwischen, abgespielt wird.
    
    ![screenshot](images/effects-storm-crow-repeat.png)

+ Anstatt für jeweils 1 Beat zu schlafen, kannst Du `rrand` verwenden, um eine Zufallszahl zwischen den beiden Werten in Klammern zu erhalten.
    
    ![Screenshot](images/effects-storm-crow-rand.png)

+ Die **Amplitude** eines Klangs ist die Größe der Schallwelle. Ändern der Amplitude einer Schallwelle ändert ihre **Lautstärke**.
    
    ![Amplitude](images/effects-amplitude.png)
    
    Du kannst `amp` verwenden, um ein Sample mit einer anderen Lautstärke abzuspielen. Bei einer Zahl unter 1 wird ein Sample leiser abgespielt.
    
    ![Screenshot](images/effects-storm-crow-amp.png)
# Kvalite

**En uppgift i att kvalitessäkra en webbplats.**

Du har fått i uppgift att validera och kontrollera en kollegas webbplats. Hen önskar
att du rättar till fel så att sidan validerar korrekt och fungerar korrekt.
I nuläget så fungerar inte bilderna och sidans formattering är konstig.
Det finns även ett antal användbarhets-problem att rätta till.

## Repository

Din kollega önskar att du commitar varje enskilt issue i ditt arbete med GitHub repot.
Detta så att det är väldigt tydligt vad du har ändrat i dokumentet. 

### Dokumentation

Din kollega vill även att du skriver en lista över vad du rättar 
till så att hen kan lära sig från dig.
Skapa validering.md och skriv i en punktlista.

## Teckenkodning

* Vad har ditt dokument för teckenkodning?
* Vad är dokumentet sparat med för teckenkodning?

Båda ska vara UTF-8.

## Sökvägar

Alla sökvägar måste vara relativa till dokumentets position.
En sökväg med C:\ är absolut och fungerar enbart på din dator.

## Validera HTML

https://validator.nu/

Arbeta med felen, ofta är fel följdfel, så börja uppifrån och arbeta dig neråt.

* Kontrollera att taggar är stängda, att de finns där de ska finnas.
* Kontrollera att attribut-värden är korrekt skrivna med "".
* Saknas attribut.
* Används felaktiga attribut.

## Validera CSS

https://jigsaw.w3.org/css-validator/validator

* Är reglerna korrekt skriva.
* Är attribut korrekta.
* Används reglerna i HTML koden.

## Bilder

Media och att anpassa storlek.
En Bakgrundsbild ska på sin höjd vara 1mb stor, gärna mindre.
Undersök filformat och bildstorlek och anpassa.

## Användbarhet

Använd Wave.
https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh
https://wave.webaim.org/extension/

* Kontrollera sidstruktur.
* Kontrollera kontraster.


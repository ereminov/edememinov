# Template voor Java uitwerkingen in IVH5 #

Deze repository bevat een mogelijke structuur voor het maken van je uitwerkingen van het Java prakticum. 

## Structuur ##

1. Er is een 'rootdirectory' die jouw naam heeft.
2. In de rootdirectory staat voor de uitwerkingen van iedere week een aparte map genaamd 'week 1' tot 'week n'.
3. Er is een `.gitignore` en een `README.md` bestand. Het `.gitignore` bestand bevat alle bestandsnamen die niet in GIT opgenomen moeten worden. Het `README.md` bestand bevat de tekst die je nu leest. Beide zijn zgn. platte-tekst bestanden.
4. Iedere week bevat een map `src\main\java`. Hierin zet je je Java source code - de uitwerkingen van je prakticum. Let op: gebruik een zinvolle packagestructuur.
5. Iedere week bevat een `gradle.build` bestand. De code compileert (en test, als je testcases hebt) door `gradle build` vanaf de commandline aan te roepen.
6. Je creëert Eclipse projectbestanden door `gradle eclipse` aan te roepen. 
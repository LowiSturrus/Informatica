# TK 1: Rondrijden

## Doel
Bouw een oefenrijbasis en maak nauwkeurige en gecontroleerde bewegingen.
 
## Oefenrijbasis
De oefenrijbasis is een basisuitvoering van een Spike-robot (zie {numref}`Fig {number} <Afbeelding_11_Oefenrijbasis>`), waarmee je de komende lessen alle belangrijke bewegingen/activiteiten kunt uitvoeren.

```{figure} Figures/Afbeelding_11_Oefenrijbasis.png
---
width: 40%
name: Afbeelding_11_Oefenrijbasis
---
Oefenrijbasis
``` 

De oefenrijbasis zal in de komende oefeningen worden uitgebreid met sensoren. Open het bestand ‘Trainingskamp 1 - Driving-base Rondrijden.pdf’ in het hoofdstuk "Bouwinstructies" en volg de instructies voor het bouwen van de oefenrijbasis.

## Programmeerinstructies
Open een nieuw project met woordblokken (zie {numref}`Fig {number} <Afbeelding_12_Nieuw_project>`).

```{figure} Figures/Afbeelding_12_Nieuw_project.png
---
width: 30%
name: Afbeelding_12_Nieuw_project
---
Nieuw project
``` 

Neem de volgende programmeerstack uit {numref}`Fig {number} <Afbeelding_13_Rondrijden>` over en voer het programma uit.

```{figure} Figures/Afbeelding_13_Rondrijden.png
---
width: 40%
name: Afbeelding_13_Rondrijden
---
Programmeerstack 'Rondrijden'
``` 

```{exercise} Opdracht 3
Beschrijf wat er gebeurt als je het programma start.                                   
```
```{exercise} Opdracht 4
Beschrijf wat er gebeurt als je op de linker knop indrukt.
```
```{exercise} Opdracht 5
Beschrijf wat er gebeurt als je op de rechter knop indrukt.
```

In de programmeerstack van figuur 12 zijn de volgende commando’s opgenomen:

```{figure} Figures/Afbeelding_14_Commandos_bewegen.png
---
width: 50%
name: Afbeelding_14_Commandos_bewegen
---
Commando's uit programmeerstack
``` 

Je gaat onderzoeken wat het verschil is tussen deze commando’s. Open daarvoor een nieuw project en neem de volgende programmeerstack over.

```{figure} Figures/Afbeelding_15_Testen_bewegen.png
---
width: 40%
name: Afbeelding_15_Testen_bewegen
---
Programmeerstack voor testen commando's
``` 

In de programmeerstack is het linker commando van figuur 13 opgenomen met de waarde ‘rechts: 100’. Door hierop te klikken kan de waarde van deze **parameter** worden veranderd.

```{exercise} Opdracht 6
Kies minimaal drie verschillende waarden voor de parameter en beschrijf wat het effect van de verandering is.                                   
```

Vervang het laatste commando in de programmeerstack van {numref}`Fig {number} <Afbeelding_15_Testen_bewegen>` door het rechter commando van {numref}`Fig {number} <Afbeelding_14_Commandos_bewegen>` en voer het programma opnieuw uit.


```{exercise} Opdracht 7
Beschrijf wat het verschil is tussen de twee commando’s van figuur 13.
```

In het rechter commando van figuur 13 is de waarde van de parameter uitgedrukt in cm. Er kan ook gekozen worden voor andere eenheden: inches, rotaties, graden en seconden. 

```{exercise} Opdracht 8
Voer het programma meerdere keren uit met telkens een andere eenheid.
```

Bij het maken van een programma kun je kiezen voor een eenheid. Het is niet mogelijk om te zeggen welke eenheid het beste is. Dit is afhankelijk van de situatie en je eigen voorkeur.


```{exercise} Opdracht 9 Een vierkant rijden

Je hebt nu alle vaardigheden om de robot rechtdoor te laten rijden en bochten te laten maken. Maak nu een programma waarmee de robot een vierkant gaat rijden. Het vierkant bestaat uit vier zijden van elk 20 cm en vier hoeken van 90 graden. Laat het eindresultaat zien aan de docent.                                   
```
```{exercise} Opdracht 10 Hindernisbaan
Je docent heeft met gekleurde stenen een hindernisbaan gemaakt. Gebruik je programmeervaardigheden om het ‘veld’ over te steken zonder de stenen te raken. Laat het eindresultaat zien aan de docent.
```

**Wachtcommando**

In het programma zie je twee wacht-commando’s.

```{figure} Figures/Afbeelding_16_Wachtcommandos.png
---
width: 50%
name: Afbeelding_16_Wachtcommandos
---
16_Wachtcommando's
``` 

Het linker commando zal duidelijk zijn: het programma wacht 1 seconde voordat het volgende commando wordt uitgevoerd. Het rechter commando betekent dat het vorige commando uitgevoerd blijft worden totdat aan de voorwaarde die is opgenomen wordt voldaan. In dit geval betekent dit dat de vorige opdracht, dat was in de programmastack van {numref}`Fig {number} <Afbeelding_13_Rondrijden>` het commando om een bocht naar rechts te maken over 100 graden, door blijft gaan totdat de gyroscoophoek ‘yaw’ groter is dan 89 graden. We gaan later in deze handleiding uitgebreider in op het laatste commando.

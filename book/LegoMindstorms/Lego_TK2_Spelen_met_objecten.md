# Trainingskamp 2: Spelen met objecten

## Doel
Gebruik sensoren om de motoren te besturen en voor interactie met objecten op het wedstrijdveld.
 
## Uitgebreide oefenrijbasis
n het vorige hoofdstuk heb je de oefenrijbasis gemaakt. Je gaat deze uitbreiden met een afstandssensor en een beweegbare arm. (zie {numref}`Fig {number} <Afbeelding_11_Oefenrijbasis>`).

```{figure} Figures/Afbeelding_17_Oefenrijbasis_2.png
---
width: 40%
name: Afbeelding_17_Oefenrijbasis_2
---
Uitgebreide oefenrijbasis met afstandssensor en bewegeegbare arm
``` 

De bouwinstructies voor de uitbreiding staan in het hoofdstuk "Bouwinstructies". Open het bestand ‘Trainingskamp 2 - Driving-base Spelen met objectenen.pdf’ en volg de instructies voor het bouwen van de uitgebreide oefenrijbasis. 

## Programmeerinstructies
Open een nieuw project met woordblokken. Neem de programmeerstack uit {numref}`Fig {number} <Afbeelding_18_Spelen_met_objecten>` over en voer het programma uit.

```{figure} Figures/Afbeelding_18_Spelen_met_objecten.png
---
width: 40%
name: Afbeelding_18_Spelen_met_objecten
---
Programmeerstack 'Spelen met objecten'
``` 

```{exercise} Opdracht 11
Beschrijf wat er gebeurt als je het programma start.                                   
```
```{exercise} Opdracht 12
Beschrijf wat er gebeurt als je op de linker knop indrukt.
```
```{exercise} Opdracht 13
Beschrijf wat er gebeurt als je op de rechter knop indrukt.
```

In de programmeerstack van {numref}`Fig {number} <Afbeelding_18_Spelen_met_objecten>` is het volgende commando opgenomen, waarmee motor E gedurende 1 seconde naar rechts draait.:

```{figure} Figures/Afbeelding_19_Laten_lopen.png
---
width: 50%
name: Afbeelding_19_Laten_lopen
---
Commando uit programmeerstack
``` 

```{exercise} Opdracht 14
Pas het commando aan zodat motor E naar rechts draait over 75 graden en vervang het laatste deel van het programma door onderstaande programmeerstack.                                   
```

```{figure} Figures/Afbeelding_20_Aanpassing_spelen_met_objecten.png
---
width: 40%
name: Afbeelding_20_Aanpassing_spelen_met_objecten
---
Aanpassing programmeerstack 'Spelen met objecten'
``` 

Als je de bouwinstructies voor de uitbreiding van de oefenrijbasis tot het eind hebt uitgevoerd, heb je ook een kubus en een markering gebouwd. Plaats de kubus op circa 5,5 cm voor de markering, plaats de robot op circa 50 cm recht voor de markering en voer het programma uit.


```{exercise} Opdracht 15
Beschrijf wat er gebeurt.                                   
```

## Woordblokcategorieën Motoren en Bewegen
Het is misschien opgevallen dat er twee categorieën commando’s zijn waarmee de motoren en beweging kan worden gecontroleerd. Voor het bewegen van een robot zijn in het algemeen twee motoren nodig. Bij het rechtdoor rijden draaien beide motoren even snel. Als er een verschil is in de snelheid waarmee de twee motoren, gaat de robot een bocht maken. Om de beweging goed te kunnen controleren is het belangrijk dat de motoren goed op elkaar staan afgesteld. Dat is het eenvoudigst te doen met behulp van de roze commando’s. Een bocht maken kan ook met behulp van de blauwe commando’s, maar dan moeten de twee motoren afzonderlijk op de goede snelheden worden ingesteld en dat kost meer bewerkingen en is dus niet handig. De blauwe commando’s worden daarom voor andere toepassingen gebruikt, namelijk toepassingen waarbij slechts één motor nodig is.  Het optillen van een voorwerp is hiervan een voorbeeld.


## Pseudocode
In hoofdstuk 1 heb je geleerd wat pseudocode is. In pseudocode beschrijf je in gewone taal de stappen in je programmeerstack die nodig zijn om de robot bepaalde handelingen te laten uitvoeren. In {numref}`Fig {number} <Afbeelding_21_Pseudocode>` is een voorbeeld gegeven.

```{figure} Figures/Afbeelding_21_Pseudocode.png
---
width: 40%
name: Afbeelding_21_Pseudocode
---
Een voorbeeld van pseudecode
``` 

```{exercise} Opdracht 16: Oefenen met pseudocode
Creëer een programmeerstack naar aanleiding van onderstaande pseudocode.
* Een hart laten oplichten;
* Als ik de kleur paars zie:
  - Een glimlach laten oplichten;
  - Motor A 30 graden laten draaien;
  - Motor A -60 graden laten draaien;
  - Motor A 60 graden laten draaien;
  - Motor A -30 graden laten draaien;
  - Een geluid afspelen;
  - Een hart laten oplichten
Controleer met je robot of je programma goed werkt. Laat het resultaat aan de docent zien.  
```

```{exercise} Opdracht 17: Estafette 
Je gaat nu een estafetteprogramma creëren. Hierbij gelden de volgende regels:
1.	Stel een afstand van 30 cm vast.
2.	Breek de kubus af in vier estafettestokjes met verschillende kleuren.
3.	Programmeer jouw oefenrijbasis zo dat deze vanaf de markering alle gekleurde stokjes om de beurt gaat ophalen.
4.	Haal elk stokje uit de oefenrijbasis zodra deze is afgeleverd.
```
```{exercise} Opdracht 17a
Schrijf de pseudocode voor het estafetteprogramma en laat dit aan de docent zien.
```
```{exercise} Opdracht 17b
Vertaal de pseudocode in een estafetteprogramma, voer dit uit en laat het resultaat zien aan de docent.
```
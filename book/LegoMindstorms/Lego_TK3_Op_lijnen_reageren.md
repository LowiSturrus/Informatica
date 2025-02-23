# TK 3: Op lijnen reageren

## Doel
Schrijf programma’s waarin de kleursensor wordt gebruikt om de rijbasis zelfstandig te maken.
 
## Uitgebreide oefenrijbasis
In het hoofdstuk 3 heb je de oefenrijbasis gemaakt. Je gaat deze uitbreiden met een lichtsensor.(zie {numref}`Fig {number} <Afbeelding_51_Oefenrijbasis_3>`).

```{figure} Figures/Afbeelding_51_Oefenrijbasis_3.png
---
width: 40%
name: Afbeelding_51_Oefenrijbasis_3
---
Met lichtsensor uitgebreide oefenrijbasis
``` 

De bouwinstructies voor de uitbreiding staan in het hoofdstuk "Bouwinstructies". Open het bestand ‘Trainingskamp 3 - Driving-base Op lijnen reageren.pdf’ en volg de instructies voor het bouwen van de uitgebreiding. 

## Programmeerinstructies
Open een nieuw project met woordblokken. Neem de programmeerstack van {numref}`Fig {number} <Afbeelding_52_Stoppen_bij_een_lijn>` over en voer het programma uit.

```{figure} Figures/Afbeelding_52_Stoppen_bij_een_lijn.png
---
width: 40%
name: Afbeelding_52_Stoppen_bij_een_lijn
---
Programmeerstack 'Stoppen bij een lijn'
``` 

```{exercise} 
Beschrijf wat er gebeurt als je het programma start.                                   
```

Het verplaatsen van een robot van een locatie naar een andere locatie is heel belangrijk. De nauwkeurigheid van de beweging blijkt deels afhankelijk van de het programma, maar er zijn ook toevallige invloeden. De toevalligheden moeten zoveel als mogelijk worden voorkomen. Hiervoor bestaan verschillende methoden, zoals het volgen van een lijn of het rijden met behulp van afstandsmeting. De eerste methode kan gebruikt worden als er lijnen op de ondergrond zijn getekend. Dat wordt in de volgende opdrachten uitgelegd. Voor de tweede methode zijn geen hulplijnen nodig, maar dit wordt in een later hoofdstuk behandeld.


```{exercise} 
Overleg in een groepje van vier leerlingen over de pseudocode voor het volgen van een lijn. Schrijf het resultaat op en laat dit aan de docent zien.                                   
```

## Uitbreidingen woordblokken
```{figure} Figures/Afbeelding_53_Icoontje.png
---
width: 25%
name: Afbeelding_53_Icoontje
figclass: margin
---
Icoontje opstarten extra programmeerblokken
```
In de linker kolom van de Lego Spike-app staan de programmeerblokken (commando’s) onderverdeeld in groepen. Bij het openen van een nieuw project worden hier de basisblokken vermeld. Hier kunnen uitbreidingen aan worden toegevoegd. Klik hiervoor linksonder in het scherm op het icoontje.

```{figure} Figures/Afbeelding_54_Extra_programmeerblokken.png
---
width: 75%
name: Afbeelding_54_Extra_programmeerblokken
---
Scherm met uitbreiding programmeerblokken
``` 

Vink alle onderdelen aan en druk op het kruisje. Je hebt nu extra woordblokken tot je beschikking. Kijk bijvoorbeeld in de categorie ‘Meer beweging’. Daar tref je het volgende commando:

```{figure} Figures/Afbeelding_55_Percentage_vermogen.png
---
width: 40%
name: Afbeelding_55_Percentage_vermogen
---
Commando ‘bewegen starten op %’
``` 


Je gaat onderzoeken wat dit commando doet. Open een nieuw project met woordblokken. Neem de volgende programmeerstack over en voer het programma uit.

```{figure} Figures/Afbeelding_56_Bewegen_percentage_vermogen.png
---
width: 40%
name: Afbeelding_56_Bewegen_percentage_vermogen
---
Programmeerstack ‘beweging starten op % vermogen’
``` 

In het derde commando staan twee waarden.

```{exercise} 
Voer het programma drie keer uit met achtereenvolgens de volgende waarden voor het vermogen:
1. 50 en 50;
2.  0 en 50;
3. 50 en 0.

Beschrijf het verschil dat ontstaat bij het uit voeren van het programma met de verschillende waarden voor het vermogen.  
```

Het commando uit {numref}`Fig {number} <Afbeelding_55_Percentage_vermogen>` wordt gebruikt in het programma voor het volgen van een lijn.

## Vervolg programmeerinstructies
Je docent heeft met een plaat met een getrokken zwarte lijn gemaakt. De robot gaat naar deze lijn rijden en vervolgens de lijn volgen.

```{exercise} 
Voeg de volgende programmeerstack aan het programma ‘volgen van een lijn’ en voer het programma uit. Laat het resultaat aan de docent zien.
```

```{figure} Figures/Afbeelding_57_Volgen_lijn.png
---
width: 40%
name: Afbeelding_57_Volgen_lijn
---
Programmeerstack 'volgen van een lijn'
```

Met het programma van {numref}`Fig {number} <Afbeelding_57_Volgen_lijn>` kun je de robot een lijn op de ondergrond laten volgen. De bewegingen zijn echter nogal schokkering; de robot beweegt steeds van links naar rechts en weer terug. Helemaal te voorkomen is dit niet, maar het is wel mogelijk om de bewegingen minder schokkerig te maken. Dit kan op twee manieren worden bereikt:
* Door het aanpassen van het ontwerp van de robot;
* Door het aanpassen van het programma.

```{exercise} Opdracht 22
Maak in hetzelfde groepje als bij opdracht 20 een aanpassing van het ontwerp van de robot, waardoor deze minder schokkerig gaat bewegen. Doorloop hierbij de volgende stappen:
* Ieder groepslid bedenkt een eigen oplossing (5 minuten);
* Ieder groepslid legt zijn oplossing uit aan de andere leden van de groep;
* Bespreek vervolgens de bedachte oplossingen;
* Kies de beste oplossing;
* Pas de gekozen oplossing toe;
* Controleer of de robot minder schokkerig beweegt.
* Laat het resultaat aan de docent zien.
``` 

In de vorige opdracht heb je de werking van de robot verbeterd door het aanpassen van het ontwerp. Je kunt een verbetering ook bereiken door het aanpassen van het programma door gebruik te maken van de volgende **operator**:

```{figure} Figures/Afbeelding_58_Operator_reflectie.png
---
width: 30%
name: Afbeelding_58_Operator_reflectie
---
Woordblok voor operator ‘reflectie’
```

```{exercise} Opdracht 23
Vraag de docent om de bovenstaande operator uit te leggen en gebruik deze operator om het programma van {numref}`Fig {number} <Afbeelding_67_Volgen_lijn>` aan te passen om de robot efficiënter te laten bewegen. Laat het resultaat aan de docent zien.
``` 
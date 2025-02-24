# TK 5: In een rechte lijn rijden

## Doel
Gebruik van een operator in een programmeerstack.
 
## Gyroscoop
In hoofdstuk 5 heb je geleerd hoe je een robot een lijn kan laten volgen. Dit is handig als je de robot nauwkeurig van de ene naar een andere locatie wilt verplaatsen. Helaas zijn niet altijd lijnen in de ondergrond beschikbaar. Ook dan kun je nauwkeurig verplaatsingen uitvoeren. Daarbij maak je gebruik van de gyroscoop voor de juiste richting en een afstandsmeter voor de juiste afstand. Dit hoofdstuk gaat over het rijden in de juiste richting, terwijl de afstand in het volgende hoofdstuk aan de orde komt.

Zoals in hoofdstuk 3 is vermeld kent de gyroscoop kent drie verschillende opties: pitch, roll en yaw. Je gaat de volgende opdrachten alleen gebruik maken van de optie yaw. Dit is voor de meeste toepassingen de belangrijkste optie. Deze optie meet hoeken waarover de steen is gedraaid ten opzichte van een beginsituatie. Hieronder wordt eerst ingegaan op de wiskunde van het meten van hoeken.

**Hoeken**
Hoeken worden in de wiskunde uitgedrukt in graden (°). Het is niet de bedoeling van deze handleiding om uitgebreid op dit onderwerp in te gaan. Hier wordt volstaan met een korte uitleg met behulp van {numref}`Fig {number} <Afbeelding_71_Yaw_hoeken>`:

* De uitgangspositie van de robot in de {numref}`Fig {number} <Afbeelding_71_Yaw_hoeken>` linksboven wordt gelijkgesteld met een hoek van 0°;
* Als de robot een kwartslag draait in de richting van de wijzers van de klok, dan is die gedraaid over een hoek van 90° (zie {numref}`Fig {number} <Afbeelding_71_Yaw_hoeken>` rechtsboven). Dit wordt in de wiskunde een rechte hoek genoemd;
* Als de robot over een hoek van 180° is gedraaid, zoals in {numref}`Fig {number} <Afbeelding_71_Yaw_hoeken>` rechtsonder, staat die precies in de tegenovergestelde richting als in de uitgangspositie;
* Bij een draaiing over 270° ontstaat weer een rechte hoek. De robot staat weer in een rechte hoek ten opzichte van de uitgangspositie. De positie komt overeen met een draaiing over 90° tegen de wijzers van de klok in. Dit wordt daarom ook wel een draaiing over -90° genoemd. De situatie is weergegeven in {numref}`Fig {number} <Afbeelding_71_Yaw_hoeken>` linksonder;
* Als de robot één keer volledig om zijn as draait en dus weer in de uitgangspositie staat, dan heeft die een hele zogenaamde cirkelbeweging uitgevoerd. De robot is dan gedraaid over een hoek van 360° (zie {numref}`Fig {number} <Afbeelding_71_Yaw_hoeken>` rechtsboven).
* Tussen de vier genoemde standen zijn de hoeken gelijkmatig verdeeld. De hoeken op een kompas zijn op dezelfde manier verdeeld, waarbij 0° overeenkomt met de richting ‘Noord’, 90° met ‘Oost’, 180° is ‘Zuid’ en 270° is ‘West’ (zie {numref}`Fig {number} <Afbeelding_72_Kompasroos>`).

```{figure} Figures/Afbeelding_71_Yaw_hoeken.png
---
width: 75%
name: Afbeelding_71_Yaw_hoeken
---
Hoeken met de wijzers van de klok mee
``` 

```{figure} Figures/Afbeelding_72_Kompasroos.png
---
width: 30%
name: Afbeelding_72_Kompasroos
---
Kompasroos
``` 

De gyroscoop in de steen houdt geen rekening met de werkelijke richtingen van het kompas, maar gaat uit van een beginsituatie die gelijk wordt gesteld aan 0°. Vervolgens wordt continu de draaihoek ten opzichte van deze beginwaarde vastgesteld. Deze waarde kan zichtbaar gemaakt worden in het dashboard ({numref}`Fig {number} <Afbeelding_73_Dashboard_gyroscoop>`). Let op, dit werkt alleen als de steen verbonden is aan je pc of tablet.

```{figure} Figures/Afbeelding_73_Dashboard_gyroscoop.png
---
width: 60%
name: Afbeelding_73_Dashboard_gyroscoop
---
Dashboard met de waarden van de o.a. yaw-hoek
``` 

De yaw kan waarden hebben van 0° tot 180° of van 0° tot -180°. Dit is afhankelijk van de beweging van de steen: naar rechts of naar links, zoals weergegeven in {numref}`Fig {number} <Afbeelding_74_Waarden_yaw_hoek>`.

```{figure} Figures/Afbeelding_74_Waarden_yaw_hoek.png
---
width: 75%
name: Afbeelding_74_Waarden_yaw_hoek
---
De waarden van de yaw-hoek
``` 

Met behulp van de programmeerstack van {numref}`Fig {number} <Afbeelding_75_Meten_yaw_hoek>` kun je de hoek van de robot meten. Open een nieuw project met woordblokken en neem de programmeerstack over. Als je het programma maakt verschijn er rechts het volgende deelscherm, waarin je de waarde van de yaw-hoek kunt aflezen.

```{figure} Figures/Afbeelding_75_Meten_yaw_hoek.png
---
width: 40%
name: Afbeelding_75_Meten_yaw_hoek
---
Programmeerstack ‘meten yaw-hoek’
``` 

```{exercise} 'Meten yaw-hoek'
Voer het programma uit. Controleer of de hoeken 90°, 180°, 270° en 360° goed worden weergegeven. Wat valt je op?                                   
```
## Programmeerinstructies
Nu je weet hoe je de gyroscoop werkt, kun je dit gebruiken om de robot een rechte lijn te laten rijden. De methode is hetzelfde als bij het volgen van een lijn:
* Als de gyroscoop een positieve hoek meet, met er naar links worden gestuurd;
* Als de gyroscoop een negatieve hoek meet, met er naar rechts worden gestuurd;

Open een nieuw project met woordblokken. Neem de volgende programmeerstack over en voer het programma uit.

```{figure} Figures/Afbeelding_76_Een_rechte_lijn.png
---
width: 80%
name: Afbeelding_76_Een_rechte_lijn
---
Programmeerstack ‘Een rechte lijn’
``` 

```{exercise} Pseudocode 'Een rechte lijn'
Schrijf de pseudecode die hoort bij het programma in {numref}`Fig {number} <Afbeelding_76_Een_rechte_lijn>`  en toon het resultaat aan de docent.                                   
```

In het programma komt het volgende woordblok voor: 

```{figure} Figures/Afbeelding_77_Timer.png
---
width: 20%
name: Afbeelding_77_Timer
---
De sensor 'Timer'
``` 

Dit is een voorbeeld van een zogenaamde ‘operator’. In dit geval maakt de operator gebruik van de sensor ‘timer’ die de tijd aangeeft nadat het programma is begonnen of de tijd die verlopen is nadat de timer gereset is. Het gebruik van deze operator in het herhaal-tot-blok van {numref}`Fig {number} <Afbeelding_76_Een_rechte_lijn>` betekent dat de commando’s in dit blok gedurende 5 s moeten worden herhaald.

De overige woordblokken zijn eerder al behandeld.

```{exercise} Programma 'Een rechte lijn'
Open een nieuw project met woordblokken. Neem de programmeerstack van {numref}`Fig {number} <Afbeelding_76_Een_rechte_lijn>` over en voer het programma uit.                                   
```

In {numref}`Fig {number} <Afbeelding_78_Variatie_een_rechte_lijn>` het dezelfde programma weergegeven, maar met een kleine variatie.

```{figure} Figures/Afbeelding_78_Variatie_een_rechte_lijn.png
---
width: 70%
name: Afbeelding_78_Variatie_een_rechte_lijn
---
Variatie op de programmeerstack ‘Een rechte lijn’ 
``` 

De volgende commando’s zijn toegevoegd of aangepast:


```{figure} Figures/Afbeelding_79_Correctie_yaw_hoek.png
---
width: 40%
name: Afbeelding_79_Correctie_yaw_hoek
---
De variabel 'Correctie'
``` 

```{figure} Figures/Afbeelding_710_M_Power_vermogen.png
---
width: 60%
name: Afbeelding_710_M_Power_vermogen
---
De variabelen 'M-Power' en 'Correctie' voor het rijden in een rechte lijn
``` 

De waarde van de variabele ‘Correctie’ is ingesteld op 0°.

```{exercise} 
Voer het programma drie keer uit met achtereenvolgens de volgende waarden voor de variabele Correctie:
1. 0
2. 45
3. 90

Beschrijf het verschil dat ontstaat bij het uit voeren van het programma met de verschillende waarden voor de variabele 'Correctie'.                          
```
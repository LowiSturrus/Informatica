# TK 4: Gebruik variabele

## Doel
Gebruik van een variabele in een programmeerstack.
 
## Wat is een variabele
In de wiskunde is een variabele een symbool of naam dat werkt als een tijdelijke aanduiding voor uitdrukkingen of grootheden die kunnen variëren of veranderen. Een variabele kan verschillende waarden aannemen. Een voorbeeld is een variabele die op de Lego-steen weergeeft welk cijfer een leerling heeft gehaald voor de laatste toets of een teller die bijhoudt hoeveel voldoendes een leerling heeft gehaald. 
Ook in het programma voor SPIKE Prime kan gebruik worden gemaakt van variabelen. Voor het gebruik van variabelen is een aparte categorie opgenomen.
 

## Maken nieuwe variabele
Open de programmeerstack van opdracht 21 ‘beweging starten op % vermogen’ ({numref}`Fig {number} <Afbeelding_66_Bewegen_percentage_vermogen>`). Je gaat dit programma aanpassen door voor het vermogen en variabele te gebruiken.  

```{exercise} Opdracht 24
Klik op de categorie ‘VARIABELEN’ en vervolgens op de knop ‘Maak een variabele’. Je krijgt nu het invulscherm in figuur 27 te zien.                                   
```

```{figure} Figures/Afbeelding_71_Nieuwe_variabele.png
---
width: 40%
name: Afbeelding_71_Nieuwe_variabele
---
Invulvenster 'Nieuwe variabele'
``` 

Geef de variabele de naam ‘Power’ en druk op ‘OK’. Je hebt nu een nieuwe variabele gemaakt. Deze kun je gebruiken door het commando.

```{figure} Figures/Afbeelding_72_Vermogen_zonder_variabele.png
---
width: 40%
name: Afbeelding_72_Vermogen_zonder_variabele
---
Commando voor vermogen met ingevulde waarden
``` 

te vervangen door

```{figure} Figures/Afbeelding_73_Vermogen_met_variabele.png
---
width: 40%
name: Afbeelding_73_Vermogen_met_variabele
---
Commando voor vermogen m.b.v. een variabele 'Power'
``` 

Vanaf nu kun je de variabele ‘Power’ gebruiken. Wel moet je deze variabel nog een waarde geven. Dat doe je met het volgende commando:

```{figure} Figures/Afbeelding_74_Variabele_power.png
---
width: 40%
name: Afbeelding_74_Variabele_power
---
Commando voor vermogen m.b.v. een variabele 'Power'
``` 

In de programmeerstack van figuur 28 is weergegeven hoe het programma ‘beweging starten op % vermogen’ er dan uit komt te zien.

```{figure} Figures/Afbeelding_75_Bewegen_met_variabele_power.png
---
width: 40%
name: Afbeelding_75_Bewegen_met_variabele_power
---
Programmeerstack ‘beweging starten op % vermogen’ met behulp van de variabele ‘Power’
``` 

```{exercise} Opdracht 25
Verander het programma ‘beweging starten op % vermogen’ en voer het uit.                                   
```

Aan de rechterkant van het Programmeerscherm is nu een Variabelenscherm te zien. Hierin staan alle variabelen die in een programma worden gebruikt met de laatste waarden.

```{figure} Figures/Afbeelding_76_Deelscherm_variabelen.png
---
width: 40%
name: Afbeelding_76_Deelscherm_variabelen
---
Deelscherm met de waarden van de variabelen
``` 

## Veranderen waarde van een variabelen
In hoofdstuk 4 heb je een programmeerstack gebruikt om de robot bij een lijn te laten stoppen. Met het programma wordt de robot gestopt bij de eerste lijn van de juiste kleur, die het tegenkomt. Maar stel nu dat je de robot moet laten stoppen bij de derde lijn van de juiste kleur. Dit kan door een nieuwe variabele te maken met de naam ‘Teller’. Deze variabele krijgt de beginwaarde 0. Elke keer als de robot een lijn van de juiste kleur tegenkomt, wordt Teller verandert met 1. Als Teller de waarde 3 heeft moet de robot stoppen.
De docent heeft en speelveld met meerdere lijnen. Gebruik dit speelveld.

```{exercise} Opdracht 26
Schrijf een programmeerstack die ervoor zorgt dat de robot stopt bij de derde groene lijn. Voer het programma uit en laat het resultaat zien aan de docent.  
```

Het commando uit {numref}`Fig {number} <Afbeelding_15_Percentage_vermogen>` wordt gebruikt in het programma voor het volgen van een lijn.

## Vervolg programmeerinstructies
Je docent heeft met een plaat met een getrokken zwarte lijn gemaakt. De robot gaat naar deze lijn rijden en vervolgens de lijn volgen.

```{exercise} Opdracht 21
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
width: 40%
name: Afbeelding_58_Operator_reflectie
---
Woordblok voor operator ‘reflectie’
```

```{exercise} Opdracht 23
Vraag de docent om de bovenstaande operator uit te leggen en gebruik deze operator om het programma van {numref}`Fig {number} <Afbeelding_57_Volgen_lijn>` aan te passen om de robot efficiënter te laten bewegen. Laat het resultaat aan de docent zien.
``` 
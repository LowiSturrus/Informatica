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
width: 30%
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
width: 30%
name: Afbeelding_76_Deelscherm_variabelen
---
Deelscherm met de waarden van de variabelen
``` 

## Veranderen waarde van een variabelen
In hoofdstuk 4 heb je een programmeerstack gebruikt om de robot bij een lijn te laten stoppen. Met het programma wordt de robot gestopt bij de eerste lijn van de juiste kleur, die het tegenkomt. Maar stel nu dat je de robot moet laten stoppen bij de derde lijn van de juiste kleur. Dit kan door een nieuwe variabele te maken met de naam ‘Teller’. Deze variabele krijgt de beginwaarde 0. Elke keer als de robot een lijn van de juiste kleur tegenkomt, wordt Teller verandert met 1. Als Teller de waarde 3 heeft moet de robot stoppen. (zie {numref}`Fig {number} <Afbeelding_66_Bewegen_percentage_vermogen>`)

```{figure} Figures/Afbeelding_77_Gebruik_teller.png
---
width: 30%
name: Afbeelding_77_Gebruik_teller
---
Commando's voor het instellen en veranderen van een variabele.
``` 

De docent heeft en speelveld met meerdere lijnen. Gebruik dit speelveld.

```{exercise} Opdracht 26
Schrijf een programmeerstack die ervoor zorgt dat de robot stopt bij de derde groene lijn. Voer het programma uit en laat het resultaat zien aan de docent.  
```
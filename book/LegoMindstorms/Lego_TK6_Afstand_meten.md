# TK 6: Afstand meten

## Doel
Gebruik van een programma om de afgelegde afstand te bepalen.
 
## Afstand meten
Met de geluidsensor kan de afstand tot een object worden gemeten. Dit kan worden gebruikt om de robot tijdig de laten stoppen, van richting te laten veranderen of een andere taak uit te laten voeren. Helaas is niet altijd een object aanwezig en dan kan de geluidsensor niet worden gebruikt. Bovendien kan met de geluidsensor niet worden bepaald hoeveel afstand door de robot is afgelegd. Met behulp van een variabele blijkt dit laatste toch mogelijk te zijn. 
Een standaard wiel dat precies één omwenteling/rotatie heeft gemaakt is gedraaid over 360° en heeft een afstand afgelegd van 17,5 cm. Voor de grote wielen is deze afstand 27,6 cm. Voor de rest van dit hoofdstuk wordt uitgegaan van standaard wielen. Als een wiel slechts een deel van de omwenteling het gedraaid, kan de afgelegde afstand berekend worden met draaihoek/360*17,5. Enkele voorbeelden maken dit duidelijk:

--Het wiel is gedraaid over 50° - Afgelegde afstand = 50/360*17,5 = 2,4 cm
Het wiel is gedraaid over 270° - Afgelegde afstand = 270/360*17,5 = 13,1 cm
Het wiel is gedraaid over 720° - Afgelegde afstand = 720/360*17,5 = 35 cm--

In Lego Spike kun je deze berekening laten uitvoeren door een variabele, bijvoorbeeld met de naam ‘Afstand’ te maken. Deze variabele gebruikt de relatieve positie van één van de wielen en een operator. Alles bij elkaar leidt dit tot het volgende commando:

```{figure} Figures/Afbeelding_81_Commando_afgelegde_afstand.png
---
width: 50%
name: Afbeelding_81_Commando_afgelegde_afstand
---
Voorbeeld van commando om afgelegde afstand te berekenen 
``` 

Om het programma goed te laten werken dienen een aantal beginwaarden te worden ingesteld. In {numref}`Fig {number} <Afbeelding_82_Programma_afgelegde_afstand>` de hele programmeerstack.

```{figure} Figures/Afbeelding_82_Programma_afgelegde_afstand.png
---
width: 70%
name: Afbeelding_82_Programma_afgelegde_afstand
---
Programmeerstack voor het meten van de afgelegde afstand  
``` 

```{exercise} Programma 'Afgelegde afstand'
Open een nieuw project met woordblokken. Neem de programmeerstack van {numref}`Fig {number} <Afbeelding_82_Programma_afgelegde_afstand>` over en voer het programma uit.                                    
```

```{exercise} 
Hoeveel afstand zal de robot afleggen voordat deze tot stilstand komt.                                    
```

Als het programma wordt uitgevoerd, wordt de positie van het wiel gemeten en gebruikt in de berekening. In het deelscherm van figuur 8.3 zijn de waarden van alle motoren en sensoren zichtbaar.

```{figure} Figures/Afbeelding_83_Waarden_van_motoren_en_sensoren.png
---
width: 70%
name: Afbeelding_83_Waarden_van_motoren_en_sensoren
---
Verbindingsknop om de waarden van motoren en sensoren zichtbaar te maken  
``` 

Je kunt hier de relatieve positie niet gelijk aflezen. De weergegeven waarde moet hier eerst op worden ingesteld. Druk hiervoor bovenin in het scherm op de verbindingsknop aangegeven door de rode pijl (zie figuur 8.3). Je komt dan in het volgende scherm. Stel het rechter wiel in op ‘RELATIEVE POSITIE’.

```{figure} Figures/Afbeelding_84_Dashboard_motoren_en_sensoren.png
---
width: 70%
name: Afbeelding_84_Dashboard_motoren_en_sensoren
---
Dashboard voor het instellen van de sensoren- en motor-waarden die getoond worden in het deelvenster van {numref}`Fig {number} <Afbeelding_83_Waarden_van_motoren_en_sensoren>` 
``` 

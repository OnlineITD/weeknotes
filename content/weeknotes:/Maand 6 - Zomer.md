---
title: "Maand 6: Zomer"
date: 2026-06-22

---

In januari begon ik vol nieuwsgierigheid aan de opdracht bij RR. Men wist dat we test-trajecten nodig hadden om te beproeven wat onze huidige staat van denken en werken zou kunnen doen in het veld.

Ik heb die handschoen opgepakt en ben gaan werken aan zgn. ‘validatie’. 
Dwz.: aansluiten bij of opzetten van verkenningen binnen de praktijk van bijv. een uitvoeringsexpert of wetgevingsjurist bij verschillende overheden. 
Het doel: Een stukje van het recht dat relevant is voor hun praktijk / beleid / wetgeving analyseren vanuit team RegelRecht. 
Hiermee zijn we begonnen met het bootstrappen van methoden.

Dat betekent in de praktijk: aan de slag gaan d.m.v. interdisciplinaire werksessies met een paar basisingrediënten (een taal om specificaties in te schrijven, een engine om die specificaties uit te voeren, een stip aan de horizon mbt. een centrale toekomstige ontwerpfilosofie, prille tooling en AI agents), maar ook een hoop ‘unknowns'. Bijvoorbeeld in wat voor trajecten kun je komen tot betrouwbare regelspecificaties? Wat voor mensen zijn daar bij nodig? Welke tooling is daarvoor essentieel en wat is juist ruis? Wie is daar dan verantwoordelijk voor?


![plaatje van iemand achter computer met wetten](/images/yamlcomputer.png)
# Testen
De bootstrap trajecten helpen erg om richting te geven aan die tooling die op hun beurt in toekomstige trajecten weer bedding kunnen krijgen in die steeds doorontwikkelende methode. Kortom: Gewoon beginnen om een potentiële feedbacklus tussen methoden, tooling en alles onder de motorkap op gang te brengen.

Wat levert dat dan op? eerste beelden van wat de praktijk goed kan gebruiken. Onderstaand een beeld van een aantal elementen waarvan ik nu denk dat het nuttige bouwblokken zijn om van wet naar regelspecificatie te komen.
### Fase 1: Bepalen van startpunt: waar bestaat het interessegebied uit?
Hunch: visuele tooling om verschillende soorten samenhang op abstract niveau (grondslagen, materiële samenhang) tussen relevante wetten in kaart te brengen helpt bij het creëren van een gezamenlijk begrip.

Bij binnenkomst in een nieuw traject moeten de betrokkenen elkaar leren begrijpen: welk recht is interessant? Voornamelijk voor mij is dit natuurlijk nieuw. Ik merk dat visuele overzichten om samenhang tussen die wetten te kunnen aanbrengen en overzicht te creeeren in een oogopslag helpt als startpunt. Nu gaat dat bijv. soms met online whiteboard tooling. Nog mooier zou zijn als dat in een later stadium in onze editor zou kunnen landen.
### Fase 2: Observeren van kernlogica van gegenereerde regelvoorstellen d.m.v. aggregaat-producten om stukken logica te verifiëren en te verbeteren
Op basis van het werkgebied worden voorstellen voor machine uitvoerbare logica gemaakt. Om te zien hoe die logica is opgebouwd is het fijn om niet alleen naar rauwe yamls te kijken.
Dat werd afgelopen tijd bijvoorbeeld geprobeerd met behulp van rapporten waar logica uit de yamls werd ‘platgeslagen’ tot iets wat lijkt op first order logica of simpele formules om de binding met de tekst uit de wettelijke bepaling inzichtelijk te maken en feedback van de juridische-of domeinexperts te verzamelen.
Deze feedback kon dan een volgende iteratie voeden. Ook konden incongruenties hier aan het licht komen. 

Het bleef lastig om in zijn geheel overzicht te krijgen over de logica. Ik denk dat hier echt nog een slag gemaakt kan worden. Dat kan alleen door dyanmisch meer ervaring op te doen. Toch denk ik dat iets van een 'view' op de yamls kan helpen.
### Fase 3: Gedrag van de regels bekijken d.m.v. tests
Die testsituaties kunnen worden vormgegeven op basis van kennis over beoogd gedrag van een regel of uit uitvoeringsbeleid. Uit leaf nodes waar bijv. besluiten vallen kan dan potentieel onverwacht gedrag van de logica naar boven komen. Van daaruit kan men backtracken.
#### Hunch voor komende tijd: Fase 4
Een fase 4 waarna dynamisch wordt gekeken dmv service pocs op basis van de regels kan helpen om tot een dieper begrip te komen over de werking van de regelspecificaties.
## Reflectie
De werkelijkheid is soms best complex: De complexiteit van het relevante recht en het leren over methoden is best een hoop, maar ook simpelweg ontzettend leuk en interessant om mee aan de slag te mogen.
Ik zie momenteel nog kinderziektes die in volgende trajecten ondervangen kunnen worden. Bijvoorbeeld door AI agents beter te kaderen met skills, door middel van strakkere toepassing van methoden en het volwassener worden van de editor-software waardoor meer werk async gedaan kan worden door betrokkenen. 
Ik geloof dus echt dat het doorleven van dit soort trajecten helpt om tot betere methoden en systemen te komen.
Ik ben hoopvol en nieuwsgierig: Ik zie niet in waarom dit in de toekomst niet kan doorontwikkelen tot iets volwassens om tot machine uitvoerbare regels te komen.

## Tot slot
Ik las de [oratie van Mariette Lokin](https://www.ou.nl/documents/40554/13061114/Oratie_Mariette_Lokin_2026_Digitaal_disciplineren_anno_2026.pdf) terug afgelopen week. 
Ik had gewild dat deze oratie als inwerkstuk bestond toen ik in januari met RegelRecht begon. 
Het geeft in een soort vogelvlucht een algemeen beeld van de stand van zaken rondom 'digitaal disciplineren'.
Ik was blij dat ik op het begrip ‘specificatiedossier’ stuitte wat afkomstig was uit een [Toetsingskader Digitalisering van de Raad van State](https://www.raadvanstate.nl/@125918/publicatie-digitalisering/) (een voortzetting van het [ongevraagde adviesstuk](https://www.raadvanstate.nl/adviezen/@112661/w04-18-0230/) uit 2018 geloof ik) over de effecten van digitalisering voor rechtsstatelijke verhoudingen.

Het scherpte mijn denken. Het specificatiedossier waarover wordt gesproken ontstaat uit deze trajecten en is er integraal onderdeel van. Kortom iets wat ik validatie noem heeft een best goed aansluitende terminologie (specificatiedossier, specificatieproces) Het is de git historie van de resultaten uit elke fase van zo’n RR traject. Daarmee draagt de methode dus verder dan alleen de sessies zelf.

Ik ben blij dat ik daarin al een begin heb mogen maken en ben nieuwsgierig naar hoe dat verder uit kan werken. De precieze methode zal vast nog flink doorontwikkelen omdat er steeds meer ervaringen worden opgedaan, maar dat er elementen worden ontdekt die broodnodig zijn is me duidelijk.

Ik hoop einde zomer weer een updateje te schrijven!






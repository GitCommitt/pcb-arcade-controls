# README: pcb-arcade-controls

# Planning: 
**Periode:** November 2026 t/m januari 2027

---

### Sprint 0
* **Periode:** 16 nov t/m 20 nov 2026
* **Taken:** 
  * Onderzoek / start

### Sprint 1
* **Periode:** 23 nov t/m 4 dec 2026
* **Taken:** 
  * Stroomschema ontwerpen

### Sprint 2
* **Periode:** 7 dec t/m 18 dec 2026
* **Taken:** 
  * Printplaat ontwerpen
  * Printplaten bestellen

### Kerstvakantie
* **Periode:** 21 dec 2026 t/m 1 jan 2027
* **Status:** Geen sprint

### Sprint 3
* **Periode:** 4 jan t/m 15 jan 2027
* **Taken:** 
  * Firmware & software
  * Handleidingen & solderen

### Sprint 4
* **Periode:** 18 jan t/m 22 jan 2027
* **Taken:** 
  * Polishen
  * CGI's
    
## Onderzoek

Bij het onderzoek zijn we begonnen met de PDF lezen en belangerijke dingen opslaan. We hebben aan het begin van dit process een [video](https://www.youtube.com/watch?v=8WXpGTIbxlQ) gekeken hoe we het software tool KiCad moeten gebruiken in combinatie met de STM32F072CBT6 Microprocessor.

## Kicad

In Kicad zijn we begonnen bij het maken van een nieuwe file met de template [library](https://github.com/GitCommitt/pcb-arcade-controls/tree/main/library/scottokeebs-main/Extras/ScottoModules/STM32F072CBT6) van de repo [Scottokeebs](https://github.com/joe-scotto/scottokeebs). Daarna hebben we voor het maken van een 3d model de [library](https://github.com/GitCommitt/pcb-arcade-controls/tree/main/library/scottokeebs-main/Extras/ScottoKicad/symbols) toegevoed aan onze preferences.

## Connectie type

We hebben voor de [JST-XH connectors](https://nl.rs-online.com/web/p/pcb-headers/8201554) gekozen als connectie type. We hebben deze keuze gemaakt aangezien deze type connector makkelijk is om te gebruiken en super gebruiksvriendelijk is. Ook was een reden dat we deze connectie type hebben gekozen dat deze connectors makkelijk op het bord passen en niet veel plek in beslag nemen op de printplaat. De andere connectie type die we als optie hadden waren de [Screw Terminals](https://www.amazon.nl/-/en/50pcs-Terminal-Connectors-Terminals-2-54mm/dp/B07BVF8MD1). Het voordeel bij deze connector was vooral dat hij universal is dus elke soort kabel kan gebruikt worden op deze connector. We hebben allene niet voor deze connector gekozen om de volgende redenen. De connectors nemen veel plek in beslag op de printplaat en  de connectors niet gebruiksvriendlijk aangezien je voor het veranderen van de kabel een schroevendraaier nodig heb. 

# Process

We zijn begonnen als een team met het bedenken van een strak plan om dit project zo goed en het soepelst mogelijk kan laten verlopen. We zijn eerst begonnen met de verdeling van de taken. In de PCB ontwerp periode zijn de volgende taken verdeelt. Fynn, Nathan en Kevin hebben de taken gekregen van het PCB ontwerp te creeren en dan ook gelijk in Kicad te verwerken. Daan en Bram hebben de taak gekregen om te kijken wat de beste opties zijn voor het gebruik van de pins. Hiermee word bedoeld van welke pins op de processor gebruikt worden voor data zodat het knoppen en joysticks goed gaan comminuceren met de processor. 

### Sprint 0 [↗️](https://github.com/GitCommitt/pcb-arcade-controls/tree/main/attachments/sprints/sprint-0)
We hebben als eerst met het gehele team gekeken naar hoe het programma Kicad in elkaar zit en hoe we dit kunnen gaan gebruiken om de PCB uiteindelijk te kunnen ontwerpen. Er is ook een vergadering plaatsgevonden met het team waarbij we alles wat we hebben bij elkaar hebben gelegd om op die manier te meten waar we in het process staan. Wij hebben hiervoor ook ene duidelijke [planning](https://github.com/GitCommitt/pcb-arcade-controls/blob/main/README.md#planning) gemaakt voor wanneer welke taak afgerond moet zijn zodat we goed op schema blijven liggen. 

Er is een design ontworpen hoe het schema er op dit moment uit ziet ([Bekijk](https://github.com/GitCommitt/pcb-arcade-controls/blob/main/attachments/sprints/sprint-0/schema.png)). Hier zijn de PCB ontwerpers bezig geweest met het bouwen van de basis, dus er is op het schema te zien dat de benodigde connectors, processor, bootloaderknop en usb c port zijn toegevoegd. Later in het process/andere spints zullen we waarschijnlijk gebruik maken van een matrix waardoor we nog meer connectors kunnen aansluiten en er daardoor meer controls zijn. 

Het schema is ook al verwerkt in een visuele printplaat ontwerp ([Bekijk](https://github.com/GitCommitt/pcb-arcade-controls/blob/main/attachments/sprints/sprint-0/pcb.png)). OP dit onterwerp is te zien dat we 24 inputconnectoren gebruiken die we later gaan vervangen voor nieuwe connectors. Dat zijn de [JST-XH connectors](https://nl.rs-online.com/web/p/pcb-headers/8201554). Ook is er op de printplaat al nagedacht over hoe de printplaat gemonteerd kan worden aan een spelkast of ander iets. Hiervoor zijn 4 montagegaten van 10 mm gemaakt in de printplaat en worden waarschijnlijk later in het process smaller gemaakt zodat ze perfect bevestigd kunnen worden met een schroefjes. De processor, bootloaderknop en usb-c aansluiting zijn op dit ontwerp mogelijk op andere plekken dan ze op het eindproduct zouden zitten.

We hebben een presentatie gemaakt die deze sprint samenvat in 5 dia's ([Bekijk](https://github.com/GitCommitt/pcb-arcade-controls/blob/main/attachments/sprints/sprint-0/Presentatie%20sprint0.pptx)). Dit hebben we gepresenteerd en hebben we ook [feedback](https://github.com/GitCommitt/pcb-arcade-controls/blob/main/attachments/sprints/sprint-0/Resultaatfeedback%20presentative.txt) op gekregen en verwerkt.

### Sprint 1
...

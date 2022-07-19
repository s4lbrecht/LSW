

# Konzept --  Leipzig Smart City Layer Model
## Ziel
Erstellung einer mehrschichtigen Grafik, die alle verschiedenen Anlagen, Geräte und Business Cases des Virtuellen Kraftwerks bzw. des Digital Twins Leipzig darstellt.

## Grundskizze

![enter image description here](https://i.imgur.com/0EBfutt.png)

## Inhalt: Schichten & Komponenten

### 1. Menschen & Geschäftsmodelle
- "Green Happy World"
- Menschen die interagieren, Familien
- Bäume
- Flüsse
- Gebäude
- Straßenkarte

### 2. Infrastruktur Anlagen / Geräte 
- Stromnetz
 - PV-Anlagen
 - BHKWs
 - Smart Plugs
 - Smartphones
 - E-Autos
 - E-Busse
 - Smart Meter
 - L-Box
 - MUC
 - LoRaWAN Gateways
 - Batteriespeicher
 
### 3. Dashboards Reporting
 - Deskriptive Statistik
 - Barcharts
 - Spidercharts
 - Piecharts
 - Heatmaps

### 4. Analytics/AI

- Darstellung als Neuronales Netzwerk
- Jedes Neuron stellt ein Teilelement dar
- Pytoch, mlflow, fastAI, Keras, etc.

### 5. Digitale Plattform

- Dezentrale Plattform aus Honigwaben
- Jede Wabe stellt ein Teilelement dar
- z.B. Docker, Kubernetes, Kafka, InfluxDB, etc.




![Diese Skizze stellt die Inhaltskomponenten dar, ist aber kein Vorbild fürs Design.](https://i.imgur.com/Okfmprj.png)
*Diese Skizze stellt die einzelnen Komponenten dar, ist aber kein Vorbild fürs Design. Auch die Reihenfolge der Schichten ist hier anders.*

## Beispielgrafiken für Schichtmodelle

### Beispiel 1:

![enter image description here](https://i.imgur.com/OV7dD0t.jpeg)
Das ist nur ein grafisches Beispiel. Hier sind keine inhaltlichen Elemente abgebildet.

**Was ist gut?**

 - Perspektive bzw. Illusion der Tiefe ohne zu stark in 3-Dimensionalität zu gehen 
 - Guter Kontrast
 - Nutzung von zwei Seiten. Dadurch freier visueller Raum 

**Was passt nicht in unseren Kontext?**

 - Zeichenstil an der Grenze zum "Kinderbuch"
 - Wenig Möglichkeit einzelne Komponenten auf den Schichten darzustellen

---
### Beispiel 2:

![enter image description here](https://i.imgur.com/hsrwoNC.jpeg)

**Was ist gut?**

 - Option viele Einzelkomponenten unterzubringen
 - Gute Positionierung der Schichten: Man sieht viel trotz der Überlagerung

**Was passt nicht in unseren Kontext?**

 - Billiger "Technologie-Zeichenstil": Grelle Farben, schlechte/unnötige Schattierung
 - Einzelne Elemente nicht konsistent in Perspektive (z.B. Gebäude hat keine Tiefe)
---
### Beispiel 3:
 
![enter image description here](https://i.imgur.com/JEUUt9l.png)
**Was ist gut?**
 - Detailreichtum: Komplexe System wird dargestellt
 
**Was passt nicht in unseren Kontext?**
 - Schwarz/weiß nicht gewünscht
 - Frontaldarstellung und Transparenz machen es schwer lesbar

---
### Beispiel 4:

![enter image description here](https://coolstuf.com.pg/wp-content/uploads/2017/09/NEC-SMART-CITY-DIAGRAM.png)

**Was ist gut?**
 - Gute Lösung von Perspektive und 3-Dimensionalität
 - Auffächern der Schichten zeigt klar, dass in der Realität alles verwoben ist
 - Diese Entzerrung würde das Problem lösen, dass Menschen eigentlich auf der Business-Ebene mit PV-Anlagen und E-Autos interagieren, diese aber trotzdem Teil der Infrastrukturschicht sind. Man könnte in der Darstellung einer gemeinsamen Schicht alle diese Elemente interagieren lassen und dann beim Auffächern Anlagen in die darunter liegende Schicht packen

**Was passt nicht in unseren Kontext?**
 - Billiger Zeichenstil

## Grundflächen der einzelnen Schichten


### 1. Streetmap oder gezeichnete Luftaufnahme (auf auf Business Schicht)
![enter image description here](https://media.istockphoto.com/vectors/city-map-with-location-markers-vector-id482541798)

![enter image description here](https://cdn.dribbble.com/users/59947/screenshots/7273489/muti_1.png?compress=1&resize=400x300)

### 2. Stromnetztopologie (Infrastrukturschicht)

![enter image description here](https://www.fuergy.com/media/pages/blog/energy-revolution-starts-with-smart-grids/0518771443-1643113532/smart-grid.png)

![enter image description here](https://www.eon.de/content/dam/eon/eon-de-zwei/images/eon-erleben/smartgrid/smartgrid-n/smart-grid-eon-teaser.jpg/jcr:content/renditions/cq5dam.web.480.480.jpeg)

### 3. Heat Maps & Spidercharts (z.B. auf Dashboard Schicht)

![enter image description here](https://i.stack.imgur.com/GEZ9R.png)

![enter image description here](https://i.pinimg.com/736x/60/0f/90/600f90badf51d3ea0a3f75ac844aea4f.jpg)

### 4. Honigwaben (auf Digitaler Plattformschicht)
![enter image description here](https://c8.alamy.com/comp/2BT9APD/abstract-background-black-hexagons-or-honeycombs-3d-rendering-hexagonal-wallpaper-network-connection-concept-geometric-illustration-design-in-4k-2BT9APD.jpg)
![enter image description here](https://miro.medium.com/max/1400/1*TEWseKCLwaLKRvPakylGUg.png)

### 5. Neuronale Netzwerkarchitektur (auf Analyse/AI Schicht)
![enter image description here](https://fr.farnell.com/wcsstore/ExtendedSitesCatalogAssetStore/cms/asset//images/common/technology/articles/2517931/2517931-neural-networks.jpg)

![enter image description here](https://image.shutterstock.com/image-illustration/artificial-neural-networks-ann-connectionist-600w-1484684003.jpg)

## Anforderungen an finales Design

 - Interaktion zwischen Schichten sichtbar (Menschen mit Geräten, Geräten mit Dashboard, Geräte mit digitaler Plattform, Dashboard mit AI, Digitale Plattform mit AI)
 - Nutzung von zwei überlappenden Seiten um visuellen Raum zu schaffen
- Falls möglich: Teilbereiche in denen Schichten zusammenlaufen ("Wie in Realität")
- ...

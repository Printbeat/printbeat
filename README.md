# ICC-profielen uitgelegd voor fotografie en print

Kleuren op een scherm en op papier gedragen zich anders. Dat is geen fout, maar een gevolg van hoe beeld wordt weergegeven. Een scherm geeft licht, terwijl papier licht reflecteert.

ICC-profielen helpen om die verschillen zo goed mogelijk te beheersen. In deze gids leggen we uit wat ICC-profielen zijn, wanneer je ze gebruikt en hoe je voorkomt dat je print er anders uitziet dan verwacht.

---

## Wat is een ICC-profiel?

Een ICC-profiel is een bestand dat beschrijft hoe een apparaat kleur weergeeft.

Dat kan zijn:
- een camera  
- een monitor  
- een printer in combinatie met een specifiek papier  

Omdat elk apparaat kleuren net anders interpreteert, is er een vertaalslag nodig. Een ICC-profiel zorgt ervoor dat kleuren consistent blijven tussen apparaten.

---

## Waarom print er anders uitziet dan je scherm

Het verschil zit in de manier waarop beeld wordt opgebouwd:

- **Scherm** → geeft licht (RGB)
- **Print** → reflecteert licht (inkt op papier)

Gevolgen:
- contrast is lager op papier  
- kleuren ogen minder fel  
- donkere partijen lopen sneller dicht  

Dit is normaal en hoort bij print.

---

## Veelgebruikte kleurprofielen

### sRGB
- Standaard profiel voor web en consumententoepassingen  
- Klein maar voorspelbaar kleurbereik  
- Veilige keuze als je geen specifieke workflow gebruikt  

### Adobe RGB
- Groter kleurbereik, vooral in groenen en cyaantinten  
- Geschikt voor fotografie en print  
- Vereist correcte workflow om voordeel te behouden  

### Printerprofielen (ICC)
- Specifiek voor printer + papier + inkt  
- Worden gebruikt bij softproofing en printvoorbereiding  
- Essentieel voor nauwkeurige kleurweergave  

---

## Hoe gebruik je ICC-profielen in je workflow

### 1. Werk in een consistent kleurprofiel
Gebruik sRGB of Adobe RGB en blijf daarbij gedurende je hele workflow.

---

### 2. Kalibreer je monitor
Zonder een gekalibreerd scherm heeft kleurbeheer weinig waarde.

Gebruik bij voorkeur een hardware kalibratie tool zoals:
- X-Rite i1Display  
- Datacolor Spyder  

Belangrijk:
- stel helderheid niet te hoog in  
- werk in een neutrale lichtomgeving  

---

### 3. Gebruik softproofing

Softproofing simuleert hoe je beeld eruitziet op een specifiek papier.

#### In Photoshop:
1. View → Proof Setup → Custom  
2. Kies het ICC-profiel van het gewenste papier  
3. Zet "Simulate Paper Color" aan  

Wat je ziet:
- minder contrast  
- verschuiving in kleurtoon  
- realistischer beeld van het eindresultaat  

---

### 4. Corrigeer op basis van de simulatie

Na softproofing kun je kleine aanpassingen doen:
- lichte correctie in contrast  
- schaduwen openen indien nodig  
- verzadiging subtiel bijstellen  

Werk terughoudend. Grote aanpassingen geven vaak onnatuurlijke prints.

---

## Veelgemaakte fouten

### Geen ICC-profiel gebruiken
Resultaat:
- kleuren wijken af van verwachting  
- geen controle over eindresultaat  

---

### Bewerken zonder softproof
Resultaat:
- prints ogen te donker  
- kleurverhoudingen kloppen niet  

---

### Verkeerd profiel exporteren
Altijd:
- embed het kleurprofiel (sRGB of Adobe RGB)  

Zonder embedded profiel weet de printer niet hoe kleuren geïnterpreteerd moeten worden.

---

### Te helder scherm
Een veelvoorkomend probleem.

Gevolg:
- je corrigeert je beeld te donker  
- print komt donkerder uit dan bedoeld  

---

## Praktisch advies

- Gebruik sRGB als je zekerheid wilt  
- Gebruik Adobe RGB alleen als je workflow dit ondersteunt  
- Softproof bij belangrijke prints  
- Houd je scherm helderheid onder controle  
- Werk met originele bestanden, niet gecomprimeerde versies  

---

## ICC-profielen gebruiken met Printbeat

Voor specifieke papiersoorten en materialen zijn ICC-profielen beschikbaar.

Denk aan:
- Fine Art papier  
- Baryta papier  
- ChromaLuxe aluminium  

Gebruik deze profielen bij softproofing om vooraf te zien hoe je print eruit zal zien.

[https://www.printbeat.nl](https://www.printbeat.nl/icc-profiles)
---

## Samenvatting

ICC-profielen zorgen voor consistentie tussen scherm en print.

Ze lossen het verschil tussen licht en reflectie niet op, maar maken het resultaat wel voorspelbaar. Dat is waar kleurbeheer om draait.

---

Voor praktische hulp of bestandscontrole:
https://www.printbeat.nl

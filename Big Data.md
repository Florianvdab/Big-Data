# Big Data

## Big Data Hype

Sinds 2012 een stijging op Google Trends. Vooral bekend bij Tech Giants als Facebook, Google, Netflix, Uber & Amazon. 

Maar nu willen alle bedrijven op de kar springen.

Andere begrippen rond Big Data zijn: AI, BI, GDPR, ML

Er word enorm veel data opgeslagen maar niet gebruikt!

Er zijn 3 belangrijke fases bij Big Data:

1. Big Data verzamelen
2. Big Data onderzoeken
3. Big Data laten spreken, laten presenteren. 

## Big Data

Er is een verschil tussen Big Data & een Big Database en tussen Big Data & Business Intelligence.

Business Intelligence is de data laten spreken.

### Geschiedenis data

Het begon met bibliotheken, recent kwamen er DBMS (manuele input en gestructureerd) daarna Big Data (Automatisch en ongestructureerd).

### Beschrijving

![1559462359090](C:\Users\Flori\Documents\Big Data MD\1559462359090.png)

Big Data kenmerken: 

- Grote hoeveelheden data
- Geen controle op het compleet zijn van elk onderdeel
- Afwezig zijn van enige onderdening
- De hoeveelheid gegevens kan op elk moment sterk veranderen

**Opgelet! Alle voorwaarden moeten samen voldaan zijn, dus VEEL gegevens en ONGEORDEND.**

Big Data is een zo grote hoeveelheid ongestructureerde en (soms) niet-complete set gegevens dat verwerking met conventionele databasesystemen niet mogelijk is.

De 6 V's van Big Data: 

1. **Volume**: Grote hoeveelheid
2. **Velocity**: Grote snelheid van ontstaan nieuwe gegevens
3. **Variety**: Grote onderlinge variatie
   1. Structured Data
   2. Semi Structured Data
   3. Unstructured Data
4. **Value**: Waarde uit de data halen
5. **Veracity**: De kwaliteit/oorsprong van de data
6. **Variability**: In hoeverre en hoe snel de structuur van je data veranderd.

### Relaties

#### Big Data

Ongeordend en deels incompleet, dus een zoekopdracht werkt altijd op de hele verzameling en heeft (soms) aanvullende zoektermen nodig.

- Chaos = Complexer
- Incompleet

#### Databasesysteem

Geordend en compleet, dus de meest voorkomende zoekopdrachten werken alleen op indexbestanden.

- Mooi geordend = Vlot a.d.h.v index
- Compleet

#### Hybride

> Databasesysteem Big Data

Schema van een gemengd informatiesysteem waarin databases worden gecombineerd met Big Data, met de belangrijkste gereedschappen (tools).

### Toepassingen

Wanneer Big Data gebruiken? Zeker niet altijd de beste oplossing!

Verhalen als: Google, Nasa & Facebook.

Er is in totaal rond de 200PB aan data in een jaar.

Het draait wel niet enkel om grote bedrijven, het kan ook een zeker impact hebben op een kleiner niveau. Denk bijvoorbeeld aan het verhaal rond de "Game Company" in het handboek.

## Opslag

### Dataontwerp

Eigen VS Wensen.

Vraag 1: Wat is de functie van het nieuwe systeem?

Vraag 2: Wat is absoluut noodzakelijk?

Vraag 3: Wat is wenselijk?

**De nodige tijd reserveren om dit grondig te doen, OPLETTEN dat vraag 2 en 3 niet door elkaar gehaald worden.**

### Dataopslag

#### Ontstaan

Data = afspiegeling van voorwerpen of gebeurtenissen

- Kernwaarden registeren (afhankelijk van situatie)
- Registratie (transactie systeem via menselijke tussenkomst of via ander systeem)

![1559462418359](C:\Users\Flori\Documents\Big Data MD\1559462418359.png)

(Te veel linken, te weinig linken, niet de juiste gegevens ...)

### Van data naar informatie

![1559462498686](C:\Users\Flori\Documents\Big Data MD\1559462498686.png)

### Opslag van informatie

Uitleggen aan de hand van een voorbeeld, neem een bedrijf dat onderhoud doet van: Centrale verwarmingen, Airco's, Warmwatersystemen enz... 

Zij hebben 2 mogelijkheden: 

#### Model Driven Storage - Datawarehouse & Datamart

Bv. Foutcodes en statusrapporten = eenvoudig te structureren data

**DBMS**

#### Data Driven Storage - Datalake & Datareservoir

Bv. Emails en telefoongesprekken = moeilijk te structureren data

**BIG DATA**

![1559462747726](C:\Users\Flori\Documents\Big Data MD\1559462747726.png)

*In grote informaticasystemen is er meestal een combinatie met uitwisseling. Datalake is dan de centrale bron. Zie bovenstaande foto.*

## Proces

### Data-Analyse

De eerste 3 zijn gestuurd door de gebruiker met een duidelijke vraag, vb. geef mij een cijfer van laatste 3 maanden over de temperatuur.

1. Reporting (statisch) - Excel
2. OLAP (dynamisch) - Tableau
3. Zoekopdrachten - SQL/NoSQL
4. Datamining - Vertrekt van de data en probeert patronen te ontdekken waardoor je niet altijd op voorhand weet welke vragen zullen beantwoord worden.

#### Reporting

![1559463069222](C:\Users\Flori\Documents\Big Data MD\1559463069222.png)

#### OLAP 

![1559463082918](C:\Users\Flori\Documents\Big Data MD\1559463082918.png)

#### Zoekopdrachten

![1559463100908](C:\Users\Flori\Documents\Big Data MD\1559463100908.png)

### Datamining

**Het ontdekken van trends en patronen in een grote berg data.**

Bv. in marketing om op basis van verkoopdata te weten te komen welke producten samen worden gekocht, op welke dagen welke promoties beter werken, welke klanten binnen welk segment vallen, … Of op basis van data dat verkregen is via webscraping, achterhalen welke online leads interessant kunnen zijn en welke direct marketingcampagnes bij welke personen succes zullen hebben, dit kan o.a door combinatie van allerlei gestructureerde en ongestructureerde data… > Big Data!
Let op: Datamining ≠ AI en Machine Learning… die laatste gaan nog verder en laten systemen zichzelf trainen en slimmer worden... Datamining beperkt zich tot bestaande datasets en wordt niet zelf beter na verloop van tijd (tenzij je zelf het systeem beter maakt).

1. **Business Understanding** - Heeft het zin om te onderzoeken?
2. **Data Understanding** - Hoe zit het in elkaar?
3. **Data Preparation** - Kwalitatief en volledig om te starten?
4. **Modeling** - Wat ontdekken we in de berg data?
5. **Evaluation** - Gewenste resultaten of bijsturen?
6. **Deployment** - Hoe passen we dit nu toe?

### Big Data-Proces

SQL Opdrachten kunnen heel lang duren, denk maar aan het voorbeeld van in het boek. 10 seconden is nog doenbaar, maar 100 seconden totaal niet. Er zijn 2 oplossingen hiervoor: 

1. Snellere servers
2. Meer servers

#### Parallel verwerken

![1559463534354](C:\Users\Flori\Documents\Big Data MD\1559463534354.png)

#### Key value

![1559463559726](C:\Users\Flori\Documents\Big Data MD\1559463559726.png)

Wordt gestructureerd a.d.h.v **de “key value” methode**.
Bv. hoeveel keer een woord voorkomt in een tekst.

#### Map Reduce

(Denk aan het lego blokjes verhaal)

![1559463619265](C:\Users\Flori\Documents\Big Data MD\1559463619265.png)

= De techniek om het werk te verdelen over de verschillende computers
‘**map**’ -> verdelen van het werk
‘**reduce**’ -> ophalen van de resultaten en het combineren om tot 1 antwoord te komen.
**2 “Map” Methodes:** 

- **Methode 1**: Eén algoritme voor alle computers (informatie wordt gelijk verdeeld over alle computers).
- **Methode 2**: er bestaan verschillende algoritmes om de info te doorzoeken. Een computer krijgt eerst het algoritme en vervolgens de aangepaste informatie.

Bedoeling is om de werklast zo goed mogelijk uit te balanceren zodat de computers ongeveer op hetzelfde moment klaar zijn met de opdracht.
Werking van verschillende computers wordt gemonitord. Indien één computer vastloopt wordt hetzelfde proces gestart op een volgende computer (ook wel ‘node’ genoemd).

#### Verwerken Big Data

vb. Hoe wordt een stukje tekstverwerkt en doorzocht?

- Bv. elke zin wordt aan 1 computer toegewezen
- Een woord wordt een 'key' en het aantal keer dat het voorkomt een 'value'
- Elke computer maakt nu zijn eigen tabel met resultaten
- Daarna worden de resultaten terug samengevoegd in een samenvattende tabel

![1559464303856](C:\Users\Flori\Documents\Big Data MD\1559464303856.png)

#### Predictive Analytics

Toepassen van een bestaand datamodel op nieuwe informatie.

vb. Het voorspellen van een tekst wat het onderwerp is?
Winkels die voorspellen wat de aankoopgewoontes de komende periode zullen zijn.

#### CAP - Theorema

![1559464379167](C:\Users\Flori\Documents\Big Data MD\1559464379167.png)

**Dit moet altijd gegarandeerd zijn!**

- **Consistency** "read" geeft meest recente write.
- **Availability** "read" geeft altijd een uitkomst, geen garantie dat het de meest recente is. DATA INTEGRITY in gevaar.
- **Partition Tolerance** Systemen blijven altijd werken!

## Beslisboom

Keuzes, keuzes en nog eens keuzes...

De eerste keuze blijft doorwerken op de volgende keuze, enz.

In beeld brengen is interessant, maar in Data Science is de vraag:
"Hoe kunnen we deze techniek gaan gebruiken om **beslissingen** te nemen op basis van informatie?"

### Het probleem

Gebruikt **elkaar uitsluitende** kenmerken, bv. kleur

![1559465366034](C:\Users\Flori\Documents\Big Data MD\1559465366034.png)

Kenmerken moeten wel **onderscheidend** zijn. Aantal wielen bv. niet relevant.

Kan een kleine testverzameling gedrag in een grote verzameling voorspellen?

![1559465414617](C:\Users\Flori\Documents\Big Data MD\1559465414617.png)

Gebruik van **koppelingen** tussen data: toevallige overeenkomst of oorzakelijk verband?

### De oplossing

![1559465448785](C:\Users\Flori\Documents\Big Data MD\1559465448785.png)

Kan een antwoord bieden op 2 zaken: 

- Is de vraagstelling of een stelling **valide** gegeven de beschikbare informatie?

Bv. Krijgen rode auto's vaker een snelheidsboete?

Op basis van een testverzameling kan je de kans gaan berekenen dat een rode auto een snelheidsboete krijgt.

- Is de vereiste **nauwkeurigheid voldoende** om uitspraken te doen?

Dit wordt medebepaald door de grootte van de steekproef en of die statische groot genoeg is om als betrouwbaar te wordenaangenomen.
M.a.w representatief

Belangrijke vraag: hoe komt de beslisboom tot stand?

- Welke kenmerken worden opgenomen?
- Welke keuze plaats je eerst, welke dan, enz...

Bij "Big Data" - Automatisering noodzakelijk a.d.h.v algoritmes!

Deze algoritmes ‘testen’ als het ware elk kenmerk op elk moment en gaan aan de hand van ‘cost’ functies afwegen welk kenmerk op welk moment in de boom het relevantste/meest voorspellend is om als volgende splitsing te nemen…

**ENTROPIE = Maatstaf voor wanorde.**

![1559465819649](C:\Users\Flori\Documents\Big Data MD\1559465819649.png)

Bij elke volgende keuze van het kenmerk kiest het algoritme het kenmerk dat entropie het meest verlaagt = informatiewinst

Ideale beslissingsboom is degene waarbij de entropie minimaal is.

### De beperkingen

Om keuzes uitsluitend te maken, werkt de beslisboom enkel met individuele kenmerken. Maar soms zijn het ‘combinaties’ van kenmerken (zie techniek ‘afleiden van regels’).
Risico van uitwerking tot in te groot detail. Belangrijke vraag is dus wanneer stoppen met verder splitsen? (Techniek van de snoeioptie om de boom terug te dringen naar de minimale vorm).
Hoe wordt dit in business context bv. gebruikt? Stel je hebt een SAAS-product op de markt gebracht. Heel belangrijk hierbij is de ‘retention rate’.
Je kan de kansen op ‘churn’ (abonnement niet verlegen) gaan onderzoeken op basis van historische gegevens en de kenmerken van klanten/gebruik van de software. Uit die conclusies kan je dan acties hieraan koppelen om in het vervolg beter te doen.

![1559465890670](C:\Users\Flori\Documents\Big Data MD\1559465890670.png)

Ander voorbeeld: werking van een Helpdesk verbeteren…
Op basis van historische data de kansen berekenen waar het probleem precies zit en welke hulp ingeschakeld moet worden

## Neurale Netwerken

![1559470600888](C:\Users\Flori\Documents\Big Data MD\1559470600888.png)

### Inleiding

Neuraal d.w.z simuleert de werking van onze hersenen (= netwerk van neuronen).

Verschil met beslisboom: Er is geen vaste combinatie van inputs die sowieso binnenkomt, het hangt af van situatie tot situatie. 
Bij een beslisboom is dat niet mogelijk want elk kenmerk kan altijd geëvalueerd worden en kan er dus niet altijd uitsluitsel gegeven worden.

![1559470734159](C:\Users\Flori\Documents\Big Data MD\1559470734159.png)

### Het probleem

Selecteer mogelijk factoren en onderzoek hun invloed.

**Controlegroep**

**Voorspelling versus echte uitkomst**

Hoe zou je de voorspelling kunnen verbeteren? 

![1559470788835](C:\Users\Flori\Documents\Big Data MD\1559470788835.png)

### De oplossing

![1559470807905](C:\Users\Flori\Documents\Big Data MD\1559470807905.png)

Neurale werking wordt dus gesimuleerd door de computer:

Een aantal belangrijke vragen: 

- Welke signalen zijn relevant om bepaalde impuls te geven in een neuron?
- Welk gewicht geef je aan elk signaal?
- Hoe moeten de verschillende neuronen verbonden worden? (netwerk van neuronen)

2 benaderingen: 

- **Vast**: je beslist zelf welke signalen (kenmerken) en welke gewichten van toepassing zijn.
- **Adaptief**: lerend algoritme

Je prompt heel veel combinaties van invoersignalen en bekende uitvoersignalen in het system en traint op die manier het systeem om de best mogelijke signalen en gewichten te ontdekken. Dit kan met of zonder supervisie.

Je voedt het systeem met inputs en de bijhorende output. Het systeem doet een voorspelling en vergelijkt met de werkelijkheid. Op basis van die resultaten zal het systeem zichzelf continu verbeteren.

Het systeem start met random gewichten (w) en zal de gewichten bij elke iteratie aanpassen om de foutenmarge te verkleinen. 

Hoe meer trainingsdata, hoe slimmer de handeling.

> The program continuously recalculates its algorithms as new information is acquired. When the AI needs to act before the opponent makes a bet or holds and does not receive new information, deep learning steps in. Neural networks, the systems that enact the knowledge acquired by deep learning, can help limit the potential situations factored by the algorithms because they have been trained on the behavior in the game. This makes the AI’s reaction both faster and more accurate, Bowling says. In order to train DeepStack’s neural networks, researchers required the program to solve more than 10 million randomly generated poker game situations.

### Beperkingen

**GOED**

- Maakt het mogelijk om met vage en incomplete data aan de slag te gaan
- Zeer flexibel: Neurale netwerken passen zich aan, aan de omstandigheden
- Goed bruikbaar bij patroonherkenning (bv. facial recog.)

**SLECHT**

- Door complexiteit van vragen is het antwoord nooit zeker, vaak incompleet. Zeker niet geschikt voor elk vraagstuk.
- Leerfase is nodig en dit kost tijd.
- Enkel effectief als er voldoende kwalitatieve data op voorhand is om te trainen.
- Gebruiker heeft nauwelijks invloed op de werken

## Clusteren

### Inleiding

![1559471194666](C:\Users\Flori\Documents\Big Data MD\1559471194666.png)

### Het probleem

Clusteren = het samenbrengen in compacte groepen op grond van 1 of meer kenmerken?

Maar wat is compact en welke kenmerken?

### De oplossing

Er bestaan veel manieren, maar wij bespreken er 3: 

1. Hiërarchisch
2. Puntsgewijs
3. Dichtheidsgewijs

#### Hiërarchisch

![1559471279712](C:\Users\Flori\AppData\Roaming\Typora\typora-user-images\1559471279712.png)

Dendogram - Gebruiker bepaalt zelf gewenste doorsnede.

#### Puntsgewijs (K-means)

![1559471325785](C:\Users\Flori\Documents\Big Data MD\1559471325785.png)

K-punten: vectoren/zwaartepunten.

"Afstand" kan op verschillende manieren en op basis van verschillende eigenschappen berekend worden.

*Clustering herhalen met verschillende startpunten*

#### Dichtheidsgewijs

![1559471383910](C:\Users\Flori\Documents\Big Data MD\1559471383910.png)

Op zoek naar deelverzamelingen met voldoende elementen, voorwaarde is wel dat er duidelijke verschillen in dichtheid zijn. Werkt met drempelwaarde.

**Validatie?**

**Interne validatie**

= uitkomst vergelijken met alternatieve methoden

**Externe validatie**

= methode wordt afgetoetst op testverzameling waarbij menselijke uitkomst bepaald is

### De beperkingen

Clustering = veel gebruikt en zeer goed als eerste aanzet om een eerste inzicht te krijgen in grote hoeveelheid data ... maar ...

- Kan kunstmatig zijn... zijn de gekozen clusters wel relevant t.o.v de vraagstelling
- Beperkte validatie

## Lineaire regressie

![1559472345948](C:\Users\Flori\Documents\Big Data MD\1559472345948.png)

### Het probleem

![1559472362569](C:\Users\Flori\Documents\Big Data MD\1559472362569.png)

![1559472389399](C:\Users\Flori\Documents\Big Data MD\1559472389399.png)

### De oplossing

![1559472401098](C:\Users\Flori\Documents\Big Data MD\1559472401098.png)

![1559472408503](C:\Users\Flori\Documents\Big Data MD\1559472408503.png)

### De beperkingen

Voorwaarden op regressie te kunnen toepassen: 

- Onafhankelijke grootheid heeft exacte waarden
- De relatie kan a.d.h.v een vergelijking worden weergegeven
- Variantie in afhankelijke grootheid is onafhankelijk van de grootte van de onafhankelijke grootheid

Belangrijk: altijd de visuele voorstelling er bij ... Want ... 

![1559472514059](C:\Users\Flori\Documents\Big Data MD\1559472514059.png)

Ook opletten met de schaal van je assen!

![1559472526769](C:\Users\Flori\Documents\Big Data MD\1559472526769.png)

## Naaste buur

### Inleiding

Toepassingen vooral bij PATROON -en BEELD herkenning

![1559472603418](C:\Users\Flori\Documents\Big Data MD\1559472603418.png)

Soort combinatie van clusteren en elementen uit lineaire regressie.

### Het probleem

*If it looks like a duck, swimslike a duck, and quacks like a duck, then it probablyis a duck*
Veronderstelling: buren hebben soortgelijke eigenschappen als onszelf.
Dit kan je ook toepassen op allerlei soorten data: als men de eigenschappen van een nieuw datapunt wil bepalen, kan men kijken bij welk ander datapunt het nieuwe punt het best aansluit en er van uit gaan dat die eigenschappen vrij gelijk zijn… (→ clusteren)
Denk aan de recommendation engines: iemand die dit en dit en dit bekeken heeft, zal waarschijnlijk ook dit interessant vinden…

Hoe je dan ‘afstand’ bepaalt, is afhankelijk van de context: dit kan letterlijk ‘meetkundige’ afstand zijn, maar hierdoor kan eender welke andere factor/maatstaf gebruikt worden.

- Van 1 tot 5 zijn de eigenschappen bekend vormen clusters (wit, grijs, zwart)
- Nieuwe punten A, B & C worden op basis van afstand in een cluster ingedeeld (zie bv. technieken lineaire regressie): 
  - A bij wit
  - B bij grijs
  - C: ?

![1559472769565](C:\Users\Flori\Documents\Big Data MD\1559472769565.png)

Merk op: belangrijk verschil met neurale netwerken: je gebruikt vooraf bestaande info, bij neurale netwerken wordt dit opgebouwd.

### De oplossing

![1559472812924](C:\Users\Flori\Documents\Big Data MD\1559472812924.png)

- A & B duidelijk: gewoon meten en kleinste afstand kiezen
- C ? 2 opties
  - Status onbenoemd
  - Resultaten van nieuwe punten worden ook meegenomen

Flexibel! 'Afstand' kan dus ook een combinatie van allerlei factoren gaan vormen met bepaald gewichten, patronen, vormen (zie facial recog.) ... Kan dus ook in meerdere dimensies.

### De beperkingen

Werkt pas goed als de instellingen voor het clusteren en de afstandsbepaling goed zijn afgesteld -> STERK afhankelijk van voorafgaande kennis

![1559472957462](C:\Users\Flori\Documents\Big Data MD\1559472957462.png)

## Regels afleiden

### Inleiding

Medische diagnose stellen, taalanalyse, ...

### Het probleem

2 tools nodig

- Grote hoeveelheid (transactie) data
- Regels

Op basis hiervan kan je dan (probabiliteits) voorspellingen doen

Hoe worden die regels achterhaald?

- Manier 1: bestaande kennisregels vertalen naar computerregels (if, then, else). Beschikbare data wordt gebruikt om betrouwbaarheid te testen. Bv. medische regels
- Manier 2: beschikbare info gebruiken om regels te achterhalen en nadien de betrouwbaarheid te testen. Bv. aankoopgedrag

### De oplossing

##### Werken met regels

Bv. ALS(Brood, boter) DAN melk

Key Value en Map Reduce kan handig ingezet worden

Moeilijk met continue waarden: oplossing is in klassen verdelen, bv.

![1559473160255](C:\Users\Flori\Documents\Big Data MD\1559473160255.png)

#### Bestaande regels

3 toepassingen: 

- Betrouwbaarheid testen bestaande regels, maar nu gebaseerd op data
- Voorspellen van acties op basis van voorwaarden
- Combinatie van beide

![1559473208856](C:\Users\Flori\Documents\Big Data MD\1559473208856.png)

#### Nieuwe regels

![1559473405166](C:\Users\Flori\Documents\Big Data MD\1559473405166.png)

### De beperkingen

Tijdrovend!
Relativiteit van ‘bekende’ ervaringsregels: kunnen soms inconsistent zijn of incompleet en moeilijk door de software te detecteren vallen
Moeilijkheid regels afleiden uit bestaande informatie:
Hoe kies je de drempels? Niet te laag (veel regels maar waarschijnlijkheid laag) – niet te hoog (weinig nieuwe info te ontdekken…)
Verschil beslisboom?
Beslisboom: per opsplitsing één regel

![1559473262336](C:\Users\Flori\AppData\Roaming\Typora\typora-user-images\1559473262336.png)

Regels afleiden: mogelijkheid meerdere regels te combineren (if (… and .. and..) in één stap
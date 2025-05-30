---
title: Baseline Informatiebeveiliging (BIO2), versie 1.1
summary: Dit document bevat de inleiding, context en werkwijze van de Baseline Informatiebeveiliging Overheid (BIO2). 
hide:
  - navigation
---

!!! warning "BIO2 in besluitvorming" 
	Deze BIO is het resultaat van de online raadpleging en input van veel andere partijen, waaronder de werkgroep BIO. Op dit moment staat deze bio ook gepubliceerd op de website [BIO-Overheid.nl] (https://www.bio-overheid.nl) als PDF en in spreadsheet formaat. Dit document bevat de laatste versie van de Baseline Informatiebeveiliging Overheid 2 (BIO2). 

Deze versie zal worden ingebracht in het OBDO voor bestuurlijke besluitvorming. De BIO2 bestaat uit drie delen: 1) een inleiding waarin de context, verplichtingen en samenhang van de BIO worden uitgelegd, 2) de verplichte overheidsspecifieke beheersmaatregelen en implementatierichtlijnen, en 3) een bijlage (in ontwikkeling) met daarin een toelichting en nadere uitleg over best practices.

Versie 1.1 Diverse tekstuele aanpassingen

## Copyright notitie

De Baseline Informatiebeveiliging Overheid 2 (BIO2) is geheel gestructureerd volgens NEN-EN-ISO/IEC 27001, bijlage A en NEN-EN-ISO/IEC 27002. Het Forum Standaardisatie heeft deze normen opgenomen in de ‘pas-toe-of-leg-uit’-lijst met verplichte standaarden voor de publieke sector, volgens het pas-toe-of-leg-uit-principe. Dit betekent dat de overheid deze normen toepast tenzij er expliciet geformuleerde redenen zijn om dat niet te doen. De BIO2 beschrijft de invulling van de laatste versie van de NEN-EN-ISO/IEC 27001 en de NEN-EN-ISO/IEC 27002 voor de overheid. Met klem vermeldt zij dat de BIO deze normen niet vervangt.

In de BIO2 zijn alleen specifieke overheidsmaatregelen opgenomen. In de GitHub versie zijn voor de leesbaarheid nog wel beheersmaatregelen opgenomen om de overheidsmaatregel in context te plaatsen.

NEN-EN-ISO/IEC 27001 en NEN-EN-ISO/IEC 27002 beschrijven de details voor implementatie (richtlijnen) en eisen voor de procesinrichting (het ISMS uit NEN-EN-ISO/IEC 27001). Het volgen van ISO 27001 is verplicht voor het inrichten van het managementsysteem voor informatiebeveiliging. Daar waar de BIO2 niet expliciet iets voorschrijft moeten de beide ISO-documenten gebruikt worden om te komen tot een goede inrichting voor risicomanagement. De ISO-documenten geven dus de details voor de toepassing, die niet in de BIO2 zijn beschreven en die nodig blijven voor een goede implementatie van de BIO2.

Het gebruik van NEN-EN-ISO/IEC-normen 27001 en 27002 in de BIO is auteursrechtelijk beschermd. Het gebruik van teksten uit deze normen in de BIO geschiedt met toestemming van het Nederlands Normalisatie Instituut. Voor meer informatie over de NEN en het gebruik van hun producten zie: www.nen.nl.

# Deel 1 BIO2-Kader

Versienummer 1.1 definitief, 11 april 2025 
In deze versie zijn termen geüniformeerd, nummercorrectie, taalkundige aanpassingen en overheidsmaatregel 5.19.01 ingekort.

De overheid vervult een essentiële rol in de samenleving door bij te dragen aan de democratische rechtsstaat en het bieden van diensten aan burgers bedrijven. Deze verantwoordelijkheden vereisen een zorgvuldige omgang met informatie en gegevens.

Om deel te kunnen nemen aan de samenleving moeten burgers en bedrijven informatie met de overheid delen, soms zelfs verplicht, en zijn zij afhankelijk van de overheid om informatie te ontvangen. De overheid heeft vanuit deze unieke rol de plicht om zorgvuldig om te gaan met de beveiliging van die gegevens. 

De Cyberbeveiligingswet (Cbw) verplicht overheidsorganisatie de BIO2 voor de sector 'Overheid' als voornaamste invulling van die zorgplicht. 

## Leeswijzer
De Baseline Informatiebeveiliging Overheid 2 (BIO2) is opgebouwd uit drie onderdelen. 
1) Deel 1: BIO2-kader - de context en het belang van informatiebeveiliging voor overheidsorganisaties, evenals de structuur en toepasselijkheid van de BIO.
2) Deel 2: BIO-overheidsmaatregelen - verplichte normen en richtlijnen, gebaseerd op internationale standaard NEN-EN-ISO/IEC 27001, aangevuld met specifieke overheidseisen.
3) Deel 3: Toelichting [in ontwikkeling] - praktische ondersteuning met extra toelichting of voorbeelden om overheidsmaatregelen effectief te implementeren. Samen vormen deze onderdelen een compleet kader voor informatiebeveiliging binnen de overheid. 

Er worden voor de (ISO-)normen in dit document geen jaartallen gebruikt. Daar waar gerefereerd wordt aan een andere norm wordt de meest actuele versie bedoeld. 

## Doel van de BIO

De Baseline Informatiebeveiliging Overheid (BIO) is het verplichte normenkader voor informatiebeveiliging binnen alle overheidsorganisaties. Het biedt richtlijnen, algemene principes en verplichte overheidsmaatregelen voor het initiëren, implementeren, onderhouden en verbeteren van informatiebeveiliging binnen de overheid en haar ketens. 

Het doel van de BIO is om de informatieveiligheid overheidsbreed op een gemeenschappelijk basisniveau te brengen en daardoor ook de ketenpartners een basis van vertrouwen te geven bij gegevensuitwisseling. De aanpak volgens de BIO vraagt inspanning door ketenorganisaties en eenduidige samenwerking.

Daarnaast biedt de BIO een basis voor overheidsorganisaties om zowel intern als extern transparant te zijn over de wijze waarop informatiebeveiliging is ingericht. Met de BIO hanteert de overheid één gezamenlijke taal en een gezamenlijk doel op het gebied van informatiebeveiliging.

De BIO is samengesteld uit de aanpak van de NEN-EN-ISO/IEC 27001 (nl) (het managementsysteem), de beheersmaatregelen en implementatierichtlijnen uit NEN-EN-ISO/IEC 27002 (nl) en aanvullende verplichte overheidsspecifieke maatregelen.  

## Toepassing BIO

Met de Cbw is de BIO verplicht voor alle organisaties die vallen onder de sector 'Overheid' en geldt voor alle informatiesystemen, zowel digitaal als fysiek, binnen deze organisaties. In de Cbw is beschreven op basis van welke criteria een organisatie als overheid wordt gezien.

De BIO is van toepassing op de informatiebeveiliging van alle typen omgevingen, onder andere ook operationele technologie (OT) en zorginformatie en brengt deze op het noodzakelijke niveau met behulp van normen en richtlijnen zoals de NEN 7510 Informatiebeveiliging in de zorg en Cybersecurity implementatierichtlijn (CSIR). 

Dit BIO2-kader en het bijbehorende deel 2 BIO-overheidsmaatregelen hebben een verplichtend karakter en moeten altijd gevolgd worden. Deel 3 is een uitwerking en verduidelijking op sommige punten van het kader en de overheidsmaatregelen.

> [!NOTE]
> _Een informatiesysteem is "een samenhangend geheel van gegevensverzamelingen, en de daarbij behorende personen, procedures, processen en programmatuur alsmede de voor het informatiesysteem getroffen voorzieningen voor opslag, verwerking en communicatie". Het gaat dus expliciet niet alleen om technische (ICT) systemen, maar informatie en organisatie._

## Verplichtingen BIO

De BIO stelt de volgende verplichtingen aan overheidsorganisaties:

- **NEN-EN-ISO/IEC 27001 moet worden toegepast op het formuleren van eisen voor het vaststellen, implementeren, bijhouden en continu verbeteren van een managementsysteem voor informatiebeveiliging en het vaststellen van het toepassingsgebied (de reikwijdte) van dit managementsysteem.**
Voor het bepalen van de context van de organisatie neemt de organisatie minimaal de beschreven context uit de BIO bij het inrichten, implementeren, in stand houden en continu verbeteren van het managementsysteem voor informatiebeveiliging.

- **NEN-EN-ISO 27002 én de verplichte overheidsspecifieke maatregelen en richtlijnen uit de BIO moet worden toegepast op het formuleren van beheersmaatregelen.**
Hierbij wordt rekening gehouden met de omgeving(en) waarin de informatiebeveiligingsrisico’s gelden. De maatregelen uit de NEN-ISO/IEC 27002 en de BIO kunnen, waar nodig én gelijkwaardig worden vervangen of gecombineerd met beheersmaatregelen uit andere normen en richtlijnen, zoals voor zorginformatie de **NEN 7510** en voor Operationele Technology (OT) de **CSIR** en IEC 62443 Industriële cybersecurity.

- **Organisaties moeten opzet, bestaan en werking van de maatregelen aantonen.** Deze vereiste volgt ook uit de Cbw/Network and Information Security directive 2 (NIS2). De BIO omvat maatregelen op tactisch niveau. Dit betekent dat de maatregelen eerst geoperationaliseerd moeten worden voordat ze geïmplementeerd kunnen worden. Deze implementatie is risicogericht en voldoet aan best practices en marktstandaarden. Onderdeel van de operationalisatie is ook het kunnen detecteren of de maatregel goed functioneert. Over het hele ontwerp wordt geborgd dat uitval van één maatregel niet leidt tot een directe kwetsbaarheid in het hele systeem.

Hoe de maatregelen zijn geoperationaliseerd wordt, via verwijzingen, vastgelegd. Hiermee toont een organisatie ‘opzet’ van maatregelen aan. Via self-assessments, audits, pentesten, redteam-testen en dergelijke. Al dan niet met behulp van externe partijen, toont een organisatie het ‘bestaan’ en de ‘werking’ aan van maatregelen.

- **Er bestaan beheersmaatregelen zonder overheidsmaatregelen.** Als een dergelijke beheersmaatregel van toepassing is, moet gebruik gemaakt worden van de bijbehorende implementatieaanwijzing uit NEN-EN-ISO/IEC 27002. Afwijken of niet toepassen van bovenliggende beheersmaatregel moet worden onderbouwd met een risicoanalyse en de referentie naar deze analyse moet in een bijlage uitzonderingen opgenomen zijn in de Verklaring van Toepasselijkheid (VvT).

- **Een beheersmaatregel kan een of meerdere overheidsmaatregelen hebben.** Deze overheidsmaatregelen vormen de minimale invulling van de beheersmaatregel. Uit een risicoanalyse moet blijken of deze voldoende zijn om het risico te beheersen en tot een acceptabel niveau verlagen.

## Het managementsysteem voor informatiebeveiliging

Het managementsysteem voor informatiebeveiliging (Information Security Management Systeem, ook wel ISMS) is een werkwijze om informatiebeveiliging op een gestructureerde manier toe te passen in de organisatie. Zo wordt de organisatie, en een bestuurder in het bijzonder, in staat gesteld om de juiste afwegingen te maken. 

> [!Note]
> _Om een veelvoorkomend misverstand te voorkomen: een managementsysteem is géén applicatie. Een applicatie kan wel ondersteunen bij het toepassen van een managementsysteem._

De BIO schrijft voor dat het managementsysteem van een organisatie voldoet aan NEN-EN-ISO/IEC 27001. Bij het bepalen van de reikwijdte van het managementsysteem moet een organisatie minimaal de bedrijfsprocessen en informatiesystemen opnemen die kritisch zijn voor haar dienstverlening, waarbij aantasting van de beschikbaarheid, integriteit of vertrouwelijkheid zou leiden tot onacceptabele impact.

Het managementsysteem voor informatiebeveiliging borgt de beschikbaarheid, integriteit en vertrouwelijkheid van informatie door een risicomanagementproces toe te passen. Dit geeft belanghebbenden het vertrouwen dat risico’s adequaat worden beheerst.

Het is belangrijk dat het managementsysteem voor informatiebeveiliging deel uitmaakt van en geïntegreerd is met de procedures van de organisatie en met de algehele managementstructuur, en dat informatiebeveiliging in aanmerking wordt genomen bij het ontwerpen van processen, informatiesystemen en beheersmaatregelen. 

### Reikwijdte managementsysteem 

Bij het bepalen van de reikwijdte van het managementsysteem moet een organisatie minimaal de bedrijfsprocessen en informatiesystemen opnemen die kritisch zijn voor haar dienstverlening. Het is aan de overheidsorganisaties zelf om te bepalen in welke mate de ondersteunende processen zijn opgenomen in het managementsysteem. 

Waar overheden gelijkwaardige processen hanteren, is het aanbevolen om, waar beschikbaar, gebruik te maken van het ondersteuningsaanbod van de koepelorganisatie. 

### Samenhang managementsystemen 

De BIO sluit aan op de [Harmonized Structure (HS)](https://www.nen.nl/managementsystemen/high-level-structure-hls), wat een consistente en uniforme structuur biedt voor managementsystemen, waardoor de integratie van verschillende ISO-normen voor managementsystemen wordt vereenvoudigd. Hierdoor wordt dubbel werk voorkomen en middelen efficiënter gebruikt. Het biedt uniformiteit bij de implementatie van verschillende ISO-managementsystemen en vereenvoudigt de integratie van deze systemen.

## Risicomanagement

Risicomanagement is een kernonderdeel van NEN-EN-ISO 27001 en vormt ook de basis van de BIO-aanpak binnen de overheid. De processen zijn ontworpen om risico's systematisch te identificeren, beoordelen, beheersen en continu te monitoren. Het risicomanagementproces verloopt in hoofdlijnen als volgt:
1.	Contextbepaling
2.	Risico-identificatie
3.	Risicoanalye
4.	Risicobehandeling en maatregelenselectie
5.	Risicomanagementmethodiek

### Contextbepaling

Volgens NEN-EN-ISO/IEC 27001 moet een organisatie eerst haar context vaststellen om relevante informatiebeveiligingsrisico’s te identificeren. De BIO vereist hierbij dat overheidsorganisaties minimaal de in de BIO beschreven context meenemen, waaronder de sector 'Overheid' en de specifieke informatiebeveiligingseisen. Dit omvat zowel interne als externe factoren die invloed hebben op de beveiliging van informatie(systemen), en de daarmee samenhangende wettelijke verplichtingen uit de Cbw.

### Risico-identificatie

In deze stap inventariseert de organisatie potentiële risico's voor haar informatie(systemen), waarbij gebruik wordt gemaakt van NEN-EN-ISO/IEC 27001 en specifieke overheidsmaatregelen uit de BIO. Voorbeelden hiervan zijn risico’s die voortkomen uit ketenafhankelijkheden,  OT, of gegevensuitwisseling met zorginstellingen. De BIO biedt hierbij richtlijnen die relevant zijn voor overheidsspecifieke omgevingen, zoals de Cybersecurity Implementatierichtlijn (CSIR) voor OT.

### Risicoanalyse

De geïdentificeerde risico's worden vervolgens geanalyseerd en geclassificeerd op basis van hun waarschijnlijkheid en impact. Gebruik in dit proces de NEN-EN-ISO/IEC 27001-methoden voor het uitvoeren van risicoanalyses, ondersteund door richtlijnen uit de BIO. Het classificeren van risico's draagt bij aan een consistent beeld van de risicoprioriteiten binnen de organisatie en de overheid als geheel.

### Risicobehandeling en maatregelenselectie

Op basis van de risicoanalyse selecteer passende beheersmaatregelen om risico's te mitigeren. De NEN-EN-ISO/IEC 27001 biedt een reeks beheersmaatregelen, die nader uitgewerkt zijn in NEN-EN-ISO/IEC 27002. De BIO vult deze aan met verplicht toe te passen overheidsmaatregelen die aansluiten op de context van de overheid. Deze overheidsmaatregelen zijn altijd verplicht en kunnen ongeacht de risico inschatting van de organisatie niet geaccepteerd worden, tenzij ze niet van toepassing kunnen zijn.

### Risicomanagementmethodiek

Een organisatie moet een risicomanagementmethodiek kiezen en toepassen (zie ook beheersmaatregel 5.08 en 5.12). Een risicomanagementmethodiek omvat ten minste de volgende onderdelen:
* Een quickscan om te bepalen of het basisniveau toereikend is of dat aanvullende maatregelen noodzakelijk zijn en waarin de classificatie van een proces en een informatiesysteem wordt uitgevoerd.
* Een methode voor een volledige risicoanalyse om te komen tot aanvullende maatregelen.
* Een risicoregister met daarin de tijdelijk geaccepteerde risico’s.
* Een proces voor opvolging van risico’s om tijdelijk geaccepteerde risico’s structureel op te lossen.

### Verklaring van toepasselijkheid (VvT)

NEN-EN-ISO/IEC 27001 vereist dat organisaties een VvT (statement of applicability) opstellen, waarin zij de geselecteerde beheersmaatregelen vastleggen en toelichten welke maatregelen zijn geïmplementeerd. Voor overheidsorganisaties geldt dat zij hierin ook de BIO-overheidsmaatregelen expliciet opnemen. Eventuele afwijkingen of niet-toepasbare beheersmaatregelen moeten in een bijlage ‘Uitzonderingen’ op de VvT worden opgenomen. 

### Monitoring en continue verbetering 

NEN-EN-ISO/IEC 27001 en de BIO leggen de nadruk op een continu verbeterproces. Een organisatie dient haar risicomanagement te onderhouden en regelmatig te evalueren om de effectiviteit van beheersmaatregelen te waarborgen. Eventuele wijzigingen in wetgeving of nieuwe bedreigingen kunnen aanleiding geven tot het bijwerken van de risicoanalyse en beheersmaatregelen. Met interne audits, managementbeoordelingen en een gestroomlijnde documentatie binnen het Information Security Management System (ISMS) houdt de organisatie haar risicomanagement actueel.

### Samenstelling overheidsmaatregelen

De set overheidsmaatregelen vormt een eerste stap naar een goed niveau van informatiebeveiliging voor elke (overheids)organisatie en moet zonder meer worden geïmplementeerd, ongeacht de mate van risico-acceptatie, tenzij een overheidsmaatregel niet van toepassingen kan zijn. Deze set bestaat uit basismaatregelen, aangevuld met ketenmaatregelen en maatregelen specifiek voor overheidsrisico’s. Het doel is hiermee een minimumstandaard te waarborgen`. Overheidsmaatregelen zijn ingedeeld naar de volgende categoriën:

- **Basishygiëne**: aan deze maatregelen dient minimaal voldaan te worden om aan NIS2 te kunnen voldoen.

- **Ketenhygiëne**: maatregelen die bijdragen aan het mitigeren van risico’s in de keten van overheden en waarbij gezamenlijk handelen door de overheid nodig is.

- **Overheidsrisico’s:** mitigeren van universele informatieveiligheidsrisico’s die gelden voor de gehele overheid.

### Continue ontwikkeling

Informatiebeveiliging is een cyclisch proces. De BIO kan niet afgedaan worden met een eenmalig project. Door het toepassen van een managementsysteem blijft een organisatie continu ontwikkelen en verbeteren.

## Transparantie en verantwoording

Burgers moeten de overheid kunnen vertrouwen. Dit wordt bereikt door transparant te zijn over de inrichting en de staat van informatieveiligheid en daar verantwoording over af te leggen aan burgers, toezichthouders, ketenpartners en stelselverantwoordelijken.

Een managementsysteem voor informatiebeveiliging (ISMS) is een belangrijke manier om gestructureerde verantwoording te ondersteunen. 

Het is vanuit NEN-EN-ISO/IEC 27001 verplicht om een reikwijdte, ook wel scope, van het ISMS en een zogenaamde VvT te hanteren. Het publiceren van de reikwijdte van het ISMS en de bijbehorende VvT draagt bij aan transparantie over de inrichting van informatiebeveiliging door de overheid. Niet publiceren van deze informatie zou een onnodige drempel opwerpen voor burgers. Het publiceren van de reikwijdte en de VvT is daarom verplicht voor een overheidsorganisatie. 
Een voorbeeld van een VvT wordt opgenomen in deel 3 van de BIO2 \[moet ontwikkeld worden\].

## Toezicht 

De BIO-aanpak is de basis voor het invullen van zorgplicht van de Cbw door overheden. NEN-EN-ISO/IEC 27001 en 27002 vormen de basis van de BIO. Het is aangeraden voor toezichthouders om deze standaarden te hanteren. De elementen uit het ISMS vormen de basis om het managementsysteem te toetsen, inclusief de verplichte overheidsmaatregelen uit de BIO.

De BIO verplicht geen NEN-EN-ISO/IEC 27001-certificering. Certificering draagt wel bij aan het vereenvoudigen van de verantwoording en geeft op basis van een onafhankelijke beoordeling aan dat de organisatie in staat is om informatiebeveiliging procesmatig uit te voeren.

## Toepasselijke overige normen, wet- en regelgeving

De BIO bevat overheidsmaatregelen die in lijn zijn met andere wet- en regelgeving, maar is daarin zeker niet uitputtend.

De BIO is expliciet niet bedoeld om alle beveiligingseisen van de overheid af te dekken. De verschillende overheidslagen hebben te maken met specifieke dreigingen. Het staat ze vrij om voor hun overheidslagen specifieke aanvullende maatregelen te benoemen en die, afhankelijk van de interne besluitvorming, verplichtend of adviserend door te voeren. Daarnaast is elke overheidsorganisatie zelf verantwoordelijk om vast te stellen welke interne en externe eisen, waaronder ook wet- en regelgeving, van toepassing zijn.

Binnen de overheid bestaan meerdere normen voor informatiebeveiliging. Naast de BIO zijn er bijvoorbeeld de Nederlandse normen NEN 7510 Informatiebeveiliging in de zorg voor verwerkers van zorginformatie, NEN-EN-ISO 22301 Managementsystemen voor bedrijfscontinuïteit en crisismanagement en de CSIR voor OT. De basis van die normen is de internationale norm NEN-EN-ISO/IEC 27001 en NEN-EN-ISO/IEC 27002. Managementsystemen en beheersmaatregelen volgens deze normen kunnen worden geïntegreerd in een managementsysteem voor informatiebeveiliging op basis van NEN-EN-ISO/IEC 27001. Daarmee vallen de twee onderdelen samen: risicomanagement en maatregelen die specifiek passen bij de context. 

### Cyberbeveiligingswet (Cbw)

Voor overheden is in de Cbw vastgelegd op welke wijze de zorgplicht voor informatiebeveiliging moet worden ingevuld. Hieronder volgt een samenvatting van de belangrijkste punten die betrekking hebben op het toepassen van de BIO:

- **Verplichting BIO**: de BIO is via de Cbw verplicht voor alle overheden die vallen onder de sector 'Overheid'.   

- **Verantwoordelijkheid bestuurder**: de bestuurder is verantwoordelijk voor:
	* het treffen van passende en evenredige technische, operationele en organisatorische maatregelen om de risico’s te beheren en afgestemd op de voor de organisatie relevante risico’s en deze beheersen;
	* het goedkeuren van te nemen maatregelen voor het beheer van cyberbeveiligingsrisico’s; 
	* het toezien op de kwaliteit van de uitvoering en het beheer van de maatregelen.

- **Opleiding**: bestuurders moeten opgeleid zijn en kennis hebben om te kunnen sturen op informatiebeveiliging-risico's. En bestuurders moeten ervoor zorgen dat hun werknemers regelmatig opleiding/training volgen aangaande het onderwerp. Dit betekent dat de opleiding moet voldoen aan \[invulling Cbw voor de sector 'Overheid'\].

- **Meldplicht:** bestuurders zijn verantwoordelijk voor het tijdig melden van incidenten. Overheden moeten binnen de doorlooptijden \[invulling Cbw voor de sector 'Overheid'\] een melding maken van een meldplichtig incident.

- **Toezicht en verantwoording:** de toezichthouder zal toezicht houden op de invulling van de zorgplicht volgens de Cbw. De RDI is als toezichthouder aangewezen voor de sector 'Overheid'.  

## Governance

De bestuurder van een overheidsorganisatie is verantwoordelijk voor het beheersen van informatiebeveiligingsrisico's. De bestuurder kan dat niet alleen. Om informatiebeveiliging gedegen in te regelen, is een structuur nodig. Het is aan de organisatie om deze structuur aan te brengen volgens NEN-EN-ISO/IEC 27001.

Voor overheden zijn er een aantal rollen die standaard deel uitmaken van informatiebeveiliging van een overheidsorganisatie. Deze rollen komen ook terug in de uitwerking van overheidsmaatregelen.

### Bestuurder

De bestuurder is verantwoordelijk voor het treffen van passende en evenredige technische, operationele en organisatorische maatregelen en moet toezien op de naleving daarvan. Kortgezegd de bestuurder is verantwoordelijk voor risicomanagement, dat gericht is op het borgen van digitale weerbaarheid van de organisatie.  
Voor de vier overheidslagen is voor de invulling van sector 'Overheid' binnen de Cbw gedefinieerd welke bestuurders worden bedoeld:

- Gemeenten: \[Volgt uit invulling Cbw voor sector 'Overheid'\]
- Provincies: \[Volgt uit invulling Cbw voor sector 'Overheid'\]
- Rijksoverheid: \[Volgt uit invulling Cbw voor sector 'Overheid'\]
- Waterschappen: \[Volgt uit invulling Cbw voor sector 'Overheid'\]

De bestuurder laat zich daarbij adviseren door een Chief Information Security Officer (CISO), Chief Information Officer (CIO) en functionaris gegevensbescherming (FG) en dergelijke.

### Lijnmanagement

Het lijnmanagement is eigenaar van informatie(systemen) en is daarmee verantwoordelijk voor het identificeren van dreigingen en risico's ten aanzien van deze informatie(systemen).
Het lijnmanagement is verantwoordelijk voor het toepassen van verplichte beheersmaatregelen en overheidsmaatregelen uit de BIO voor het informatiesysteem. In alle gevallen waar het lijnmanagement afwijkt van overheidsmaatregelen, ook waar dat expliciet als bevoegdheid genoemd is, vraagt het lijnmanagement aan de CISO om advies.

### CISO

De CISO:
- is verantwoordelijk voor de coördinatie van informatiebeveiliging; 
- ondersteunt de bestuurder en moet gevraagd en ongevraagd advies kunnen geven aan de bestuurder;
- vertaalt wetgeving en bedrijfsdoelstellingen naar een informatiebeveiligingsbeleid; 
- rapporteert aan het bestuur hoe het lijnmanagement het informatiebeveiligingsbeleid implementeert en op welke wijze wordt voldaan aan de BIO, om ervoor zorg te dragen dat de bestuurder geïnformeerde besluiten kan maken over de behandeling van informatiebeveiligingsrisico's; 
- is uitdrukkelijk niet verantwoordelijk voor de informatiebeveiliging door het lijnmanagement. 

### Interne toezichthouder

Een bestuurder moet toezien op de toepassing van informatiebeveiliging in de organisatie. Een interne toezichthouder kan helpen bij dit toezicht. 

## Leveranciers

Leveranciers bieden diensten en/of producten aan overheidsorganisaties. Een overheidsorganisatie blijft zelf verantwoordelijk voor het behandelen van risico's die betrekking hebben op de uitbestede of ingekochte dienst of product.

Afhankelijk van het risico behoren daarom verplichtingen van de overheid die volgen uit de BIO of uit andere richtlijnen te worden meegenomen bij het samenstellen van inkoopeisen aan leveranciers. 

## Informatiebeveiligingsprincipes

Overheidsmaatregelen uit BIO moeten risicogericht worden toegepast en geoperationaliseerd. Daarbij is het praktisch om informatiebeveiligingsprincipes te definiëren en toe te passen zoals security by design & default, toegang op basis van need to know, assume breach, zero trust, shit happens, dingen gaan fout, defense in depth e.d.

## Operationaliseren maatregelen / balans in de maatregelenset

De BIO bevat maatregelen op tactisch niveau, die geoperationaliseerd moeten worden. Hierbij is het belangrijk om in de maatregelenset balans te houden tussen:
- Balans tussen beschikbaarheids-, integriteits-, vertrouwelijkheidsmaatregelen
- Balans tussen organisatorische/proces-, mensen/gedrag, applicatieve/technische maatregelen
- Balans tussen identify, protect, detect, respond, recover

## Treffen aanvullende maatregelen
	
Overheden kennen verschillende soorten informatie. Het is aan de organisatie zelf om te bepalen welk typen informatie wordt verwerkt door de organisatie en welke aanvullende beveiligingsmaatregelen getroffen moeten worden. Bij deze afweging moeten in ieder geval – en niet uitsluitend - de volgende typen gegevens worden afgewogen:
- Open data
- (Bijzondere) persoonsgegevens
- Gevoelige of interne informatie
- Gerubriceerde informatie

## Impact van risico's

De impact van een informatiebeveiligingsincident hangt sterk af van de context. Overheidsorganisaties ondervinden vaak specifieke gevolgen door hun rol in de samenleving en democratie, hun bestuursstijl en hun verhouding tot de burgers. Bij het bepalen van de impact moeten minimaal onderstaande impactsgebieden worden afgewogen: 
- Politieke schade aan een bestuurder
- Diplomatieke schade
- Financiële gevolgen
- Directe imagoschade
    * Verlies van publiek respect of vertrouwen
    * Organisatiebrede negatieve publiciteit
- Significant verlies van motivatie van medewerkers
- Belangrijk verlies van management control

De impactgebieden kunnen ook bijdragen aan begrip bij de uitwisseling van impact met ketenpartners.

## Relatie BIO en andere onderwerpen

De BIO richt zich op informatiebeveiliging. Onderwerpen zoals privacybescherming, informatievoorziening, beheersprocessen en bedrijfscontinuïteit zijn aanpalend aan informatiebeveiliging. Voor deze onderwerpen zijn vaak aparte standaarden opgezet. Deze onderwerpen worden daarom niet uitgewerkt in de BIO. Daar waar nuttig wordt verwezen naar deze separate standaarden.  

## Dankwoord

Wij danken iedereen die direct of indirect heeft bijgedragen aan de totstandkoming van de BIO2. In willekeurige volgorde danken wij de vertegenwoordigers van de koepels (Vereniging van Nederlandse Gemeenten, Interprovinciaal Overleg, Unie van Waterschappen), Chief Information Security Officer (CISO’s) van overheidsorganisaties, de Auditdienst Rijk (ADR), de Rijksinspectie Digitale Infrastructuur (RDI), medewerkers van ministeries, het Nationaal Cyber Security Centrum (NCSC), het Centrum Informatiebeveiliging en Privacybescherming (CIP), de informatiebeveiligingsdienst voor gemeenten (IBD), bestuurders en functionarissen van overheden en alle anderen die hebben bijgedragen.

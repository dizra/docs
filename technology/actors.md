---
description: >-
  Deze pagina beschrijft de systeemactoren en de functies van iedere actor.
---

# Systeemactoren en haar systeemfuncties

Iedere deelnemer kan één of meerdere systeemrollen in het ecosysteem vervullen. Wat de deelnemer is bepaalt "wat" voor data en services zij aanbiedt. Het "hoe" wordt bepaalt door de systeemrol die zij heeft. We onderkennen primaire systeemrollen en ondersteunende systeemrollen. De primaire systeemrollen zijn de rollen van deelnemers. De ondersteunende systeemrollen zijn rollen die nodig zijn om het systeem te laten werken, zodat een afnemer een aanbieder van data kan vinden of kan vertrouwen bijvoorbeeld.

Op deze pagina beschrijven we de systeemrollen en de functies waarvoor een systeemrol verantwoordelijk is.

## Aanbieder

Een **aanbieder** van data en services is een rol van een deelnemende organisatie die data en services in het ecosysteem vindbaar, interoperabel en toegankelijk maakt voor hergebruik. Cliënten hebben niet de rol van aanbieder, zij zijn gegevensregisseur en/of gezondheidsregisseur.

![Data vanuit de bron](../.gitbook/assets/motivation/datastation.svg)

Een afnemer heeft de volgende verantwoordelijk:

- **Publicatie van datacatalogus**; een aanbieder moet haar datacatalogus publiceren voor vindbaarheid.
- **Authenticatie**; een aanbieder moet een actor in het ecosysteem kunnen authenticeren.
- **Autorisatie**; een aanbieder moet een actor in het ecosysteem kunnen autoriseren.
- **Veilige communicatie** tussen actoren en aanbieder.
- **Publicatie van data en services** aan de geautoriseerde actoren in het ecosysteem overeenkomstig de ontologie van het domein van de deelnemer die de rol van aanbieder heeft.
- **Beantwoording in de taal van het domein**; een aanbieder moet de beantwoording doen in de ontologie van het domein.
- **Verificatie van de geldigheid van een bewijs** die verkregen is van een actor in het ecosysteem.
- **Verantwoording** over de toegang, uitwisseling van data met, en gebruik van services door het ecosysteem; een aanbieder moet al haar activiteiten loggen.

## Afnemer

Een afnemer is een rol van een deelnemende organisatie die data en services afneemt van een aanbieder. Cliënten hebben niet de rol van afnemer, zij zijn gegevensregisseur en/of gezondheidsregisseur.

Een afnemer heeft de volgende verantwoordelijk:

- **Bewijslast identiteit**; een afnemer moet tegenover een andere deelnemer haar identiteit kunnen bewijzen. Een identiteit kan in deze zowel een identificerend nummer zijn als een ander attribuut gerelateerd aan de identiteit, bijvoorbeeld de naam van de organisatie.
- **Bewijslast rechtmatigheid verwerking persoonsgegevens**; een afnemer moet tegenover een aanbieder kunnen bewijzen dat gegevensuitwisseling van persoonsgegevens rechtmatig is. Een aanbieder kan op basis van het bewijs een afnemer toegang geven.
- **Bewijslast deelnemer aan het informatiestelsel**; een afnemer moet kunnen bewijzen dat zij een rechtmatige deelnemer is aan het informatiestelsel, waaronder het bewijs dat zij aan alle voorwaarden voldoet.
- **Vindbaar voor berichten**; een afnemer moet vindbaar zijn voor berichten zoals notificaties.
- **Vraagstelling in de taal van het domein**; een afnemer moet de vraagstelling doen in de ontologie van het domein.
- **Verantwoording** over het gebruik van data en services in het ecosysteem; een afnemer moet al haar activiteiten loggen.

## Gegevensautoriteit

Een gegevensautoriteit is een rol van een organisatie. Het is een erkenning van die organisatie in het informatiestelsel dat zij de bron is voor een gegevensattribuut, bijvoorbeeld een identificatie of een kwalificatie (zoals de kwalificatie dat een organisatie een zorgaanbieder is). Het belang van een gegevensautoriteit en haar erkenning is met name van belang als de gegevens gebruikt worden voor bewijsvoering.

Een gegevensautoriteit heeft de volgende verantwoordelijk:

- **Uitgifte van een verklaring** zoals een artsenverklaring, een bewijs van registratie, een derdenverklaring of een bewijs van identiteit. Ook voor de herkomst van gegevens kan een verklaring gewenst zijn dat een organisatie de gegevens oorspronkelijk heeft uitgegeven.
- **Publicatie van de publieke sleutels** van de gegevensautoriteit zodat de elektronische handtekening van een gegevensautoriteit kan worden geverifieerd.
- **Registratie en publicatie van het schema met attributen in de verklaring** voor controle op volledigheid van de verklaring.
- **Registratie en publicatie van de status van een verklaring** voor verificatie van geldigheid van een verklaring.

## Gegevensregisseur

De gegevensregisseur is een rol van de cliënt. De locatie van de gegevens van een persoon, veelal weergegeven in een tijdlijn, worden via de cliënt toegankelijk gemaakt. Toegang kan verkregen zijn door gegevensuitwisseling via de cliënt of door gegevensuitwisseling met toestemming van de cliënt. Een gegevensregisseur moet ook de mogelijkheid hebben om vooraf gegevens klaar te zetten in het geval van spoedeisende hulp.

![Vormen van regie op gegevens](../.gitbook/assets/motivation/self-or-consent.svg)

Een gegevensregisseur kan de volgende verantwoordelijk hebben:

- **Toestemming verlenen** voor een gegevensuitwisseling tussen deelnemers aan het informatiestelsel.
- **Verklaringen ontvangen, veilig houden en presenteren**. Hiermee kan een cliënt gegevens meenemen en zelf verstrekken aan een deelnemer in het ecosysteem.
- **Weergave van een tijdlijn** van gebeurtenissen in de zorg en ondersteuning. De tijdlijn is een verzameling referenties naar gebeurtenissen in de zorg en ondersteuning. Met alle ontvangen verklaringen kan de tijdlijn worden gerealiseerd.

## Gegevensgids

Een gegevensgids is een leverancier van een index van datacatalogussen voor de vindbaarheid van gegevens en services. Samen met andere leveranciers van indexen maakt zij afspraken over de standaarden voor het vinden van data en services. Een aanbieder van het ecosysteem moet haar datacatalogus laten indexeren om vindbaar te zijn.

Een gegevensgids heeft de volgende verantwoordelijk:

- **Indexeren van datacatalogussen**; een gegevensgids moet de datacatalogussen indexeren van alle aanbieders in het ecosysteem (of van alle aanbieders in een domein).
- **Doorzoekbaar maken van de index**; een gegevensgids moet de indexering van datacatalogussen doorzoekbaar maken voor de deelnemers in het ecosysteem.

## Gezondheidsregisseur

De gezondheidsregisseur is eveneens een rol van de cliënt. De nadruk bij de gezondheidsregisseur ligt op het gebruik van gegevens voor je persoonlijke gezondheid (regie op gezondheid) terwijl de nadruk van een gegevensregisseur ligt op regie op gegevens.

Een gezondheidsregisseur kan de volgende verantwoordelijk hebben:

- **Regie op gezondheid** overeenkomstig de functies van een persoonlijke gezondheidsomgeving.

## Vertrouwensleverancier

Een vertrouwensleverancier levert samen met andere vertrouwensdienstverleners een infrastructuur voor publieke sleutels en andere data voor de verificatie van de geldigheid en herkomst van gegevens. De vertrouwensleveranciers maken samen afspraken over de standaarden die zij hanteren.

Een vertrouwensleverancier heeft de volgende verantwoordelijk:

- **Registratie van publieke sleutels** en de identificatie horende bij de publieke sleutel. Met de publieke sleutel kan een ontvanger van de verklaring verifiëren dat de verklaring afkomstig is van een gegevensautoriteit.
- **Registratie en publicatie van de lijst met vertrouwde gegevensautoriteiten**, oftewel de uitgevers van de verklaringen.

Heronder beschrijven we het vertrouwensmodel voor het ecosysteem en de rol van de vertrouwensleverancier hierin. Vertrouwen is geen automatisme. Mensen en organisaties moeten geloof hebben in het systeem. We kiezen daarom voor een robuust vertrouwensmodel opp basis van cryptografie. De bron van het vertrouwensmodel is [Trust Over IP](https://trustoverip.org) zoals hieronder weergegeven.

![Het vertrouwensmodel en de lagen van Trust Over IP](../.gitbook/assets/ToIP-stack-with-quadrant-labels-2020-05-06.png)In het Trust Over IP vertrouwensmodel zijn 4 lagen onderkend. De lagen zijn van onder naar boven beschreven.

### 1. Een cryptografische basis

Het toepassen van cryptografie vereist een public key infrastructure (PKI). Traditioneel is een PKI geïmplementeerd met certificaten van een certificaatautoriteit (CA), bijvoorbeeld PKIOverheid. Een alternatief is een decentrale public key infrastructure (DPKI). Hierin zijn de publieke sleutels gepubliceerd in een blockchain, in een gedistribueerd grootboek, een decentraal bestandssysteem of in ieder andere voorziening waarmee het noodzakelijke vertrouwen kan worden geborgd.

Een vertrouwensleverancier levert samen met andere vertrouwensleveranciers de (decentrale) public key infrastructure voor de cryptografische basis van het ecosysteem. Het zijn bestaande infrastructuren waarvoor afgesproken moet zijn dat ze vertrouwd zijn. Door middel van een vertrouwenslijst kunnen de vertrouwde infrastructuren (en daarmee de vertrouwensleveranciers) gepubliceerd worden.

### 2: Veilige elektronische communicatie

De communicatie tussen deelnemers moet veilig zijn. Dat wordt gerealiseerd door enerzijds afspraken over standaarden voor bijvoorbeeld de versleuteling van het berichtenverkeer en anderzijds door afspraken over de uitwisselingssystemen die vertrouwd zijn.

### 3: Betrouwbare verklaringen

Gegevens moeten betrouwbaar zijn om hergebruikt te worden. Daarom zijn afspraken nodig om een deelnemer als gegevensautoriteit te erkennen. Maar ook om de betrouwbaarheid te blijven verzekeren.

### 4: Het ecosysteem voor de zorg

De afspraken voor een ecosysteem zijn afspraken over het informatiestelsel in de zorg. Afspraken over de deelnemers aan het ecosysteem en de actoren. Het brengt de afspraken samen en maakt mogelijk keuzes voor vertrouwensleveranciers, voor softwareleveranciers met uitwisselingssystemen, voor gegevensautoriteitem en borgt het vertrouwen in deze partijen door middel van bijvoorbeeld audits.

## Operationeel beheerder

De operationeel beheerder bewaakt het ecosysteem of een deel van het ecosysteem. Een operationeel beheerder kan ook een gezamenlijke helpdesk vormen. De operationeel beheerder kan voor een keten of samenwerkingsverband worden ingericht indien daar behoefte en een business case voor is.

Een operationeel beheerder heeft de volgende verantwoordelijk:

- Een **gemeenschappelijke helpdesk**;
- **Verzekeren van de kwaliteit en de betrouwbaarheid** van het ecosysteem.

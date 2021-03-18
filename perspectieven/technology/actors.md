---
description: >-
  Deze pagina beschrijft de systeemactoren en de functies van iedere actor.
---

# Systeemactoren en haar systeemfuncties

Iedere deelnemer kan één of meerdere systeemrollen in het ecosysteem vervullen. Wat de deelnemer is bepaalt "wat" voor data en services zij aanbiedt. Het "hoe" wordt bepaalt door de systeemrol die zij heeft. We onderkennen primaire systeemrollen en ondersteunende systeemrollen. De primaire systeemrollen zijn de rollen van deelnemers. De ondersteunende systeemrollen zijn rollen die nodig zijn om het systeem te laten werken, zodat bijvoorbeeld een afnemer een bronhouder van data kan vinden of kan vertrouwen. In het figuur hieronder zijn de systeemrollen en hun samenhang weergegeven.

![Samenhang tussen systeemactoren](../../.gitbook/assets/actorcoherence.svg)

Op deze pagina beschrijven we de systeemrollen en de functies waarvoor een systeemrol verantwoordelijk is.

## Bronhouder

Een **bronhouder** is een rol van een deelnemende organisatie die data en services in het ecosysteem vindbaar, interoperabel en toegankelijk maakt voor hergebruik. Cliënten hebben niet de rol van bronhouder, zij zijn gegevensregisseur en/of gezondheidsregisseur.

![Data vanuit de bron](../../.gitbook/assets/datastation.svg)

Een afnemer heeft de volgende verantwoordelijkheid:

- **Publicatie van datacatalogus**; een bronhouder moet haar datacatalogus publiceren voor vindbaarheid.
- **Authenticatie**; een bronhouder moet een actor in het ecosysteem kunnen authenticeren.
- **Autorisatie**; een bronhouder moet een actor in het ecosysteem kunnen autoriseren.
- **Veilige communicatie** tussen actoren en bronhouder.
- **Publicatie van data en services** aan de actoren in het ecosysteem overeenkomstig de ontologie van het domein.
- **Beantwoording in de taal van het domein**; een bronhouder moet de beantwoording doen in de ontologie van het domein.
- **Verificatie van de geldigheid van een bewijs** die verkregen is van een actor in het ecosysteem.
- **Verantwoording** over de toegang, uitwisseling van data met, en gebruik van services door het ecosysteem; een bronhouder moet al haar activiteiten loggen.

## Auditor

Een auditor is een rol uit de besturing van het informatiestelsel. Voor het ecosysteem voert zij audits uit en geeft derdenverklaringen uit. We hebben de rol in deze pagina opgenomen om een volledig beeld te geven van alle partijen die betrokken zijn in het vertrouwen. Een auditor kan een bevoegde uitgever zijn voor de derdenverklaring in het ecosysteem.

## Afnemer

Een afnemer is een rol van een deelnemende organisatie die data en services afneemt van een bronhouder. Cliënten hebben niet de rol van afnemer, zij zijn gegevensregisseur en/of gezondheidsregisseur.

Een afnemer heeft de volgende verantwoordelijkheid:

- **Bewijslast identiteit**; een afnemer moet tegenover een andere deelnemer haar identiteit kunnen bewijzen. Een identiteit kan in deze zowel een identificerend nummer zijn als een ander attribuut gerelateerd aan de identiteit, bijvoorbeeld de naam van de organisatie.
- **Bewijslast rechtmatigheid verwerking persoonsgegevens**; een afnemer moet tegenover een bronhouder kunnen bewijzen dat gegevensuitwisseling van persoonsgegevens rechtmatig is. Een bronhouder kan op basis van het bewijs een afnemer toegang geven.
- **Bewijslast deelnemer aan het informatiestelsel**; een afnemer moet kunnen bewijzen dat zij een rechtmatige deelnemer is aan het informatiestelsel, waaronder het bewijs dat zij aan alle voorwaarden voldoet.
- **Vindbaar voor berichten**; een afnemer moet vindbaar zijn voor berichten zoals notificaties.
- **Vraagstelling in de taal van het domein**; een afnemer moet de vraagstelling doen in de ontologie van het domein.
- **Verantwoording** over het gebruik van data en services in het ecosysteem; een afnemer moet al haar activiteiten loggen.

## Bevoegde uitgever van verklaringen

Een bevoegde uitgever is een rol van een organisatie of persoon. Het is een erkenning dat zij bevoegd is voor het uitgeven van een verklaring, bijvoorbeeld een identificatie of een kwalificatie.

Een bevoegde uitgever heeft de volgende verantwoordelijkheid:

- **Uitgifte van een verklaring** zoals een bewijs van registratie of identiteit.
- **Veilige opslag van de private sleutel** waarmee de bevoegde uitgever een verklaring elektronisch ondertekent.
- **Publicatie van de publieke sleutels** van de bevoegde uitgever zodat de elektronische handtekening van de bevoegde uitgever kan worden geverifieerd. De publieke sleutel wordt bij een vertrouwensleverancier geregistreerd en via de voorziening van deze leverancier gepubliceerd.
- **Registratie en publicatie van het schema met attributen in de verklaring** voor controle op volledigheid van de verklaring.
- **Registratie en publicatie van de status van een verklaring** voor verificatie van geldigheid van een verklaring.

## Gegevensgids

Een gegevensgids is een leverancier van een doorzoekbare index van datacatalogussen voor de vindbaarheid van data en services. Samen met andere gegevensgidsen maakt zij afspraken over de standaarden voor het vinden van data en services. Een bronhouder in het ecosysteem moet haar datacatalogus laten indexeren om vindbaar te zijn.

Een gegevensgids heeft de volgende verantwoordelijkheid:

- **Indexeren van datacatalogussen**; een gegevensgids moet de datacatalogussen indexeren van alle bronhouders in het ecosysteem \(of van alle bronhouders in een domein\).
- **Doorzoekbaar maken van de index**; een gegevensgids moet de indexering van datacatalogussen doorzoekbaar maken voor de deelnemers in het ecosysteem.

## Gegevensregisseur

De gegevensregisseur is een rol van een cliënt. De locatie van de gegevens van een persoon, veelal weergegeven in een tijdlijn, worden via de cliënt toegankelijk gemaakt. Toegang kan verkregen zijn door gegevensuitwisseling via de cliënt of door gegevensuitwisseling met toestemming van de cliënt. Een gegevensregisseur moet ook de mogelijkheid hebben om vooraf gegevens klaar te zetten in het geval van spoedeisende hulp.

![Vormen van regie op gegevens](../../.gitbook/assets/self-or-consent.svg)

Een gegevensregisseur kan de volgende verantwoordelijkheid invullen:

- **Toestemming verlenen** voor een gegevensuitwisseling tussen deelnemers aan het informatiestelsel.
- **Verklaringen ontvangen, veilig houden en presenteren**. Hiermee kan een cliënt gegevens meenemen en zelf verstrekken aan een deelnemer in het ecosysteem.
- **Weergave van een tijdlijn** van gebeurtenissen in de zorg en ondersteuning. De tijdlijn is een verzameling referenties naar gebeurtenissen in de zorg en ondersteuning. Met alle ontvangen verklaringen kan de tijdlijn worden gerealiseerd.

## Gezondheidsregisseur

De gezondheidsregisseur is eveneens een rol van een cliënt. De nadruk bij de gezondheidsregisseur ligt op het gebruik van gegevens voor je persoonlijke gezondheid \(regie op gezondheid\) terwijl de nadruk van een gegevensregisseur ligt op regie op gegevens.

Een gezondheidsregisseur kan de volgende verantwoordelijkheid invullen:

- **Regie op gezondheid** overeenkomstig de functies van een persoonlijke gezondheidsomgeving.

## Ledenadministratie

Een ledenadministratie registreert de leden in het ecosysteem. Het zijn zowel de deelnemers aan het ecosysteem als de actoren die een gemeenschappelijke voorziening leveren voor de werking van het ecosysteem. In het ecosysteem kunnen meerdere ledenadministraties zijn zoals een ledenadministratie voor zorgaanbieders, een ledenadministratie voor secundaire deelnemers, etc.

Een ledenadministratie heeft de volgende verantwoordelijkheid:

- **Registratie en publicatie van leden**. Ieder lid van het ecosysteem kan door de registratie een ander lid herkennen. Een ledenadministratie kan een bevoegde uitgever zijn in het ecosysteem voor een bewijs van registratie.

## Operationeel ketenbeheerder

De operationeel ketenbeheerder bewaakt een keten in het ecosysteem. Een operationeel ketenbeheerder kan ook een gezamenlijke helpdesk vormen. De operationeel ketenbeheerder kan voor een keten of samenwerkingsverband worden ingericht indien daar behoefte en een business case voor is.

Een operationeel ketenbeheerder heeft minimaal de volgende verantwoordelijkheid:

- Een **gemeenschappelijke helpdesk**.
- **Monitoring** van berichten.

## Stelselbeheerder

De stelselbeheerder is een rol binnen de besturing van het informatiestelsel. Naast haar rol in het stelselmanagement heeft de stelselbeheerder ook een rol in het vertrouwen van het ecosysteem.

De **stelselbeheerder** is verantwoordelijk voor:

- Het **publiceren van een vertrouwenslijst** van vertrouwensleveranciers.
- **Registratie en publicatie van derdenverklaringen** over producten van softwareleveranciers. Met de derdenverklaring verklaart een auditor dat het product voldoet aan de afspraken en gebruikt kan worden voor de implementatie van een \(gemeenschappelijke\) voorziening.
- Het **aanwijzen van de ledenadministratie** voor de deelnemers en de leveranciers van gemeenschappelijke voorzieningen.
- Het **aanwijzen van de verzekeraar betrouwbaarheid** voor de verklaringen.

## Vertrouwensleverancier

Een vertrouwensleverancier levert samen met andere vertrouwensdienstverleners een infrastructuur voor publieke sleutels. De vertrouwensleveranciers maken samen afspraken over de standaarden die zij hanteren.

Een vertrouwensleverancier heeft de volgende verantwoordelijkheid:

- **Registratie van publieke sleutels** en de identificatie horende bij de publieke sleutel. Met de publieke sleutel kan een ontvanger van de verklaring verifiëren dat de verklaring afkomstig is van een bevoegde uitgever.

## Verzekeraar betrouwbaarheid

Een verzekeraar moet inzichtelijk maken welke verklaringen uitgegeven mogen worden door welke organisaties of personen. Met name bij personen kan sprake zijn van een indirecte autorisatie omdat autorisatie verkregen is door een verklaring van een organisatie. Een voorbeeld is de BIG-registratie van een voorschrijver.

De **verzekeraar** is verantwoordelijk voor:

- **Registratie en publicatie van bevoegde uitgevers**. Hierdoor weet een actor in het ecosysteem dat een uitgever bevoegd is voor het uitgeven van een verklaring.

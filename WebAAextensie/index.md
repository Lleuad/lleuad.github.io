# WebAAextensie
- [Feature overzicht](#features)
- [Changelog](#changelog)

<a name="features"></a>
## Features
### Agenda
- Het "Medewerker"-veld wordt automatisch gevuld bij een nieuwe afspraak
- De "Medewerker"-, "Ruimte"- en "Handeling"-velden kleuren rood of groen als ze leeg resp. ingevuld zijn
- De pijltjestoetsen en Hometoets kunnen worden gebruikt voor navigatie
### Bestellingen
- In het overzicht zijn alle bestellingsregels standaard aangevinkt
### HP2
- Hulp bij het invullen van de COSI scores (popup menu van de extensie) *__[nieuw]__*
### Intakeformulier
- Niet-revelante tabbladen zijn verwijderd
- De navigatiebalk schuift mee met de pagina
- Verdiepende vragen worden verborgen als ze niet aan de orde zijn
- Ingevulde velden kleuren groen
- Standaard antwoorden op sommige vragen kunnen worden ingesteld *__[nieuw]__*
### Klantkaart
- Wanneer de cursor op een niet nagekomen afspraakregel rust verschijnt de reden voor niet nakomen *__[nieuw]__*
### Leveringsbonnen
- De terugknop vanuit een leveringsbon of offerte gaan nu altijd terug naar het overzicht van de klant
### Memo's
- Het memoveld heeft nu een spellingscontrole
### Reparaties
- Het maximum toegestaan aantal tekens voor de klachtomschrijving is niet meer te overschrijden
### Overig
- In de navigatiebalk staat "Agenda" boven "Klanten"
- "Agenda", "Klanten", "Inkoop" en "Artikelen" openen een standaard overzicht
- Het standaard aantal weergegeven regels in de verschillende tabellen is instelbaar

<a name="changelog"></a>
## Changelog
### 2.0:
#### Intakeformulier:
   - Autofill voor "Verwachting/wensen"
   - Autofill voor "Oorzaak slechthorendheid"
   - Autofill voor "Oorinspectie"
#### Hoorprotocol2:
   - Popup venster geeft de minale COSI scores per domein en categorie weer
#### Opties:
   - Opties zijn verplaatst naar een eigen pagina
#### Klantkaart:
   - Alt tekst voor agendaregels geven reden voor niet nakomen
#### bugfix:
   - Intaketype COSI kreeg geen opmaak

### 1.6:
#### Memo's:
   - Spellcheck staat aan
#### Agenda:
   - De velden voor "Medewerker", "Ruimte" en "Handeling" zijn kleurgecodeerd of ze zijn ingevuld bij het wijzigen van een afspraak
   - Sneltoetsen voor navigatie zijn instelbaar
   - PageUp en PageDown werken ook wanneer de het agenda veld niet de focus heeft
#### Artikelen knop:
   - Opent direct de serienummergebondenvoorraad
#### bugfix:
   - Wanneer er meer dan een gegevens tabel aanwezig is volgde het aantal weer te geven resultaten alleen voor de eerste daarvan de instelling

### 1.5:
#### Bestelbonnen:
   - In het bestelbonnen overzicht staat standaard alle regels aangevinkt
#### Agenda Nieuwe Afspraak:
   - De ingelogde medewerker staat automatisch ingevuld bij "Medewerker"
   - De velden voor "Medewerker", "Ruimte" en "Handeling" kleurgecodeerd of ze zijn ingevuld
   - Bovengenoemde wijzigingen zijn instelbaar via de opties
#### Reparaties:
   - Klikken op de reparatie klachtomschrijving wordt alle text geselecteerd
#### bugfix:
   - Klanten knop opende niet het klantoverzicht vanuit een kassaverkoop waar een klant aan gekoppeld is
   - Foutmelding bij verwijderen van intakeformulier dat `Tabs.offset().top` niet geldig is

### 1.4:
#### Klanten knop:
   - Opent direct het klantoverzicht
#### Inkoop knop:
   - Opent direct het inboekoverzicht
#### bugfix:
   - Bij het verbergen van de optiekvragen werd ook "Andere problemen/opmerkingen" verborgen
  
### 1.3:
#### opties:
   - Het aantal resultaten dat weergegeven wordt in een tabel (10, 25, 50 of 100)
#### Reparaties:
   - Maximaal aantal tekens voor een reparatie opmerking is 58
   
### 1.2:
#### opties:
   - Highlight- en achtergrondkleuren van het intakeformulier
   - Drempelwaarde voor het verbergen van de optiekvragen in het intakeformulier
   - Opties voor het wel of niet verbergen van niet relevante regels in het intakeformulier

### 1.1:
#### Leverbonnen/offertes:
   - Terug knop vanuit een wijziging verwijst terug naar de klant

### 1.0:
#### Agenda knop:
   - Staat als tweede
   - Opent direct de agenda
#### Intake forumlier:
   - Achtergrond is grijs voor beter contrast met de invulvelden
   - Iedere regel is omlijnd
   - Niet relevante regels verdwijnen automatisch
   - Tabbalk blijft zichtbaar boven in de pagina

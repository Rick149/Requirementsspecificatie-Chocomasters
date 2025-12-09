# Requirementengineering
Om een passende applicatie te kunnen ontwikkelen is het van belang de eisen en wensen in kaart te brengen. Door de beschikbare bronnen te analyseren zijn een aantal requirements, zowel functioneel als niet functioneel, opgesteld. Aan de hand van deze requirements zijn userstory's ontworpen en is een inschatting van de complexiteit toegevoegd.

## Requirementsanalyse

### Functionele requirements

1. De gebruiker moet aangekochte producten kunnen registreren

2. De app moet een QR Code kunnen scannen

3. De gebruiker moet een batchnummer, postcode of kassabon kunnen invoeren

4. De app moet een dashboard bevatten met daarop een overzicht van geregistreerde producten, inclusief aankoopdatum, houdbaarheid, allergeneninformatie, herkomst van de cacao, productspecificaties en certificeringen

5. De gebruiker ontvangt automatisch een notificatie sturen wanneer een product bijna over de datum is, wanneer een seizoensproduct opnieuw beschikbaar komt of wanneer er belangrijke updates over duurzaamheid of veiligheid zijn.

6. De app bevat een bibliotheek met digitale productkaarten die specifiek zijn voor elk geregistreerd product, interactieve tutorials, video’s over de chocoladeproductie en recepten die gebruikers stap-voor-stap begeleiden.

7. De gebruiker kan zoeken in de bibliotheek via een zoekfuntie.

8. De gebruikers ontvangen via de applicatie pushnotificaties wanneer er nieuwe smaakvarianten, limited editions of seizoensproducten beschikbaar zijn

9. Zakelijke klanten ontvangen aanvullende notificaties over wijzigingen in levertijden, voorraadstatus en productieplanning.

10. Zakelijke klanten kunnen nieuwe producten direct via de app bestellen

11. De gebruiker kan een formulier invullen en foto's of video's toevoegen

12. De applicatie kan indien mogelijk direct een oplossing voorstellen

13. De gebruiker kan de status van de klacht/melding volgen en krijgt updates over de status hiervan

14. De applicatie bevat een chatbot die veelgestelde vragen kan beantwoorden.

15. De gebruiker kan een livechat starten met de klantenservice

16. De chatbot bevat een terugbelfunctie voor buiten openingstijden

17. De gebruiker ontvangt aanbevelingen op basis van de klantgeschiedenis

18. De applicatie toont exclusieve aanbiedingen voor app-gebruikers, geeft early-access tot limited editions, en biedt informatie over aankomende feestdagenproducten en proeverijevenementen.

19. De gebruiker kan voorkeuren instellen voor het type promoties dat deze wil ontvangen

20. De applicatie beschikt over een forum waar gebruikers met elkaar in contact kunnen komen en ervaringen kunnen delen

21. Het forum bevat gamification-elementen als badges, punten, challenges en seizoenswedstrijden

22. De applicatie toont de dichtstbijzijnde winkels, marktkramen, verkooppunten en deelnemende cafe's. 

23. Klanten kunnen zich via de app inschrijven voor o.a. workshops

24. De gebruiker ontvangt afspraakgerinneringen en updates

25. De gebruiker kan notificatievoorkeuren instellen

26. De gebruiker kan niet storen periodes instellen

27. De gebruiker kan thema's, lay out, accountgegevens en privacyniveau aanpassen

28. De applicatie bevat een helpsectie met FAQ's, handleidingen, meldingen en productregistratie
    

### Niet functionele requirements

1. De app is gekoppeld aan het ERP Systeem

2. De chatbot is 24/7 beschikbaar

3. De livechat is alleen beschikbaar gedurende openingstijden

4. De Chatbot is gekoppeld aan het CRM Systeem

5. de applicatie maakt gebruik van geolocatie om actuele locatie te bepalen

6. De applicatie beschikt over end to end encriptie

7. De applicatie beschikt over twee factor authenticatie bij inloggen

8. De app voldoet aan AVG/GDPR en andere relevante privacywetgeving

9. De applicatie is gekoppeld aan Power BI 

10. Het ontwerp is responsief en past zich aan aan schermgrootte

11. De navigatie is intuitief

12. De applicatie ondersteunt schermlezers, aanpasbare lettergroottes en contrastinstellingen.

13. De applicatie ondersteund meerdere taalopties 

14. content wordt gelokaliseerd per regio

15. De applicatie verzamelt anonieme gebruikersdata

16. De architectuur is modulair en schaalbaar en ondersteunt nieuwe functionaliteiten

17. De applicatie moet binnen 2 seconden opstarten

18. De navigatie moet logisch

19. De applicatie bevat robuuste foutafhandeling zoals errormessages en vervolgstappen

20. De applicatie is 99,9% van de tijd online

21. De ontwikkelaar voert regelmatig updates uit met nieuwe functionaliteiten en verbeterde beveiliging. 

## Minimum Viable Product 
Op basis van de requirements is er een MVP opgesteld. De MVP bevat alleen basisfunctionaliteiten en vormt de basis voor feedback van vroege gebruikers. Onderstaande requirements zijn geselecteerd en vormen samen een functioneel product geschikt als eerste versie.

1. De gebruiker moet aangekochte producten kunnen registreren
2. De gebruiker moet een batchnummer, postcode of kassabon kunnen invoeren
3. De app moet een dashboard bevatten met daarop een overzicht van geregistreerde producten
4. De app bevat een bibliotheek met digitale productkaarten die specifiek zijn voor elk geregistreerd product
5. De gebruiker kan zoeken in de bibliotheek via een zoekfuntie.
6. Gebruikers kunnen nieuwe producten direct via de app bestellen
7. De gebruiker kan een formulier invullen en foto's of video's toevoegen
8. De applicatie bevat een chatbot die veelgestelde vragen kan beantwoorden.
9. De gebruiker kan een livechat starten met de klantenservice
10. De applicatie beschikt over een forum waar gebruikers met elkaar in contact kunnen komen en ervaringen kunnen delen



## Userstory's, acceptatiecriteria en Inschatting
Om de requirements voor het Minimum Viable Product bruikbaar te maken is er voor elk van deze requirements een userstory toegevoegd. Deze beschrijft de noodzaak van de requirement voor de gebruiker. Daarnaast is er een inschatting van de complexiteit voor de betreffende userstory toegevoegd. Dit is gedaan met T-Shirt sizes, een veelvoorkomende methode. Elke userstory is voorzien van een s, m, l of xl.

|Requirement|Userstory|Acceptatiecriteria|Inschatting
| --- | --- | --- | --- | 
|De gebruiker moet aangekochte producten kunnen registreren| Als gebruiker wil ik mijn product kunnen registreren zodat ik kan bijhouden welke producten ik heb gekocht. | - Er is een registratieknop op het scherm, - er is een invoerveld om het product te registreren, - er is een knop om de registratie te bevestigen | S
|De gebruiker moet een batchnummer, postcode of kassabon kunnen invoeren|Als gebruiker wil ik een batchcode, postcode of kassabon kunnen invoeren zodat ik mijn product handmatig kan registreren|- Er is een invoerveld voor postcode, batchcode en kassabon, - Elk invoerveld bevat controle op juiste dataformat |S
|De app moet een dashboard bevatten met daarop een overzicht van geregistreerde producten| Als gebruiker wil ik een dashboard zien zodat ik mijn geregistreerde producten kan bekijken. | - Er is een scherm waarom alle geregistreerde producten van de gebruiker zichtbaar zijn, - Elk product heeft een eigen kaart, - Er is een knop waarmee een product verwijderd kan worden. | M
|De app bevat een bibliotheek met digitale productkaarten die specifiek zijn voor elk geregistreerd product|Als gebruiker wil ik een biblitoheek kunnen zien waarin ik producten kan vinden zodat ik informatie over deze producten kan opzoeken. | - Er is een pagina met producttegels, - Er is een tegel voor elk bestaand product | XL
|De gebruiker kan zoeken in de bibliotheek via een zoekfuntie.| Als gebruiker wil ik kunnen zoeken in de bibliotheek zodat ik het betreffende product snel kan vinden| - Er is een zoekbalk aanwezig, - De gebruiker kan text in de zoekbalk invoeren, - De resultaten komen overeen met de invoer in de zoekbalk | L
|Gebruikers kunnen nieuwe producten direct via de app bestellen|Als gebruiker wil ik een product direct via de app kunnen bestellen zodat ik niet naar een externe website hoef te navigeren|- Er is een bestelknop bij elk product, - Er is een invoerveld om het aantal gewenste producten in te voeren, - Er is een knop om de bestelling te bevestigen|M
|De gebruiker kan een formulier invullen en foto's of video's toevoegen|Als gebruiker wil ik een formulier kunnen invullen zodat ik mijn probleem makkelijk kan melden|- Er is een pagina met invoerveld voor het probleem, - Er is een invoerveld voor klantgegevens, - Er is een verzend formulier knop|M|
|De applicatie bevat een chatbot die veelgestelde vragen kan beantwoorden.|Als gebruiker wil ik een chatbot hebben zodat ik mijn vraag eenvoudig en snel kan stellen en direct een oplossing ontvang|- Er is een knop voor chatbot aanwezig, - Er is een invoerveld in de chatbot, - De chatbot bevat de vooraf opgestelde veelgestelde vragen|L|
|De gebruiker kan een livechat starten met de klantenservice|Als gebruiker wil ik een livechat kunnen starten met de klantenservice zodat ik altijd passende hulp krijg bij mijn probleem|- Er is een knop om de livechat te starten, - De livechat verbindt automatisch|S
|De applicatie beschikt over een forum waar gebruikers met elkaar in contact kunnen komen en ervaringen kunnen delen|Als gebruiker wil ik met medegebruikers in contact kunnen komen om ervaringen te delen en hulp te ontvangen|- Er is een overzichtspagina met artikelen van gebruikers, - Er is een knop om een artikel aan te maken, - Er is een knop om op een artikel te reageren, - Er is een knop om bestanden toe te voegen |L|









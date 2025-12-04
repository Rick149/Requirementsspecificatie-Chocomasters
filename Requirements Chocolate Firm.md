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



## Userstory's, acceptatiecriteria en Inschatting

Onderstaande tabel geeft een helder overzicht van de opgestelde requirements  met bijbehorende userstory, acceptatiecriteria en complexiteitsinschatting.

| Requirement                                                                                                                                                                                                                | Userstory                                                                                                                                                                                                                                                                                                        | Acceptatiecriteria                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Inschatting |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |:-----------:|
| De gebruiker moet aangekochte producten kunnen registreren                                                                                                                                                                 | Als gebruiker wil ik het gekochte product kunnen registreren zodat ik inzicht krijg in de productdetails en herkomst.                                                                                                                                                                                            | - De gebruiker kan een productregistratiepagina openen vanuit het menu of dashboard <br/><br/>- De gebruiker moet minimaal een uniek productnummer (bijv. serienummer / QR-code / batchnummer) invoeren of scannen.<br/>-De gebruiker ontvangt een duidelijke bevestiging dat het product succesvol is geregistreerd.<br/><br/>- De registratie wordt opgeslagen in het gebruikersprofiel en is later in te zien.                                                                                                                                                   | M           |
| De gebruiker moet een QR-Code kunnen scannen                                                                                                                                                                               | Als gebruiker wil ik de QR-code op de verpakking kunnen scannen zodat ik het product eenvoudig kan registreren                                                                                                                                                                                                   | - Het systeem kan een QR-code scanner openen vanuit het dashboard<br/><br/>- De scanner moet een code succesvol kunnen lezen<br/><br/>- Het systeem vult de data uit de QR-code automatisch in in de registratiemodule<br/><br/>                                                                                                                                                                                                                                                                                                                                    | S           |
| De gebruiker moet een batchnummer, postcode of kassabon kunnen invoeren                                                                                                                                                    | Als gebruiker wil ik een batchnummer, postcode of kassabon kunnen invoeren om mijn product handmatig te registreren                                                                                                                                                                                              | - De gebruiker moet een invoerveld voor zowel batchnummer, postcode of kassabon kunnen openen vanaf het dashboard<br/><br/>- Het invoerveld accepteert alleen invoer van het gekozen type<br/><br/>- Er is een button waarmee de gebruiker de invoer kan bevestigen                                                                                                                                                                                                                                                                                                 | M           |
| De app moet een dashboard bevatten met daarop een overzicht van geregistreerde producten, inclusief aankoopdatum, houdbaarheid, allergeneninformatie, herkomst van de cacao, productspecificaties en certificeringen       | Als gebruiker wil ik een dashboard met een overzicht van geregistreerde producten, inclusief aankoopdatum, houdbaarheid, allergeneninformatie, herkomst van de cacao, productspecificaties en certificeringen zodat ik inzicht krijg in mijn aankopen en relevante informatie.                                   | - Het systeem toont per product de: aankoopdatum, houdbaarheid, allergeneninformatie, herkomst van de cacao, productspecificaties en certificeringen<br/><br/>- Als er geen allergenen van toepassing zijn, toont het systeem duidelijk “Bevat geen allergenen”.<br/><br/>- De aankoopdatum wordt opgeslagen bij registratie en is zichtbaar in het productoverzicht en de productdetailpagina.                                                                                                                                                                     | L           |
| De gebruiker ontvangt automatisch een notificatie wanneer een product bijna over de datum is, wanneer een seizoensproduct opnieuw beschikbaar komt of wanneer er belangrijke updates over duurzaamheid of veiligheid zijn. | Als gebruiker wil ik een notificatie ontvangen wanneer een product bijna over de datum is, wanneer een seizoensproduct opnieuw beschikbaar komt of wanneer er belangrijke updates over duurzaamheid of veiligheid zijn zodat ik altijd op de hoogte ben van de staat van mijn producten en nieuwe ontwikkelingen | - De gebruiker ontvangt een notificatie wanneer een geregistreerd product bijna over datum is.<br/><br/>- De notificatie bevat minimaal: Productnaam en Houdbaarheidsdatum<br/><br/>- Wanneer een eerder geregistreerd seizoensproduct opnieuw beschikbaar komt, ontvangt de gebruiker een notificatie.<br/><br/>- De notificatie bevat minimaal: Productnaam, Seizoensperiode of beschikbaarheidsstatus<br/><br/>- Wanneer er relevante updates zijn over het product, ontvangt de gebruiker een notificatie.<br/>- De notificatie bevat: Productnaam, Type update | M           |







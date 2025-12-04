# Domeinmodel en UML klassendiagram
_Het onderstaande diagram toont het domeinmodel/UML-klassendiagram voor de mobiele applicatie van ChocoMasters._

```mermaid
classDiagram
    direction LR

    class Klant {
      +int klantId
      +String naam
    }

    class Product {
      +int productId
      +String naam
    }

    class ProductRegistratie {
      +int registratieId
      +Date registratiedatum
    }

    class Bestelling {
      +int bestellingId
      +Date besteldatum
    }

    class Bestelregel {
      +int bestelregelId
      +int aantal
    }

    class Klacht {
      +int klachtId
      +Date datum
      +String status
    }

    class Event {
      +int eventId
      +String naam
      +Date datum
    }

    class Locatie {
      +int locatieId
      +String naam
      +String plaats
    }

    Klant "1" --> "0..*" ProductRegistratie : registreert >
    Product "1" --> "0..*" ProductRegistratie : betreft >

    Klant "1" --> "0..*" Bestelling : plaatst >
    Bestelling "1" --> "1..*" Bestelregel : bevat >
    Product "1" --> "0..*" Bestelregel : wordtBesteldIn >

    Klant "1" --> "0..*" Klacht : dientIn >
    ProductRegistratie "0..1" --> "0..*" Klacht : gaatOver >

    Locatie "1" --> "0..*" Event : vindtPlaats >
    Event "1" --> "0..*" Klant : heeftDeelnemers >


# Domeinmodel en UML klassendiagram
_Het onderstaande diagram toont het domeinmodel voor de applicatie van ChocoMasters._

```mermaid
classDiagram
    class Klant {
      +int klantId
      +String naam
      +String email
      +Boolean isZakelijk
    }

    class Product {
      +int productId
      +String naam
      +Float cacaoPercentage
      +Boolean isSeizoensproduct
      +String allergenenInfo
    }

    class ProductBatch {
      +int batchId
      +String batchNummer
      +Date houdbaarTot
      +String qrCode
    }

    class GeregistreerdProduct {
      +int registratieId
      +Date registratiedatum
      +String registratiemethode
    }

    class Bestelling {
      +int bestellingId
      +Date besteldatum
      +String status
      +Float totaalBedrag
    }

    class Bestelregel {
      +int bestelregelId
      +int aantal
      +Float stuksPrijs
    }

    class Klacht {
      +int klachtId
      +Date aangemaaktOp
      +String type
      +String omschrijving
      +String status
    }

    class InhoudItem {
      +int inhoudId
      +String titel
      +String type
      +String taal
    }


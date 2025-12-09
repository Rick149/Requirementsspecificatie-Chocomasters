# Sitemap
Om een helder inzicht in de structuur van de applicatie te krijgen is een sitemap opgesteld. Onderstaand model beschrijft de verschillende pagina's in de applicatie en de onderlinge samenhang van deze pagina's. Het model is opgesteld voor de MVP.
---
```mermaid
flowchart TD

    %% Hoofdniveau
    A[Dashboard]

    %% Niveau 1
    A --> B[Mijn producten]
    A --> C[Forum]
    A --> D[Support]

    %% Mijn producten
    B --> B1[Bestellen]
    B --> B2[Productregistratie]
    B --> B3[Bibliotheek]

    B1 --> B1a[Productoverzicht]

    B3 --> B3a[Productoverzicht]

    %% Forum
    C --> C1[Artikel]

    %% Support
    D --> D1[Chatbot]
    D --> D2[Formulier]

    D1 --> D1a[Livechat]

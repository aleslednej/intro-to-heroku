```mermaid
flowchart TD
    A[Zadání objednávky] --> B[Validace objednávky]
    B --> C[Kontrola dostupnosti zboží]
    C --> D[Vytvoření objednávky]
    D --> E[Odeslání objednávky do ERP]
    E --> F[Potvrzení objednávky v ERP]
    F --> G[Generování faktury]
    G --> H[Odeslání potvrzení zákazníkovi]

# MEDITZsro/.github

Výchozí soubory pro všechna repa organizace `MEDITZsro`. Repo je **veřejné**, jinak by je GitHub nepoužil. Nepatří sem nic interního: žádné adresy instancí kromě veřejných domén, žádné tokeny, žádné názvy klientů.

| Soubor | Co dělá |
| --- | --- |
| `ISSUE_TEMPLATE/pozadavek.yml` | jediný formulář Požadavek nebo problém, psaný pro produkťáka |
| `ISSUE_TEMPLATE/config.yml` | vypíná prázdnou issue bez formuláře |

Formulář platí v každém repu organizace, které nemá vlastní složku `.github/ISSUE_TEMPLATE/`. Jakmile ji repo má, výchozí formulář se v něm nepoužije. Proto repa vlastní formuláře nezakládají.

Formulář nenastavuje štítky ani typ issue. Štítek by musel existovat v každém repu a druh (chyba, změna, dotaz) produkťák volí v poli O co jde. Typ issue organizace (`Task`, `Bug`, `Feature`) a štítky nastavuje vývoj při zatřídění.

Pravidla pro BI jsou v `BI/docs/13-dokumentace-repozitare.md`, kapitola 6.

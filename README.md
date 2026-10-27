# MEDITZsro/.github

Výchozí soubory pro všechna repa organizace `MEDITZsro`. Repo je **veřejné**, jinak by je GitHub nepoužil. Nepatří sem nic interního: žádné adresy instancí kromě veřejných domén, žádné tokeny, žádné názvy klientů.

| Soubor | Co dělá |
| --- | --- |
| `ISSUE_TEMPLATE/chyba.yml` | formulář Chyba, typ issue `Bug` |
| `ISSUE_TEMPLATE/zmena.yml` | formulář Změna nebo nová funkce, typ issue `Feature` |
| `ISSUE_TEMPLATE/config.yml` | vypíná prázdnou issue bez formuláře |

Formuláře platí v každém repu organizace, které nemá vlastní složku `.github/ISSUE_TEMPLATE/`. Jakmile ji repo má, výchozí formuláře se v něm nepoužijí vůbec, ani jeden. Proto repa vlastní formuláře nezakládají.

Formuláře nepoužívají štítky, protože štítek by musel existovat v každém repu. Druh issue nese typ (`Bug`, `Feature`), který je nastavený na úrovni organizace.

Pravidla pro BI jsou v `BI/docs/13-dokumentace-repozitare.md`, kapitola 6.

# Kanalinsikter

Kanalinsikter är en statisk webbapp för att analysera Facebook- och Instagram-exporter från Meta Business Suite. All CSV-bearbetning sker lokalt i användarens webbläsare.

## Funktioner

- import och kontroll av två Meta-exporter
- separata normalvärden för Facebook och Instagram
- 70/30-modell för räckvidd och engagemang
- manuella markeringar för Instagram Collab, eget organiskt och marknadsfört
- export av en fullständig Excelrapport med 11 flikar, 40 analysfält, månadsutveckling och två grafer
- export av normaliserad CSV, kanalinsikter och ändringslogg
- export/import av manuella regler mellan månader

## Publicering

Repositoryt publiceras till GitHub Pages genom workflow-filen i `.github/workflows/pages.yml`. Webbplatsen innehåller ingen Meta-data; användarnas filer lämnar inte webbläsaren.

## Begränsningar i version 1

- en aktuell Facebookfil och en aktuell Instagramfil laddas upp
- separata månadsfiler slås ännu inte ihop automatiskt
- Instagramdistribution måste verifieras manuellt när exporten saknar sponsringsuppgift
- Graferna i Excelrapporten bäddas in som tydliga bilder. De följer med i filen men är inte redigerbara Excel-diagramobjekt.

Det tidigare Evenemangsguiden-verktyget finns bevarat som `evenemangsguiden.html`.

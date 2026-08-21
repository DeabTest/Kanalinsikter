# Kanalinsikter

Kanalinsikter är en statisk webbapp för att analysera Facebook- och Instagram-exporter från Meta Business Suite. All CSV-bearbetning sker lokalt i användarens webbläsare.

## Funktioner

- import och kontroll av två Meta-exporter
- separata normalvärden för Facebook och Instagram
- 70/30-modell för räckvidd och engagemang
- manuella markeringar för Instagram Collab, eget organiskt och marknadsfört
- export av Excelrapport, normaliserad CSV, kanalinsikter och ändringslogg
- export/import av manuella regler mellan månader

## Publicering

Repositoryt publiceras till GitHub Pages genom workflow-filen i `.github/workflows/pages.yml`. Webbplatsen innehåller ingen Meta-data; användarnas filer lämnar inte webbläsaren.

## Begränsningar i version 1

- en aktuell Facebookfil och en aktuell Instagramfil laddas upp
- separata månadsfiler slås ännu inte ihop automatiskt
- Instagramdistribution måste verifieras manuellt när exporten saknar sponsringsuppgift
- Excelrapporten innehåller tabeller och nyckeltal men inte samma redigerbara diagramobjekt som originalarbetsboken

Det tidigare Evenemangsguiden-verktyget finns bevarat som `evenemangsguiden.html`.

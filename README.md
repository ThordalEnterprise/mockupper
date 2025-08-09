# MockUpper

En enkel single-file mockup- og wireframe-builder til web, iOS og Android – direkte i browseren.

## Funktioner
- Træk, slip og ændr størrelse på komponenter på et lærred
- Vælg mellem komponentbiblioteker: Web, iOS og Android (Material)
- Skift mellem Wireframe-mode (lav-fidelitet) og Detaljeret UI-mode
- Eksportér til HTML/CSS eller billede (PNG/JPEG) – alt kører client-side
- Canvas-presets (Desktop, Tablet, iPhone, Android) samt custom størrelser

## Kom i gang
1. Åbn `index.html` i din browser (Chrome, Edge, Firefox, Safari).
2. Tilføj komponenter fra venstre side ved at klikke på dem.
3. Flyt elementer ved at trække dem; ændr størrelse i hjørnerne.
4. Dobbeltklik på tekst/knapper for at redigere teksten.
5. Slet valgte elementer med `Delete`/`Backspace`.

## Tilstande
- Wireframe: Enkel, lav-fidelitets-visning med stiplede rammer og afdæmpede billeder.
- Detaljeret: Høj-fidelitets-styles (Tailwind-baseret) for realistisk UI.

## Eksport
- HTML: Klik "Eksportér HTML" for at downloade en selvstændig HTML-side med layoutet.
- PNG/JPEG: Klik "PNG" eller "JPEG" for at eksportere lærredet som et billede.

Bemærk: Eksterne billeder hentes med `crossOrigin='anonymous'` for at muliggøre eksport; enkelte kilder kan stadig blokere CORS.

## Teknologi
- Tailwind CSS (via CDN) til moderne styling
- Interact.js til drag/resize
- html2canvas til billed-eksport

## Licens
MIT

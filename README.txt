SNÖJAKT – första fungerande PWA-prototypen

Filer:
- index.html: appen
- manifest.webmanifest: installerbar webbapp
- sw.js: enkel offline-cache för appskalet
- icon.svg: ikon

VIKTIGT:
1. Lägg upp hela innehållet på en HTTPS-webbserver (t.ex. GitHub Pages eller annan statisk hosting).
2. Öppna URL:en i Safari på iPhone.
3. Tryck Dela -> Lägg till på hemskärmen.

Prognosen hämtas från SMHI:s öppna SNOW1gv1 punkt-API. Appen använder ett urval orter inom 300 km för att hålla antalet API-anrop rimligt.
Poängen är en grov uppskattning av snöförutsättningar utifrån prognostiserad nederbörd och temperatur – inte verifierat väglag eller snödjup på vägen. Den ska vidareutvecklas/valideras mot SMHI:s aktuella parameterlista innan skarp användning.

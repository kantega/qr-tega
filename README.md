# Kantega QR-generator

Generer Kantega-merkede QR-koder direkte i nettleseren — ingen server, ingen installasjon.

## Bruk

Åpne `index.html` i en nettleser, eller deploy til GitHub Pages.

Skriv inn en URL, velg bakgrunn og klikk **Generer QR-kode**. Last ned resultatet som PNG.

## Bakgrunnsvalg

| Valg | Beskrivelse |
|---|---|
| Hvit | Lys bakgrunn med mørk lilla prikker |
| Mørk lilla | Kantega-bakgrunn (`#27003D`) med hvite prikker |
| Gjennomsiktig | Gjennomsiktig bakgrunn, egnet for overlay på presentasjoner o.l. |

## GitHub Pages

Gå til repo-innstillinger → Pages → kilde: `main`, rot `/`. Siden er én selvinneholdt HTML-fil uten eksterne avhengigheter.

## Innhold

```
index.html       — hele appen (bibliotek og logoer er innbakt)
logos/           — Kantega K-symbol (PNG)
```

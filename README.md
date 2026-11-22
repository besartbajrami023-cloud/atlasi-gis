# Atlasi GIS – Besart Bajrami

**MSc. Besart Bajrami, GIS Specialist**: harta, analiza hapësinore, video MP4 dhe punime të tjera GIS (Kosovë / Drenas).

🌐 **Portofoli:** https://besartbajrami023-cloud.github.io/atlasi-gis/

## Struktura

| Dosja | Përmbajtja |
|---|---|
| `harta/` | Harta përfundimtare (PNG, PDF) |
| `analiza/` | Të dhëna dhe skripte (GeoPackage, Shapefile, Python) |
| `video/` | Video MP4 dhe kopertinat e tyre |
| `index.html` | Faqja e portofolit (GitHub Pages) |
| `punimet.json` | Lista e punimeve që shfaqen në faqe |

## Si shtohet një punim i ri

1. Ngarko fajllin në dosjen përkatëse (p.sh. `harta/2026-11-tri-detet.png`).
2. Shto një rresht në `punimet.json`:

```json
{
  "lloji": "harta",
  "titulli": "Tri detet e Kosovës",
  "data": "2026-11-22",
  "fajlli": "harta/2026-11-tri-detet.png",
  "kopertina": "",
  "pershkrimi": "Ndarja e pellgjeve ujëmbledhëse sipas detit ku derdhen.",
  "shkarko": "analiza/tri-detet.gpkg"
}
```

`lloji`: `harta`, `analiza` ose `video`. Për video, `kopertina` mund të jetë një PNG.

## Kufizime

- Fajllat mbi 100 MB nuk pranohen nga GitHub. Për MP4 apo DEM të mëdhenj përdor Git LFS ose Releases.
- Repoja është publike: mos ngarko të dhëna kadastrale personale apo dokumente të brendshme.

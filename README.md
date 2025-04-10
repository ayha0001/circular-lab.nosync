# Teknisk dokumentation for Tema 8 gruppeprojekt

Her står vores fælles retningslinjer for dette projekt.

## Projektstruktur

Vores Astro projekt består af de følgende mapper og filer:

```text

/
├── public/
│ └── favicon.svg
├── src/
│ ├── assets/
│ │ └──
│ ├── components/
│ │ └──
│ ├── css/
│ │ └── generel.css
│ ├── layouts/
│ │ └── Layout.astro
│ └── pages/
│ └── index.astro
│ └── overview.astro
│ └── singleview.astro
└── package.json

```

Fonte bliver hentet via en embed kode og embeddes derefter i html head'en i layout.astro.

## Navngivning

```
Filer bliver navngivet efter hvad siden er til/handler om. Så hvis man laver en component fil til headeren eller hero section, kalder man den header.astro, hero.astro osv.
Component filerne navngives med stort forbogstav og resten småt og helst enkeltord.
```

## Branches

Vi navngiver branches ved at skrive "navn-" også hvad der laves på branchen.
Eksempelvis: navn-header.

## Arbejdsflow

Vi aftaler i gruppen, hvordan fordelingen af de forskellige sider, componenter og andre ting sker, inden man går i gang med at kode. Vi ændre heller ikke i andres filer, med mindre man har kommunikeret det med hinanden inden. Man skriver i sin commit-besked hvad man har add/remove/fix, så vi kan gå tilbage og have styr på hvad der sker i filerne.
Når man merger en feature ind, kommunikerer man det til resten af gruppen, så de har mulighed for at pulle.

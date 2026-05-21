# Lingua · Kroužek předškoláka

Aplikace pro **půlroční kurz Kroužek předškoláka** ZŠ Lingua Universal — příprava k zápisu do 1. třídy.

**KOMPLETNÍ VERZE — všech 6 oblastí hotových!** ✅

## Vizuál

- **Font**: Barlow Condensed
- **Hlavní barvy**: školní modrá `#32a0d2` + oranžová `#ffaa37`
- **Akcent per oblast** (6 různých barev)
- Sjednoceno se stylem LinguaCzech / II / Deutsch

## 6 oblastí

| Oblast | Cvičení | Barva |
|--------|---------|-------|
| 🔢 **Předmatematické představy** | Kde je víc, Bingo s tečkami, Spoj počet s číslem | růžová |
| 👂 **Sluchové vnímání** | První písmeno, Rýmy, Počty slabik, Krátká/dlouhá (s audiem) | zelená |
| 👁️ **Zrakové vnímání** | Najdi rozdíl, Doplň vzor, Najdi všechna stejná | fialová |
| 🧭 **Prostorová orientace** | Kterým směrem, Kde je předmět, Bludiště | žlutá |
| ⏰ **Časová orientace** | Co bylo dřív, Denní režim, Roční období | modrá |
| 🖍️ **Grafomotorika** | Čáry, Vlnky a kličky, Tvary (SVG tracing) | červená |

**CELKEM: 19 interaktivních cvičení**

## Soubory

```
index.html               ← Landing - 6 oblastí
rodice.html              ← Pro rodiče - tipy, diagnostika, tisk
predmatematicke.html     ← 3 cvičení (růžová)
sluchove.html            ← 4 cvičení s audiem (zelená)
zrakove.html             ← 3 cvičení (fialová)
prostorova.html          ← 3 cvičení (žlutá)
casova.html              ← 3 cvičení (modrá)
grafomotorika.html       ← 3 tracing cvičení (červená)
logo.png                 ← Školní logo
```

## Speciální funkce

### 🔊 Audio (sluchové vnímání)
Web Speech API s `lang="cs-CZ"`. Funguje v Chrome, Edge, Safari.

### 🖍️ SVG Tracing (grafomotorika)
- Funguje **myší i prstem** (touch events)
- Hodnocení podle pokrytí vzorové čáry
- 15 různých tvarů (čáry, vlnky, kličky, geometrické tvary, srdíčko, hvězda)

### 🐭 Bludiště (prostorová)
- 7×7 mřížka s ovládáním šipek
- 3 různá bludiště
- Hodnocení podle počtu tahů

### 👨‍👩‍👧 Pro rodiče
- Detailní popis každé oblasti
- Vhodné aktivity pro domov
- Diagnostické tlačítka (Začíná / Zkouší / Zvládá / Expert)
- **Tisknutelný záznamový arch** — titulní strana + tabulka

## Bodový systém

⭐ Hvězdičky místo trofejí. Body se ukládají per oblast v localStorage:
- `lingua-predskolak-predmat-v1`
- `lingua-predskolak-sluchove-v1`
- `lingua-predskolak-zrakove-v1`
- `lingua-predskolak-prostorova-v1`
- `lingua-predskolak-casova-v1`
- `lingua-predskolak-grafomotorika-v1`
- `lingua-predskolak-diagnostika-v1` (rodičovská diagnostika)

## Nasazení

V repu `LinguaPredskolak`:
- `https://linguauniversal.github.io/LinguaPredskolak/`

## Licence

Vzdělávací materiál pro ZŠ a MŠ Lingua Universal Litoměřice.

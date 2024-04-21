# HunCoder

A HunCoder WebDev egy Visual Studio Code-ba telepíthető automatikus kitöltő (jelenleg még csak) HTML fájlokhoz. Kezdő webfejleszők munkáját szeretnénk meggyorsítani, behívható magyar parancsokkal, amik automatikusan kitöltik a megfelelő HTML tageket.

> Tip: Many popular extensions utilize animations. This is an excellent way to show off your extension! We recommend short, focused animations that are easy to follow.

## Használat

Egy felkiáltójel beírásával a Visual Studio Code ki fogja listázni az összes parancsot, amit használhatsz.

## Példa

Ahhoz, hogy ne kelljen legépelni minden új HTML dokumentumba a kihagyhatatlan alap tageket (DOCTYPE, html, head,
title, meta, body), elég csak beírni a következő kódot:

```html
!html5
```

Az enter lenyomásával pedig a következőképpen töltődik ki a fájlod:

```html
<!DOCTYPE html>
<html>
  <head>
    <!-- ITT ADHATOD MEG AZ OLDAL NEVÉT -->
    <title>Oldal neve</title>

    <!-- AZ OLDALLAL KAPCSOLATOS FONTOS ADATOK -->
    <meta charset='UTF-8' />
    <meta name='description' content='Rövid leírás az oldal tartalmáról' />
    <meta name='keywords' content='Keresést, Segítő, Szavak, Vesszővel, Elválasztva'/>
    <meta name='author' content='Neved' />
    <meta name='viewport' content='width=device-width, initial-scale=1.0' />
  </head>
  <body></body>
</html>
```

## Verziók

Itt találod meg, hogy pontosan miket tartalmaznak az új verziók.

### 0.0.1

Teszt fázis, alap HTML5 kód generálása, stílusfájl behívása.

## Parancsok listája

**!html5** - Alap HTML5 dokumentum generálása az oldal címével és a fontos meta tagekkel.  
**!stilusfajl** - Stílusfájlt behívó sor generálása.

---

## További segédanyagok

Ha többet szeretnél tudni rólunk, [Látogass el weboldalunkra](http://huncoder.hu)

**Hujber Balázs**

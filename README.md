# HunCoder WebDev

A HunCoder WebDev egy Visual Studio Code-ba telepíthető automatikus kitöltő (jelenleg még csak) HTML fájlokhoz. Kezdő webfejleszők munkáját szeretnénk meggyorsítani, behívható magyar parancsokkal, amik automatikusan kitöltik a megfelelő HTML tageket.

## Használat

Egy felkiáltójel beírásával a Visual Studio Code ki fogja listázni az összes parancsot, amit használhatsz.

## Parancsok listája

**!html5** - Alap HTML5 dokumentum generálása az oldal címével és a fontos meta tagekkel.  
**!dolt** - Félkövér szöveg definiálása.  
**!horgony** - Szimpla a tag.  
**!dolt** - Dőlt szöveg definiálása..  
**!kep** - Kép csak leírással.  
**!kep2** - Kép leírással és méretekkel.  
**!lablec** - Oldal lábléce.  
**!link** - Kattintható link.  
**!komment** - HTML komment.  
**!sortores** - Sortörés.  
**!stilusfajl** - Stílusfájlt behívó sor generálása.  
**!tablazat** - Két soros táblázat, melynek első sora fejléc (th), második sora sima sor (td).

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
    <meta name='description' content='Rövid leírás az oldal tartalmáról'/>
    <meta name='keywords' content='Keresést, Segítő, Szavak, Vesszővel, Elválasztva'/>
    <meta name='author' content='Neved'/>
    <meta name='viewport' content='width=device-width, initial-scale=1.0'/>
  </head>
  <body>

  </body>
</html>
```

**VAGY**

~~~html
!tablazat
~~~

Ezt a parancsot választva a program automatikusan kitölt egy két soros táblázatot, melynek az első sora egy fejléc:

~~~html
<table>
    <tr>
       <th>Fejléc 1. cella</th>
       <th>Fejléc 2. cella</th>
       <th>Fejléc 3. cella</th>
   </tr>
   <tr>
       <td>2. sor 1. cella</td>
       <td>2. sor 2. cella</td>
       <td>2. sor 3. cella</td>
   </tr>
</table>
~~~

## Verziók

Itt találod meg, hogy pontosan miket tartalmaznak az új verziók.

### 0.0.1

Teszt fázis, pár alap kitöltés.

---

## További segédanyagok

Ha többet szeretnél tudni rólunk, [Látogass el weboldalunkra](http://huncoder.hu)
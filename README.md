# HunCoder WebDev

A HunCoder WebDev egy Visual Studio Code-ba telepíthető automatikus kitöltő (jelenleg még csak) HTML fájlokhoz. Kezdő webfejleszők munkáját szeretnénk meggyorsítani, behívható magyar parancsokkal, amik automatikusan kitöltik a megfelelő HTML tageket.

## Használat

Egy felkiáltójel beírásával a Visual Studio Code ki fogja listázni az összes parancsot, amit használhatsz.

## Parancsok listája

**!html5** - Alap HTML5 dokumentum generálása az oldal címével és a fontos meta tagekkel.  
**!alahuzott** - Aláhúzott szöveg definiálása.  
**!be-datum** - Dátum beviteli mező.  
**!be-email** - Email beviteli mező.  
**!be-fajl** - Fájl beviteli mező.  
**!be-gomb** - Gomb "bevitel" (inputban definiált gomb).  
**!be-jelszo** - Jelszó bevitel.  
**!be-url** - URL bevitel.  
**!be-szin** - Szín bevitel.  
**!be-szoveg** - Sima szöveg beviteli mező.  
**!bekezdes** - Bekezdés.  
**!cim1** - 1. szintű cím.  
**!cim2** - 2. szintű cím.  
**!cim3** - 3. szintű cím.  
**!cim4** - 4. szintű cím.  
**!cim5** - 5. szintű cím.  
**!cim6** - 6. szintű cím.  
**!dolt** - Félkövér szöveg definiálása.  
**!fejlec** - Oldal fejléce.  
**!gomb** - Szimpla gomb.  
**!horgony** - Szimpla a tag.  
**!dolt** - Dőlt szöveg definiálása..  
**!kep** - Kép csak leírással.  
**!kep2** - Kép leírással és méretekkel.  
**!kuldes** - Küldés gomb űrlaphoz.  
**!lablec** - Oldal lábléce.  
**!link** - Kattintható link.  
**!lista** - Nem számozott lista.  
**!komment** - HTML komment.  
**!sortores** - Sortörés.  
**!szamozottlista** - Számozott lista.  
**!stilusfajl** - Stílusfájlt behívó sor generálása.  
**!tablazat** - Két soros táblázat, melynek első sora fejléc (th), második sora sima sor (td).  
**!urlap** - Űrlap definiálása.  
**!video** - Beágyazott videólejátszó.  
**!vonal** - Vízszintes vonal.

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

HTML5-ben hat szinten tudunk címet létrehozni az oldalon. Első szintű címhez elég begépelni a következőt:

~~~html
!cim1
~~~

Ennek köszönhetően kitöltődik egy első szintű cím az oldalunkon:

~~~html
<h1>Ez egy 1. szintű cím</h1>
~~~

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

### 0.3.1

Pár bevitel űrlaphoz. (sima szöveg, jelszó dátum, email, szín, sima gomb, küldés gomb, url, fájl)

### 0.2-0.3

Frissítés tesztelés, videólejátszó.

### 0.0.1

Teszt fázis

---

## További segédanyagok

Ha többet szeretnél tudni rólunk, [Látogass el weboldalunkra](http://huncoder.hu)
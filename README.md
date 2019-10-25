
# Hópverkefni 1 

Notast var við fyrirmyndir og myndband til að sjá cirka hvernig síðurnar líta út 

Allar myndir eru undir `img` möppuna 

* Fyrir útlit gildir að nota Open Sans eða helvetica, arial eða sans-serif letur sem meginmál en Oswald, Verdana eða serif letur fyrir fyrirsagnir.

* Nota skal grind: 
    * Hámarksstærð `1200px` 
    * 12 dálkar 
    * `20px` gutter 
    
* grid.css skal notað til að láta efni falla rétt að grind 

* Meginmál efnis passa innan grid dálkunum 

* Öll bil eru hálft, heilt, tvöfalt eða þrefalt margfeldi af gutter. 

## Fyrirsagnir 

## Fótur 

## Síður 

### Vörur 

Samtal 6 vörur sem settar voru sem kort. 

#### Útlit 

* Meginmál er með hálft bil gutter uppi og 2*gutter niðri

* Bil á milli haus og fóturs og meginmáls. Einnig eru bil innan í kortin í `.products` milli efnis þess. Miðað var bilin við stærðin á gutter. 

* Bil milli kortana skal vera jafn og gutter. 

* Allar upplýsingar um vörurnar eru undir `.products__info` og boxin undir `.magn`.

* Setja skal 2 "box" fyrir magn vöru og óvirkur takki til að "Setja í körfu". 

* Magnið "box" skal vera með default gildið 1 og hægt að hækka, breiddin á því er ca. `65%` kortsins. 

* "Setja í körfu" boxið skal innihald mynd af körfu undir `img` möppuna og með ljósgráan lit sem bakgrunnslitur. 

* Þessi box/takki skal breytist yfir í bláa lit þegar mús er sett yfir, `hover`. 


#### Skjalanleiki 

Notast var mobile-first sem leiðarljósi, þ.a. allt er stílar áður en media quieries eru  notaðar og miðað við `<800px` brotpunkt. 


Fyrir brotpunkta gildir: 
* `<800px`  
    * Dálkar í `.products` eru `100%` og fyllir upp í foreldra þess 

* `>=800px` 
    * Dálkar í `.products` breytir í eru `50%` og fyllir upp í foreldra þess og eru 2 saman í línu 
    * Skipunin skiptist frá `column` yfir í `row` og raðast dálkarnir 2 saman hlið við hlið 
    
* `>=1200px` 
    * Dálkar í `.products` breytir í eru `33.33%` og fylla upp í foreldra þessa og eru 3 saman í línu 
    * padding er tekið af meginmáli vegna grid 

* `>=1240px` 
    * `padding right` er tekið af kortunum sem eru lengst til hægri vegna grid 

### Stafsfólk 

Samtals 4 starfsfólk sem sett voru í kort. 

#### Útlit 

* Meginmál hefur tvöfaldan gutter bil fyrir ofan og fyrir neðan 

* Einnig eru bil á milli kortunum, tvöfaldan gutter milli myndar fyrir ofan og neðan en einfaldan gutter milli myndana hlið við hlið. 

* Allar upplýsingar um stafsfólkið er hægt að finna á bakvið myndina þeirra þegar þær snúi við og eiga þær að vera miðjusettar. 

* Snúning á myndunum fæst með því að nota `transition: transform 200ms`, `transition-timing-function: ease-in-out` og `transform-style: preserve-3d` ásamt öðrum nauðsynlegum yfirlýsingum eins og `transform: rotateY(180deg)` og fleira. 

* Þegar kortin snúa þá er bakhliðin falin. 

#### Skjalanleiki 

* `<800px`  
    * Dálkar í `.flip` eru `100%` og fyllir upp í foreldra þess 

* `>=800px` 
    * Dálkar í `.products` breytir í eru `50%` og fyllir upp í foreldra þess og eru 2 saman í línu 
    * Skipunin skiptist frá `column` yfir í `row` og raðast dálkarnir 2 saman hlið við hlið 
    
* `>=1200px` 
    * Dálkar í `.products` breytir í eru `33.33%` og fylla upp í foreldra þessa og eru 3 saman í línu 
    * padding er tekið af meginmáli vegna grid 

* `>=1240px` 
    * `padding right` er tekið af kortunum sem eru lengst til hægri vegna grid 

## Hópur 







# Hópverkefni 1

Verkefnið felst í því að smíða vef eftir forskrift.

Gefnar eru [fyrirmyndir](utlit/) í `500px`, `800px` og `1500px` með grind ásamt `1500px` án grindar og yfirliti yfir virkni vefs í `utlit/video.mp4`.

## Síður

Gögn fyrir síður eru í viðeigandi textaskrám (t.d. forsida.txt) undir `efni/`. Myndir fyrir síður eru gefnar undir `img/`. Afrita þarf öll gögn á milli síðna, ekki er krafa um að setja upp sameiginlegan haus/fót á síðum með einhverju kerfi eða forritun.

Efni síðu skal ekki vera breiðara en `1200px`. Litir í haus og fæti skulu fylla út í allt lárétt pláss.

Síður hafa allar sama haus og sama fót. Vöruflokkar í fæti skulu allir vísa á `pages/products.html`. Námskeið í fæti skulu vís á `pages/course.html`

Grunn leturstærð er 16px og fylgja allar aðrar leturgerðir eftirfarandi skala: `12 14 16 18 21 24 36 48 60`.

Litapalletta fyrir vef er `#000000`, `#fffcf2`, `#ff5000` og `#00b7ff`.

Letur fyrir meginmál er Open Sans eða helvetica, arial eða sans-serif letur.
Letur fyrir fyrirsagnir er Oswald, Verdana eða serif letur.

Flest allt er sett upp í 12 dálka grind með `20px` gutter.

Öll bil eru hálft, heilt, tvöfalt eða þrefalt margfeldi af gutter. Hægt er að nota reglustiku tól (t.d. http://www.arulerforwindows.com/ eða http://www.pascal.com/software/freeruler/) til að finna nákvæmar stærðir en mestu skiptir að lausn svipi til en sé ekki nákvæmlega eins og fyrirmynd.

Allar hreyfingar gerast á `200ms` með `ease-in-out` hröðunarfalli.

Ekki þarf að útfæra neina virkni fyrir takka eða form.

## Hópavinna

Verkefnið skal unnið í hóp með þremur einstaklingum. Skráning í hópa fer fram í [Google sheets](https://docs.google.com/spreadsheets/d/1GwC9OvnpGHIkuX7ArRG7UQ-JV74b_pomegGXOWF1od0/edit?usp=sharing)

Notast skal við Git og GitHub. Engar zip skrár með kóða ættu að ganga á milli í hópavinnu, heldur á að „committa“ allan kóða og vinna gegnum Git.

## Lýsing á verkefni

`README.md` skrá skal vera í rót verkefnis og innihalda:

* Upplýsingar um hvernig keyra skuli verkefnið
* Lýsingu á uppsetningu verkefnis, hvernig því er skipt í möppur, hvernig CSS er skipulagt og fleira sem á við
* Upplýsingar um alla sem unnu verkefnið
* Leyfilegt er að halda eftir þessari verkefnalýsingu en hún skal þá koma _á eftir_ ykkar lýsingu

## Tæki og tól

Setja skal upp Sass og stylelint fyrir verkefnið. Gefin er `styles.scss` skrá með grunn upplýsingum.

Gefin er `.stylelintrc` skrá sem segir til um hvernig lint fyrir `scss` skrár skuli háttað.

Í `.gitignore` er `styles.css` hunsað sem þýðir að það verður _ekki_ checkað inn. Það er gert vegna þess að það er búið til af sass út frá `styles.scss`

## Gefnar skrár

Eftirfarandi er sett upp í verkefni:

* `.stylelintrc` með upplýsingum um hvernig stylelint eigi að haga sér. Setja þarf upp `stylelint-config-primer` pakkann
* `.gitignore` sem hunsar algengar skrár, [sjá nánar](https://help.github.com/ignore-files/)
* `.gitattributes` sem kemur í veg fyrir ósamræmi sem geta komið upp þegar unnið er á milli stýrikerfa
* `.editorconfig` sem samræmir notkun á tabs og spaces, bilum [og fleira](https://editorconfig.org/)
* `index.html` með vísun í `styles.css` og `grid.css` ásamt tómum skrám fyrir `products.html`, `staff.html`, `course.html` og `cart.html` undir `pages/`, halda skal þessu skipulagi
* `grid.css` til að sjá grid sem fyrirmynd er unnin eftir

Setja þarf upp `package.json` og sækja viðeigandi pakka til að tæki og tól sem verkefnið á að nýta virki.

## Mat

* 10% - `README` eftir forskrift, tæki og tól uppsett
* 20% – Snyrtilegt, gilt (skv. stylelint) CSS/Sass, gilt og aðgengilegt HTML
* 30% – Almennt útlit
* 8% – Forsíða
* 8% – Vörur síða
* 8% – Námskeið síða
* 8% – Starfsfólk síða
* 8% – Karfa síða

## Sett fyrir

Verkefni sett fyrir í fyrirlestri mánudaginn 7. október 2019.

## Skil

Einn aðili úr hóp skal skila fyrir hönd allra og skila skal undir „Verkefni og hlutaprófa“ á Uglu í seinasta lagi fyrir lok dags föstudaginn 25. október 2019.

Skil skulu innihalda:

* Nöfn allra í hóp ásamt notendanafni
* Slóð á GitHub repo fyrir verkefni, og öllum dæmatímakennurum skal hafa verið boðið í repo ([sjá leiðbeiningar](https://help.github.com/articles/inviting-collaborators-to-a-personal-repository/)). Notendanöfn þeirra eru `anz1e`, `gunnnnii`, `magdadianaa`, `OlafurjonHI` og `Wolfcoder13` .
* Slóð á verkefnið keyrandi á vefnum.

## Einkunn

Sett verða fyrir tíu minni verkefni þar sem átta bestu gilda 3,5% hvert, samtals 28% af lokaeinkunn.

Sett verða fyrir tvö stærri verkefni þar sem hvort um sig gildir 11%, samtals 22% af lokaeinkunn.

## Myndir

Myndir frá:

* [Innkaupakörfu fengin á iconfinder](https://www.iconfinder.com/icons/216460/cart_icon)
* [Aðrar myndir fengnar frá Unsplash](https://unsplash.com/photos/N4QTBfNQ8Nk)

---

> Útgáfa 0.1

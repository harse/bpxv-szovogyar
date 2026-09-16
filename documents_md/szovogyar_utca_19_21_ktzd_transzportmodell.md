---
id: 113
title: "A Szövőgyár utcai szennyezettségről készült kiegészítő tényfeltárási záródokumentáció függelékei: szovogyar_utca_19_21_ktzd_transzportmodell.pdf"
date: "2026.09.04."
author: "BPXV Önkormányzat"
recipient: "IV. és XV. kerületi lakosság"
summary: "A korábban közzétett törzsanyag után most a Szövőgyár utca 19–21. szám alatti ingatlanon és környezetében feltárt szennyezettségről készült kiegészítő tényfeltárási záródokumentáció mellékleteit, függelékeit és táblázatait is közzéteszi az önkormányzat."
source_url: "https://www.bpxv.hu/sites/default/files/media/file/2026/09/szovogyar_utca_19_21_ktzd_transzportmodell.pdf"
original_filename: "szovogyar_utca_19_21_ktzd_transzportmodell.pdf"
---
ADEPT ENVIRO KFT

Székhely: 1117 Budapest, Lágymányosi utca 12. Fszt. 2.
Iroda: 1095 Budapest, Máriássy utca 5.

+36-309-703-713
adeptenviro@adeptenviro.com

BUDAPEST XV., SZÖVŐGYÁR UTCA 19-21.

KIEGÉSZÍTŐ TÉNYFELTÁRÁSI ZÁRÓDOKUMENTÁCIÓ
HIDRODINAMIKAI-ÉS TRANSZPORT MODELLEZÉS

# VOLT BUDAPESTI
FINOMKÖTÖTTÁRUGYÁR TELEPHELY

1151 BUDAPEST XV., SZÖVŐGYÁR UTCA 19-21.

## KIEGÉSZÍTŐ TÉNYFELTÁRÁSI
ZÁRÓDOKUMENTÁCIÓ

### HIDRAULIKAI-ÉS TRANSZPORTMODELLEZÉS

#### 1.FÜGGELÉK

![img-0.jpeg](img-0.jpeg)

2026. ÁPRILIS

KÉSZÍTETTE: ADEPT ENVIRO KFT.

1/24

Dokumentum azonosító: 0383/T/01/02 (Készült: 2026.04.30)

---

ADEPT ENVIRO KFT

Székhely: 1117 Budapest, Lágymányosi utca 12. Fszt. 2.
Iroda: 1095 Budapest, Máriássy utca 5.

+36-309-703-713
adeptenviro@adeptenviro.com

BUDAPEST XV., SZÖVŐGYÁR UTCA 19-21.

KIEGÉSZÍTŐ TÉNYFELTÁRÁSI ZÁRÓDOKUMENTÁCIÓ
HIDRODINAMIKAI-ÉS TRANSZPORT MODELLEZÉS

# TARTALOM

1. Hidraulikai- és transzport modellezés ... 4
1.1. A modellszámítás célja ... 4
1.2. Modellezett szennyező komponensek ... 4
1.3. Alkalmazott szoftvercsomag ... 5
1.4. Hidrodinamikai modell ... 6
1.4.1. Modellgeometria ... 6
1.4.2. Modellrétegek földtani jellemzői ... 6
1.4.3. Hidraulikai jellemzők ... 8
1.4.4. Hidraulikai peremfeltételek ... 9
1.4.4.1. Nyugalmi víznyomás eloszlás ... 9
1.4.4.2. Felszíni vizek ... 9
1.4.4.3. Vákuumtechnikai gépgyár kármentesítő kútjai ... 10
1.4.4.4. Egyéb vízkitermelő objektumok ... 11
1.4.5. Hidraulikai input paraméterek ... 12
1.5. Transzport szimuláció ... 13
1.5.1. Transzport paraméterek ... 14
1.5.1.1. Szorpciós tényező ... 14
1.5.1.2. Bomlási állandó ... 16
1.5.1.3. Szennyezőanyag szóródás ... 16
1.5.2. Szennyezőforrásból történő utánpótlódás ... 17
1.6. Modellezés eredményei ... 20
1.6.1. Hidraulikai modell ... 20
1.6.2. Transzport modellezés ... 22

KÉSZÍTETTE: ADEPT ENVIRO KFT.

2/24

Dokumentum azonosító: 0383/T/01/02 (Készült: 2026.04.30)

---

ADEPT ENVIRO KFT

Székhely: 1117 Budapest, Lágymányosi utca 12. Fszt. 2.
Iroda: 1095 Budapest, Máriássy utca 5.

+36-309-703-713
adeptenviro@adeptenviro.com

BUDAPEST XV., SZÖVŐGYÁR UTCA 19-21.

KIEGÉSZÍTŐ TÉNYFELTÁRÁSI ZÁRÓDOKUMENTÁCIÓ
HIDRODINAMIKAI-ÉS TRANSZPORT MODELLEZÉS

## ÁBRÁK

**1F-1** Nyugalmi FAV eloszlás - F szint
**1F-2** Nyugalmi FAV eloszlás - A szint
**1F-3** Számított nyugalmi FAV eloszlás - A szint
**1F-4** Számított nyugalmi FAV eloszlás - F szint
**1F-5** Keresztszelvény nyomvonal (hidraulikai – földtani)

### Transzport ábrák

**2F-1** Oldott PCE transzport eloszlásai felső vízadóban
**2F-2** Oldott PCE transzport eloszlásai az alsó vízadóban

## MELLÉKLETEK

**1M** Szilas-patak geodéziai felmérése

KÉSZÍTETTE: ADEPT ENVIRO KFT.

3/24

Dokumentum azonosító: 0383/T/01/02 (Készült: 2026.04.30)

---

ADEPT ENVIRO KFT

Székhely: 1117 Budapest, Lágymányosi utca 12. Fszt. 2.
Iroda: 1095 Budapest, Máriássy utca 5.

+36-309-703-713
adeptenviro@adeptenviro.com

BUDAPEST XV., SZÖVŐGYÁR UTCA 19-21.

KIEGÉSZÍTŐ TÉNYFELTÁRÁSI ZÁRÓDOKUMENTÁCIÓ
HIDRODINAMIKAI-ÉS TRANSZPORT MODELLEZÉS

# 1. HIDRAULIKAI- ÉS TRANSZPORT MODELLEZÉS

## 1.1. A MODELLSZÁMÍTÁS CÉLJA

Jelen kiegészítő tényfeltárás keretén belül felépített modellszimuláció célja, hogy a korábban feltárt **alifás-és aromás szénhidrogén szennyezés** (mely bizonyosan a Budapesti Finomkötöttárugyár területén fellelhető), továbbá a 2023 év során észlelt **illékony klórozott alifás szénhidrogén szennyezés** (mely mind a volt Finomkötöttárugyár, mind pedig a szomszédos Leánynevelő Intézet területen azonosított) oldott állapotban, várhatóan milyen mértékben és mekkora területen szennyezi tovább a felszín alatti víztestet, beavatkozás nélküli esetben.

## 1.2. MODELLEZETT SZENNYEZŐ KOMPONENSEK

A területen jelentős mértékű a földtani közeghez kötött **alifás-aromás szénhidrogének és klórozott szénhidrogén** komponensek mennyisége. Továbbá a területen létesült mintavételi furatok közül 3 ponton (CLRT-F01, CLRT-F101, CLRT-F109) LNAPL típusú felúszó CH szennyezőt is észleltünk a területen, változó vastagságban (átlagosan 1-5 cm) a mintavételi időszakok során, ugyanakkor a 2026 januári egyidejű vízszintmérési ciklus alkalmával az F01 jelű furatban, több mint 1 méter vastagságot is meghaladta, míg DNAPL tekintetében nem mértünk alulúszó szénhidrogént a területen létesült furatokban.

A 2025-2026 év közötti időszakban, 10x10 m raszteres mintavételi feltárással szennyezettségi góckutatást végeztünk az Olajszármazék és Tetraklór-etén térrészeken, mely során azonosítottuk a szennyezőforrások területeit, melyet követően mind vertikálisan, mind pedig horizontálisan lehatároltnak tekintjük. A laboranalitikai eredmények értékelését követően megállapítottuk, hogy földtani közeghez kapcsolódó szennyezés domináns részarányát a **TPH** és **PCE** komponenskör adja. Ugyanakkor a klórozott komponensek tekintetében feltártunk egyéb, földtani közeghez adszorbeálódott, eltérő klóratomszámmal rendelkező vegyületet is, mint TCE, DCE és vinil-klorid, továbbá az olajszármazékok esetében is nem elhanyagolható mértékben fellelhetőek BTEX és PAH vegyületei.

A vizsgált területen kimutatott szennyezőanyagok együttes értékelését követően a transzportmodellezés során a **PCE** és a **TPH** komponensek terjedési ütemét vizsgáltuk. Ezen komponensek a klórozott szénhidrogén primer, míg az olajszármazékok fő szennyezői, továbbá ezek az alkotók adják a meghatározott szennyezőanyag tömegmennyiség jelentős részarányát mind a felszín alatti vízben, mind pedig a földtani közegben. A kimutatott TCE, DCE és vinil-klorid komponensek a PCE komponens anaerob degradációs bomlástermékei, melyek koncentráció térbeli eloszlása és mintázata a PCE transzportjához, illetve bomlási

KÉSZÍTETTE: ADEPT ENVIRO KFT.

4/24

Dokumentum azonosító: 0383/T/01/02 (Készült: 2026.04.30)

---

ADEPT ENVIRO KFT

Székhely: 1117 Budapest, Lágymányosi utca 12. Fszt. 2.
Iroda: 1095 Budapest, Máriássy utca 5.

+36-309-703-713
adeptenviro@adeptenviro.com

BUDAPEST XV., SZÖVŐGYÁR UTCA 19-21.

KIEGÉSZÍTŐ TÉNYFELTÁRÁSI ZÁRÓDOKUMENTÁCIÓ
HIDRODINAMIKAI-ÉS TRANSZPORT MODELLEZÉS

folyamatához szorosan kapcsolódnak. Ahogyan említettük, a szennyezőcsóva-tömegáramát is döntően a PCE komponens határozza meg, mely a bomlási sor legmagasabb klórtartalmú és legnagyobb molekulatömegű eleme, így a felszín alatti rendszer transzportfolyamatát elsődlegesen a PCE komponens határozza meg. Továbbá a góckutatás során a meghatározott TCE és DCE komponensek (PCE területéről) eltérő szennyezőforrás területét nem azonosítottuk, így az alacsonyabb klórszámú komponensek önálló modellezése nem indokolt. Ennek megfelelően a PCE reaktív transzportjának modellezése (megfelelő bomlási kinetika alkalmazásával) a bomlási termékek megjelenését és várható terjedését közvetetten leírja, így azok önálló modellezése a jelen célkitűzés szempontjából nem indokolt.

A BTEX és PAH komponensek a fűtőolaj szennyezés kísérő vegyületei, azonban mobilitásuk és perzisztenciájuk eltérő. A BTEX-ek jellemzően magasabb oldhatóságúak, jobban biodegradálódnak, illetve jóval mobilasabb alkotók, míg a PAH vegyületek alacsony vízoldhatóságúak továbbá erősen kötődnek a talajszemcsékhez, így mobilitásuk is korlátozott. Ráadásul a BTEX és PAH komponensek (B) szennyezettségi határérték feletti területi eloszlása jóval kisebb, illetve kisebb koncentráció arány jellemzi. Vizsgáltuk továbbá több pont esetében a szennyezettségi kromatogramokat, mely alapján megállapítottuk, hogy az illékony komponensek részaránya jelentősen alulmarad az EPH komponenseitől, az-az a feltárt szennyezők esetén gyakorlatilag minden ponton a C₁₂-C₃₅ szénatomszámú komponensek dominálnak. Összegezve, a TPH komponens transzportjának vizsgálata a feltárt felszín alatti közegre vonatkozó szénhidrogén terhelést jól reprezentálja, továbbá konzervatív megközelítést ad az olajeredetű származékok várható transzportjára.

Továbbá a többkomponensű, reaktív transzport modell alkalmazása a szükséges reakciókinetikai paraméterek bizonytalansága miatt nem elhanyagolható kockázatot hordozna a modell előrejelzés megbízhatósága szempontjából.

A fentiekből adódóan a transzport szimulációt, beavatkozás nélküli esetben (nem történik talajkitermelés és talajvíz tisztítás sem) a halogénezett komponensek esetében a PCE, míg az olajszármazékok esetében TPH komponensek transzportmodellezését végeztük el 10 és 20 évesidőtávra vonatkozóan, melyből adódóan nyomon követhetjük a komponensek várható transzportját a területen.

### 1.3. ALKALMAZOTT SZOFTVERCSOMAG

A modellszimulációt Visual MODFLOW Pro programcsomaggal végeztük, melynek megoldása véges differencia módszerén alapul. Az alkalmazott program a szivárgási térben végbemenő vízmozgás, többrétegű és 3D megközelítéssel történő leírására alkalmas. A vízmozgás

KÉSZÍTETTE: ADEPT ENVIRO KFT.

5/24

Dokumentum azonosító: 0383/T/01/02 (Készült: 2026.04.30)

---

ADEPT ENVIRO KFT

Székhely: 1117 Budapest, Lágymányosi utca 12. Fszt. 2.
Iroda: 1095 Budapest, Máriássy utca 5.

+36-309-703-713
adeptenviro@adeptenviro.com

BUDAPEST XV., SZÖVŐGYÁR UTCA 19-21.

KIEGÉSZÍTŐ TÉNYFELTÁRÁSI ZÁRÓDOKUMENTÁCIÓ
HIDRODINAMIKAI-ÉS TRANSZPORT MODELLEZÉS

hidrodinamikai számításaira a USGS Modflow2005, míg a transzport szimulációhoz a többkomponensű transzportfuttatások során az RT3D/MT3DMS modulokat alkalmaztuk, míg a számítás eredményeinek értelmezéséhez és térképi megjelenítésére a Surfer 28.4 verzióját alkalmaztuk.

## 1.4. HIDRODINAMIKAI MODELL

### 1.4.1. MODELLGEOMETRIA

A modellezett térrészt úgy választottuk meg, hogy számításba vegye a felszín alatti víz áramlási irányát és mértékét, melyből adódóan modellezett szennyezőkomponensek várható terjedési üteme meghatározható, továbbá biztosítsa az alkalmazott hidraulikai peremfeltételek megfelelőségét. A modellteret 1,1kmx1,4 km-es területként definiáltunk, melyet kezdetben 10x10 m-es felosztású rácshálóval fedtük le, mely a tényfeltárási szakaszok, illetve a góckutatás során elvégzett fúrási- és mintavételi pontsűrűségből adódóan megfelelőnek gondoljuk. A modelltér terepfelszíni kialakításánál a tényfeltárások alkalmával elvégzett geodéziai felmérésből nyert magassági adatokat alkalmaztuk. A modelltér sarokponti koordinátáit az alábbi határoló pontok jelölik:

EOV X (654 700; 655 800)
EOV Y (247 100; 248 500)

### 1.4.2. MODELLRÉTEGEK FÖLDTANI JELLEMZŐI

A 2023-2026 évek közötti tényfeltárási (I., II. és kiegészítő ütem) és góckutató szakaszok során létesült furatokban feltárt földtani jellemzők, továbbá a földtani adattárból nyert regionális fúrási naplók alapján a modellt vertikálisan 5 főrétegre osztottuk, melyben a sekély szinten lévő vízadót (98,1 mBf.) és mélyebb rétegek vízadóját (104,3 mBf.) különítettünk el. Továbbá ezen fő modellrétegeket a heterogenitás végett tovább osztottunk zónás parametrizálás céljából, melyet követően összesen 7 rétegből épül fel a földtani modell, amit az alábbi 1.4.5. fejezet **1.táblázatban** jellemzünk.

A földtani modell legfelső rétegét a felszíntől kezdődően homokos (kissé iszapos) feltöltés, illetve kissé iszapos-agyagos homok alkotja átlagosan, mintegy 3,4 m mélységig. Ezt követően, kis áteresztőképességű (gyengén homokos) iszapos-agyag, agyagos-iszap váltakozása jelenik meg heterogén eloszlásban, melyek a telítetlen zónában rendkívül nagy jelentőséggel bírnak a szennyezőkomponensek adszorpcióját illetően. Így ezen lencsés megjelenésű, agyagos kiterjedésű zónák beépítése elengedhetetlen volt a modellbe. Mivel ezen rétegek kifejlődése

KÉSZÍTETTE: ADEPT ENVIRO KFT.

6/24

Dokumentum azonosító: 0383/T/01/02 (Készült: 2026.04.30)

---

ADEPT ENVIRO KFT

Székhely: 1117 Budapest, Lágymányosi utca 12. Fszt. 2.
Iroda: 1095 Budapest, Máriássy utca 5.

+36-309-703-713
adeptenviro@adeptenviro.com

BUDAPEST XV., SZÖVŐGYÁR UTCA 19-21.

KIEGÉSZÍTŐ TÉNYFELTÁRÁSI ZÁRÓDOKUMENTÁCIÓ
HIDRODINAMIKAI-ÉS TRANSZPORT MODELLEZÉS

nem folytonos a fúrási feltárások alapján, így modellezés technikai szempontból zónásított hidraulikai paraméterekkel (fentebb hivatkozott 1.táblázat) láttunk el, mely finomszemcsés üledékek területi kiterjedését az alábbi 4.ábrán mutatjuk be.

Negyedik rétegként iszapos finomhomokokat definiáltunk átlagosan 105,3 mBf. szinten, míg ötödik rétegként (kissé iszapos) finom/középhomok rétegek (mint felső vízadó zóna) következnek átlagosan 8,4 m mélységig. Hatodik modellrétegként (mint alsó vízadó) kavicsos-homokok/homokos-durva kavics rétegeket határoztunk meg.

A földtani felépítést végül a teraszüledék alatt vízrekesztő, kissé kötött agyagfekü zárja, melynek kifejlődése a modelltér ÉNy-Ny-i felén már inkább iszapos-agyag, agyagos-iszap minőségű, növekvő szervesagyagtartalommal. Az agyagfekü a terep felszíne alatt átlagosan 5-17 m körül jelenik meg, mely a modelltér Ny-ÉNy-i felén, illetve a Szilas-patak túloldalán létesített furatokban feltárt földtan alapján már mindössze 5-6 méteres mélységben elérjük, mely térrészen ezáltal jelentősen lecsökkent a durva szemcsés, víztartó közeg vastagsága.

![img-1.jpeg](img-1.jpeg)

1. ábra A terület földtani szelvényeinek nyomvonala

KÉSZÍTETTE: ADEPT ENVIRO KFT.

7/24

Dokumentum azonosító: 0383/T/01/02 (Készült: 2026.04.30)

---

ADEPT ENVIRO KFT

Székhely: 1117 Budapest, Lágymányosi utca 12. Fszt. 2.
Iroda: 1095 Budapest, Máriássy utca 5.

+36-309-703-713
adeptenviro@adeptenviro.com

BUDAPEST XV., SZÖVŐGYÁR UTCA 19-21.

KIEGÉSZÍTŐ TÉNYFELTÁRÁSI ZÁRÓDOKUMENTÁCIÓ
HIDRODINAMIKAI-ÉS TRANSZPORT MODELLEZÉS

![img-2.jpeg](img-2.jpeg)

2. ábra Részletes földtani felépítés

Tekintettel arra, hogy a létesült mintavételi furatok eloszlása nem teljesen fedte le a modellezett területet, így az földtani adattári, regionális fúrási naplók alapján pontosítottuk a földtani felépítést, illetve így a feltáratlan területen interpolált réteg vastagságot alkalmaztunk.

### 1.4.3. HIDRAULIKAI JELLEMZŐK

A felszín alatti vízmozgás a fent részletezett földtani felépítés szerint a kissé iszapos, finomhomok/középhomok és kavicsos-homok/homokos kavicsrétegekben történik, így a szennyezőanyag transzport folyamatok is ezen rétegekben zajlik. A terepi méréseink alapján a vertikális hidraulikát illetően azt látjuk, hogy a sekélyebb zónák folyadékpotenciál szintjei minimális mértékben magasabbak, mint a mélyebben húzódó alsó vízadó zónáé, így vertikális áramlás gyakorlatilag elhanyagolható mértékű a vizsgált területen, melyet a 6-7. ábrán bemutatott hidrodinamikai sebesség szelvény is bemutat. A horizontális áramképet tekintve megállapítottuk, hogy a sekély és a mélyebb vízadóban kismértékben eltérő a hidraulikai gradiens, továbbá az áramlási irányok is. A felszín alatti víz áramlási iránya mindkét víztartóban észak-nyugatias volt a 2026. áprilisában, míg meghatározott gradiensek a mélyebb vízadóban 2,664x10⁻³ m/m, a felső szintben pedig 2,601x10⁻³ m/m.

KÉSZÍTETTE: ADEPT ENVIRO KFT.

8/24

Dokumentum azonosító: 0383/T/01/02 (Készült: 2026.04.30)

---

ADEPT ENVIRO KFT

Székhely: 1117 Budapest, Lágymányosi utca 12. Fszt. 2.
Iroda: 1095 Budapest, Máriássy utca 5.

+36-309-703-713
adeptenviro@adeptenviro.com

BUDAPEST XV., SZÖVŐGYÁR UTCA 19-21.

KIEGÉSZÍTŐ TÉNYFELTÁRÁSI ZÁRÓDOKUMENTÁCIÓ
HIDRODINAMIKAI-ÉS TRANSZPORT MODELLEZÉS

### 1.4.4. HIDRAULIKAI PEREMFELTÉTELEK

A rendelkezésre álló, teljes modellezett teret lefedő vízszintmérési adatsorok alapján, permanens állapotra végeztük a számításokat, melyet a 2026. áprilisi nyomásadatokhoz kalibráltuk. A modelltér vízadó rétegeiben állandó nyomású peremi cellákat alkalmaztunk a keleti és nyugati oldalakon, továbbá hidraulikai peremfeltételként vettük számításba a maradó beszivárgás, átlagos becsült 57 mm/év értékét. Ugyanakkor a gócterület jelentős része betonlapokkal burkolt felület, melyek közötti a beszivárgás lehetősége korlátozott, így ezen térrész és környezetében 33 mm/év beszivárgást¹ vettünk alapul.

A modelltér dél-nyugati területein elhelyezkedő, egykori Vákuumtechnikai Gépgyár területén feltárt felszín alatti szennyezettség tekintetében a Naturaqua Kft. 2021 évben tényfeltárást végzett, majd műszaki beavatkozást tervezett, melynek hatósági elfogadását követően a területen aktív, felszín alatti víztisztító rendszer kiépítése valósult meg, majd szakaszos üzemeltetése zajlik. Az elérhető és publikus környezetvédelmi tanulmányokból kinyertük a tervezett kármentesítő rendszer kitermelő-és visszasajtoló kutak műszaki paramétereit és üzemi adatait, majd vizsgáltuk a kitermelő-nyeletű kútrendszer hatását és depressziós terét jelen tényfeltárási területünkre vonatkozóan, melyet az 1.4.4.3 fejezetben részletezünk.

#### 1.4.4.1. NYUGALMI VÍZNYOMÁS ELOSZLÁS

A permanens modellszámítások során a 2026. áprilisában mért nyugalmi vízszintmérés adatsoraiból készült víznyomás eloszlást alkalmaztuk, melyhez kalibráltuk a hidraulikai modellt. A számított víznyomás eloszlási térképeket az 1F-1 és 1F-2. ábramellékletben mutatjuk be.

#### 1.4.4.2. FELSZÍNI VIZEK

A modell tér északi felén húzódó Szilas-patakról vízmérce adatok érhetőek el. Ugyanakkor a földtani adatsorok értékelése után megállapítást nyert, hogy az oldott szennyezés transzportját jelentős mértékben befolyásolja a Szilas-patak medre, melynek mélysége mintegy 8-9 méterrel vágódik be a teraszüledék zónamélységébe (113 mBf. körüli), így a patakmeder környezetében a felszín alatti víz szintje ezen 104-106 mBf szintnél nem tud magasabbra emelkedni, csak a patak magas vízállásakor rövid időre. A tényfeltárási dokumentációban megállapított, jelenlegi patakmederre vonatkozó kérdések tisztázására geodéziailag felmértük a teljes modelltéren végig húzódó patak szélességét, vízszint mélységét

¹ NATÉR-MBSZF, CARPATCLIM-HU adatbázis 30 éves (1975-2004) beszivárgási átlagértekei és Kun (2017) beszivárgás eloszlási modell

KÉSZÍTETTE: ADEPT ENVIRO KFT.

9/24

Dokumentum azonosító: 0383/T/01/02 (Készült: 2026.04.30)

---

ADEPT ENVIRO KFT

Székhely: 1117 Budapest, Lágymányosi utca 12. Fszt. 2.
Iroda: 1095 Budapest, Máriássy utca 5.

+36-309-703-713
adeptenviro@adeptenviro.com

BUDAPEST XV., SZÖVŐGYÁR UTCA 19-21.

KIEGÉSZÍTŐ TÉNYFELTÁRÁSI ZÁRÓDOKUMENTÁCIÓ
HIDRODINAMIKAI-ÉS TRANSZPORT MODELLEZÉS

a meder alját és a mederiszap, mint kolmatált zóna vastagságát, melyről készült jegyzőkönyvet az 1M. mellékletben csatoljuk.

A felmérés alapján megállapíthatjuk, hogy a patakmederben csekély mennyiségű víz áramlik, továbbá gyakorlatilag a teljes modelltér szakaszán a patak meder betonlapokkal kirakott, így a mérhető iszaptartalom 0 mm. Melyből adódóan a patak jelenlegi medre nincs közvetlen hidraulikai kapcsolatban a térség felszín alatti vízforgalmával, a vízgyűjtőterületről érkező vizeket a patak gyakorlatilag teljesmértékben elvezeti a Duna irányába.

Ugyanakkor a tényfeltárási dokumentációban részletezett, régi patak-meder (durva szemcsés teraszüledék) drénező hatását a továbbiakban vizsgálni szükséges ugyanis vélhetően a régi teraszmeder jobb és bal partja közti nyomás különbségből adódóan a szennyezettség csupán minimálisan jut át a patak túlpartján lévő északi területekre. Jelen fázisban a patak jobb partja, illetve az ideeső északi területek hidraulikai szempontból ismeretlenek, így a fenti feltételezés jelen szakaszban nem bizonyított, melyből adódóan jelen modellezés során a pataktól északra eső területeket inaktív cellazónának tekintjük, azaz nem végzünk hidraulikai számításokat.

A következő vizsgálati ütemben fontos tisztázni, hogy a feltárt szennyezettségi csóva É-i irányban történő tovább haladását a Szilas-patak „völgye” korlátozza-e, avagy elvezeti egészen a Duna vonaláig.

### 1.4.4.3. VÁKUUMTECHNIKAI GÉPGYÁR KÁRMENTESÍTŐ KÚTJAI

A modellezett területünkön csupán 3 db kitermelő (T-jelű) és 4 db nyelőkútsor (Ny-jelű) került kiépítésre. A kutak kitermelési üteméről nem kaptunk pontos információkat, csupán közelítő üzemelési adatokat (függően karbantartástól, műszaki problémák és egyéb ipari igények tekintetében), ugyanakkor az kiderült, hogy október-március hónapok között jellemzően nem működik a tisztító rendszer. Az üzemeltetési hozamok 10-30 m³/nap, míg a nyeletési ütem 8-30 m³/nap mennyiségre tehető, míg a kutak kizárólag a legfelső vízadót (F) szűrőzve épültek ki.

A fentieket figyelembe véve, jelen hidraulikai modellünk nyugati felébe beépítettük ezeket a kutakat. A modellfuttatás eredményei alapján pedig megállapíthatjuk, hogy a kutak szuperponált távolhatása (ld. alábbi 3. ábra) alapján is alig 95 m-es a hatóterületük, melyek következtében a Vákuumtechnika területén üzemelő aktív kármentesítés nincs hatással jelen tényfeltárással érintett területünk hidraulikai viszonyaira.

KÉSZÍTETTE: ADEPT ENVIRO KFT.

10/24

Dokumentum azonosító: 0383/T/01/02 (Készült: 2026.04.30)

---

ADEPT ENVIRO KFT

Székhely: 1117 Budapest, Lágymányosi utca 12. Fszt. 2.
Iroda: 1095 Budapest, Máriássy utca 5.

+36-309-703-713
adeptenviro@adeptenviro.com

BUDAPEST XV., SZÖVŐGYÁR UTCA 19-21.

KIEGÉSZÍTŐ TÉNYFELTÁRÁSI ZÁRÓDOKUMENTÁCIÓ
HIDRODINAMIKAI-ÉS TRANSZPORT MODELLEZÉS

![img-3.jpeg](img-3.jpeg)

3. ábra A modelltéren üzemelő, aktív kármentesítő rendszer (Vákuumtechnológia), üzemi kútjainak hatása

#### 1.4.4.4. EGYÉB VÍZKITERMELŐ OBJEKTUMOK

A VGT3 adatbázisában a modelltér tágabb környezetében több vízkitermelő kút ismert, míg közvetlenül a modelltéren lévő, vízkivételi objektumok a Schiller Opel autószervíz 1.sz. mosókútja, illetve a Tarzan-park területén létesült kút. Ezen két kútról semmilyen információt nem kaptunk az üzemeltetés tekintetében, így nem kerültek beépítésre.

Továbbá a Naturaqua Zrt. elmondása alapján az UTE Atlétika Stadion környezetében lévő lakóingatlanokon, különösen a nyári időszakban jelentős vízkivételek lehetnek, melyek módosíthatják a térség vízforgalmát. Pontos információkkal erről sem rendelkezünk.

KÉSZÍTETTE: ADEPT ENVIRO KFT.

11/24

Dokumentum azonosító: 0383/T/01/02 (Készült: 2026.04.30)

---

ADEPT ENVIRO KFT

Székhely: 1117 Budapest, Lágymányosi utca 12. Fszt. 2.

Iroda: 1095 Budapest, Máriássy utca 5.

+36-309-703-713

adeptenviro@adeptenviro.com

BUDAPEST XV., SZÖVŐGYÁR UTCA 19-21.

KIEGÉSZÍTŐ TÉNYFELTÁRÁSI ZÁRÓDOKUMENTÁCIÓ

HIDRODINAMIKAI-ÉS TRANSZPORT MODELLEZÉS

### 1.4.5. HIDRAULIKAI INPUT PARAMÉTEREK

A numerikus modellszámításhoz rétegenként a horizontális és vertikális szivárgási tényezők, valamint a porozitás indexek meghatározására van szükség. A vizsgált térrész több szűrőzött pontján szivattyútesztet végeztünk, melynek eredményeiből nyert hidraulikai paramétereket (horizontális szivárgási tényező, porozitás) kezdeti input paraméterként alkalmaztuk. Az anizotrópia-faktor esetében a finomszemcsés, kötött üledékek esetén 10⁻¹ nagyságrendet alkalmaztunk, míg a többi képződményre vonatkozóan szakirodalmi és tapasztalatai adatokat használtunk.

A hidraulikai számításokhoz szükséges egyéb parametrizálást szakirodalmi adatbázisok alapján származtattuk. A feltárt iszapos-agyagos lencsék és betelepülések parametrizálását zónásan építettük a modellbe, melyet az 1.táblázatban és 4.ábrán szemléltetünk.

1.táblázat A modellszámítás során alkalmazott hidraulikai paraméterek

|  réteg | szín kód | réteg minőség | k_{h} (m/s) | k_{v} (m/s) | k_{ε} (m/s) | n_{0} effektív porozitás  |
| --- | --- | --- | --- | --- | --- | --- |
|  1 |  | kissé iszapos homokos-feltöltés | 5.51E-5 | 5.51E-5 | 5.51E-5 | 0.13  |
|  2 |  | homokos, agyagos-iszap | 6.33E-7 | 6.33E-7 | 6.33E-7 | 0.08  |
|  3 |  | erősen kötött agyag | 3.20E-8 | 3.20E-8 | 3.20E-8 | 0.04  |
|  4 |  | iszapos-homok | 6.11E-6 | 6.11E-6 | 6.11E-6 | 0.10  |
|  5 |  | finomhomok/középhomok | 6.74E-5 | 6.74E-5 | 6.74E-5 | 0.15  |
|  6 |  | homokos-kavics/kavicsos-durva homok | 8.52E-4 | 8.52E-4 | 6.72E-4 | 0.23  |
|  7 |  | agyagfekü | 2.00E-8 | 2.00E-8 | 2.00E-9 | 0.04  |

KÉSZÍTETTE: ADEPT ENVIRO KFT.

12/24

Dokumentum azonosító: 0383/T/01/02 (Készült: 2026.04.30)

---

ADEPT ENVIRO KFT

Székhely: 1117 Budapest, Lágymányosi utca 12. Fszt. 2.
Iroda: 1095 Budapest, Máriássy utca 5.

+36-309-703-713
adeptenviro@adeptenviro.com

BUDAPEST XV., SZÖVŐGYÁR UTCA 19-21.

KIEGÉSZÍTŐ TÉNYFELTÁRÁSI ZÁRÓDOKUMENTÁCIÓ
HIDRODINAMIKAI-ÉS TRANSZPORT MODELLEZÉS

![img-4.jpeg](img-4.jpeg)

4. ábra A modelltéren alkalmazott zónásított hidraulikai paraméterek (Ny-K szelvény)

![img-5.jpeg](img-5.jpeg)

5. ábra A modelltéren alkalmazott zónásított hidraulikai paraméterek (felszíni metszet)

## 1.5. TRANSZPORT SZIMULÁCIÓ

Az előzmény dokumentációk és jelen kiegészítő tényfeltárási szakaszból nyert eredmények alapján a modelltéren jelentős mértékű az olajeredetű alifás-aromás szénhidrogének, illetve a klórozott alifás szénhidrogének szennyezés található a felszín alatti közegben.

Kimagasló mértékű földtani közeg szennyezettséget tártunk fel a telítetlen zóna mélységközben (113-106 mBf.) a felszíntől mérten mintegy -7 m mélységig, továbbá a telített zónatérben (106-96 mBf.) TPH, illetve tetraklór-etilén komponensek tekintetében. Az észlelt

KÉSZÍTETTE: ADEPT ENVIRO KFT.

13/24

Dokumentum azonosító: 0383/T/01/02 (Készült: 2026.04.30)

---

ADEPT ENVIRO KFT

Székhely: 1117 Budapest, Lágymányosi utca 12. Fszt. 2.
Iroda: 1095 Budapest, Máriássy utca 5.

+36-309-703-713
adeptenviro@adeptenviro.com

BUDAPEST XV., SZÖVŐGYÁR UTCA 19-21.

KIEGÉSZÍTŐ TÉNYFELTÁRÁSI ZÁRÓDOKUMENTÁCIÓ
HIDRODINAMIKAI-ÉS TRANSZPORT MODELLEZÉS

klórozott szénhidrogén komponensek eltérő klóratomszámmal rendelkező vegyületeinek bomlási sorát is kimutattuk a területen, ugyanakkor az 1.2 fejezetben részletezetteknek megfelelően a transzport szimulációt a PCE és TPH komponensekre végeztük el jelen fázisban 10 és 20 éves időszakra vonatkozóan.

Jelen kiegészítő tényfeltárás során elvégzett mintavételek laboranalitikai eredményei alapján a vizsgált szennyezőanyag csoportot a földtani közegre és talajvízre vonatkozóan lehatároltnak tekintjük (B) szennyezettségi határérték tekintetében.

A modellezés során a beavatkozás nélküli eset vizsgáljuk, mely során a feltárt, szennyezett talajtest nem kerül kitermelésre, nem történik a modelltéren víztisztítás, így a felszínről beszivárgó csapadék folyamatosan utánpótlódó forrászónát képez az oldott komponensek számára.

A térrész transzport folyamatait a bemutatott hidrodinamikai modellen alapuló RT3D/MT3D alapú transzportcsomaggal végeztük. Porózus közegben a kémiai anyagáramlás főbb komponensei az advektív anyagáramok, valamint a diffúzió és diszperzió következtében létrejött anyagtranszport. Oldott fázisban maradó komponens anyagmennyiségét továbbá befolyásolja az adszorpciós folyamat és a lebomlás. Tekintve a modellezett terület körülményeit a destruktív transzportmechanizmusok közül az advekciót, diszperziót, adszorpciót és a bomlást is figyelembe vettük. A transzport szimulációhoz szükséges paramétereket korábbi, hasonló feltételekkel rendelkező területek és szakirodalmi adatsorok² alapján határoztuk meg, melyet összegezve az alábbi fejezetek táblázataiban mutatunk be.

## 1.5.1. TRANSZPORT PARAMÉTEREK

### 1.5.1.1. SZORPCIÓS TÉNYEZŐ

A szennyezőanyag felületi adszorpcióját, Henry-féle lineáris szorpcióval közelítettük, mely során feltételezzük, hogy az adszorbeált anyagmennyisége és a pórusvíz koncentrációja egyenes arányos, így a szorpciós folyamat lineáris. Ez esetben a Kd megoszlási hányadost állandónak tekintjük, állandó rétegbeli hőmérsékletet feltételezve. A természetben ugyanakkor nem minden esetben áll fenn egyenes arányosság, többnyire a Freundlich izoterma modell érvényesül, de laboratóriumi adszorpciós mérések hiányában linearitást feltételezünk és elfogadjuk ezen konzervatív megközelítést. A jellemző szorpciós Kd paraméter értéke (megoszlási tényező) több tényezőtől függő, melyek közül legjelentősebbek a

² Envirobase-Base (Waterloo Hydrogeologic), Royal Society of Chemistry-ChemSpider

*: TPH frakciók súlyozásából meghatározottak

KÉSZÍTETTE: ADEPT ENVIRO KFT.

14/24

Dokumentum azonosító: 0383/T/01/02 (Készült: 2026.04.30)

---

ADEPT ENVIRO KFT

Székhely: 1117 Budapest, Lágymányosi utca 12. Fszt. 2.

Iroda: 1095 Budapest, Máriássy utca 5.

+36-309-703-713

adeptenviro@adeptenviro.com

BUDAPEST XV., SZÖVŐGYÁR UTCA 19-21.

KIEGÉSZÍTŐ TÉNYFELTÁRÁSI ZÁRÓDOKUMENTÁCIÓ

HIDRODINAMIKAI-ÉS TRANSZPORT MODELLEZÉS

szennyezőanyag-és földtani közeg minősége (mátrix), továbbá pH-értéke, hőmérséklete és ennek szervesanyag tartalma. A pH-tól, hőmérséklettől és a szervesanyagtól eltekintünk, állandónak feltételezzük. Az elérhető szakirodalmi adatbázisokban fellelhető, illetve hasonló kifejlődésű területekre épült modellek tapasztalatai alapján határoztuk meg a komponensekre jellemző Kd értékeket, rétegenként eltérően melyet az alábbi 2. táblázatban mutatunk be.

2. táblázat A modellezés során alkalmazott szorpciós paraméterek

|  réteg | szín kód | réteg minőség | PCE Kd (l/μg) | TPH* Kd (l/μg)  |
| --- | --- | --- | --- | --- |
|  1 |  | kissé iszapos homokos-feltöltés | 1.21E-10 | 1.4E-9  |
|  2 |  | homokos, agyagos-iszap | 8.01E-10 | 2.9E-8  |
|  3 |  | erősen kötött agyag | 3.12E-9 | 6.0E-8  |
|  4 |  | iszapos-homok | 5.11E-10 | 1.4E-9  |
|  5 |  | finomhomok/középhomok | 7.11E-11 | 5.2E-9  |
|  6 |  | homokos-kavics/kavicsos-durva homok | 4.55E-12 | 8.7E-9  |
|  7 |  | agyagfekü | 2.00E-9 | 6.0E-8  |

A modellezett komponensekre jellemző Koc-érték, mely a szerves széntartalomra normalizált megoszlási együttható, megmutatja, hogy milyen mértékű az adott komponens mobilitása, melyet az alábbi 3-4. táblázatokban részletezünk, melyből láthatjuk, hogy a modellezett klórozott alifás komponenseket többnyire a mérsékelt mobilitás, míg a TPH komponenseit a kevésbé mobilis tulajdonság jellemez, mely nagyon közel van az immobilis állapothoz.

A TPH komponens szénatomszám-eloszlása alapján a kimutatott szennyezettség átlagosan 97%-a C10-C40 frakcióba (EPH) tartozik. Míg az összegkomponenst részletezve megállapítottuk, hogy a szennyezés mintegy 11,87%-a C10-C12, 31,7 %-a C12-C16, 56,3 %-a C16-C35 szénatomszám-frakcióba tartozik. Tekintve a szennyezőanyag tömegmennyiségének mértékét, konzervatív megközelítést alkalmazva a legnagyobb %-os arányú eloszlásnak (>C16) megfelelő értéket alkalmaztuk.

Míg a DNAPL szennyezők esetén a klóratomszámok alapján az összes VOCl komponens 99,22%-át a tetraklór-etilén alkotja.

3. táblázat A modellezett komponens Koc paraméter

|  szennyező komponens | log Koc (l/kg)  |
| --- | --- |
|  PCE | 2,4  |
|  TPH | 4,8  |

KÉSZÍTETTE: ADEPT ENVIRO KFT.

15/24

Dokumentum azonosító: 0383/T/01/02 (Készült: 2026.04.30)

---

ADEPT ENVIRO KFT

Székhely: 1117 Budapest, Lágymányosi utca 12. Fszt. 2.
Iroda: 1095 Budapest, Máriássy utca 5.

+36-309-703-713
adeptenviro@adeptenviro.com

BUDAPEST XV., SZÖVŐGYÁR UTCA 19-21.

KIEGÉSZÍTŐ TÉNYFELTÁRÁSI ZÁRÓDOKUMENTÁCIÓ
HIDRODINAMIKAI-ÉS TRANSZPORT MODELLEZÉS

4. táblázat A modellezett komponens log Koc indexe³

|  Koc (mL/g or L/kg) | Log Koc (mL/g or L/kg) | Mobility Class  |
| --- | --- | --- |
|  < 10 | < 1 | Highly Mobile  |
|  10-100 | 1 - 2 | Mobile  |
|  100-1,000 | 2 - 3 | Moderately Mobile  |
|  1,000 - 10,000 | 3 - 4 | Slightly Mobile  |
|  10,000 - 100,000 | 4 - 5 | Hardly Mobile  |
|  > 100 ,000 | > 5 | Immobile  |

### 1.5.1.2. BOMLÁSI ÁLLANDÓ

A komponensek elsőrendű bomlási állandóját ennek anyagminősége (szén és klóratomszám) határozza meg, ugyanakkor jelentősen függ a felszín alatti rendszer ORP-viszonyaitól, az aktív mikrobiológiai környezettől és egyéb kémiai adottságoktól. Annak vonatkozásában, hogy a felső és az alsó vízadókban is többnyire aerob körülmények uralkodnak, így az első rendű bomlási állandó jól jellemzi a komponensek várható bomlását, melynek paramétereit az alábbi 5. táblázatban részletezzük.

5. táblázat A modellezés során alkalmazott bomlási paraméterek

|  komponens | bomlási állandó (1/d)  |
| --- | --- |
|  PCE | 0.000548  |
|  TPH* | 0.000334  |

*: anaerob környezetben, súlyozott frakciókkal

### 1.5.1.3. SZENNYEZŐANYAG SZÓRÓDÁS

A vizsgált szennyezőanyag szóródását alapvetően a diszperzió jelensége határozza meg ezen durva szemcsés vízadóban, míg a diffúzió hatásának jelentősége kisebb ugyanakkor nem elhanyagolható a finomszemcsés üledéktartalom miatt. A diffúziót jellemző paraméter a diffúziós-állandó, melynek értéke függ a koncentráció változástól és a közegbéli hőmérséklettől, de a modellszámítás során ezt rétegenként állandónak tekintjük.

Rétegenként eltérő diszperzió és diffúzió értékeket alkalmaztunk, melynek értékeit az alábbi 6. táblázatban részletezünk.

³ United States Environmental Protection Agency database

KÉSZÍTETTE: ADEPT ENVIRO KFT.

16/24

Dokumentum azonosító: 0383/T/01/02 (Készült: 2026.04.30)

---

ADEPT ENVIRO KFT

Székhely: 1117 Budapest, Lágymányosi utca 12. Fszt. 2.

Iroda: 1095 Budapest, Máriássy utca 5.

+36-309-703-713

adeptenviro@adeptenviro.com

BUDAPEST XV., SZÖVŐGYÁR UTCA 19-21.

KIEGÉSZÍTŐ TÉNYFELTÁRÁSI ZÁRÓDOKUMENTÁCIÓ

HIDRODINAMIKAI-ÉS TRANSZPORT MODELLEZÉS

6. táblázat A modellezés során alkalmazott diszperziós paraméterek

|  réteg | szín kód | horizontális/ longitudinális diszperzivitás (-) | vertikális/ longitudinális diszperzivitás (-) | diffúziós koeff. (m²/nap)  |
| --- | --- | --- | --- | --- |
|  1 |  | 0.09 | 0.009 | 3E-5  |
|  2 |  | 0.07 | 0.007 | 2E-5  |
|  3 |  | 0.03 | 0.003 | 4E-6  |
|  4 |  | 0.1 | 0.01 | 2.5E-5  |
|  5 |  | 0.12 | 0.012 | 3.5E-5  |
|  6 |  | 0.3 | 0.03 | 6E-5  |
|  7 |  | 0.02 | 0.002 | 5E-6  |

### 1.5.2. SZENNYEZŐFORRÁSBÓL TÖRTÉNŐ UTÁNPÓTLÓDÁS

A modellezés során figyelembe vettük a földtani közeg teljes feltárt szennyezőanyag mennyiségét, mely a szennyezett talajtestből a felszíni beszivárgás hatására a várható felszín alatti víz szennyezésének utánpótlódás mértékét határozza meg.

A transzportszámításokat megelőzően a területre kiterjedően, kellő mennyiségű, idősoros kalibrációs adathalmaz hiányában, szennyezőanyag tömegszámítást végeztünk. Konkrét információnk nem állt rendelkezésre arról, hogy mekkora volt a kiömlött, elfolyt szennyezőanyagok mennyisége, így számítással próbáltuk ezt megbecsülni. A földtani közegre és felszín alatti víz szennyezőanyag tömegmennyiségére kapott számítási eredményeket az alábbi 7-8. táblázatban mutatjuk be.

Földtani közegben meghatározott szennyezőanyag mennyisége (B) szennyezettségi határérték felett (7.táblázat):

|  primer szennyező | számított tömeg [kg]  |
| --- | --- |
|  összes VOCI (~PCE) | 2810  |
|  TPH | 147 100  |

Felszín alatti vízben meghatározott szennyezőanyag mennyisége (B) szennyezettségi határérték felett (8.táblázat):

|  primer szennyező | számított tömeg [kg]  |
| --- | --- |
|  összes VOCI (~PCE) | 608.8  |
|  TPH | 51.7  |

KÉSZÍTETTE: ADEPT ENVIRO KFT.

17/24

Dokumentum azonosító: 0383/T/01/02 (Készült: 2026.04.30)

---

ADEPT ENVIRO KFT

Székhely: 1117 Budapest, Lágymányosi utca 12. Fszt. 2.

Iroda: 1095 Budapest, Máriássy utca 5.

+36-309-703-713

adeptenviro@adeptenviro.com

BUDAPEST XV., SZÖVŐGYÁR UTCA 19-21.

KIEGÉSZÍTŐ TÉNYFELTÁRÁSI ZÁRÓDOKUMENTÁCIÓ

HIDRODINAMIKAI-ÉS TRANSZPORT MODELLEZÉS

A bemutatott tömegszámítás egy egyszerűsített módszer, ugyanakkor a fúrási feltárás sűrűségéből és az ebből nyert talajminták laboranalitikai eredményei alapján jó közelítéssel jellemzik a területen adszorbeálódott szennyezőanyag mennyiséget, így ebből jól becsülhető a szennyezőanyag tömegmennyisége, melyből a várható utánpótlódás mértéke megállapítható. A feltárt szennyezőanyag esetében a Surfer szoftver térfogat és felület számító függvénymodulja segítségével meghatároztuk a talajszelvényekben lévő szennyezőanyag mennyiségét, az előzetesen számított szennyezett talajtest átlagos koncentrációjának, térfogatának, ennek vastagságának és porozitásának ismeretében. Végül definiáltuk a szennyezett talajtestből (bennmaradó-és teljes talajmennyiség esetén is) kiáramló anyagfluxus (M) mennyiségét, az alábbi tömegfluxusegyenlet szerint:

$$M = \sum cqA \tag{1}$$

melyből az M: szennyezőanyag fluxus mennyiség [g/nap/felület], c: szelvényenkénti összegzett, felületi integrálból eredő, átlagos talajszennyezettségi koncentráció [mg/kg], q: a felszínről történő beszivárgás sebessége [mm/év], míg A: a szennyezett talajtest egységnyi felülete [m²]. A felszín alatti rendszerben lévő egyensúlyi állapot az adszorbeált és deszorbeált anyagmennyiségek között az alábbi egyenlet alapján írható fel:

$$\Theta \cdot dV \frac{\partial C}{\partial t} = -\rho_b \cdot dV \frac{\partial C'}{\partial t} \tag{2}$$

ahol C: a pórusfolyadék koncentrációja, C': a szennyezőanyag koncentrációja a talajban, míg ρb: a porózus közeg testsűrűsége és Θ a térfogatszázalékban kifejezett víztartalom, amely telített közegben egyenlő a hézagtérfogattal és V a teljes vizsgált térfogat. Amennyiben a kémiai egyensúly már kialakult – jelen esetben a feltételezések szerint több évtizede a felszín alatti közegben van a szennyezőcsopo C' = KdC megkötött anyag koncentrációja számítható az alábbi összefüggéssel:

(3)

Jelen felszín alatti környezetben a feltárt talajszennyezés a telített és telítetlen közegben is van egyaránt, így a megoszlási hányados és a talajban lévő átlagos koncentráció viszonyok alapján kell meghatároznunk a pórusvíz szennyezőanyag koncentráció tartalmát (C). Az így nyert koncentráció adatot a fluxus egyenlet (1) pórusvíz koncentrációjához behelyettesítve megkapjuk, hogy a szennyezett talajtest felületén átáramló, azaz a felszínről leszivárgó csapadék évente mekkora mennyiségű szennyezőanyagot old ki, így áramoltat a talajvízbe. A fejezetben bemutatott számítások alapján az (1) szennyezőanyag-fluxus egyenletet megoldva meghatároztuk a komponensek anyagfluxus viszonyait:

KÉSZÍTETTE: ADEPT ENVIRO KFT.

18/24

Dokumentum azonosító: 0383/T/01/02 (Készült: 2026.04.30)

---

ADEPT ENVIRO KFT

Székhely: 1117 Budapest, Lágymányosi utca 12. Fszt. 2.
Iroda: 1095 Budapest, Máriássy utca 5.

+36-309-703-713
adeptenviro@adeptenviro.com

BUDAPEST XV., SZÖVŐGYÁR UTCA 19-21.

KIEGÉSZÍTŐ TÉNYFELTÁRÁSI ZÁRÓDOKUMENTÁCIÓ
HIDRODINAMIKAI-ÉS TRANSZPORT MODELLEZÉS

**PCE (tetraklór-etén)** esetén a meghatározott anyagfluxus: 3,85 kg/év/felület, mely a bennmaradó teljes szelvény vastagságban lévő PCE szennyezőanyag-mennyiség, konzervatívan számítva minimálisan még legalább 95 évig táplálja a talajvízben oldott szennyeződését, melyet követően megszűnik a komponens utánpótlódása.

**TPH** esetén a meghatározott anyagfluxus: 18,1 kg/év/felület, mely a bennmaradó teljes szelvény vastagságban lévő TPH szennyezőanyag-mennyiség, konzervatívan számítva több, mint 200 évig táplálja a talajvízben oldott szennyeződését, melyet követően megszűnik a komponens utánpótlódása.

A terjedési számítások során Mass-loading típusú transzport peremfeltéltelt alkalmaztuk, ahol a számított tömegmennyiség beoldódását adtuk meg anyagfluxusként (M/T).

KÉSZÍTETTE: ADEPT ENVIRO KFT.

19/24

Dokumentum azonosító: 0383/T/01/02 (Készült: 2026.04.30)

---

ADEPT ENVIRO KFT

Székhely: 1117 Budapest, Lágymányosi utca 12. Fszt. 2.
Iroda: 1095 Budapest, Máriássy utca 5.

+36-309-703-713
adeptenviro@adeptenviro.com

BUDAPEST XV., SZÖVŐGYÁR UTCA 19-21.

KIEGÉSZÍTŐ TÉNYFELTÁRÁSI ZÁRÓDOKUMENTÁCIÓ
HIDRODINAMIKAI-ÉS TRANSZPORT MODELLEZÉS

## 1.6. MODELLEZÉS EREDMÉNYEI

### 1.6.1. HIDRAULIKAI MODELL

A hidraulikai modellszámítást permanens állapotra végeztük, mely során a szivárgási egyenlet paramétereit fokozatosan változtatva finomhangoltuk a számítási eredményeket, míg a kapott értékek jól közelítették a valóságban mért értékeket, melynek eredménye szerint a kalibrációs adathalmazunk megfelelő illesztést ért el, mely a hidraulikai input adathalmaz megfelelőségét mutatja, ezzel alkalmassá téve a modellt a szennyező komponensek transzport vizsgálatára. A modellben alkalmazott számított nyomáseloszlásokat a **1F-3** és **1F-4. mellékletek**ben mutatjuk be.

![img-6.jpeg](img-6.jpeg)

6. ábra Hidraulikai kalibrációs pontdiagram – F és A vízadó esetén

(NRMS: 5,994 %, standard hiba: 0,011m; R²: 94,1%)

Az alábbi **7-8. ábra** sorozaton bemutatjuk a felszín alatti térben lévő áramlási sebességvektorokat, miszerint a vasút környezetében a vízadó elvékonyodik, megnő a sebesség (melyet a nagyobb méretű vektornyíl jelez), mely ezen a térrészen várhatóan az oldott csóva nagyobb ütemű terjedését indukálja. Ebből adódóan is rendkívül fontos a patak túloldalának közvetlen környezetében a földtani és hidraulikai viszonyokat megismerni, különösen a vízadók vastagságát, melyben az anyagtranszport zajlik.

KÉSZÍTETTE: ADEPT ENVIRO KFT.

20/24

Dokumentum azonosító: 0383/T/01/02 (Készült: 2026.04.30)

---

ADEPT ENVIRO KFT

Székhely: 1117 Budapest, Lágymányosi utca 12. Fszt. 2.

Iroda: 1095 Budapest, Máriássy utca 5.

+36-309-703-713

adeptenviro@adeptenviro.com

BUDAPEST XV., SZÖVŐGYÁR UTCA 19-21.

KIEGÉSZÍTŐ TÉNYFELTÁRÁSI ZÁRÓDOKUMENTÁCIÓ

HIDRODINAMIKAI-ÉS TRANSZPORT MODELLEZÉS

![img-7.jpeg](img-7.jpeg)

7. ábra Felszín alatti sebesség alakulása: Ny-K szelvény

![img-8.jpeg](img-8.jpeg)

8. ábra Felszín alatti sebesség alakulása: É-D szelvény

KÉSZÍTETTE: ADEPT ENVIRO KFT.

21/24

Dokumentum azonosító: 0383/T/01/02 (Készült: 2026.04.30)

---

ADEPT ENVIRO KFT

Székhely: 1117 Budapest, Lágymányosi utca 12. Fszt. 2.
Iroda: 1095 Budapest, Máriássy utca 5.

+36-309-703-713
adepteriviro@adepteriviro.com

BUDAPEST XV., SZÖVŐGYÁR UTCA 19-21.

KIEGÉSZÍTŐ TÉNYFELTÁRÁSI ZÁRÓDOKUMENTÁCIÓ
HIDRODINAMIKAI-ÉS TRANSZPORT MODELLEZÉS

## 1.6.2. TRANSZPORT MODELLEZÉS

A transzport számítások során két szennyező komponens (PCE, TPH) térbeli-és időbeli változását vizsgáltuk 10, illetve 20 éves terjedési időintervallumra vonatkozóan, beavatkozás nélküli esetben. Permanens állapotban már egy 5-10 éves intervallumban történő modellszámítás is jelentős bizonytalanságokat tartalmaz, ugyanakkor a környezetben mért felszín alatti adatsorok alapján jó közelítésre alkalmas. A számítás célja volt, hogy megállapítsuk az oldott komponensek várható terjedési ütemét és mértékét kármentesítési eljárás nélkül a vizsgált 10-20 éves időszakban. A korábbi években elvégzett állapotfelmérés, majd tényfeltárási sorozatok alapján során meghatároztuk a gócterületen lévő talajhoz kötött szennyezőanyagok mennyiségét és területi eloszlását, melyek a felszín alatti víz számára utánpótlódás forrásként szolgál jelenleg.

Ahogyan már fentebb részleteztük a számításokat a Szilas-patak nyomvonaláig tudtuk megfelelően értelmezni, ugyanis az ettől északra lévő területeken (illetve a patak jobb partjától északra) nem ismert kellő részletességgel, különösen a patakmeder teraszanyagának nyomás viszonyai és földtana, így jelen fázisban ezen térrészen inaktivitást alkalmaztunk a cella transzportok során.

A bomlástermékek koncentrációi, illetve az ÁVK paraméterek koncentrációja, továbbá a mintavételkori helyszíni ORP értékekből láthatjuk, hogy aktívan zajló degradációs folyamat van, ugyanakkor jelenleg, olyan mennyiségű és mértékű szennyezőanyag van a felszín alatti közegben, hogy az utánpótlódás hajtóereje nagyobb, mint ahogyan az átalakulás, lebontás végbemegy. Számítási eredményeink a PCE komponens esetében a reziduális talajszennyezés még legalább 95 évig biztosít szennyezőanyag utánpótlódást a felszín alatti víz számára, melyet követően kiürül. Ezen időszak alatt kismértékű koncentráció növekmény is valószínűsíthető a gócterületen, mind koncentráció mind pedig ennek területi kiterjedése tekintetében. A 10 éves majd 20 éves terjedési időket figyelembe véve azt látjuk, hogy a szemcsés vízadókban csekély mértékben összehúzódik a csóvatest a peremi területen, kissé nyugatra tolódik majd az áramlási iránynak megfelelően, ugyanakkor a csóvatest belső területein megnövekedhet a magas oldott koncentrációjú zónák területe. A modellezett komponensek várható transzportviszonyait a 2F-1, 2F-2 és 3F ábrákon mutatjuk be.

Végül, végeztünk egy 'fiktív' szimulációt, mely esetben nem vettük figyelembe a Szilas-patak régi medervonal drénező hatását – ami jelentősen módosítani fogja a terjedési irányokat és mértéket –, mely számítással a térség felszín alatti transzport viszonyaira vonatkozóan kaptunk egy közelítő adatot. Ez alapján PCE esetében az alsó vízadóban mintegy 295 m-t haladhat az oldott csóvaperem a következő 20 évben. Erről a számítási eredményről nem készült külön mellékletben, csupán az alábbiakban, 8. szövegközi ábraként mutatjuk be.

KÉSZÍTETTE: ADEPT ENVIRO KFT.

22/24

Dokumentum azonosító: 0383/T/01/02 (Készült: 2026.04.30)

---

ADEPT ENVIRO KFT

Székhely: 1117 Budapest, Lágymányosi utca 12. Fszt. 2.
Iroda: 1095 Budapest, Máriássy utca 5.

+36-309-703-713
adeptenviro@adeptenviro.com

BUDAPEST XV., SZÖVŐGYÁR UTCA 19-21.

KIEGÉSZÍTŐ TÉNYFELTÁRÁSI ZÁRÓDOKUMENTÁCIÓ
HIDRODINAMIKAI-ÉS TRANSZPORT MODELLEZÉS

A modellszámítások eredményei alapján összességében **PCE komponens** alsó vízadóban való transzportja esetében megállapíthatjuk, hogy a következő 20 évben tovább terjed az oldott szennyezés, megnyúlik az oldott gócterület mértéke, míg kismértékben elvékonyodhat a degradációs folyamatok miatt, illetve megnyúlik a csóvafront. Ugyanakkor a pontos terjedési tulajdonságok előrejelzéshez feltétlen szükséges feltárni a patakmeder jobb és balparti hidraulikai viszonyait.

A PCE felső vízadóját az alsó kavicsos üledékhez képest, jóval finomabb szemcsés homok, néhol iszapos-homok alkotja melynek diszperziós és szorpciós tulajdonságai nagyságrenddel eltérnek az alsóbb réteg vízadójához képest. Továbbá a rétegben meghatározott gradiens mértéke is kisebb. Ezen kezdeti feltételekből kiindulva a felsőbb réteg csóvafronti, hosszirányú terjedése jóval kisebb, továbbá a peremi koncentrációk mértéke a természetes bomlásból adódóan csökken. Ugyanakkor jelentős különbség, hogy a gócterület környezetében erőteljesen megnövekszik az oldott koncentráció kiterjedése, ebben a vízadóban erőteljesebb a diffúzió, mely a koncentráció különbségek miatt hajtóenergiaként szolgál az oldott szennyezés további terjedésének.

TPH esetében, ennek minőségéből adódóan csak a felső vízadóban vizsgáltuk a transzportját, melynek eredményei alapján a TPH helyben marad, nem terjed majd az évtizedek során, fokozatos, nagyon kismértékű összehúzódás valószínűsíthető. A TPH ezen frakciók oldhatósága ugyanakkor nem érik el a szennyezettségi határértéket, így a felszín alatti vízben a laboratóriumban mért szénhidrogén koncentrációk részben a mintavételi körülmények, részben a laboratóriumi akkreditált mintaelőkészítés következtében állhattak elő. Ugyanakkor a frakciók súlyozásával és a meghatározott kezdeti koncentrációk alapján végeztük a transzportszámításokat. A TPH kapott számítási eredményeit ábramellékleten nem részletezzük, ugyanis területi zsugorodás mértéke elhanyagolható.

**Összegezve a felszín alatti vízben oldott PCE komponens beavatkozás nélkül a következő 20 évben biztosan tovább szennyezi a környezetét, míg TPH esetében további terjedés nem várható.**

KÉSZÍTETTE: ADEPT ENVIRO KFT.

23/24

Dokumentum azonosító: 0383/T/01/02 (Készült: 2026.04.30)

---

ADEPT ENVIRO KFT

Székhely: 1117 Budapest, Lágymányosi utca 12. Fszt. 2.

Iroda: 1095 Budapest, Máriássy utca 5.

+36-309-703-713

adeptenviro@adeptenviro.com

BUDAPEST XV., SZÖVŐGYÁR UTCA 19-21.

KIEGÉSZÍTŐ TÉNYFELTÁRÁSI ZÁRÓDOKUMENTÁCIÓ

HIDRODINAMIKAI-ÉS TRANSZPORT MODELLEZÉS

![img-9.jpeg](img-9.jpeg)

8. ábra Fiktív terjedési ütem PCE – Alsó vízadóban

KÉSZÍTETTE: ADEPT ENVIRO KFT.

24/24

Dokumentum azonosító: 0383/T/01/02 (Készült: 2026.04.30)
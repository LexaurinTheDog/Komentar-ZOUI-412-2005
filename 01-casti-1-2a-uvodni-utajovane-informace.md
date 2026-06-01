# Část první — Základní ustanovení & Část druhá (Hlavy I–X) — Ochrana utajovaných informací (§§ 1–62)

> **Téma kapitoly:** První kapitola komentáře pokrývá **Část první** zákona č. 412/2005 Sb., o ochraně utajovaných informací a o bezpečnostní způsobilosti (dále „**ZOÚI**" či „**zákon**"), tedy předmět úpravy (§ 1) a vymezení pojmů (§ 2), a první polovinu **Části druhé**, která tvoří materiální jádro celé úpravy — vlastní ochranu utajovaných informací. V této části zákon zavádí klíčové dogmatické konstrukce: **trojstupňovou škálu újmy zájmu České republiky** a **čtyřstupňovou škálu utajení** (§§ 3–4 — Vyhrazené, Důvěrné, Tajné, Přísně tajné), **šest pilířů ochrany** (§ 5 — personální, průmyslová, administrativní, fyzická, IS/KS a kryptografická bezpečnost), strukturuje **podmínky přístupu fyzických osob a podnikatelů** k utajovaným informacím (Hlavy II–III), upravuje **manipulaci s utajovanými informacemi** (administrativní bezpečnost — Hlava IV), **fyzickou bezpečnost objektů a oblastí** (Hlava V), bezpečnost **informačních a komunikačních systémů** (Hlava VI), ochranu při zpracování v zařízeních mimo IS/KS (Hlava VII), **kryptografickou ochranu** včetně kompromitujícího vyzařování (Hlava VIII), **certifikaci** technických prostředků, IS, kryptografických prostředků, pracovišť a stínicích komor (Hlava IX) a režim **osvědčení fyzické osoby, osvědčení podnikatele a zvláštních přístupů** (Hlava X v rozsahu §§ 54–62).

> **Architektonický klíč:** Zákon je strukturován do tří úrovní ochrany, které se vzájemně podmiňují — **bezpečnost informace** (její klasifikace, označení, manipulace), **bezpečnost osoby** (kdo k informaci smí), a **bezpečnost prostředí** (kde a jak se s informací nakládá: objekty, IS, KS, kryptoprostředky). Ústředním orgánem dozoru je **Národní bezpečnostní úřad** (zkratka **Úřad** ve smyslu legislativní zkratky § 6 odst. 3), jehož kompetence se ovšem od velké novely (zákon č. 205/2017 Sb., účinný od 1. 8. 2017) v oblasti IS, kryptografické ochrany a kompromitujícího vyzařování dělí s **Národním úřadem pro kybernetickou a informační bezpečnost** (NÚKIB). Tato dualita gestora je v komentáři systematicky zdůrazňována.

---

## ČÁST PRVNÍ — ZÁKLADNÍ USTANOVENÍ

### § 1 — Předmět úpravy

> **§ 1**
>
> *Tento zákon upravuje zásady pro stanovení informací jako informací utajovaných, podmínky pro přístup k nim a další požadavky na jejich ochranu, zásady pro stanovení citlivých činností a podmínky pro jejich výkon a s tím spojený výkon státní správy.*

**Výklad:**

#### Dvojí osa působnosti — utajované informace a citlivé činnosti

Předmět úpravy je formulován **dvouosově**. První osa pokrývá oblast **utajovaných informací** (Část druhá zákona): zásady pro klasifikaci informace jako utajované, podmínky přístupu (personální a průmyslová bezpečnost) a požadavky na její ochranu (administrativní, fyzická, IS/KS, kryptografická). Druhá osa se týká tzv. **citlivých činností** a **bezpečnostní způsobilosti** (Část třetí — vně rozsahu této kapitoly): jde o činnosti, jejichž neoprávněný výkon by mohl ohrozit zájmy státu, aniž by přitom šlo o klasický přístup k utajované informaci (typicky činnosti v jaderné energetice, na letištích, u kritické infrastruktury — řešeno v §§ 80 a násl.).

Třetí, sekundární osou je úprava **výkonu státní správy** na tomto úseku — kompetence Národního bezpečnostního úřadu (dále „**Úřad**"), Národního úřadu pro kybernetickou a informační bezpečnost (dále „**NÚKIB**"), Ministerstva vnitra v případech podle § 141, zpravodajských služeb v případech podle § 140 a kompetence Ministerstva obrany v oblasti vojenského kryptografického materiálu a NATO COSMIC TOP SECRET (§ 43a).

#### Postavení zákona v právním řádu — lex specialis ke svobodnému přístupu k informacím

ZOÚI je **lex specialis** vůči zákonu č. 106/1999 Sb., o svobodném přístupu k informacím — utajovaná informace je z působnosti zákona č. 106/1999 Sb. vyloučena (§ 7 InfZ). Zákon současně provádí ústavní mantinely čl. 17 odst. 4 Listiny základních práv a svobod, dle něhož lze svobodu projevu a právo na informace omezit zákonem, jde-li mj. o opatření v demokratické společnosti nezbytná pro ochranu bezpečnosti státu, veřejné bezpečnosti a ochrany práv a svobod druhých. Ústavní soud v nálezu sp. zn. Pl. ÚS 11/2000 (k zákonu č. 148/1998 Sb., předchůdci ZOÚI) potvrdil, že utajování informací představuje ústavně přípustný zásah, je-li ovládáno principem proporcionality a podléhá řádnému soudnímu přezkumu.

#### Vztah k dalším zákonům

- **Zákon č. 240/2000 Sb., krizový zákon** — ZOÚI se uplatní i za krizových stavů (krizový stav je v § 57 odst. 9 ZOÚI legislativně definován).
- **Zákon č. 153/1994 Sb., o zpravodajských službách ČR** — § 140 ZOÚI deleguje výkon některých kompetencí na BIS, ÚZSI a Vojenské zpravodajství u jejich příslušníků.
- **Zákon č. 273/2008 Sb., o Policii ČR** — § 141 ZOÚI deleguje obdobné kompetence na Ministerstvo vnitra ve vztahu k vybraným policistům.
- **Zákon č. 181/2014 Sb., o kybernetické bezpečnosti** — ZoKB řeší ochranu IS jakožto kritické informační infrastruktury obecně; ZOÚI má užší dosah (jen IS nakládající s utajovanými informacemi), avšak silnější ochranné standardy (certifikace NÚKIB ex ante).
- **Zákon č. 90/1995 Sb., o jednacím řádu Poslanecké sněmovny** a zákon č. 107/1999 Sb., o jednacím řádu Senátu — řeší kontrolu nakládání s utajovanými informacemi v parlamentní práci.
- **Trestní zákoník** (zákon č. 40/2009 Sb.) — § 316 (vyzvědačství), § 317 (ohrožení utajované informace), § 318 (ohrožení utajované informace z nedbalosti) — trestněprávní úsek ochrany.

#### Mezinárodněprávní rozměr

Ochrana utajovaných informací je významně **harmonizována mezinárodně**: ČR je vázána zejména:
- Smlouvou o NATO a navazující bezpečnostní politikou C-M(2002)49 a C-M(2002)50,
- právem EU — zejm. rozhodnutím Rady 2013/488/EU o bezpečnostních pravidlech na ochranu utajovaných informací EU (EUCI),
- bilaterálními dohodami o vzájemné ochraně utajovaných informací (typicky se státy NATO, EU, Švýcarskem, Izraelem, Ukrajinou aj.).

Zákon na tyto závazky reaguje výslovně — § 21 odst. 2 (převzetí značení cizí mocí), § 21 odst. 11 (zničení EUCI), § 23 odst. 4 (sdělení převodních tabulek), § 43a (distribuce kryptomateriálu NATO/EU), § 57 (osvědčení pro cizí moc).

---

### § 2 — Vymezení pojmů

> **§ 2**
>
> *Pro účely tohoto zákona se rozumí*
>
> *- a) utajovanou informací informace v jakékoliv podobě označená stupněm utajení podle tohoto zákona, jejíž vyzrazení nebo zneužití může způsobit újmu zájmu České republiky nebo může být pro tento zájem nevýhodné, a kterou lze podřadit pod položku uvedenou v katalogu oblastí utajovaných informací (§ 139),*
>
> *- b) zájmem České republiky zachování její ústavnosti, svrchovanosti a územní celistvosti, zajištění vnitřního pořádku a bezpečnosti, mezinárodních závazků a obrany, ochrana ekonomiky a ochrana života nebo zdraví fyzických osob,*
>
> *- c) porušením povinnosti při ochraně utajované informace porušení povinnosti uložené tímto zákonem nebo na základě tohoto zákona,*
>
> *- d) orgánem státu organizační složka státu (...), kraj, hlavní město Praha, městská část hlavního města Prahy a obec při výkonu státní správy ve věcech, které stanoví zvláštní právní předpis; orgánem státu se rozumí i zpravodajské služby a Česká národní banka,*
>
> *- e) odpovědnou osobou* [katalog 16 typů odpovědné osoby — od ministra po tajemníka úřadu městské části, řediteli zpravodajských služeb, guvernér ČNB, statutární orgán právnické osoby — podnikatele, vedoucí Kanceláře PSP/Senátu],
>
> *- f) původcem utajované informace orgán státu, právnická osoba podle § 60b nebo podnikatel, u nichž utajovaná informace vznikla, nebo Úřad průmyslového vlastnictví podle § 70 odst. 4,*
>
> *- g) cizí mocí cizí stát nebo jeho orgán anebo nadnárodní nebo mezinárodní organizace nebo její orgán,*
>
> *- h) neoprávněnou osobou osoba, která nesplňuje podmínky přístupu k utajované informaci stanovené tímto zákonem,*
>
> *- i) poučením písemný záznam o seznámení fyzické osoby s jejími právy a povinnostmi v oblasti ochrany utajovaných informací a s následky jejich porušení,*
>
> *- j) bezpečnostním standardem utajovaný soubor pravidel (...) pro zajištění nejmenší možné míry ochrany utajovaných informací,*
>
> *- k) bezpečnostním provozním módem prostředí, ve kterém informační systém pracuje, charakterizované stupněm utajení zpracovávané utajované informace a úrovněmi oprávnění uživatelů.*

**Výklad:**

#### Pojem utajované informace [písm. a)] — třísložkový test

Definice utajované informace je **trojkonjunktivní** (kumulativní): aby šlo o utajovanou informaci, musí být splněny **současně tři podmínky**:

1. **Formální označení** stupněm utajení podle § 4 (Vyhrazené, Důvěrné, Tajné, Přísně tajné). Bez označení (nebo bez postupu podle § 4 odst. 3–5 u ústního, elektronického či analogového zpřístupnění) o utajovanou informaci nejde — princip „**konstitutivního označení**". Tento aspekt má zásadní procesní důsledky: pokud původce informaci neoznačil, nelze ji následně chránit jako utajovanou bez retrospektivní klasifikace (viz § 22).
2. **Materiální obsah** — vyzrazení nebo zneužití může způsobit **újmu** zájmu ČR (definováno v § 3 odst. 1–4 ve třech stupních: mimořádně vážná, vážná, prostá újma), nebo být pro tento zájem **nevýhodné** (§ 3 odst. 5 — kategorie pro stupeň Vyhrazené). Klíčové je modální sloveso „**může**" — zákon nevyžaduje, aby újma reálně vznikla, postačí potenciální způsobilost informace újmu způsobit.
3. **Katalogová způsobilost** — informaci lze podřadit pod položku v **katalogu oblastí utajovaných informací** podle § 139 (vydávaného nařízením vlády č. 522/2005 Sb., ve znění pozdějších předpisů). Katalog je taxativní v tom smyslu, že informaci, kterou pod žádnou položku katalogu podřadit nelze, **nelze utajit**. Tím je dáno **negativní vymezení utajovatelnosti** — bezpečnostní orgán nemůže utajit cokoliv, jen položky stanovené vládou.

Tato třísložková konstrukce je systematickým rozdílem oproti předchozí úpravě (zákon č. 148/1998 Sb.), kde materiální kritérium dominovalo bez explicitního katalogu. Současná konstrukce je výsledkem snahy zákonodárce omezit svévoli při klasifikaci a zajistit její přezkoumatelnost — soud (zejm. NSS) může ověřit, zda informace skutečně spadá pod položku katalogu (rozsudek NSS sp. zn. 5 As 41/2009).

#### Forma informace — irrelevantní

Slovní obrat „v jakékoliv podobě" reflektuje technologickou neutralitu zákona. Utajovanou informací může být:
- **písemný dokument** v analogové (papír) i elektronické podobě (§ 4 odst. 4 a 5),
- **ústní sdělení** (§ 4 odst. 3 — ústní prohlášení),
- **obrazové či zvukové zpřístupnění** (§ 4 odst. 3),
- **fyzický předmět**, jehož samotná existence či vlastnosti jsou utajované (kryptografické zařízení, vzorek zbraně, model),
- **informace v paměti počítače** apod.

#### Zájem České republiky [písm. b)] — taxativní katalog 6 zájmů

Pojem „zájem ČR" je definován taxativně **šesti chráněnými hodnotami**:

| Hodnota | Obsah |
|---|---|
| Ústavnost | Existence a fungování ústavních orgánů, demokratický právní stát |
| Svrchovanost | Vnější nezávislost státu |
| Územní celistvost | Integrita státního území |
| Vnitřní pořádek a bezpečnost | Vnitřní bezpečnost, veřejný pořádek, ochrana proti vnitřním hrozbám |
| Mezinárodní závazky a obrana | Plnění závazků z NATO, EU, dalších smluv; obranyschopnost |
| Ochrana ekonomiky | Měnová a finanční stabilita, zahraničně-obchodní zájmy |
| Ochrana života nebo zdraví FO | Plošná ochrana populace (typicky v krizových režimech, CBRN) |

Tento výčet je **uzavřený** — informace, jejíž vyzrazení by mohlo poškodit jiný „zájem" (např. čistě komerční zájem konkrétního podnikatele bez vazby na ekonomickou bezpečnost státu), není utajovanou informací ve smyslu ZOÚI; jde-li o obchodní tajemství, chrání se podle občanského zákoníku a zákona o obchodních korporacích.

#### Orgán státu [písm. d)] — široké pojetí včetně samosprávy

Definice „orgánu státu" zahrnuje nejen organizační složky státu podle zákona č. 219/2000 Sb. (ministerstva, jiné ústřední správní úřady, soudy, státní zastupitelství, Kancelář prezidenta, Kanceláře PSP a Senátu, ÚSC ve významu zákona o majetku státu apod.), ale výslovně i **kraje, hlavní město Praha, městské části HMP a obce** — ovšem **pouze při výkonu státní správy** ve věcech, které stanoví zvláštní předpis (typicky výkon přenesené působnosti v oblasti krizového řízení, civilní ochrany, evidence obyvatel). Při výkonu samostatné působnosti se obec orgánem státu pro účely ZOÚI nestává.

Specificky se za orgán státu považují **zpravodajské služby** (BIS, ÚZSI, Vojenské zpravodajství) a **Česká národní banka** — bez ohledu na jejich postavení ústředního správního úřadu (zákonem č. 153/1994 Sb. a zákonem č. 6/1993 Sb. jsou samostatnými právními subjekty).

#### Odpovědná osoba [písm. e)] — 16 typů

Katalog odpovědných osob je výslovně taxativní a zajišťuje, že každý subjekt nakládající s utajovanými informacemi má jednoznačně určenou „špičku" odpovědnosti. Klíčové typy:

| Subjekt | Odpovědná osoba |
|---|---|
| Ministerstvo | Ministr |
| Jiný ústřední správní úřad (jednočlenný) | Předseda |
| Jiný ústřední správní úřad (kolektivní) | FO, která řídí činnost orgánu |
| Zpravodajská služba | Ředitel |
| ČNB | Guvernér |
| Kraj | Ředitel krajského úřadu |
| HMP | Ředitel magistrátu |
| Statutární město | Tajemník magistrátu |
| Obec (jiná) | Tajemník úřadu, není-li, starosta |
| Podnikatel — PO | Statutární orgán (FO) |
| Podnikatel — FO | Tato FO |
| Poslanecká sněmovna | Vedoucí Kanceláře PSP |
| Senát | Vedoucí Kanceláře Senátu |

Odpovědná osoba je adresátem řady neperenosných povinností (vydání oznámení o splnění podmínek pro přístup k Vyhrazenému, schválení projektu fyzické bezpečnosti, schválení IS do provozu atd.). Část svých kompetencí může delegovat na **bezpečnostního ředitele** (§ 71) a na **jí pověřené osoby**, nicméně právní odpovědnost zůstává primárně u ní.

#### Bezpečnostní standard [písm. j)] — utajovaný předpis nižší síly

Zvláštní kategorií je „**bezpečnostní standard**" — soubor pravidel, který sám o sobě je utajovanou informací (proto není publikován ve Sbírce zákonů) a stanoví **minimální** bezpečnostní opatření. Standardy vydává Úřad nebo NÚKIB v rámci své věcné kompetence (§ 137 ZOÚI). Z hlediska teorie pramenů práva jde o **vnitřní předpis veřejné správy** s vázanou působností pro subjekty, jež nakládají s utajovanými informacemi; jejich „utajenost" je sama o sobě legitimním omezením publikace, jež však vyvolává polemiku v doktríně i mezinárodní kritiku (recommandace expertních misí — např. GRECO, OECD).

#### Bezpečnostní provozní mód [písm. k)]

Termín z oblasti IS, který charakterizuje souběh dvou veličin: **maximální stupeň utajení zpracovávané informace** a **úroveň oprávnění uživatelů**. Konkrétní typologie módů (dedicated mode, system high, compartmented, multilevel) je dále upravena prováděcí vyhláškou č. 523/2005 Sb. a navazujícími standardy NÚKIB; pojem koresponduje s terminologií NATO (SECAN).

---

## ČÁST DRUHÁ — OCHRANA UTAJOVANÝCH INFORMACÍ

### Hlava I — Úvodní ustanovení

### § 3 — Újma zájmu České republiky a nevýhodnost pro zájmy České republiky

> **§ 3 odst. 1**
>
> *Újmou zájmu České republiky se pro účely tohoto zákona rozumí poškození nebo ohrožení zájmu České republiky. Podle závažnosti poškození nebo ohrožení zájmu České republiky se újma člení na mimořádně vážnou újmu, vážnou újmu a prostou újmu.*

(Odstavce 2–5 obsahují katalogy konkrétních následků pro každou kategorii.)

**Výklad:**

#### Trojstupňová škála újmy + kategorie „nevýhodnost"

§ 3 zavádí **kvalitativně odstupňovanou škálu** materiálního kritéria pro klasifikaci informace. Pojem **újma** sám o sobě má dva komponenty:
- **poškození** — již realizovaný negativní následek (př. odhalení agenta, fyzická ztráta na životech),
- **ohrožení** — vznik reálného nebezpečí takového následku, byť ještě nenastalo.

Třístupňová škála **újmy** je doplněna o čtvrtou, kvalitativně nižší kategorii — **nevýhodnost pro zájmy ČR** (odst. 5), která vytváří materiální podklad pro nejnižší stupeň utajení **Vyhrazené**. „Nevýhodnost" je definována jako stav, který je sice negativní, avšak nedosahuje intenzity „újmy" — typicky komplikuje práci zpravodajských služeb, narušuje obchodní jednání, ohrožuje vyšetřování běžných (nikoli „zvlášť závažných") trestných činů.

#### Mimořádně vážná újma (odst. 2) — kvalifikované katastrofické následky

Odst. 2 vypočítává osm typů následků, jež zakládají mimořádně vážnou újmu (a tedy stupeň Přísně tajné):
- **bezprostřední** ohrožení svrchovanosti, územní celistvosti, demokratických základů,
- **rozsáhlé** ztráty na životech nebo rozsáhlé ohrožení zdraví obyvatel,
- **mimořádně vážné nebo dlouhodobé** poškození ekonomiky,
- **značné** narušení vnitřního pořádku a bezpečnosti,
- **mimořádně vážné** ohrožení zpravodajských operací,
- **mimořádně vážné** ohrožení činnosti NATO, EU nebo členského státu,
- **mimořádně vážné** ohrožení bojeschopnosti AČR / NATO / EU,
- **mimořádně vážné** poškození diplomatických vztahů s NATO/EU.

Kvalifikátor „mimořádně vážný"/„značný"/„rozsáhlý" má normativně-interpretační funkci — odlišuje od následků uvedených v odst. 3 (Tajné), jež jsou typově shodné, ovšem s nižší kvalifikací intenzity. Z dogmatického hlediska jde o **klouzavou škálu (sliding scale)**, kdy hranice mezi jednotlivými stupni je nezbytně interpretačně otevřená — výklad provádí původce informace, jeho rozhodnutí je však následně přezkoumatelné Úřadem (§ 22 odst. 9) a v krajním případě i soudem.

#### Vážná újma (odst. 3) — stupeň Tajné

Devět typů následků, paralelních k odst. 2, s nižší intenzitou: „ohrožení" (bez kvalifikátoru „bezprostřední"), „značná škoda" (oproti „mimořádně vážnému dlouhodobému poškození"), „ztráty na životech" (oproti „rozsáhlým"), „vážné ohrožení", „vážné zvýšení mezinárodního napětí".

#### Prostá újma (odst. 4) — stupeň Důvěrné

Osm typů následků s ještě nižší intenzitou. Klíčová je zde **distinkce vůči nevýhodnosti** (odst. 5):
- prostá újma — *zmaření, ztížení nebo ohrožení prověřování nebo vyšetřování **zvlášť závažných zločinů***;
- nevýhodnost — *zmaření, ztížení nebo ohrožení prověřování nebo vyšetřování **ostatních trestných činů***.

Tato dichotomie reflektuje obecné kategorie trestního zákoníku (§ 14 odst. 3 TZ) — zvlášť závažný zločin je úmyslný čin se sazbou nejméně 10 let.

#### Nevýhodnost (odst. 5) — stupeň Vyhrazené

Pět typů následků pro nejnižší stupeň. Mimo již uvedené (vyšetřování běžných trestných činů) zahrnuje narušení činnosti AČR/NATO/EU, poškození významných ekonomických zájmů, narušení obchodních či politických jednání ČR s cizí mocí, narušení bezpečnostních operací.

#### Pravidlo nejvyššího stupně při slučování informací (vazba na § 4 odst. 2)

§ 3 nutno systematicky číst spolu s § 4 odst. 2 — sestává-li dokument z dílčích utajovaných informací různých stupňů, řídí se **nejvyšším** z nich nebo vyšším. To brání tzv. **agregačnímu úniku** — kdy by součet jednotlivě méně chráněných informací odhalil informaci vyššího stupně.

---

### § 4 — Stupně utajení

> **§ 4 odst. 1**
>
> *Informaci, jejíž vyzrazení nebo zneužití může způsobit újmu zájmu České republiky nebo může být pro tento zájem nevýhodné a kterou lze podřadit pod položku uvedenou v katalogu oblastí utajovaných informací, klasifikuje a označí původce stupněm utajení*
>
> *- a) Přísně tajné, jestliže (...) může způsobit mimořádně vážnou újmu (...),*
>
> *- b) Tajné, jestliže (...) může způsobit vážnou újmu (...),*
>
> *- c) Důvěrné, jestliže (...) může způsobit prostou újmu (...), nebo*
>
> *- d) Vyhrazené, jestliže (...) může být nevýhodné pro zájem České republiky.*
>
> *(2) Pokud je utajovaná informace tvořena dílčími utajovanými informacemi různého stupně utajení, klasifikuje se a označí se stupněm utajení podle nejvyššího stupně utajení dílčí utajované informace nebo vyšším.*
>
> *(3) Utajovaná informace se při ústním, obrazovém nebo zvukovém zpřístupnění označí ústním prohlášením nebo jiným vhodným způsobem (...).*
>
> *(4) Utajovaná informace v analogové podobě se označí tak, že se na ní vyznačí stupeň utajení.*
>
> *(5) Utajovaná informace v elektronické podobě se před jejím zpřístupněním elektronicky označí stupněm utajení; není-li to možné, označí se při jejím zpřístupnění podle odstavce 3.*

**Výklad:**

#### Čtyřstupňová škála — sladění s NATO a EU

Český systém je **čtyřstupňový**, plně harmonizovaný s NATO a EU:

| Stupeň ČR | Ekvivalent NATO | Ekvivalent EU |
|---|---|---|
| Přísně tajné (PT) | COSMIC TOP SECRET | TRES SECRET UE / EU TOP SECRET |
| Tajné (T) | NATO SECRET | SECRET UE / EU SECRET |
| Důvěrné (D) | NATO CONFIDENTIAL | CONFIDENTIEL UE / EU CONFIDENTIAL |
| Vyhrazené (V) | NATO RESTRICTED | RESTREINT UE / EU RESTRICTED |

Převodní tabulky se zveřejňují sdělením Úřadu ve Sbírce zákonů (§ 23 odst. 4 ZOÚI). Sladění zajišťuje, že informace označená v některé spojenecké jurisdikci určitým stupněm je v ČR automaticky chráněna ekvivalentním stupněm (převody jsou jednoznačné, byť výjimky existují u některých subkategorií, např. EU LIMITE — nejde o utajovanou informaci ve smyslu ZOÚI).

#### Konstitutivní akt klasifikace — povinnost a oprávnění původce

Klasifikaci a označení **provádí původce** (§ 2 písm. f) — orgán státu, podnikatel nebo právnická osoba podle § 60b, u nichž informace vznikla. Akt klasifikace má **konstitutivní** povahu — bez něho informace není utajovanou informací (i kdyby materiálně způsobilá byla). Tím je posílena právní jistota a vyloučena retrospektivní utajenost (s výjimkou § 22 odst. 1 a § 70 zákona — utajení nevyznačené informace tam, kde to umožňuje další ustanovení).

Klasifikace musí být **proporční**: § 22 odst. 4 ukládá původci stupeň zrušit nebo změnit, zjistí-li, že pominul důvod utajení, důvody neodpovídají stupni, nebo byl stupeň stanoven neoprávněně. Současně § 22 odst. 5 vyžaduje **periodickou prověrku** — minimálně jednou za 5 let.

#### Princip nejvyššího stupně při agregaci (odst. 2)

Z důvodu zamezení agregačnímu úniku se sestava klasifikuje stupněm **nejvyšším**, případně i vyšším. Použití formulace „nebo vyšším" znamená, že **sám souhrn** dílčích informací nižšího stupně může — vzhledem ke kontextu a vzájemné souvislosti — věcně dosáhnout vyššího stupně utajení; klasifikuje se pak vyšším stupněm než kterýkoliv jednotlivý dílčí podklad.

#### Pravidla označování v různých formách (odst. 3–5)

- **Ústní/obrazové/zvukové zpřístupnění** (odst. 3): ústní prohlášení nebo „jiný vhodný způsob" — typicky úvodní formule jednání, sdělení v záhlaví prezentace.
- **Analogová podoba** (odst. 4): vizuální vyznačení (záhlaví/zápatí, razítka, barva). Konkrétní grafický vzhled stanoví prováděcí vyhláška č. 529/2005 Sb., o administrativní bezpečnosti.
- **Elektronická podoba** (odst. 5): elektronické značení (metadata, vodoznak, label v rámci ISMS); není-li možné, použije se ústní označení podle odst. 3 při zpřístupnění.

#### Doba utajení a periodická revize (§ 22 odst. 3, 5)

Původce může na utajované informaci vyznačit **dobu utajení** — po jejím uplynutí stupeň utajení automaticky zaniká. Není-li doba vyznačena, trvá utajení tak dlouho, dokud trvají důvody (§ 22 odst. 2). Periodická prověrka podle § 22 odst. 5 je **každých 5 let**; jejím účelem je předejít „permanentní" utajenosti informací, jež už ochranu nepotřebují.

---

### § 5 — Druhy zajištění ochrany utajovaných informací

> **§ 5**
>
> *Ochrana utajovaných informací je zajišťována*
>
> *- a) personální bezpečností (...),*
>
> *- b) průmyslovou bezpečností (...),*
>
> *- c) administrativní bezpečností (...),*
>
> *- d) fyzickou bezpečností (...),*
>
> *- e) bezpečností informačních nebo komunikačních systémů (...) a*
>
> *- f) kryptografickou ochranou (...).*

**Výklad:**

#### Šest pilířů ochrany — vrstvená (defense-in-depth) architektura

§ 5 je systematickou osou celého zákona — zavádí **šest pilířů** ochrany, které tvoří **vrstvenou (defense-in-depth) bezpečnostní architekturu**. Každá vrstva chrání jiný atribut ochrany (CIA — důvěrnost, integritu, dostupnost) a každá je v zákoně rozvinuta samostatnou Hlavou Části druhé.

| Pilíř | Hlava | §§ | Funkce |
|---|---|---|---|
| Personální | II | 6–14 | Výběr a prověření FO |
| Průmyslová | III | 15–20 | Prověření a podmínky podnikatele |
| Administrativní | IV | 21–23 | Manipulace s UI, evidence, skartace |
| Fyzická | V | 24–33 | Ochrana objektů, oblastí |
| IS / KS | VI–VII | 33a–36 | Bezpečnost počítačových systémů |
| Kryptografická | VIII | 36a–45 | Šifrová ochrana |

Žádná z vrstev sama nestačí; jejich kombinací se dosahuje úrovně ochrany odpovídající stupni utajení. Princip je opakovaně promítnut do prováděcích předpisů (zejm. vyhláška č. 528/2005 Sb. — fyzická bezpečnost, č. 523/2005 Sb. — bezpečnost IS, č. 524/2005 Sb. — administrativní bezpečnost).

---

### Hlava II — Personální bezpečnost

### Podmínky přístupu fyzické osoby k utajované informaci stupně utajení Vyhrazené (§§ 6–10)

### § 6 — Podmínky přístupu k Vyhrazené informaci a oznámení

> **§ 6 odst. 1**
>
> *Fyzické osobě lze umožnit přístup k utajované informaci stupně utajení Vyhrazené, jestliže jej nezbytně potřebuje k výkonu své funkce, pracovní nebo jiné činnosti, je držitelem oznámení o splnění podmínek pro přístup k utajované informaci stupně utajení Vyhrazené (dále jen „oznámení"), osvědčení fyzické osoby (§ 54) nebo dokladu (§ 80) a je poučena, nestanoví-li tento zákon nebo zvláštní právní předpis jinak (§ 58 až 62).*
>
> *(2) Oznámení se vydá fyzické osobě, která*
>
> *- a) je plně svéprávná,*
>
> *- b) dosáhla alespoň 18 let věku,*
>
> *- c) je bezúhonná podle § 8.*
>
> *(3) Splnění podmínek (...) ověřuje a oznámení (...) vydává ten, kdo je vůči ní v rámci služebního poměru nebo pracovněprávního, členského či obdobného vztahu odpovědnou osobou, nebo jí určená osoba. (...) V ostatních případech (...) Národní bezpečnostní úřad (...) na základě odůvodněné písemné žádosti.*

**Výklad:**

#### Princip need-to-know

Klíčová podmínka — „**nezbytně potřebuje k výkonu své funkce, pracovní nebo jiné činnosti**" — je promítnutím mezinárodního principu **need-to-know**: přístup nesmí být umožněn pouze proto, že osoba má dostatečné oprávnění, nýbrž **musí existovat aktuální věcný důvod** v podobě plnění konkrétního úkolu. Princip se uplatňuje napříč celým zákonem (srov. § 11 odst. 1 — vyšší stupně, § 15 — podnikatel).

#### Tři podmínky souběžně — funkce, oprávnění, poučení

K přístupu k Vyhrazené informaci je třeba **kumulativně**:
1. potřeba k výkonu činnosti (need-to-know),
2. **oprávnění** v jedné ze tří forem:
   - **oznámení** podle § 6 odst. 2 — tříprvkový test (svéprávnost, věk 18+, bezúhonnost),
   - **osvědčení fyzické osoby** podle § 54 — pro vyšší stupně, automaticky pokrývá i Vyhrazené,
   - **doklad** podle § 80 — speciální oprávnění bezpečnostní způsobilosti,
3. **poučení** podle § 2 písm. i) a § 9 — písemný záznam o seznámení s povinnostmi.

#### Hierarchie vydavatelů oznámení

Oznámení vydává **odpovědná osoba** (či jí určená osoba) toho subjektu, k němuž je FO ve služebním/pracovněprávním/členském/obdobném vztahu. Jde-li o osobu „mezi subjekty" (např. externí konzultant bez stabilního vztahu), vydá je odpovědná osoba toho, kdo přístup umožní. Subsidiárně — pokud nelze žádnou cestou — vydá je **Úřad** na odůvodněnou písemnou žádost.

Tato struktura odráží **decentralizovaný model** ochrany — Úřad nevydává oznámení rutinně, ale je gestorem výjimek a obecné odpovědnosti za systém.

---

### § 7 — Prokazování podmínek

> **§ 7 odst. 1**
>
> *Podmínka svéprávnosti se prokazuje prohlášením fyzické osoby o svéprávnosti. Podmínka věku se prokazuje občanským průkazem nebo cestovním dokladem (...). Podmínka bezúhonnosti se prokazuje výpisem z evidence Rejstříku trestů a v případě cizince i obdobným dokladem státu, jehož je cizinec státním příslušníkem (...). Doklady k ověření bezúhonnosti nesmějí být starší než 3 měsíce od jejich vydání.*

**Výklad:**

Procesní pravidla pro prokazování. Klíčové aspekty:
- **Svéprávnost** — čestné prohlášení (FO ručí pravdivostí).
- **Věk** — OP nebo cestovní pas.
- **Bezúhonnost** — výpis z RT, u cizinců navíc obdobný doklad státu, kde po 15. roce věku pobývali souvisle déle než 6 měsíců, nebo státu, kde za posledních 10 let pobývali souvisle déle než 6 měsíců. Pokud daný stát doklad nevydává, lze nahradit čestným prohlášením.
- **Maximální stáří dokladu** — 3 měsíce.

V odst. 2 je upraveno, že je-li ověřovatelem orgán státu, vyžádá si výpis z RT sám (princip jednotlivého kontaktu — citizen-friendly e-Government). Jinak doklady předkládá FO.

---

### § 8 — Bezúhonnost pro oznámení

> **§ 8**
>
> *Podmínku bezúhonnosti pro účely vydání oznámení splňuje fyzická osoba, která nebyla pravomocně odsouzena za spáchání úmyslného trestného činu nebo trestného činu vztahujícího se k ochraně utajovaných informací, anebo se na ni hledí, jako by odsouzena nebyla.*

**Výklad:**

#### Bezúhonnost — užší než pro osvědčení (§ 13)

Pro úroveň Vyhrazené je bezúhonnost definována poměrně **úzce**: nezpůsobuje ji jakékoliv pravomocné odsouzení za **úmyslný trestný čin** nebo za **trestný čin vztahující se k ochraně UI**. Z výčtu je vyloučeno odsouzení za nedbalostní trestný čin (s výjimkou těch vztahujících se k UI — typicky § 318 TZ — ohrožení UI z nedbalosti).

Bezúhonnost se „obnovuje" zahlazením odsouzení (§ 105 TZ) — zákon používá formulaci „nebo se na ni hledí, jako by odsouzena nebyla", tedy zahlazení působí ex lege.

Pro vyšší stupně (Důvěrné, Tajné, Přísně tajné) je bezúhonnost rozšířena v § 13 o postupy v případech podmíněného zastavení trestního stíhání nebo schválení narovnání — tam ochranná doba 5 let od právní moci.

---

### § 9 — Poučení a platnost oznámení

> **§ 9 odst. 1**
>
> *Před prvním přístupem k utajované informaci stupně utajení Vyhrazené ten, kdo je vůči fyzické osobě (...) osobou odpovědnou, zajistí její poučení. (...) Poučení podepisuje fyzická osoba a ten, kdo poučení provedl; jeden výtisk poučení jí předá a jeden výtisk uloží.*
>
> *(2) Ten, kdo vydal oznámení, je povinen každých 5 let ode dne jeho vydání ověřovat splnění podmínek (...).*
>
> *(3) Platnost oznámení zaniká* [10 důvodů — písm. a)–j)]

**Výklad:**

#### Periodická reverifikace (odst. 2)

Vydavatel oznámení má **aktivní povinnost** každých 5 let ověřovat trvání podmínek svéprávnosti a bezúhonnosti. Při důvodných pochybnostech lze ověřit i dříve. Doklady lze uchovávat nejdéle 5 let po zániku platnosti oznámení (omezení podle GDPR).

#### Katalog zániku platnosti (odst. 3) — 10 důvodů

Platnost oznámení zaniká:
- **a) doručením vyrozumění** o ztrátě podmínek (a, c) — administrativní cestou,
- **b) skončením** služebního/pracovního/členského/obdobného vztahu,
- **c) vznikem nového** takového vztahu (pokud oznámení vydala odp. osoba toho, kdo přístup umožnil, nebo Úřad podle § 6 odst. 3),
- **d) úmrtím / prohlášením za mrtvou**,
- **e) ohlášením odcizení nebo ztráty**,
- **f) ohlášením poškození** (nečitelnost / porušení celistvosti),
- **g) doručením vyrozumění** o nesplnění oznamovací povinnosti podle § 10 odst. 2 písm. b),
- **h) vrácením** oznámení vydavateli,
- **i) 15. dnem od doručení osvědčení FO nebo dokladu** — vyšší oprávnění absorbuje nižší,
- **j) změnou údaje** v oznámení.

#### Procedurální následky zániku (odst. 4–7)

Při zániku podle a) a g) musí vydavatel zajistit, aby FO neměla přístup, a písemně ji vyrozumět s uvedením důvodu. Při zániku podle b)–d), f), h) nebo i) vydavatel pořídí pouze interní záznam.

Důležitá ochranná norma — odst. 7: **při zániku platnosti oznámení se má za to, že FO poučena není**. Toto je důsledek **personální vazby** poučení na konkrétní platné oprávnění — nelze „přenášet" poučení mezi obdobími.

---

### § 10 — Trvalé plnění podmínek a oznamovací povinnosti

§ 10 stanoví, že FO musí podmínky svéprávnosti a bezúhonnosti plnit **po celou dobu** přístupu k Vyhrazené informaci. Současně ukládá oznamovací povinnost ve lhůtě **15 dnů** (resp. 30 dnů u změny údaje v oznámení) ohledně:
- změny týkající se svéprávnosti / bezúhonnosti,
- odcizení / ztráty / poškození oznámení,
- doručení osvědčení FO nebo dokladu,
- skutečností podle § 9 odst. 3 písm. c), f) a j).

Nesplnění této oznamovací povinnosti je samostatným důvodem zániku platnosti oznámení podle § 9 odst. 3 písm. g).

---

### Podmínky přístupu k Přísně tajné, Tajné nebo Důvěrné informaci (§§ 11–14)

### § 11 — Osvědčení fyzické osoby a poučení

> **§ 11 odst. 1**
>
> *Fyzické osobě lze umožnit přístup k utajované informaci stupně utajení Přísně tajné, Tajné nebo Důvěrné, jestliže jej nezbytně potřebuje k výkonu své funkce, pracovní nebo jiné činnosti, je držitelem platného osvědčení fyzické osoby (§ 54) příslušného stupně utajení a je poučena (...).*

**Výklad:**

#### Skoková změna oprávnění — od oznámení k osvědčení

Pro vyšší tři stupně (D, T, PT) **nestačí oznámení** vydávané odpovědnou osobou, vyžaduje se **osvědčení fyzické osoby** vydávané výlučně **Úřadem** (§ 54), a to po formálním **bezpečnostním řízení** podle Části čtvrté zákona (§§ 93 a násl. — vně rozsahu této kapitoly). Mezi oznámením a osvědčením je **kvalitativní rozdíl** v rozsahu prověrky:
- oznámení: pouze svéprávnost, věk, bezúhonnost (RT),
- osvědčení: navíc **státní občanství** (ČR / EU / NATO), **bezpečnostní spolehlivost** (§ 14), širší bezúhonnost (§ 13), prověrka zpravodajskými službami, dotazníky majetkové, finanční, vztahové.

Osvědčení se vydává **pro příslušný stupeň**; osvědčení nižšího stupně neopravňuje k přístupu k vyššímu (osvědčení PT však pokrývá i T a D, osvědčení T pokrývá i D — princip „vyšší zahrnuje nižší").

#### Poučení a zaslání kopie Úřadu (odst. 2)

Postup je obdobný jako u Vyhrazené, ale **kopii poučení obdrží Úřad** — má tak centrální evidenci osob, jež skutečně přistupují k vyšším stupňům utajení (lze i elektronicky). Výjimky jsou pro zpravodajské služby (§ 140) a MV (§ 141), které vedou vlastní evidenci.

#### Zvláštní pravidla pro vedoucí představitele (odst. 3)

Poučení ředitelů Úřadu a BIS provádí **předseda vlády**, ředitele ÚZSI **ministr vnitra**, ředitele Vojenského zpravodajství **ministr obrany**. Reflektuje hierarchii zpravodajské soustavy.

#### Domněnka nepoučenosti (odst. 4)

Obdobně § 9 odst. 7 — při zániku platnosti osvědčení FO nebo skončení vztahu, v němž byl umožněn přístup, se má za to, že FO poučena není.

---

### § 11a — Trvající povinnost mlčenlivosti

> **§ 11a**
>
> *V případě skončení služebního poměru nebo pracovněprávního, členského či obdobného vztahu nebo při změně služebního úřadu, ve kterém byl fyzické osobě umožněn přístup k utajovaným informacím, je tato osoba povinna písemně potvrdit, že si je vědoma povinnosti zachovávat mlčenlivost o utajovaných informacích, ke kterým měla přístup, a neumožnit k nim přístup neoprávněné osobě. (...)*

**Výklad:**

Klíčová **doživotní (resp. trvající) povinnost mlčenlivosti** — povinnost neskončí spolu se vztahem, jenž byl důvodem přístupu. FO je při ukončení vztahu povinna **písemně potvrdit** své vědomí o této povinnosti; provedení úkonu zajišťuje odpovědná osoba. Porušení této povinnosti zakládá:
- správní odpovědnost podle Části páté ZOÚI (přestupky a správní delikty — § 148 a násl.),
- v kvalifikovaných případech trestní odpovědnost podle § 316 nebo § 317 TZ.

Mlčenlivost trvá tak dlouho, dokud trvá stupeň utajení informace; zrušením stupně utajení podle § 22 odst. 4 (např. odtajnění historických spisů) zaniká i povinnost mlčenlivosti.

---

### § 12 — Podmínky pro vydání osvědčení FO

> **§ 12 odst. 1**
>
> *Osvědčení fyzické osoby Úřad vydá fyzické osobě, která*
>
> *- a) je státním občanem České republiky nebo státním příslušníkem členského státu Evropské unie nebo Organizace Severoatlantické smlouvy,*
>
> *- b) splňuje podmínky uvedené v § 6 odst. 2 písm. a) a b),*
>
> *- c) je bezpečnostně spolehlivá a*
>
> *- d) je bezúhonná podle § 13.*

**Výklad:**

#### Čtyři kumulativní podmínky — pětistupňový test

Pro osvědčení FO (D/T/PT) zákon klade **čtyři kumulativní podmínky**:

1. **Státní občanství ČR / EU / NATO** — zákon č. 412/2005 Sb. tradičně omezuje ochranu UI na občany ČR, ale s ohledem na členství v EU a NATO byla podmínka rozšířena. **Cizí mocnost mimo NATO/EU** (typicky občané USA, jež nejsou v EU ani NATO současně, byť USA jsou v NATO; nebo občané třetích zemí) jsou z přístupu **zcela vyloučeni**, ovšem cizí moc může požadovat speciální osvědčení pro přístup k její vlastní informaci (§ 57 — viz dále).
2. **Svéprávnost a věk 18+** (převzato z § 6).
3. **Bezpečnostní spolehlivost** (§ 14) — nepřítomnost bezpečnostního rizika.
4. **Bezúhonnost** (§ 13) — širší než pro Vyhrazené.

Trvání podmínek je vyžadováno po celou dobu platnosti osvědčení (odst. 2). Při ztrátě jakékoliv z nich Úřad zahájí řízení o zrušení platnosti osvědčení (§ 101 a násl., zejm. § 123).

---

### § 13 — Bezúhonnost pro osvědčení FO

> **§ 13 odst. 1**
>
> *Podmínku bezúhonnosti pro účely vydání osvědčení fyzické osoby splňuje fyzická osoba, která nebyla pravomocně odsouzena za spáchání úmyslného trestného činu nebo trestného činu vztahujícího se k ochraně utajovaných informací, nebo se na ni hledí, jako by odsouzena nebyla. Jestliže trestní stíhání pro takový trestný čin bylo podmíněně zastaveno nebo bylo podmíněně odloženo podání návrhu na potrestání, je podmínka bezúhonnosti splněna až poté, co se fyzická osoba osvědčila podle jiného právního předpisu. V případě rozhodnutí o schválení narovnání v trestním řízení o úmyslném trestném činu je podmínka bezúhonnosti splněna, pokud od právní moci takového rozhodnutí uplynula doba alespoň 5 let.*

**Výklad:**

#### Rozšíření o podmíněné zastavení a narovnání

Oproti § 8 (bezúhonnost pro oznámení) zákon rozlišuje tři speciální procesní situace, jež bezúhonnost dočasně narušují:
- **podmíněné zastavení trestního stíhání** (§ 307 TŘ) — bezúhonnost se obnovuje, až se FO osvědčí (po uplynutí zkušební doby — § 308 TŘ),
- **podmíněné odložení návrhu na potrestání** (§ 179g TŘ),
- **schválení narovnání** (§ 309–314 TŘ) — bezúhonnost se obnovuje **až po 5 letech** od právní moci.

Bezúhonnost se ověřuje **opisem z RT** (nikoli pouze výpisem) — tj. včetně všech zahlazených odsouzení (§ 22 odst. 4 zákona o RT) — a u cizinců obdobnými doklady.

---

### § 14 — Bezpečnostní spolehlivost

> **§ 14 odst. 1**
>
> *Podmínku bezpečnostní spolehlivosti splňuje fyzická osoba, u níž není zjištěno bezpečnostní riziko.*

**Výklad:**

#### Bezpečnostní riziko — dvojvrstvý katalog (odst. 2 a 3)

§ 14 je jedním z **dogmaticky nejcitlivějších** ustanovení zákona — definuje, kdy lze FO odepřít přístup k utajované informaci z jiných než trestních důvodů. Riziko se dělí na:

**Tvrdá rizika (odst. 2) — automatická nezpůsobilost**

Jakékoliv ze čtyř rizik znamená nesplnění podmínky:
- a) **činnost proti zájmu ČR** (zájmu vymezenému v § 2 písm. b)),
- b) **činnost spočívající v potlačování základních práv a svobod**, nebo její podpora,
- c) **majetkové poměry zjevně nepřiměřené** řádně přiznaným příjmům — protikorupční clausula, požaduje srovnání s daňovými přiznáními,
- d) **opakované neposkytnutí nezbytné součinnosti** v probíhajícím řízení o zrušení platnosti osvědčení (procesní riziko — viz § 107 odst. 4).

**Měkká rizika (odst. 3) — kontextuální posouzení**

Tato rizika nezakládají automaticky nezpůsobilost, posuzují se v kontextu (odst. 5):
- a) zařazení v **bývalé StB** (rozvědka / kontrarozvědka), zpravodajské správě Generálního štábu ČSLA, OVO SNV nebo **prokazatelná spolupráce** s nimi — historicko-bezpečnostní lustrace,
- b) **úmyslné porušení právních předpisů** s následkem újmy zájmu ČR,
- c) chování s **negativním vlivem na důvěryhodnost nebo ovlivnitelnost** — typicky závislosti, hazard, vydírání,
- d) **styky s osobou** vyvíjející činnost proti zájmu ČR,
- e) porušení podmínek přístupu k UI nebo jiné povinnosti při ochraně UI,
- f) **porucha zdraví nebo charakteristiky osobnosti** s negativním vlivem na schopnost utajovat — psychiatrické / psychologické vyšetření.

#### Časový rozsah ověřování (odst. 4)

Zákonné období prověřování závisí na typu rizika a stupni utajení:

| Riziko | Období |
|---|---|
| Odst. 2 písm. a)–c) a odst. 3 písm. a) | Od 15 let věku |
| Odst. 2 písm. d) | Pouze v probíhajícím řízení |
| Odst. 3 písm. b)–e) — Důvěrné | 10 let zpět |
| Odst. 3 písm. b)–e) — Tajné | 15 let zpět |
| Odst. 3 písm. b)–e) — Přísně tajné | 20 let zpět |

Vždy se však uplatní kratší období, pokud FO dosud nebyla 15 let stará.

#### Komplexní posouzení (odst. 5)

Při posuzování měkkých rizik se zohledňuje:
- míra vlivu na schopnost utajovat,
- doba výskytu (čím déle v minulosti, tím menší váha),
- rozsah a charakter,
- chování FO v relevantním období.

To dává Úřadu **diskreční prostor**; rozhodnutí je však plně přezkoumatelné soudem v rámci správního soudnictví (§ 133 a násl. ZOÚI ve vazbě na § 65 a násl. SŘS). Judikatura NSS (např. rozsudek sp. zn. 1 As 27/2009, sp. zn. 5 As 138/2013) stanoví, že posouzení musí být **odůvodněné, proporční a opřené o konkrétní zjištění**; nelze zamítnout pouze paušálním odkazem na „bezpečnostní riziko".

#### Fyziodetekční, psychologické a lékařské vyšetření (odst. 6)

Speciální oprávnění mají **zpravodajské služby u svých příslušníků a uchazečů** — mohou provést **fyziodetekční vyšetření** (polygraf) při ověřování spolehlivosti. **Psychologické a lékařské vyšetření** podle odst. 3 písm. f) mohou provést zpravodajské služby (§ 140) a Ministerstvo vnitra (§ 141) **vlastním odborným pracovištěm**. Tyto invazivní metody jsou tedy vyloučeny pro běžné bezpečnostní řízení Úřadu.

---

### Hlava III — Průmyslová bezpečnost

### § 15 — Podmínky přístupu podnikatele k UI a formy přístupu

> **§ 15**
>
> *Přístup k utajované informaci lze umožnit podnikateli, který je fyzickou osobou s trvalým pobytem na území České republiky zapsanou do živnostenského rejstříku, obchodního rejstříku nebo jiné evidence (...) nebo právnickou osobou se sídlem v České republice zapsanou v obchodním rejstříku (...), jestliže jej nezbytně potřebuje k výkonu své činnosti, a pokud při přístupu k utajované informaci*
>
> *- a) stupně utajení Vyhrazené*
>
> *- 1. doloží písemným prohlášením svou schopnost zabezpečit ochranu utajovaných informací (dále jen „prohlášení podnikatele"), nebo*
>
> *- 2. je držitelem platného osvědčení podnikatele, nebo*
>
> *- b) stupně utajení Důvěrné a vyšší je držitelem platného osvědčení podnikatele příslušného stupně utajení (...).*

**Výklad:**

#### Pojem podnikatele pro účely zákona — užší než v ObčZ/ZOK

Pro ZOÚI je **podnikatelem** pouze:
- FO s trvalým pobytem v ČR zapsaná v ŽR/OR/jiné evidenci, provozující podnikatelskou činnost,
- **PO se sídlem v ČR** zapsaná v OR, **jejíž hlavní činností je podnikatelská činnost**.

Vyloučeny jsou tedy zahraniční subjekty (jejich přístup řeší § 60a — zpracování UI v ČR pro zahraniční subjekt) a PO bez podnikatelské povahy (spolky, ústavy — pro ně režim § 60b).

#### Dvojí režim pro Vyhrazené, jednotný režim pro vyšší stupně

Pro **Vyhrazené** podnikatel může volit:
- **prohlášení podnikatele** (§ 15a) — zjednodušený proces, sám podnikatel deklaruje schopnost zajistit ochranu,
- **osvědčení podnikatele** (§ 16) — formální řízení Úřadu.

Pro **Důvěrné a vyšší** je **vždy nutné osvědčení podnikatele**, formy přístupu definuje § 20:
- **forma a) — UI u podnikatele vzniká nebo je mu poskytována**,
- **forma b) — UI je přístupna pouze zaměstnancům podnikatele** v souvislosti s činností pro podnikatele.

Formy mají různé požadavky na ochranu — forma b) podle § 20 odst. 2 vyžaduje **pouze personální bezpečnost** ze složek § 5, neboť informace u podnikatele fyzicky není.

---

### § 15a — Prohlášení podnikatele

> **§ 15a odst. 1**
>
> *Podnikatel je oprávněn učinit prohlášení podnikatele, pokud*
>
> *- a) má pro ochranu utajované informace stupně utajení Vyhrazené vytvořeny podmínky odpovídající formě přístupu (...) a příslušnému druhu zajištění její ochrany (§ 5),*
>
> *- b) odpovědná osoba je držitelem oznámení, osvědčení fyzické osoby nebo dokladu.*

**Výklad:**

Prohlášení podnikatele je **sebedeklaratorní instrument** — podnikatel písemně prohlašuje, že má vytvořeny podmínky pro ochranu informace stupně Vyhrazené. Předává je **poskytovateli vyhrazené informace** (subjekt, jenž mu informaci poskytuje), případně Úřadu (vzniká-li UI přímo u podnikatele).

#### Platnost prohlášení (odst. 5) — 6 důvodů zániku

- a) **uplynutím 5 let**,
- b) doručením vlastního oznámení podnikatele o ukončení přístupu,
- c) doručením osvědčení podnikatele,
- d) zrušením/zánikem podnikatele,
- e) přestal-li podnikatel splňovat podmínky odst. 1,
- f) změnou údaje v prohlášení.

Prohlášení nepředstavuje veřejnoprávní oprávnění (nejde o správní akt Úřadu), proto je proces zjednodušený. Úřad však dostává kopii a může provést dohlížecí kontrolu.

---

### § 16 — Podmínky pro vydání osvědčení podnikatele

Osvědčení podnikatele Úřad vydá podnikateli, který:
- **a) je ekonomicky stabilní** (§ 17),
- **b) je bezpečnostně spolehlivý** (§ 18),
- **c) je způsobilý zabezpečit ochranu** UI (§ 19),
- **d) odpovědná osoba je držitelem platného osvědčení FO** nejméně pro stejný stupeň,
- **e) je bezúhonný** (§ 19a).

Pět kumulativních podmínek. Zánik nebo nesplnění kterékoliv vede k zahájení řízení o zrušení platnosti.

---

### § 17 — Ekonomická stabilita

§ 17 člení důvody nesplnění ekonomické stability na **tvrdé** (odst. 1) a **měkké** (odst. 2).

**Tvrdé důvody (odst. 1) — automatická diskvalifikace:**
- a) **moratorium** vyhlášené soudem (insolvenční zákon č. 182/2006 Sb.),
- b) **rozhodnutí o úpadku**,
- c) **nucená správa** (3 roky) nebo dočasná správa anebo opatření k řešení krize na finančním trhu (zákon č. 374/2015 Sb.),
- d) **záporný vlastní kapitál** v posledních 5 účetních obdobích.

**Měkké důvody (odst. 2) — diskreční posouzení:**
- a) nedoplatek na pojistném/dani/cle,
- b) jiný daňový/celní nedoplatek,
- c) trvalé nebo opakované neplnění finančních povinností,
- d) **exekuce** na majetek,
- e) opakovaná **ztráta** v 5 zdaňovacích obdobích,
- f) jednorázová záporná vlastní kapitálová pozice.

Konstrukce má **protikorupční charakter** — zamezuje přístupu osob v ekonomické tísni, jež jsou náchylné ke zradě za úplatu.

---

### § 18 — Bezpečnostní spolehlivost podnikatele

§ 18 je paralelou § 14 pro PO, je však významně širší — reflektuje **agregovanou riziko**:
- chování statutárů a kontrolních orgánů,
- prokuristy,
- FO s rozhodujícím vlivem (skuteční majitelé),
- svěřenské konstrukce,
- vlastnické struktury, zejm. zahraniční.

**Tvrdá rizika (odst. 2):** činnost proti zájmu ČR ze strany podnikatele/statutáře/prokuristy/skutečného majitele; potlačování práv a svobod; specifický režim svěřenských fondů; opakované neposkytnutí součinnosti.

**Měkká rizika (odst. 3) — třináct typů (a–m):** kapitálové/finanční/obchodní vztahy k rizikovým osobám, personální nestabilita, problematické chování, porušení povinnosti při ochraně UI, odsouzení společníka s rozhodujícím vlivem, úmyslné porušení předpisů, problematické vztahy osob s vlivem, **PO v statutárním orgánu**, odsouzení podnikatele, neplnění finančních dluhů, **zahraniční vlastník**, jehož vlastnickou strukturu nelze ověřit, zahraniční osoba ve vlastnické struktuře, jíž nelze prověřit bezpečnostní spolehlivost.

**Rozhodující vliv (odst. 4)**: schopnost prosadit jmenování/odvolání/volbu většiny členů statutárního nebo kontrolního orgánu, **i nepřímo přes jiné PO**. Pro účely odst. 3 písm. h) (vliv na jednání podnikatele) postačí i jakákoliv přímá či nepřímá schopnost ovlivnit jednání.

**Posouzení měkkých rizik (odst. 5)**: rozsah, charakter, doba výskytu, vliv na schopnost utajovat.

Tato úprava je odpovědí na zkušenosti s **vlastnickou neprůhledností** a snahy zahraničních (zejm. ruských a čínských) entit získat citlivé zakázky. Současný režim je významně **přísnější** než předúpravy z 2000s a reflektuje akty EU (např. nařízení o screeningu přímých zahraničních investic 2019/452).

---

### § 19 — Způsobilost zabezpečit ochranu UI

Podnikatel splňuje podmínku **způsobilosti zabezpečit ochranu UI**, je-li schopen zajistit a dodržovat jednotlivé druhy ochrany podle § 5 — odstupňováno podle stupně utajení a formy přístupu (§ 20). Konkrétně musí mít odpovídající personální obsazení, prostory, IS, kryptografická řešení (jsou-li relevantní), bezpečnostní dokumentaci.

---

### § 19a — Bezúhonnost podnikatele

Obdobně § 13 — bezúhonnost neporušuje pravomocné odsouzení za úmyslný TČ nebo TČ vztahující se k ochraně UI; podmíněné zastavení (až po osvědčení podle TŘ) a narovnání (5 let od právní moci) řeší obdobně. Posuzuje se **samotný podnikatel — PO/FO**, nikoli jeho statutáři (ti jsou prověřováni samostatně přes § 14 jako FO ucházející se o osvědčení FO).

---

### § 20 — Formy přístupu podnikatele k UI

> **§ 20 odst. 1**
>
> *Podnikatel má přístup k utajované informaci,*
>
> *- a) která u něho vzniká, nebo je mu poskytnuta, nebo*
>
> *- b) ke které mají přístup zaměstnanci podnikatele nebo osoby jednající jménem podnikatele nebo za podnikatele, a to v souvislosti s výkonem pracovní nebo jiné činnosti pro podnikatele na základě smlouvy, aniž by byla podnikateli poskytnuta nebo u něho vznikala.*
>
> *(2) V případě přístupu podle odstavce 1 písm. b) musí podnikatel splňovat podmínku podle § 16 odst. 1 písm. c) pouze zajištěním ochrany utajované informace personální bezpečností [§ 5 písm. a)].*

**Výklad:**

#### Forma a) — UI fyzicky u podnikatele

Klasický model — typicky obranný dodavatel zpracovávající utajovanou technickou dokumentaci, nebo dodavatel IT řešení pro zpravodajskou službu, jenž má UI v interních systémech. Vyžaduje plnou škálu ochrany podle § 5 odpovídající stupni utajení.

#### Forma b) — pouze zaměstnanci přistupují k UI v cizím prostředí

Typický případ — konzultanti, jejichž zaměstnanci pracují u zadavatele a tam přistupují k UI bez její fyzické přítomnosti u podnikatele. Zde **odpadají** požadavky na fyzickou bezpečnost, administrativní bezpečnost, IS atd. — postačí pouze zajištění **personální bezpečnosti** (správný výběr a poučení zaměstnanců).

Forma se vyznačuje v osvědčení podnikatele (§ 54 odst. 3 písm. c)). Při změně formy je nutné vydat nové osvědčení.

---

### Hlava IV — Administrativní bezpečnost

### § 21 — Vyznačování údajů, evidence, manipulace, přeprava, skartace

> **§ 21 odst. 1**
>
> *Na utajovanou informaci je původce povinen vyznačit svůj název, stupeň jejího utajení, její evidenční označení a datum jejího vzniku, není-li dále stanoveno jinak.*

**Výklad:**

#### Povinné identifikační údaje (odst. 1)

Každá UI musí nést **čtyři identifikátory**: název původce, stupeň utajení, evidenční označení, datum vzniku. Tyto údaje jsou **nezbytnou podmínkou** pro správní stopu informace v rámci systému administrativní bezpečnosti.

#### Speciální režim pro UI cizí moci (odst. 2)

Příjímá-li ČR UI cizí moci a eviduje ji jako první (§§ 77–79), vyznačí na ní:
- stupeň utajení podle § 4 (český ekvivalent),
- **zkratku** podle mezinárodní smlouvy (např. „EU", „EURA", „NATO") nebo podle stupně utajení vyznačeného cizí mocí.

**Nepřevzeme** název původce ani datum vzniku — chrání tak partnerskou stranu před zveřejněním zdroje.

#### Zvláštní režim nakládání (odst. 3)

Některé UI vyžadují **zvláštní režim nakládání** (vyšší míru ochrany než daný stupeň utajení): zejména **KRYPTO** (kryptografická ochrana) a **ATOMAL** (zbraně hromadného ničení — atomová munice; NATO termín). Tyto kategorie podléhají dalším bezpečnostním standardům.

#### Evidence v administrativních pomůckách (odst. 5)

UI se eviduje v administrativních pomůckách (podací deník UI, evidenční pomůcky kryptomateriálu — § 37 odst. 5). Výjimka: u **podkladových materiálů** stupně Vyhrazené k UI stupně Vyhrazené může odpovědná osoba stanovit, že se neevidují (zjednodušení pro masové operativní materiály). Eviduje se nejen samotná informace, ale i **pohyb** (předávání, přebírání, seznámení).

#### Reprodukce (odst. 6)

- **Přísně tajné**: opis, kopie, překlad, výpis — **pouze s písemným souhlasem původce**.
- **Tajné, Důvěrné**: **písemný souhlas přímo nadřízené osoby**.
- **Vyhrazené**: zákon neomezuje, podléhá obecným pravidlům.

#### Přeprava a přenášení (odst. 7)

UI se přepravuje pouze:
- v **přenosných schránkách nebo uzavřeném obalu**,
- prostřednictvím **kurýra nebo držitele poštovní licence** (typicky Česká pošta, příp. specializovaný kurýrní podnik s oprávněním).

Přeprava je rizikovým úsekem — proto zákonné požadavky na fyzické zabezpečení (pečetě, kurýrní listy, přebírací protokoly podle prováděcí vyhlášky č. 529/2005 Sb.).

#### Půjčování (odst. 9)

UI lze zapůjčit **pouze FO** ve vztahu k subjektu, jenž ji uložil (zaměstnanec, příslušník, člen). Vylučují se externí osoby — ti musí mít vlastní vztah k podnikateli/orgánu.

#### Skartace (odst. 10)

UI při vyřazování ve skartačním řízení podléhá zákonu č. 499/2004 Sb., o archivnictví a spisové službě, a navazujícím vyhláškám. **Skartace UI** vyžaduje fyzické zničení takovým způsobem, aby informaci nebylo možné obnovit.

#### Nouzové zničení EUCI (odst. 11)

Speciální klauzule pro **utajované informace Evropské unie (EUCI)**: hrozí-li bezprostřední riziko vyzrazení, **původce/kurýr/adresát zničí UI** způsobem znemožňujícím obnovení; následně neprodleně **písemně oznámí Úřadu a původci**. Reflektuje pravidla rozhodnutí Rady 2013/488/EU.

---

### § 22 — Vyznačování a změna stupně utajení

> **§ 22 odst. 1**
>
> *Stupeň utajení na utajované informaci vyznačí původce při jejím vzniku, nestanoví-li tento zákon jinak (§ 70).*
>
> *(2) Vyznačení stupně utajení (...) musí být zachováno po celou dobu trvání důvodů utajení. Bez souhlasu původce nebo poskytující cizí moci nesmí být stupeň utajení změněn nebo zrušen.*
>
> *(3) Vyžaduje-li to charakter utajované informace, musí původce vyznačit (...) dobu, po kterou bude informace utajována (...).*
>
> *(4) Stupeň utajení původce neprodleně zruší nebo změní po zjištění, že pominul důvod pro utajení informace, důvody pro utajení neodpovídají stanovenému stupni utajení nebo byl-li stupeň utajení stanoven neoprávněně (...).*
>
> *(5) Původce je povinen prověřit, zda důvod pro utajení informace trvá, a to nejméně jednou za pět let ode dne jejího vzniku.*

**Výklad:**

#### Princip „spravce informace = původce"

Klasifikační autonomie patří **původci**. Změnit nebo zrušit stupeň smí jen **původce, jeho právní nástupce, případně cizí moc** (jde-li o UI poskytnutou cizí mocí). Adresát (příjemce) UI **sám klasifikaci měnit nesmí** — to brání svévolnému odtajnění.

#### Periodicita prověrek a aktivní povinnost odtajnění (odst. 4, 5)

Původce má **dvě nepřenosné povinnosti**:
1. **Neprodleně zrušit nebo změnit** stupeň, pokud zjistí, že důvod pominul, neodpovídá nebo byl stanoven neoprávněně.
2. **Nejméně jednou za 5 let** přezkoumat trvání důvodu utajení.

Tím zákon vyvažuje veřejný zájem na transparentnosti a princip přiměřené ochrany. Praxe však ukazuje, že **odtajňování** je oproti utajování slabší proces — historické dokumenty nezřídka zůstávají utajené déle, než by věcně bylo třeba (kritika ze strany Archivu bezpečnostních složek, akademické obce a investigativní žurnalistiky).

#### Notifikace adresátům (odst. 6, 7)

Při změně/zrušení musí původce **neprodleně písemně oznámit** adresátům. Adresát musí oznámit **dalším adresátům**, kterým UI zpřístupnil — kaskádově. Adresát po obdržení oznámení **vyznačí změnu** na své kopii UI.

#### Zánik původce (odst. 8)

Zanikl-li původce, přebírá kompetence **právní nástupce**; není-li jej (nebo nesplňuje podmínky), **Úřad**. Tím se předchází „permanentnímu" utajení zaniklých orgánů.

#### Kontrolní oprávnění Úřadu (odst. 9)

Klíčové ustanovení **správního dozoru nad klasifikací**: Úřad na žádost orgánu státu, jenž vede řízení s UI, ověří správnost klasifikace. Po konzultaci s původcem může **vyzvat** k změně/zrušení. Pro zpravodajské služby je v odst. 9 stanovena výjimka — ověření v případě správního řízení neprovádí Úřad, nýbrž **sama dotčená zpravodajská služba** (samokontrola — ve světle nezávislosti zpravodajských služeb).

---

### § 23 — Specifické situace a zmocňovací ustanovení

§ 23 obsahuje:
- **odst. 1** — výjimky z povinnosti potvrzení převzetí (např. mezi zpravodajskými službami při operativní spolupráci),
- **odst. 2** — zmocnění pro prováděcí předpis (vyhláška č. 529/2005 Sb., o administrativní bezpečnosti),
- **odst. 3** — speciální režim **elektronického systému spisové služby** (eSSL) — pro UI v eSSL splňujícím národní standard se použijí ustanovení obdobně,
- **odst. 4** — **převodní tabulky** mezinárodních stupňů utajení (Úřad je publikuje sdělením ve Sbírce zákonů).

---

### Hlava V — Fyzická bezpečnost

### § 24 — Objekty, zabezpečené oblasti, jednací oblasti

> **§ 24**
>
> *(1) Pro zabezpečení ochrany utajovaných informací v rámci fyzické bezpečnosti se určují objekty, zabezpečené oblasti a jednací oblasti.*
>
> *(2) Objektem je budova nebo jiný ohraničený prostor, ve kterém se zpravidla nachází zabezpečená oblast nebo jednací oblast.*
>
> *(3) Zabezpečenou oblastí je ohraničený prostor v objektu.*
>
> *(4) Jednací oblastí je ohraničený prostor v objektu. Utajovanou informaci stupně utajení Přísně tajné nebo Tajné lze pravidelně projednávat pouze v jednací oblasti.*

**Výklad:**

#### Trojí topologie chráněného prostoru

ZOÚI rozlišuje **tři vrstvy prostorové ochrany**:

| Vrstva | Pojem | Funkce |
|---|---|---|
| Vnější | **Objekt** | Budova / ohraničený prostor, perimetr |
| Vnitřní | **Zabezpečená oblast** | Prostor pro **zpracování** a **ukládání** UI |
| Speciální | **Jednací oblast** | Prostor pro **projednávání** UI (PT a T pravidelně **pouze zde**) |

Důležité distinkce:
- **Zabezpečená oblast** je primárně určena pro **zpracování** UI (papírová, elektronická manipulace),
- **Jednací oblast** pro **ústní projednávání** UI (jednání, prezentace, briefingy).

#### Místa zpracování UI (odst. 5)

UI se zpracovává:
- a) v **ZO příslušné kategorie** nebo vyšší,
- b) v **objektu příslušné kategorie** nebo vyšší (je-li zajištěno, že NO nemá přístup),
- c) v **objektu nižší kategorie** — pouze s písemným souhlasem odp. osoby/bezp. ředitele a při zajištění proti přístupu NO,
- d) **mimo objekt** — pouze s písemným souhlasem odp. osoby/bezp. ředitele a při zajištění proti přístupu NO (typicky mobilní zpracování, terénní operace).

#### Ukládání UI (odst. 6)

UI se **ukládá** výhradně v ZO příslušné kategorie nebo vyšší, dále v **trezoru, uzamykatelné skříni** nebo jiné schránce — parametry stanoví prováděcí vyhláška č. 528/2005 Sb.

---

### § 25 — Kategorie a třídy zabezpečených oblastí

Zákon rozlišuje:

**Kategorie ZO a objektů** (odst. 1) podle nejvyššího stupně utajení:
- a) Přísně tajné,
- b) Tajné,
- c) Důvěrné,
- d) Vyhrazené.

**Třídy ZO** (odst. 2) podle možnosti přístupu k UI:
- **třída I** — vstup = seznámení s UI (UI je v ZO viditelná, např. na pracovních stolech),
- **třída II** — vstup ≠ seznámení (UI je uzamčena v trezoru, vstup neumožňuje její faktické vnímání).

Distinkce má **praktický dopad na kontrolu vstupu**: do **třídy I** smí vstoupit pouze osoba splňující podmínky přístupu k UI příslušného stupně. Do **třídy II** **smí vstoupit i neoprávněná osoba** (NO), avšak **pouze s osobou, která má vstup povolen** (princip doprovodu) — odst. 3 in fine. To umožňuje vstup např. servisních techniků, úklidu, návštěv, aniž by museli mít vlastní oprávnění.

#### Dočasná změna třídy (odst. 4)

V odůvodněných případech a s písemným souhlasem odp. osoby/jí pověřené osoby lze **třídu I dočasně přeřadit do třídy II** — na dobu nezbytně nutnou, při zajištění proti přístupu NO. Typicky umožní vstup techniků do prostoru, jenž jinak slouží jako pracoviště s viditelnou UI.

---

### § 26 — Projednávání UI v jednací oblasti

> **§ 26 odst. 2**
>
> *Ke splnění povinnosti podle odstavce 1 je odpovědná osoba povinna požádat Národní úřad pro kybernetickou a informační bezpečnost o prověření, zda v jednací oblasti nedochází k nedovolenému použití technických prostředků určených k získávání informací; o prověření může odpovědná osoba požádat rovněž u zabezpečené oblasti kategorie Tajné nebo Přísně tajné. (...) Prověření Národní úřad pro kybernetickou a informační bezpečnost zajistí v součinnosti se zpravodajskými službami a Policií České republiky (...).*

**Výklad:**

#### Aktivní antiodposlechová ochrana jednacích oblastí

Odpovědná osoba **musí** požádat NÚKIB o prověření (anti-bugging sweep) jednací oblasti — povinný preventivní úkon. U ZO kategorií T a PT je tato žádost fakultativní. **Prověřování** zajišťuje NÚKIB ve spolupráci se zpravodajskými službami a Policií ČR; **pro vlastní potřeby** si zpravodajské služby a policie prověření provádějí samy.

Tato povinnost je důsledkem zkušeností s odposlechovými kauzami (např. odposlech sekretariátu předsedy vlády 2012 — kauza „Nagyová") a snahou zákonodárce systémově zajistit, aby kruciální jednání byla chráněna proti elektronickému odposlechu.

#### Vstup neoprávněných osob (odst. 3)

NO může do jednací oblasti vstoupit pouze **s osobou, která má vstup povolen** — obdobně jako u ZO třídy II.

---

### § 27 — Opatření fyzické bezpečnosti (taxativní výčet)

Tři kategorie:
- **a) ostraha** (lidská přítomnost — § 28),
- **b) režimová opatření** (administrativní pravidla — § 29),
- **c) technické prostředky** (fyzické a elektronické zařízení — § 30).

Tyto tři pilíře musí být **kombinovány** tak, aby dosáhly **bodové hodnoty** odpovídající kategorii ZO/objektu (§ 31).

---

### § 28 — Ostraha podle kategorie

| Kategorie ZO | Minimální ostraha |
|---|---|
| **Přísně tajné** | Nejméně **2 osoby** u objektu (nepřetržitě) |
| **Tajné** | Nejméně **1 osoba** u objektu + 1 osoba s rychlým zásahem na poplach |
| **Důvěrné** | Nejméně **1 osoba** s rychlým zásahem na poplach |
| **Vyhrazené** / bez ZO | Rozsah stanoví odp. osoba |

Pro **jednací oblasti** s pravidelným projednáváním PT: nejméně 2 osoby; pro T: 1 osoba u objektu + 1 osoba s rychlým zásahem.

Personál ostrahy: zaměstnanci orgánu/PO/podnikatele, příslušníci ozbrojených sil nebo OBS, příslušníci ozbrojených sil cizí moci, **zaměstnanci bezpečnostní ochranné služby** (BOS — soukromé bezpečnostní agentury podle zákona č. 229/2024 Sb. o BOS).

---

### § 29 — Režimová opatření

Režimová opatření jsou **administrativní pravidla**, jež stanoví:
- oprávnění osob a dopravních prostředků pro vstup/vjezd do objektu,
- oprávnění pro vstup do ZO a JO,
- způsob kontroly oprávnění,
- manipulaci s klíči, identifikačními prostředky (pro systémy podle § 30 odst. 1 písm. b)),
- manipulaci s technickými prostředky a jejich užíváním,
- výstup osob, výjezd dopravních prostředků a jejich kontrolu,
- pohyb osob v objektu/ZO/JO,
- kontrolu vynášení UI.

Režimová opatření jsou součástí **provozního řádu objektu**, jenž je součástí **projektu fyzické bezpečnosti** (§ 32).

---

### § 30 — Technické prostředky

Demonstrativní výčet technických prostředků (osm typů):
- a) **mechanické zábranné prostředky** (zámky, mříže, trezory, oplocení),
- b) **elektrická zámková zařízení a systémy pro kontrolu vstupů** (přístupové karty, biometrie),
- c) **poplachové zabezpečovací a tísňové systémy** (alarm, SOS),
- d) **dohledové videosystémy** (CCTV),
- e) **zařízení EPS** (elektrická požární signalizace),
- f) **detektory** nebezpečných látek/předmětů (RTG, kovohledačky, výbušniny),
- g) **zařízení fyzického ničení nosičů** (skartovače, demagnetizéry),
- h) **zařízení proti pasivnímu a aktivnímu odposlechu**.

#### Certifikace a body (odst. 2)

Bodová hodnota se přiřazuje **certifikovaným** prostředkům (§ 46 odst. 1 písm. a)) a necertifikovaným prostředkům **schváleným odpovědnou osobou nebo její pověřenou osobou**.

#### Nouzové nahrazení ostrahou (odst. 3)

V krizových režimech (válečný stav, nouzový stav, stav ohrožení státu, mezinárodní mise, zpravodajské operace, vojenská cvičení mimo dislokaci) lze technické prostředky nahradit **zvýšenou ostrahou** prováděnou ozbrojenými silami, OBS, ozbrojenými silami cizí moci nebo BOS cizí moci.

---

### § 31 — Bodové vyjádření míry zabezpečení

§ 31 zavádí **bodové hodnocení**: každé opatření má bodovou hodnotu, jejich součet musí dosáhnout **nejnižší míry zabezpečení** stanovené prováděcím předpisem (vyhláška č. 528/2005 Sb., přílohy). Výsledek závisí na:
- **vyhodnocení rizik** (threat assessment) — odst. 1,
- **kategorii ZO** nebo **stupni utajení** UI projednávaných v JO,
- **typu prostoru**.

Hodnocení rizik je **průběžné** (odst. 4) — mění se hrozby (od kybernetických po fyzické), opatření se upravují.

#### Pravidelné ověřování (odst. 5)

Orgán státu / PO / podnikatel je povinen **pravidelně ověřovat**, zda opatření odpovídají projektu a předpisům. Periodicita podle vyhlášky.

---

### § 32 — Projekt fyzické bezpečnosti

> **§ 32 odst. 1**
>
> *Projekt fyzické bezpečnosti v případech, kdy se v objektu nacházejí zabezpečené oblasti kategorie Přísně tajné, Tajné nebo Důvěrné, obsahuje*
>
> *- a) určení objektu a zabezpečených oblastí, včetně jejich hranic a určení kategorií a tříd zabezpečených oblastí,*
>
> *- b) vyhodnocení rizik,*
>
> *- c) způsob použití opatření fyzické bezpečnosti,*
>
> *- d) provozní řád objektu a*
>
> *- e) plán zabezpečení objektu a zabezpečených oblastí v krizových situacích.*

**Výklad:**

#### Pět úrovní obsahu projektu

Zákon diferencuje obsah **projektu fyzické bezpečnosti** podle situace:
- **odst. 1**: objekty s ZO kategorie PT/T/D — plný obsah (5 položek),
- **odst. 2**: objekty s ZO pouze kategorie V — zjednodušený obsah (2 položky),
- **odst. 3**: objekty s JO — plný obsah s JO místo ZO,
- **odst. 4**: objekty kategorií PT/T/D bez ZO/JO — bez určení hranic ZO,
- **odst. 5**: objekty kategorie V bez ZO — pouze určení objektu a hranic.

#### Uložení projektu (odst. 7)

Projekt se ukládá u **odpovědné osoby nebo bezpečnostního ředitele**. Sám projekt je často **utajovanou informací** (vlastní obsah popisuje slabá místa) — typicky stupně Vyhrazené nebo vyššího.

---

### § 33 — Zmocňovací ustanovení (fyzická bezpečnost)

Zmocnění k vydání prováděcí vyhlášky č. 528/2005 Sb., o fyzické bezpečnosti — stanovuje detailní požadavky na JO, způsob ukládání, ostrahu, režimová opatření, technické prostředky, bodové hodnocení, ověřování a obsah provozního řádu.

---

### Hlava VI — Bezpečnost informačních a komunikačních systémů

### § 33a — Příslušnost NÚKIB

> **§ 33a**
>
> *Státní správu v oblasti ochrany utajovaných informací podle této hlavy vykonává Národní úřad pro kybernetickou a informační bezpečnost, pokud tento zákon nestanoví jinak.*

**Výklad:**

#### Přesun kompetencí na NÚKIB (od 1. 8. 2017)

§ 33a (zavedený zákonem č. 205/2017 Sb.) **přenáší výkon státní správy** ve věcech IS/KS, kompromitujícího vyzařování a kryptografické ochrany na **NÚKIB** — samostatný ÚSO zřízený zákonem č. 181/2014 Sb. Toto rozdělení reflektuje technickou specializaci NÚKIB. Úřad si nadále podržel kompetence v oblasti:
- personální bezpečnost (osvědčení FO),
- průmyslová bezpečnost (osvědčení podnikatele),
- administrativní bezpečnost (vč. evidence UI cizí moci),
- fyzická bezpečnost (objekty, ZO, JO — § 24 a násl.),
- bezpečnostní způsobilost (Část třetí).

NÚKIB má naopak kompetence v IS, KS, kryptografii, kompromitujícím vyzařování a tzv. zařízení mimo IS/KS.

---

### § 34 — Informační systém pro UI

> **§ 34 odst. 1**
>
> *Informačním systémem nakládajícím s utajovanými informacemi se pro účely tohoto zákona rozumí jeden nebo více počítačů, jejich programové vybavení, k tomu patřící periferní zařízení, správa tohoto informačního systému a k tomuto systému se vztahující procesy nebo prostředky schopné provádět sběr, tvorbu, zpracování, ukládání, zobrazení nebo přenos utajovaných informací (...).*
>
> *(2) Informační systém musí být certifikován Národním úřadem pro kybernetickou a informační bezpečnost (...) a písemně schválen do provozu odpovědnou osobou nebo jí pověřenou osobou. (...)*

**Výklad:**

#### Široké pojetí IS — hardware + software + procesy

Definice IS je úmyslně **funkčně-systémová**: zahrnuje nejen HW (počítače, periferie) a SW (operační systém, aplikace), ale i **správu IS** a **procesy** schopné nakládat s UI. Z toho plyne, že:
- IS není pouze technické zařízení, ale **socio-technický systém**,
- bezpečnost IS vyžaduje organizační, personální i technická opatření,
- bezpečnostní dokumentace IS pokrývá všechny tři vrstvy.

#### Dvojí podmínka uvedení do provozu (odst. 2)

K provozu IS pro UI je nutné:
1. **Certifikace NÚKIB** podle § 46 odst. 1 písm. b) — formální správní akt, jenž ověřuje způsobilost IS,
2. **Písemné schválení do provozu odpovědnou osobou** — interní akt provozovatele, jenž potvrzuje organizační připravenost.

Bez **kumulativního** splnění obou podmínek **nesmí být UI v IS zpracovávána** (odst. 5).

#### IS cizí moci — akreditace (odst. 2 in fine)

Pro IS cizí moci, jenž má v ČR nakládat s UI, se neaplikuje certifikace, nýbrž **akreditace** prováděná NÚKIB — uznání zahraniční certifikace s ověřením relevantních aspektů.

#### IS podnikatele s Vyhrazenými UI (odst. 3)

IS podnikatele s přístupem k UI Vyhrazené **smí být schválen jen v době platnosti prohlášení podnikatele**; zánikem prohlášení automaticky zaniká schválení IS — řetězení platností.

#### Doplňující bezpečnostní opatření (odst. 4)

NÚKIB může z důvodu identifikovaných hrozeb stanovit zavedení **dalších bezpečnostních funkcí nebo opatření**. Provozovatel ohlásí jejich zavedení. Toto ustanovení reflektuje **dynamický charakter** kybernetického prostředí — bezpečnost není statický stav certifikátu, ale průběžně přizpůsobovaný proces.

#### Notifikační povinnost (odst. 6)

Schválení IS do provozu **musí** odp. osoba **písemně oznámit NÚKIB do 30 dnů** — slouží k evidenci a kontrolnímu přehledu NÚKIB.

---

### § 35 — Komunikační systém

> **§ 35 odst. 1**
>
> *Komunikačním systémem nakládajícím s utajovanými informacemi (...) se pro účely tohoto zákona rozumí systém zajišťující přenos těchto informací mezi koncovými uživateli a zahrnující koncové komunikační zařízení, periferní zařízení, přenosové prostředí, kryptografické prostředky, obsluhu a provozní podmínky a postupy.*

**Výklad:**

#### Rozdíl mezi IS a KS

| Atribut | IS | KS |
|---|---|---|
| Primární funkce | **Zpracování** UI (sběr, tvorba, ukládání, zobrazení) | **Přenos** UI mezi koncovými uživateli |
| Klíčový komponent | Software, databáze | Kryptoprostředky, přenosové prostředí |
| Akt schvalování | **Certifikace** IS (§ 48) | **Schválení projektu bezpečnosti** KS (§ 35 odst. 2) |
| Platnost | 3–5 let | (Projekt = bez explicitního omezení — schválení trvalé do změny) |

KS je obvykle součástí širší komunikační infrastruktury (typicky vojenské komunikační sítě, sítě zpravodajských služeb, kryptolinky mezi diplomatickými misemi).

#### Schválení projektu bezpečnosti KS

Pro KS se vyžaduje **schválení projektu bezpečnosti KS** NÚKIBem. Žádá orgán státu, PO podle § 60b, nebo podnikatel. Bez schválení **nelze KS provozovat**.

#### Schválení do provozu odpovědnou osobou (odst. 4) a vazba na prohlášení podnikatele (odst. 5)

Analogicky § 34 odst. 3 — KS podnikatele s Vyhrazenou UI je svázán s platností prohlášení podnikatele.

---

### § 35a — Taktická informace

> **§ 35a odst. 1**
>
> *Taktickou informací se pro účely tohoto zákona rozumí utajovaná informace s krátkou dobou trvání důvodu utajení. Taktická informace se zpracovává v informačním nebo komunikačním systému a při přenosu se chrání kryptografickou ochranou.*

**Výklad:**

#### Speciální režim pro „rychle stárnoucí" informace

**Taktická informace** je pojem reflektující operativní realitu — informace, jejichž důvod utajení je **krátkodobý** (typicky polohové údaje vojenských jednotek v reálném čase, kódy denního provozu, krátkodobá zpravodajská hlášení). Pro takové informace má klasický režim ochrany nepřiměřeně vysoké nároky vs. rizika.

Pro taktickou informaci do stupně **Tajné** lze ochranu zajistit **souborem opatření na základě vyhodnocení rizik** (rizikově orientovaný přístup namísto plné certifikace). Konkrétní pravidla stanoví **bezpečnostní standard** NÚKIB.

#### Praktický význam

Institut umožňuje **agilní operace** ozbrojených sil a zpravodajských služeb — typicky v zahraničních misích, kde by čekání na certifikaci paralizovalo operační schopnosti.

---

### Hlava VII — Ochrana UI při zpracování v zařízení mimo IS/KS

### § 35b — Příslušnost NÚKIB

Obdobně § 33a — pro Hlavu VII (kategorie zařízení mimo IS/KS) je gestorem NÚKIB.

### § 36 — Zařízení mimo IS/KS

> **§ 36 odst. 1**
>
> *Při zpracování utajované informace v elektronické podobě v zařízení, které není součástí informačního nebo komunikačního systému, zejména v psacím stroji s pamětí a v zařízení umožňujícím kopírování, záznam nebo zobrazení utajované informace anebo její převod do jiného datového formátu, musí být zajištěna ochrana této utajované informace.*

**Výklad:**

#### Tzv. „samostatná zařízení"

§ 36 pokrývá kategorii **technických prostředků se schopností zpracovávat UI v elektronické podobě**, jež **nejsou součástí IS/KS**:
- multifunkční tiskárny (kopírky, scannery),
- zařízení pro převod formátu (analogové → digitální, např. skener),
- elektronické psací stroje s pamětí (dnes téměř obsoletní, ale stále v zákoně),
- mobilní fotoaparáty, diktafony, kamery,
- specializovaná měřící zařízení s pamětí.

#### Povinnosti provozovatele (odst. 2)

Provozovatel je povinen:
- **a) vydat bezpečnostní provozní směrnici** — v souladu s ní lze UI zpracovávat,
- **b) zaslat NÚKIB informace** o zařízení (k 31. 12., do 1. 2.) — kvazi-evidenční povinnost umožňující NÚKIB přehled o samostatných zařízeních.

---

### Hlava VIII — Kryptografická ochrana

### § 36a — Příslušnost NÚKIB

Stejně § 33a, § 35b — pro kryptografickou ochranu vykonává státní správu NÚKIB.

### § 37 — Kryptografický materiál a pracoviště

> **§ 37 odst. 1**
>
> *Kryptografickým materiálem je kryptografický prostředek, materiál k zajištění jeho funkce nebo kryptografický dokument.*
>
> *(2) Kryptografické prostředky používané pro kryptografickou ochranu utajovaných informací musí být certifikovány Národním úřadem pro kybernetickou a informační bezpečnost (...); v případě utajované informace poskytované cizí moci (...) lze použít i kryptografický prostředek schválený příslušným orgánem cizí moci (...).*

**Výklad:**

#### Trojí složka kryptomateriálu (odst. 1)

- **Kryptografický prostředek** — vlastní zařízení / software realizující šifrování (HSM, šifrovací karta, šifrový software),
- **Materiál k zajištění funkce** — typicky **klíče**, **kódové knihy**, **plánovací materiály** (key material), **konfigurace**,
- **Kryptografický dokument** — dokumentace, manuály, certifikační zprávy.

#### Certifikace prostředku (odst. 2)

Kryptoprostředek musí být **certifikován NÚKIB** (§ 46 odst. 1 písm. c)). Pro UI poskytovanou cizí moci v rámci akreditovaného/certifikovaného IS lze použít i prostředek schválený **cizí mocí** — typicky NATO COMSEC equipment certified by NSA/CESG (UK NCSC).

#### Kryptografické pracoviště (odst. 3, 4)

**Kryptografické pracoviště** je pracoviště pro výkon kryptografické ochrany — bezpečnostní správa kryptomateriálu, výroba/servis kryptoprostředku, distribuce klíčů.

- **Obecné kryptopracoviště**: schválení do provozu odp. osobou nebo bezp. ředitelem; musí splňovat bezpečnostní standardy.
- **Specializované kryptopracoviště** (výroba/testování keymateriálu nebo centrální distribuční místo): vyžaduje **certifikaci NÚKIB** podle § 46 odst. 1 písm. d).

#### Evidence (odst. 5)

Vede se evidence:
- kryptomateriálu,
- pracovníků kryptografické ochrany,
- provozní obsluhy kryptoprostředků,
- kurýrů kryptomateriálu,
- osob nakládajících s kryptomateriálem podle § 42a.

---

### § 37a — Kontrolovaná kryptografická položka (CCI)

CCI je **neutajované zařízení** (nebo jeho součást) na seznamu vedeném NÚKIB, jež slouží k ochraně **informací** (nikoliv nutně utajovaných) využitím kryptografických metod. Příklad — civilní šifrovací produkty s exportní kontrolou. Užití podle bezpečnostního standardu.

Zařazení na seznam — písemnou žádost výrobce/dovozce/distributora/uživatele, NÚKIB schvaluje, je-li to v souladu se záměry ČR v ochraně UI.

### § 37b — Kontrolovaná položka

Stejný režim jako CCI, ale pro **neutajované zařízení, jež není CCI**. Vede vedlejší seznam NÚKIB. Slouží k udržení přehledu o kryptografickém ekosystému ČR i pro neutajované, ale bezpečnostně relevantní produkty.

---

### § 38 — Výkon kryptografické ochrany

> **§ 38 odst. 1**
>
> *Výkonem kryptografické ochrany se rozumí*
>
> *- a) její bezpečnostní správa,*
>
> *- b) speciální obsluha kryptografického prostředku, nebo*
>
> *- c) výroba nebo servis kryptografického prostředku nebo materiálu k zajištění jeho funkce.*
>
> *(2) Výkon kryptografické ochrany provádí pracovník kryptografické ochrany, který je*
>
> *- a) k výkonu kryptografické ochrany pověřen odpovědnou osobou (...),*
>
> *- b) držitelem platného osvědčení fyzické osoby a poučení a*
>
> *- c) držitelem osvědčení o zvláštní odborné způsobilosti pracovníka kryptografické ochrany (...).*

**Výklad:**

#### Trojí kvalifikační podmínka pro pracovníka kryptografické ochrany

Pracovník kryptografické ochrany musí kumulativně:
1. být **pověřen** odp. osobou,
2. mít **platné osvědčení FO** (D/T/PT — Vyhrazené nestačí, ale šetřilo by se to v § 41 odst. 3),
3. mít **osvědčení o zvláštní odborné způsobilosti** — vydává NÚKIB po odborné zkoušce.

#### Tři typy činností (odst. 1)

- **Bezpečnostní správa**: nastavení, distribuce klíčů, audit, monitoring,
- **Speciální obsluha**: pokročilé uživatelské funkce kryptoprostředku,
- **Výroba nebo servis**: technické úkony s kryptoprostředkem.

(Pozn.: jednoduchá **provozní obsluha** kryptoprostředku (běžné šifrovací úkony) podléhá lehčímu režimu — § 40.)

---

### § 39 — Zvláštní odborná způsobilost a zkouška

Specializovaný atest vydávaný NÚKIB po zkoušce **před zkušební komisí**. Komisaře jmenuje odp. osoba NÚKIB nebo orgánu státu, jenž zkoušku provádí na základě smlouvy podle § 52. Osvědčení platí **nejdéle 5 let**.

#### Decentralizace zkoušky

NÚKIB může uzavřít smlouvu s orgánem státu o provedení zkoušky (osvědčení vydá tento orgán státu); s PO podle § 60b nebo s podnikatelem může uzavřít smlouvu pouze o **části zkoušky** týkající se speciální obsluhy nebo výroby/servisu.

---

### § 40 — Provozní obsluha kryptografického prostředku

Nižší kvalifikační stupeň — **provozní obsluha** zahrnuje běžné uživatelské funkce. Osoba musí:
- a) být pověřena odp. osobou,
- b) splňovat podmínky přístupu k UI (§ 6 odst. 1 nebo § 11 odst. 1 — postačí tedy i Vyhrazené, je-li UI Vyhrazená),
- c) být **zaškolena** (ne plnoprávně atestována).

---

### § 41 — Manipulace s kryptomateriálem a CCI

Pravidla pro **přenášení, přepravu, půjčování, ukládání, vyřazování** kryptomateriálu. Klíčové aspekty:

- **odst. 2**: kryptomateriál lze evidovat a manipulovat pouze způsobem a prostředky zajišťujícími jeho ochranu (prováděcí předpis — vyhláška č. 432/2011 Sb.),
- **odst. 3**: přístup ke kryptografickému dokumentu (manuál apod.) lze umožnit FO, jež neprovádí činnosti podle § 38 odst. 1, splňuje-li podmínky § 38 odst. 2 písm. b) (platné osvědčení FO + poučení) a je řádně poučena v oblasti kryptografické ochrany,
- **odst. 4**: kryptoprostředek a keymateriál do stupně Důvěrné lze chránit bez ukládání, je-li trvale pod **dohledem** oprávněného uživatele (typicky služební mobilní šifrátor nošený příslušníkem),
- **odst. 5**: CCI a kontrolovaná položka — podle bezpečnostního standardu.

---

### § 42 — Přeprava kryptomateriálu a vývoz kryptoprostředku

#### Kurýr kryptomateriálu (odst. 1)

Specializovaný kurýr s trojí kvalifikací:
- pověření odp. osoby,
- splnění podmínek přístupu k UI nejméně pro stupeň přepravovaného materiálu,
- zaškolení k přepravě.

#### Vývoz kryptoprostředku (odst. 2, 3, 4)

Certifikovaný kryptoprostředek lze z ČR **vyvážet pouze s povolením NÚKIB**. Žádost je písemná, povolení vydáno na **konkrétní prostředek** s **účelem vývozu**. NÚKIB **nevydá** povolení, byla-li by ohrožena UI ČR nebo UI, k jejíž ochraně se ČR zavázala. **Není právní nárok** na povolení.

Výjimka: **používání mimo území ČR orgánem státu** (typicky AČR/policejní jednotky v zahraničí, diplomatické mise) se nepovažuje za vývoz.

NÚKIB vede **evidenci povolení**.

### § 42a — Nakládání s kryptomateriálem jiným způsobem

Pokud FO nakládá s kryptomateriálem jinak než podle § 38, 40, 41 odst. 3 nebo § 42 (typicky transport mezi pracovišti, vyřazování, přechodné držení), musí být:
- pověřena odp. osobou,
- držitelem osvědčení FO + poučení (§ 38 odst. 2 písm. b)),
- držitelem osvědčení o zvláštní odborné způsobilosti (§ 38 odst. 2 písm. c)).

Tedy obdobné požadavky jako na pracovníka kryptografické ochrany.

---

### § 43 — Kompromitace kryptomateriálu

> **§ 43 odst. 1**
>
> *Kompromitací kryptografického materiálu se rozumí nakládání s kryptografickým materiálem, které způsobilo nebo by mohlo způsobit porušení ochrany utajované informace.*

**Výklad:**

#### Notifikační povinnost (odst. 2)

Při kompromitaci **musí** orgán státu / PO podle § 60b / podnikatel **neprodleně** oznámit NÚKIB. Reakce NÚKIB obvykle zahrnuje:
- zákaz dalšího použití kompromitovaného materiálu,
- distribuci nového keymateriálu,
- vyšetřování zdroje kompromitace.

Kompromitace je nejzávažnější incident v kryptografické ochraně — může vést k nutnosti **rekey** celého systému (vč. spojeneckých sítí).

---

### § 43a — Distribuce a evidence kryptomateriálu (NÚKIB / MO)

Centrální distribuce a evidence kryptomateriálu:
- **NÚKIB**: kryptomateriál ČR, EU a kryptomateriál na základě mezinárodní smlouvy (s výjimkou vojenského),
- **Ministerstvo obrany**: kryptomateriál NATO a kryptomateriál pro vojenské účely.

Toto dvojkolejné dělení reflektuje **specializaci ozbrojených sil** a tradiční vazbu vojenské kryptografie na MO; navíc kryptomateriál NATO podléhá samostatnému režimu COMSEC se sídlem v Bruselu (NATO C3 Board, NICA Mons).

---

### § 44 — Zmocňovací ustanovení (kryptografická ochrana)

Zmocňuje k vydání prováděcí vyhlášky (zejm. vyhláška č. 432/2011 Sb., o zajištění kryptografické ochrany utajovaných informací) — náležitosti přihlášky ke zkoušce, organizace zkoušky, požadavky na kryptopracoviště, manipulace s materiálem, evidence atd.

---

### Kompromitující vyzařování (§§ 45–45a)

### § 45 — TEMPEST

> **§ 45 odst. 1**
>
> *Ochranou utajovaných informací stupně utajení Přísně tajné, Tajné nebo Důvěrné před jejich únikem kompromitujícím vyzařováním je zabezpečení elektrických a elektronických zařízení, zabezpečené oblasti, jednací oblasti nebo objektu.*

**Výklad:**

#### Mezinárodní termín TEMPEST

„Kompromitující vyzařování" je český překlad mezinárodního termínu **TEMPEST** (Transient Electromagnetic Pulse Emanation Standard) — elektromagnetické emise elektronických zařízení, jež mohou prozradit obsah zpracovávané informace (klávesnice, monitor, kabeláž).

#### Ochrana stínicí komorou (odst. 2)

Stínicí komora (Faraday cage) musí být **certifikována NÚKIB** podle § 46 odst. 1 písm. e). Stínicí komora je technické řešení pro vysoce citlivá pracoviště — typicky šifrová pracoviště, briefingové místnosti zpravodajských služeb.

#### Ověřování způsobilosti (odst. 3, 4, 5)

Ověřování provádí NÚKIB při certifikaci IS, kryptoprostředku, schvalování projektu KS, nebo na žádost. Pro dílčí měření lze uzavřít smlouvu (§ 52). **Zpravodajské služby** mají oprávnění **provádět měření samy** pro svá zařízení/oblasti — bez smlouvy podle § 52 (ochrana zpravodajských metod).

### § 45a — Hlava IX — Příslušnost NÚKIB

Obdobně § 33a — pro **certifikaci** (Hlava IX, §§ 46–53) vykonává státní správu zejména NÚKIB, s výjimkami uvedenými níže.

---

### Hlava IX — Certifikace

### § 46 — Společná ustanovení

> **§ 46 odst. 1**
>
> *Certifikace je postup, jímž Úřad nebo Národní úřad pro kybernetickou a informační bezpečnost*
>
> *- a) ověřuje způsobilost technického prostředku k ochraně utajovaných informací,*
>
> *- b) ověřuje způsobilost informačního systému k nakládání s utajovanými informacemi,*
>
> *- c) ověřuje způsobilost kryptografického prostředku k ochraně utajovaných informací,*
>
> *- d) ověřuje způsobilost kryptografického pracoviště pro vykonávání činností podle § 37 odst. 4, nebo*
>
> *- e) ověřuje způsobilost stínicí komory k ochraně utajovaných informací.*

**Výklad:**

#### Pět druhů certifikace a dělba kompetencí

| Certifikace | § | Gestor |
|---|---|---|
| a) Technický prostředek (fyz. bezp.) | § 47 | **Úřad** |
| b) Informační systém | § 48 | NÚKIB |
| c) Kryptografický prostředek | § 49 | NÚKIB |
| d) Kryptografické pracoviště | § 50 | NÚKIB |
| e) Stínicí komora | § 51 | NÚKIB |

**Úřad** zůstal příslušný pouze pro certifikaci **technických prostředků fyzické bezpečnosti** (zámky, trezory, EZS, CCTV — § 30). Vše ostatní přešlo na NÚKIB.

#### Certifikát jako veřejná listina (odst. 3)

Certifikát je **veřejnou listinou** ve smyslu § 134 OSŘ — má presumpci pravdivosti.

#### Náležitosti certifikátu (odst. 4–9)

Detailní katalog povinných údajů — evidenční číslo, identifikace prostředku/držitele/výrobce, doba platnosti, otisk razítka (nebo el. podpis), případně specifické položky (kategorie kryptopracoviště, stupeň utajení pro IS/kryptoprostředek/stínicí komoru).

#### Zánik platnosti certifikátu (odst. 11)

Rozdělení pravomocí ke zrušení certifikátu:
- **Úřad** ruší certifikát technického prostředku (§ 47 odst. 4 písm. b)),
- **NÚKIB** ruší certifikáty podle § 48, 49, 50, 51.

**Odvolání proti zrušení nemá odkladný účinek**; proti zrušení certifikátu IS nebo kryptoprostředku NÚKIB **odvolání není přípustné** (definitivnost zajištění bezpečnosti).

#### Odevzdání certifikátu (odst. 12)

Po zániku platnosti — odevzdání do 5 dnů příslušnému gestor (NÚKIB / Úřad). Týká se pouze certifikátů ne-elektronických.

#### Smluvní podpora certifikace (odst. 14, 15, 16, 17, 18)

- Úřad může uzavřít smlouvu s orgánem státu / PO podle § 60b / podnikatelem o **vydávání posudku** vlastností technického prostředku (odst. 14),
- NÚKIB může uzavřít smlouvu o **dílčích úlohách** certifikace u IS, kryptoprostředku, kryptopracoviště, stínicí komory (odst. 15) — s výjimkou vlastnictví zpravodajských služeb,
- Seznamy smluvních partnerů (kromě zpravodajských služeb) jsou veřejné (odst. 16),
- Pro IS/kryptoprostředek atd. **zpravodajských služeb** zpravodajské služby provádějí dílčí úlohy **samy** (odst. 17) a jsou povinny dodržovat zákon, předpisy a standardy NÚKIB (odst. 18) — princip operativní autonomie zpravodajských služeb při zachování metodického dohledu NÚKIB.

#### Účastník řízení (odst. 19)

Jediným účastníkem řízení o certifikaci nebo o zrušení platnosti je **žadatel** (§ 47–51 odst. 1).

---

### § 47 — Certifikace technického prostředku (Úřad)

- O certifikaci písemně žádá u **Úřadu** výrobce/dovozce/distributor/uživatel.
- Doba platnosti: **nejdéle 5 let**.
- Seznam certifikovaných prostředků je **veřejný** (na webu Úřadu) — kromě těch certifikovaných na žádost uživatele.
- Zánik: uplynutím doby, nebo rozhodnutím Úřadu (prostředek neodpovídá zákonu/posudku).
- Po uplynutí doby platnosti lze **stále používat** — odst. 6 (zákon nevyžaduje vyřazení, jen brání novému nasazení).
- Úřad může přihlédnout k zahraničnímu certifikátu (mezinárodní uznávání).

### § 48 — Certifikace IS (NÚKIB)

- O certifikaci IS žádá u **NÚKIB** orgán státu / PO podle § 60b / podnikatel, jenž bude IS provozovat.
- Doba platnosti:
  - **PT, T, D**: nejdéle **3 roky**,
  - **Vyhrazené**: nejdéle **5 let**.
- Zánik: uplynutím doby; **u IS pro D a vyšší — zánikem osvědčení podnikatele**; zrušením orgánu státu / zánikem PO podle § 60b; rozhodnutím NÚKIB; oznámením držitele o zrušení IS.
- **Opakovaná žádost**: musí být doručena **nejméně 6 měsíců** před uplynutím doby platnosti.
- Lhůty: NÚKIB rozhodne **do 1 roku**, ve zvlášť složitých případech **do 2 let**, s prodloužením ředitele NÚKIB nejvýše o 6 měsíců.

### § 49 — Certifikace kryptoprostředku (NÚKIB)

- Žadatel: výrobce/dovozce/distributor/uživatel. Podnikatel jen s osvědčením podnikatele pro formu § 20 odst. 1 písm. a).
- NÚKIB může **odmítnout** žádost, není-li v souladu se záměry ČR; **odvolání ani soudní přezkum** nepřípustné (politicko-bezpečnostní rozhodnutí).
- Doba platnosti: nejdéle **5 let**.
- Zánik: uplynutím doby nebo rozhodnutím NÚKIB (přestal být způsobilý).
- Opakovaná žádost: nejméně **6 měsíců** před uplynutím.
- NÚKIB může přihlédnout k zahraničnímu certifikátu.
- **Přerušení řízení** je možné při dotazu zahraničnímu subjektu.
- NÚKIB může stanovit způsobilost kryptoprostředku **k ochraně taktické informace** (§ 35a).
- Lhůty podle § 48 odst. 6.

### § 50 — Certifikace kryptopracoviště (NÚKIB)

- Žadatel: orgán státu / PO podle § 60b / podnikatel s osvědčením podnikatele.
- Doba platnosti: nejdéle **3 roky**.
- Zánik: uplynutím doby, zánikem osvědčení podnikatele, zrušením/zánikem žadatele, rozhodnutím NÚKIB, oznámením o zrušení pracoviště.
- Opakovaná žádost: nejméně **6 měsíců** před uplynutím.
- Lhůty: **6 měsíců**, složité případy **1 rok**, prodloužení **až o 3 měsíce**.

### § 51 — Certifikace stínicí komory (NÚKIB)

- Žadatel: orgán státu / PO podle § 60b / podnikatel.
- Doba platnosti: nejdéle **5 let**.
- Zánik: stejné kategorie jako u § 50.
- Opakovaná žádost: nejméně **12 měsíců** před uplynutím (delší než u jiných — fyzické zařízení vyžaduje delší přípravu rekertifikace).
- Lhůty podle § 50 odst. 6.

---

### § 52 — Smlouva o zajištění činnosti

> **§ 52 odst. 1**
>
> *Smlouva o zajištění činnosti (...) uvedená v § 39 odst. 3, § 45 odst. 4 a § 46 odst. 14 a 15 se uzavírá na dobu určitou nebo neurčitou. Smlouva musí mít písemnou formu. Projev vůle účastníků smlouvy musí být na téže listině.*

**Výklad:**

#### Smluvní outsourcing části státní správy

§ 52 je obecný procesní rámec pro **smluvní delegaci** specializovaných úkolů Úřadu/NÚKIB na **orgány státu, PO podle § 60b nebo podnikatele**:
- vydávání posudků k technickým prostředkům (§ 46 odst. 14),
- dílčí úlohy certifikace (§ 46 odst. 15),
- odborné zkoušky (§ 39 odst. 3),
- měření kompromitujícího vyzařování (§ 45 odst. 4).

Smlouva má povahu **veřejnoprávní** v širším smyslu — řídí se ZOÚI, subsidiárně občanským zákoníkem (odst. 9).

#### Podmínky uzavření (odst. 2, 3)

- Odborná způsobilost zaměstnanců,
- Organizační/technické/materiální zajištění,
- Pro podnikatele: sídlo v ČR + platné osvědčení podnikatele (kromě posudku podle § 46 odst. 14).

#### Obsah smlouvy (odst. 4)

Obligatorní náležitosti — označení, předmět/rozsah, práva/povinnosti, kontrola, podmínky odstoupení, souhlas se zveřejněním (u posudků).

#### Kontrola a sankce (odst. 5, 6)

Úřad/NÚKIB je oprávněn kontrolovat plnění; **musí odstoupit** v případě porušení povinnosti druhým účastníkem.

---

### § 53 — Zmocňovací ustanovení (certifikace)

Zmocnění k prováděcí vyhlášce: detaily žádostí, dokumentace, postup certifikace, vzory certifikátů. Zejména vyhláška č. 525/2005 Sb. (technické prostředky), č. 523/2005 Sb. (IS), č. 524/2005 Sb. (administrativní bezpečnost — částečně se vztahuje), č. 432/2011 Sb. (kryptografie).

---

### Hlava X — Osvědčení FO, osvědčení podnikatele, zvláštní přístup, zproštění mlčenlivosti

### Osvědčení fyzické osoby a osvědčení podnikatele (§§ 54–57)

### § 54 — Náležitosti osvědčení

> **§ 54 odst. 1**
>
> *Osvědčení fyzické osoby a osvědčení podnikatele jsou veřejnými listinami.*

**Výklad:**

#### Povaha osvědčení — veřejná listina

Obě osvědčení jsou **veřejnými listinami** se silou presumpce pravdivosti (§ 134 OSŘ). Vydává **výlučně Úřad** (s výjimkami pro zpravodajské služby a MV — § 56 odst. 1 písm. g)–i)).

#### Náležitosti osvědčení FO (odst. 2)

- a) jméno, příjmení, rodné příjmení,
- b) datum a místo narození,
- c) státní občanství,
- d) **nejvyšší stupeň utajení**, pro nějž osvědčení opravňuje,
- e) datum vydání a doba platnosti,
- f) otisk úředního razítka a podpis zástupce Úřadu.

#### Náležitosti osvědčení podnikatele (odst. 3)

- a) identifikace firmou/názvem + IČ (PO) nebo jménem/firmou + IČ (FO),
- b) **nejvyšší stupeň utajení**,
- c) **forma přístupu** podle § 20,
- d) datum vydání a doba platnosti,
- e) razítko a podpis.

#### Změna údaje (odst. 4)

Při změně údaje Úřad **bezodkladně** vydá nové osvědčení; přístup k UI **není dotčen** do doby doručení nového.

---

### § 55 — Doba platnosti

> **§ 55**
>
> *Platnost osvědčení fyzické osoby a osvědčení podnikatele je pro stupeň utajení*
>
> *- a) Přísně tajné 5 let a*
>
> *- b) Tajné a Důvěrné 10 let.*

**Výklad:**

Diferencovaná platnost:
- **PT — 5 let** (kratší = častější reverifikace u nejcitlivějšího stupně),
- **T, D — 10 let**.

Toto je významná úspora administrativní zátěže oproti starému zákonu (148/1998 Sb. — platnost 5 let pro všechny stupně). Pro Vyhrazené (oznámení) je periodicita reverifikace **5 let** podle § 9 odst. 2.

---

### § 56 — Zánik platnosti osvědčení

§ 56 odst. 1 vypočítává **12 důvodů zániku platnosti**:

| Písm. | Důvod |
|---|---|
| a) | Uplynutím doby |
| b) | Dnem vykonatelnosti rozhodnutí Úřadu o zrušení (§ 123 odst. 3, § 126 odst. 4) |
| c) | Úmrtím FO / prohlášením za mrtvou |
| d) | Zrušením/zánikem podnikatele |
| e) | Ohlášením odcizení/ztráty |
| f) | Ohlášením poškození (nečitelnost/porušení celistvosti) |
| g) | U osvědčení FO vydaného Úřadem — vznik služebního/pracovního poměru u zpravodajské služby / příslušníka BIS/ÚZSI / MO Vojenské zpravodajství; nebo se osoba stane osobou podle § 141 odst. 1 (MV) |
| h) | U osvědčení FO vydaného **zpravodajskou službou** — skončením vztahu se zpravodajskou službou |
| i) | U osvědčení FO vydaného **Ministerstvem vnitra** — přestala-li FO být osobou podle § 141 odst. 1 |
| j) | Vrácením držitelem vydavateli |
| k) | Doručením nového osvědčení FO |
| l) | Doručením nového osvědčení podnikatele pro stejnou formu přístupu |

#### Důsledky zániku (odst. 2, 3)

Při zániku osvědčení **podnikatele** podle a), b), d), j): podnikatel **odevzdá** UI poskytnutou tomu, kdo mu ji poskytl; UI vzniklé u něj — orgánu státu, do jehož působnosti náleží, jinak Úřadu.

Při zániku osvědčení **FO** podle a), b), j): odp. osoba nebo ten, kdo poučil, zajistí, aby FO neměla přístup k UI.

#### Záchranná lhůta (odst. 4)

Při zániku podle e) (odcizení/ztráta) nebo f) (poškození) může držitel do **15 dnů** požádat o nové osvědčení — přístup k UI není dotčen. Úřad vydá nové do **5 dnů** od žádosti.

#### Záchranná lhůta při doručení nového (odst. 5)

Při zániku podle k) (doručení nového) není přístup dotčen, je-li FO **poučena do 15 dnů** ode dne tohoto zániku.

---

### § 56a — Návaznost osvědčení vydaných různými orgány

§ 56a řeší specifickou situaci, kdy FO **přechází** mezi orgány s různými vydavatelskými kompetencemi:
- vstoupí do zpravodajské služby nebo MV → původní osvědčení Úřadu zaniká (§ 56 odst. 1 písm. g)), nové vydá příslušná zpravodajská služba nebo MV (odst. 1),
- vystoupí ze zpravodajské služby nebo MV → původní osvědčení zaniká (písm. h), i)), nové vydá:
  - **zpravodajská služba**, vstoupí-li do jiné zpravodajské služby,
  - **MV**, stane-li se osobou podle § 141 odst. 1,
  - **Úřad** v ostatních případech (do 5 dnů od žádosti, žádost lze podat do **30 dnů** od zániku).

#### Předávání bezpečnostního svazku (odst. 4)

Orgán, jenž vydá nové osvědčení, si **písemně vyžádá bezpečnostní svazek** od předchozího vydavatele — předání do 5 dnů. Tím se zachová **kontinuita prověřování** a sníží duplicitní bezpečnostní řízení.

---

### § 57 — Osvědčení pro cizí moc (PSC FCO / FSC FCO)

> **§ 57 odst. 1**
>
> *Má-li mít fyzická osoba nebo podnikatel přístup k utajované informaci cizí moci, musí splňovat podmínky podle § 11 nebo § 15 písm. b), a požaduje-li tak cizí moc, být též držitelem osvědčení pro cizí moc.*

**Výklad:**

#### Mezinárodní rozměr — PSC a FSC

Osvědčení pro cizí moc (Personnel Security Clearance for Foreign Country / Facility Security Clearance for Foreign Country, v EU terminologii) je dokument vystavený Úřadem, jenž **potvrzuje vůči zahraničnímu partnerovi**, že FO nebo podnikatel splňuje českou bezpečnostní prověrku a může mít přístup k UI cizí moci.

Vydává se na **písemnou odůvodněnou žádost** držitele platného osvědčení FO/podnikatele, je-li to v souladu s bezpečnostními a ekonomickými zájmy ČR a se závazky z mezinárodní smlouvy a neprobíhá-li řízení o zrušení platnosti.

#### Souběh s žádostí o vydání osvědčení (odst. 3)

Pokud je žádost o osvědčení pro cizí moc podána současně s žádostí o vydání osvědčení FO/podnikatele (§§ 94, 96 ZOÚI), Úřad postupuje **neprodleně** po vydání osvědčení FO/podnikatele.

#### Doba platnosti (odst. 7)

Vydává se na dobu nezbytně nutnou, **nejdéle však na dobu platnosti** osvědčení FO/podnikatele.

#### Krizové prodloužení (odst. 9)

V případě **krizového stavu** (válečný stav, nouzový stav nebo stav ohrožení státu pro celé území ČR) **neplatnost osvědčení podle § 56 odst. 1 písm. a)** (uplynutí doby) **automaticky neznamená zánik platnosti osvědčení pro cizí moc** — to platí dále až do rozhodnutí o nové žádosti, nejdéle **12 měsíců**. Tím se zachovává **operační kontinuita** v krizi.

#### Potvrzení o rozsahu ochrany u PO podle § 60b (odst. 12)

Speciální nástroj pro PO podle § 60b — Úřad vydá časově omezené potvrzení o rozsahu ochrany UI zajištěné u této PO, vyžaduje-li to její zahraniční partner.

---

### Zvláštní přístup k utajované informaci (§§ 58–62)

### § 58 — Osoby s přístupem ex constitutionne

> **§ 58 odst. 1**
>
> *Osobami, které mají přístup k utajované informaci všech stupňů utajení bez platného osvědčení fyzické osoby a poučení, jsou*
>
> *- a) prezident republiky,*
>
> *- b) poslanci a senátoři Parlamentu,*
>
> *- c) členové vlády,*
>
> *- d) veřejný ochránce práv, ochránce práv dětí a jejich zástupce,*
>
> *- e) soudci a*
>
> *- f) prezident, viceprezident a členové Nejvyššího kontrolního úřadu.*

**Výklad:**

#### Ústavní výjimka z bezpečnostní prověrky

Ustanovení reflektuje **principy ústavního práva** — funkcionáři, jejichž legitimita pochází z volby/jmenování v ústavně předvídaných postupech, nemohou být **podmiňováni** prověrkou ze strany výkonné moci (Úřadu), neboť by tím byla narušena dělba moci.

Katalog šesti kategorií:
- **a) prezident republiky** — hlava státu (čl. 54 Ústavy),
- **b) poslanci a senátoři** — zákonodárná moc (čl. 15),
- **c) členové vlády** — výkonná moc (čl. 67),
- **d) veřejný ochránce práv, ochránce práv dětí a zástupci** — kontrolní orgán (zákon č. 349/1999 Sb.),
- **e) soudci** — soudní moc (čl. 81 a násl.),
- **f) prezident/viceprezident/členové NKÚ** — kontrolní orgán (čl. 97).

#### Časový a věcný rozsah (odst. 2)

Přístup je ex constitutionne ode **dne zvolení/jmenování po dobu výkonu funkce** a v **rozsahu nezbytném pro její výkon** (need-to-know zachován).

#### Operativní výjimky (odst. 3)

Bez osvědčení FO mohou mít přístup:
- FO jednající ve prospěch zpravodajské služby (typicky agenti),
- informátoři,
- FO se zvláštní/krátkodobou ochranou (svědci, oběti — zákon č. 137/2001 Sb.),
- příslušníci zpravodajské služby v záloze zvláštní / zvláštní dispozici.

Poučení provede ten, kdo přístup umožní; přístup k UI cizí moci pouze v souladu s požadavky této cizí moci.

#### Procesní výjimky v soudních řízeních (odst. 4, 5, 6)

Klíčové ustanovení pro **právní stát** — zvláštní právní předpis (typicky TŘ § 8b–c, OSŘ § 40 odst. 2, SŘ § 17, SŘS) stanoví, **které osoby a za jakých podmínek** mají přístup k UI bez osvědčení v:
- **trestním řízení** (obviněný, obhájce, znalec, tlumočník, poškozený, zúčastněná osoba),
- **občanském soudním řízení**,
- **správním řízení** a **soudním řízení správním**.

Přístup je umožněn **v rozsahu nezbytném pro uplatnění práv** a jen **na základě poučení** podle odst. 5. Tím je vyvážena ochrana UI s **právem na obhajobu** a **na spravedlivý proces** (čl. 36, 40 Listiny; čl. 6 EÚLP). Judikatura ÚS (např. Pl. ÚS 41/02, II. ÚS 28/03) opakovaně potvrdila ústavní mantinely — UI nesmí vést k „**slepým" procesům**, kde strana nezná podklad.

#### UI cizí moci v řízeních (odst. 6)

Pro UI cizí moci je přístup omezen jen na **prezidenta, poslance/senátora, člena vlády a soudce** — ostatní osoby z odst. 4 (typicky obhájce, znalec) mají přístup **po předchozím souhlasu cizí moci**. Reflektuje princip suverenity klasifikujícího státu (originator control).

Poučení v přípravném trestním řízení provádí **policejní orgán nebo státní zástupce**, v řízení před soudem **předseda senátu**.

---

### § 58a — Osoby s přístupem k Vyhrazenému bez oznámení

> **§ 58a odst. 1**
>
> *Osobami, které mají přístup k utajované informaci stupně utajení Vyhrazené bez platného oznámení po dobu trvání služebního nebo pracovního poměru a v rozsahu nezbytném pro jeho výkon, jsou*
>
> *- a) příslušníci bezpečnostních sborů,*
>
> *- b) státní zaměstnanci,*
>
> *- c) vojáci v činné službě a*
>
> *- d) státní zástupci,*
>
> *pokud jsou poučené a zařazené na místě nebo vykonávají funkci, na kterých je nezbytné mít přístup k utajovaným informacím, a které jsou uvedené v přehledu podle § 69 odst. 1 písm. b).*

**Výklad:**

#### Zjednodušený přístup pro „silové" složky

§ 58a je **významnou administrativní úlevou** zavedenou novelami od roku 2017. Pro čtyři kategorie funkcionářů (příslušníci bezp. sborů, státní zaměstnanci, vojáci v činné službě, státní zástupci) **odpadá** povinnost mít oznámení podle § 6 — postačí:
- platné služební/pracovní zařazení,
- poučení (§ 9 odst. 1 obdobně),
- místo/funkce uvedené v **přehledu podle § 69 odst. 1 písm. b)** — interní katalog míst, kde je přístup k UI nezbytný.

#### Zánik (odst. 3)

Při skončení vztahu nebo změně služebního úřadu se má za to, že FO **není poučena** (obdobně § 9 odst. 7); měla-li přístup k UI, postupuje se podle § 11a (potvrzení mlčenlivosti).

---

### § 58b — Zvláštní oprávnění zpravodajských služeb

Zpravodajská služba může umožnit přístup k UI FO/podnikateli **bez osvědčení/oznámení**, je-li to **nezbytné**:
- a) pro plnění zákonné povinnosti FO/podnikatele,
- b) v rámci **zpravodajských operací**.

Operativní oprávnění reflektující charakter zpravodajské práce (agenturní operace, oslovování zdrojů, krycí aktivity). Postup podle § 60 odst. 2–6 se použije **obdobně** (poučení, evidence, dohled).

---

### § 58c — Zvláštní oprávnění Policie ČR

Policie může umožnit přístup k UI FO bez osvědčení/oznámení, **je-li to nezbytné** pro plnění zákonných úkolů v oblasti:
- zvláštní ochrany a pomoci (zákon č. 137/2001 Sb.),
- krátkodobé ochrany (chráněné osoby),
- zajišťování bezpečnosti chráněných objektů a prostorů (vč. určených osob),
- sledování osob a věcí (§ 158d TŘ).

**Vyloučen** je přístup k UI cizí moci a UI stupně **Přísně tajné**. Postup podle § 60 odst. 2–5 obdobně, ale poučení a záznam se Úřadu **nezasílají** — ukládají se u policie.

---

### § 59 — Jednorázový přístup k vyššímu stupni

> **§ 59 odst. 1**
>
> *Na základě písemné žádosti odpovědné osoby může Úřad ve výjimečných a odůvodněných případech vydat souhlas s jednorázovým přístupem k utajované informaci se stupněm utajení o jeden vyšším, než na který je vydáno platné osvědčení fyzické osoby nebo osvědčení podnikatele, a to na dobu nezbytně nutnou, nejdéle však na dobu 6 měsíců.*

**Výklad:**

#### Operativní výjimka pro zvláštní situace

Jednorázový přístup je nástroj pro situace, kdy je třeba **rychle** umožnit přístup k informaci o stupeň vyššímu, než pro který má FO/podnikatel osvědčení (např. zapojení do mezirezortní pracovní skupiny, urgentní krizové řízení). Podmínky:
- **písemná žádost** odpovědné osoby (u zpravodajských služeb ředitel, u policie podle § 141 odst. 1 ministr vnitra — odst. 3),
- **výjimečnost a odůvodněnost**,
- pouze o **jeden stupeň** vyšší,
- nejdéle **6 měsíců**,
- **nelze udělit dvakrát** téže osobě (odst. 6) — princip jednorázovosti.

U podnikatele lze udělit pouze pro formu přístupu § 20 odst. 1 písm. b) — zaměstnanci přistupují v cizím prostředí (nedochází k fyzickému ukládání UI vyššího stupně u podnikatele).

#### Lhůta vydání (odst. 5)

Úřad vydá **neprodleně, nejpozději do 5 dnů**. Odp. osoba (nebo pověřená) následně **provede poučení** FO před přístupem.

#### Nepřípustnost u UI cizí moci (odst. 7)

K UI cizí moci lze jednorázový přístup umožnit **pouze v souladu s požadavky cizí moci** — originator control.

---

### § 59a — Operativní zvýšení o dva stupně pro orgány TŘ

Speciální výjimka pro:
- osoby služebně činné v policejním orgánu,
- státní zástupce jako orgány činné v trestním řízení,
- státní zástupce plnící úkoly podle jiného předpisu.

Úřad může vydat souhlas s přístupem k UI **až o dva stupně vyšší**, než pro nějž má FO osvědčení.

Pro osobu **služebně činnou v policejním orgánu** musí být žádost doplněna **souhlasným stanoviskem dozorujícího státního zástupce**; u UI **Přísně tajné** též stanoviskem **vedoucího státního zástupce nejblíže vyššího státního zastupitelství**. Tato kaskádová kontrola reflektuje princip **soudního dozoru nad orgány policie v trestním řízení**.

---

## Závěr kapitoly

Část první a první polovina Části druhé zákona č. 412/2005 Sb. tvoří **kostru** systému ochrany utajovaných informací v ČR. Klíčové strukturální prvky lze shrnout takto:

1. **Trojkonjunktivní definice utajované informace** (§ 2 písm. a) — označení + materiální následek + katalogová podřaditelnost) brání svévolné klasifikaci a zajišťuje přezkoumatelnost.

2. **Čtyřstupňová škála utajení** (§ 4) ve spojení s **trojstupňovou škálou újmy + nevýhodnost** (§ 3) je plně harmonizována s NATO a EU; konverze se uskutečňuje **převodními tabulkami** sdělenými ve Sbírce zákonů (§ 23 odst. 4).

3. **Šest pilířů ochrany** (§ 5) — personální, průmyslová, administrativní, fyzická, IS/KS, kryptografická — tvoří **defense-in-depth** architekturu, v níž se vrstvy vzájemně doplňují a kompenzují.

4. **Dvouinstanční gestor** — od 1. 8. 2017 sdílí kompetence **Úřad** (personální, průmyslová, administrativní, fyzická bezpečnost, bezpečnostní způsobilost) a **NÚKIB** (IS, KS, kompromitující vyzařování, kryptografická ochrana, jejich certifikace). Toto rozdělení reflektuje technickou specializaci NÚKIB jakožto centrálního orgánu kybernetické bezpečnosti.

5. **Stupňovitý systém oprávnění**:
   - **Vyhrazené**: oznámení (svéprávnost + 18+ + bezúhonnost) → vydává odpovědná osoba,
   - **Důvěrné, Tajné, Přísně tajné**: osvědčení FO → vydává **výlučně Úřad** (s výjimkami pro zpravodajské služby a MV),
   - **Podnikatel**: prohlášení (Vyhrazené) nebo osvědčení podnikatele (vše vyšší),
   - **Cizí moc**: dodatečné osvědčení pro cizí moc (§ 57).

6. **Ústavní výjimky** (§ 58) zajišťují přístup ústavních činitelů, soudců a kontrolních orgánů bez prověrky — princip dělby moci. Procesní výjimky pro účastníky řízení vyvažují ochranu UI s právem na obhajobu a spravedlivý proces (Listina, EÚLP).

7. **Princip need-to-know** prochází napříč zákonem — jakékoli oprávnění samo o sobě nestačí; vyžaduje se aktuální věcný důvod.

8. **Periodicita revizí** — oznámení 5 let (§ 9 odst. 2), osvědčení 5/10 let (§ 55), prověření trvání důvodů utajení 5 let (§ 22 odst. 5), certifikace IS 3/5 let (§ 48), kryptoprostředek 5 let (§ 49), kryptopracoviště 3 roky (§ 50), stínicí komora 5 let (§ 51).

9. **Trvalost mlčenlivosti** (§ 11a) — povinnost mlčenlivosti přesahuje skončení vztahu, jenž byl důvodem přístupu.

10. **Mezinárodněprávní rozměr** — celý systém je harmonizován s NATO a EU; pro UI cizí moci se uplatní zvláštní pravidla (§ 21 odst. 2 a 11, § 23 odst. 4, § 43a, § 57, § 58 odst. 6, § 59 odst. 7).

Druhá polovina Části druhé (§§ 60 a násl. — speciální subjekty, evidence, povinnosti a postavení Úřadu) a celá Část třetí (bezpečnostní způsobilost a citlivé činnosti), Část čtvrtá (bezpečnostní řízení), Část pátá (přestupky a delikty) a další jsou předmětem následujících kapitol komentáře.

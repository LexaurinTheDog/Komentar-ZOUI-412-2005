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

#### F. Kazuistika

**1. Modelová situace.** Spolek pro ochranu krajiny podá podle zákona č. 106/1999 Sb. žádost ministerstvu obrany o poskytnutí podkladové studie k umístění radarového stanoviště. Ministerstvo žádost zamítne s odkazem na to, že jde o utajovanou informaci stupně Důvěrné, vyloučenou z působnosti InfZ. Spolek brojí žalobou ke správnímu soudu; tvrdí, že předmět úpravy ZOÚI nemůže zcela vyloučit ústavně garantované právo na informace a že studie obsahuje i běžné environmentální údaje. Účastníci: spolek (žadatel/žalobce), ministerstvo obrany jako povinný subjekt a původce. Důkazy: spisová dokumentace o klasifikaci, doklad o podřaditelnosti pod katalog § 139, případně oddělitelné neutajované části studie.

**2. Právní otázka.** Lze celý dokument vyjmout z působnosti InfZ jen proto, že ZOÚI upravuje „další požadavky na ochranu" utajovaných informací, nebo musí povinný subjekt zkoumat dělitelnost a poskytnout neutajované části?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 1 ZOÚI — vymezuje předmět úpravy (zásady klasifikace, podmínky přístupu, ochrana), čímž zakládá ZOÚI jako lex specialis.
- *Související ustanovení téhož zákona:* § 2 písm. a) (definiční znaky utajované informace), § 4 (stupně utajení), § 139 (katalog oblastí UI) — bez podřaditelnosti pod katalog o utajovanou informaci nejde.
- *Související předpisy:* § 7 a § 12 zákona č. 106/1999 Sb. (vyloučení utajovaných informací a princip oddělitelnosti), čl. 17 odst. 4 Listiny (mez práva na informace).
- *Judikatura:* nález ÚS sp. zn. Pl. ÚS 11/2000 (utajování jako ústavně přípustný zásah ovládaný proporcionalitou a soudním přezkumem); ustálená judikatura NSS k povinnosti poskytnout oddělitelné neutajované části dokumentu.

**4. Subsumpce.** Předmět úpravy ZOÚI (§ 1) sice zakládá zvláštní ochranný režim, avšak nepůsobí jako paušální blanketní výjimka: aplikuje se jen na informace, jež jsou utajovanými ve smyslu § 2 písm. a) a § 4. Pokud studie obsahuje oddělitelné údaje bez klasifikace, na ně se režim ZOÚI nevztahuje a platí InfZ. Sporné je, zda je dokument fakticky dělitelný bez ohrožení utajované části.

**5. Řešení.** Povinný subjekt nemůže odmítnout celou žádost jen odkazem na předmět úpravy ZOÚI; musí zkoumat, zda jednotlivé části naplňují znaky utajované informace, a neutajované oddělitelné části poskytnout. Pravděpodobný výsledek: částečné zrušení rozhodnutí pro nepřezkoumatelnost, vrácení k posouzení dělitelnosti. Procesní krok: vyžádat klasifikační doklad a katalogovou položku. Riziko: pokud je celý dokument provázán tak, že oddělení by odhalilo utajovaný celek (agregační únik — srov. § 4 odst. 2), odmítnutí obstojí.

**6. Varianty.** (a) Studie by nebyla nikým označena stupněm utajení — pak o utajovanou informaci nejde a InfZ se uplatní plně. (b) Šlo by o jaderné stanoviště spadající pod citlivou činnost (§ 80 a násl.) — pak nastupuje druhá osa působnosti § 1 a režim bezpečnostní způsobilosti, nikoli pouze utajení informace.

#### G. Protiargumenty a rizika

- *Protiargument 1:* „ZOÚI jako lex specialis zcela vylučuje InfZ." Neutralizace: lex specialis vylučuje obecný předpis jen v rozsahu, v němž věc skutečně reguluje — tj. jen u informací, jež jsou utajovanými; mimo to platí InfZ a princip oddělitelnosti (§ 12 InfZ).
- *Protiargument 2:* „Předmět úpravy je natolik široký, že pokrývá i citlivé činnosti, takže žádost spadá pod § 80 a násl." Neutralizace: dvojí osa § 1 je oddělená; konkrétní studie je informací, nikoli výkonem citlivé činnosti — rozhodný je obsah a klasifikace, ne abstraktní šíře předmětu úpravy.
- *Slabé místo:* § 1 je čistě deklaratorní (programové) ustanovení; sám o sobě nezakládá práva ani povinnosti, ty plynou z navazujících ustanovení. Argumentace opřená jen o § 1 je bez vazby na § 2, § 4, § 139 nedostatečná.

#### H. Praktický závěr

Ustanovení § 1 slouží jako interpretační rámec a klíč k systematice celého zákona; v praxi se nikdy neaplikuje samostatně, nýbrž vždy ve spojení s definičními a klasifikačními ustanoveními. Při kolizi s právem na informace je nutné vždy provést test dělitelnosti, nikoli paušálně odmítat.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Jde o informaci, nebo o citlivou činnost (která osa § 1)?
- [ ] Je informace skutečně klasifikována stupněm utajení (§ 4) a podřaditelná pod katalog (§ 139)?
- [ ] Lze dokument rozdělit a poskytnout neutajované části (§ 12 InfZ)?
- [ ] Je zásah do práva na informace proporční (čl. 17 odst. 4 Listiny)?
- [ ] Který orgán je gestorem (Úřad / NÚKIB / ZS / MV / MO)?

**Typicky rozhodné důkazy / podklady:** klasifikační doklad původce, doložení katalogové položky § 139, posouzení dělitelnosti dokumentu, případně stanovisko příslušného gestora.

---


<!-- LEGAL-REVISION:BEGIN id=c0f5b8804a4a7f847a9e generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 1 — Předmět úpravy

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> Tento zákon upravuje zásady pro stanovení informací jako informací utajovaných, podmínky pro přístup k nim a další požadavky na jejich ochranu, zásady pro stanovení citlivých činností a podmínky pro jejich výkon a s tím spojený výkon státní správy.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Místní znění neobsahuje výslovný vnitřní odkaz.

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=c0f5b8804a4a7f847a9e -->

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
> *- d) orgánem státu organizační složka státu podle zvláštního právního předpisu1), kraj2), hlavní město Praha3), městská část hlavního města Prahy a obec4) při výkonu státní správy ve věcech, které stanoví zvláštní právní předpis; orgánem státu se rozumí i zpravodajské služby56) a Česká národní banka7),*
>
> *- e) odpovědnou osobou*
>
> *- 1. u ministerstva ministr,*
>
> *- 2. u jiného ústředního správního úřadu ten, kdo stojí v jeho čele; jde-li o kolektivní orgán, je odpovědnou osobou pouze ta fyzická osoba, která řídí činnost tohoto orgánu,*
>
> *- 3. u organizační složky státu, zřízené jinou organizační složkou státu, ten, kdo je odpovědnou osobou u organizační složky státu vykonávající funkci jejího zřizovatele,*
>
> *- 4. u dalších organizačních složek státu ten, kdo stojí v jejich čele,*
>
> *- 5. u zpravodajské služby ředitel,*
>
> *- 6. u České národní banky guvernér,*
>
> *- 7. u kraje ředitel krajského úřadu,*
>
> *- 8. u hlavního města Prahy ředitel Magistrátu hlavního města Prahy,*
>
> *- 9. u městské části hlavního města Prahy tajemník úřadu městské části, a není-li jej, starosta městské části,*
>
> *- 10. u statutárního města tajemník magistrátu,*
>
> *- 11. u dalších měst a obcí tajemník jejich úřadu, a není-li jej, starosta,*
>
> *- 12. u organizační složky územního samosprávného celku ten, kdo je odpovědnou osobou u územního samosprávného celku vykonávajícího funkci jejího zřizovatele,*
>
> *- 13. u podnikatele podle § 15, který je právnickou osobou, a u jiné právnické osoby neuvedené v bodech 6 až 11 fyzická osoba, která je jejím individuálním statutárním orgánem, nebo v případě, že má právnická osoba více individuálních statutárních orgánů nebo je statutární orgán této právnické osoby kolektivní, člen statutárního orgánu, který je fyzickou osobou a je určen pro jednání ve věcech upravených tímto zákonem,*
>
> *- 14. u podnikatele podle § 15, který je fyzickou osobou, a u jiné podnikající fyzické osoby tato fyzická osoba,*
>
> *- 15. u Poslanecké sněmovny vedoucí Kanceláře Poslanecké sněmovny, a*
>
> *- 16. u Senátu vedoucí Kanceláře Senátu,*
>
> *- f) původcem utajované informace orgán státu, právnická osoba podle § 60b nebo podnikatel, u nichž utajovaná informace vznikla, nebo Úřad průmyslového vlastnictví podle § 70 odst. 4,*
>
> *- g) cizí mocí cizí stát nebo jeho orgán anebo nadnárodní nebo mezinárodní organizace nebo její orgán,*
>
> *- h) neoprávněnou osobou osoba, která nesplňuje podmínky přístupu k utajované informaci stanovené tímto zákonem,*
>
> *- i) poučením písemný záznam o seznámení fyzické osoby s jejími právy a povinnostmi v oblasti ochrany utajovaných informací a s následky jejich porušení,*
>
> *- j) bezpečnostním standardem utajovaný soubor pravidel, ve kterém se stanoví postupy, technická řešení, bezpečnostní parametry a organizační opatření pro zajištění nejmenší možné míry ochrany utajovaných informací,*
>
> *- k) bezpečnostním provozním módem prostředí, ve kterém informační systém pracuje, charakterizované stupněm utajení zpracovávané utajované informace a úrovněmi oprávnění uživatelů.*

**Výklad:**

**Judikatura (z místních zdrojů):**

- *NSS* [10 As 91/2023 - 39](https://vyhledavac.nssoud.cz/DokumentOriginal/Text/716109) — 13. 11. 2023
  > „Městský soud dospěl k závěru, že informaci nelze poskytnout pouze na základě toho, že je označena za utajovanou, ale je nutné se zabývat všemi znaky utajované informace ve smyslu § 2 písm. a) zákona č. 412/2005 Sb., o ochraně utajovaných informací a o bezpečnostní způsobilosti … Dospěl k závěru, že správní orgány srozumitelně nevysvětlily, proč obsah usnesení, resp. v nich obsažené označení podkladových „utajených“ materiálů … naplňuje jednotlivé znaky legální definice utajované informace"

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

#### F. Kazuistika

**1. Modelová situace.** Krajský úřad při výkonu přenesené působnosti v oblasti krizového řízení zpracuje materiál, který označí stupněm Vyhrazené. Krajské zastupitelstvo poté při výkonu samostatné působnosti požaduje materiál vidět. Současně vyvstává otázka, kdo je za ochranu odpovědný — ředitel krajského úřadu, nebo hejtman. Účastníci: kraj (orgán státu při přenesené působnosti vs. samosprávný subjekt při samostatné), ředitel krajského úřadu (kandidát na odpovědnou osobu), hejtman. Důkazy: vymezení, zda materiál vznikl při výkonu státní správy; doklad o jeho podřaditelnosti pod katalog § 139; organizační řád úřadu.

**2. Právní otázka.** Je kraj v dané věci „orgánem státu" podle § 2 písm. d) a kdo je „odpovědnou osobou" podle § 2 písm. e) bodu 7 — a může se s materiálem seznámit zastupitel jednající v samostatné působnosti?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 2 písm. a) (třísložkový test utajované informace), písm. d) (orgán státu jen při výkonu státní správy), písm. e) bod 7 (odpovědná osoba u kraje = ředitel krajského úřadu).
- *Související ustanovení téhož zákona:* § 4 (označení stupněm), § 6 odst. 1 (need-to-know), § 139 (katalog), § 71 (bezpečnostní ředitel).
- *Související předpisy:* zákon č. 129/2000 Sb., o krajích (dělba samostatné a přenesené působnosti); zákon č. 240/2000 Sb. (krizový zákon).
- *Judikatura:* rozsudek NSS sp. zn. 10 As 91/2023 — informaci nelze utajit pouze proto, že je takto označena; je nutné zkoumat naplnění všech znaků legální definice utajované informace dle § 2 písm. a).

**4. Subsumpce.** Materiál vznikl při výkonu státní správy (krizové řízení) → kraj je orgánem státu (písm. d). Odpovědnou osobou je ředitel krajského úřadu (písm. e bod 7), nikoli hejtman. Aby šlo o utajovanou informaci, musí kumulativně být splněn třísložkový test písm. a): formální označení, materiální způsobilost přivodit újmu/nevýhodnost, podřaditelnost pod katalog. Zastupitel v samostatné působnosti zpravidla need-to-know nesplňuje, nemá-li věcný důvod a oprávnění.

**5. Řešení.** Přístup zastupitele nelze připustit jen z titulu mandátu; chybí need-to-know a oprávnění (oznámení/osvědčení). Odpovědnou osobou je ředitel krajského úřadu, který odpovídá za ochranu, popř. deleguje na bezpečnostního ředitele (§ 71). Pravděpodobný výsledek: žádost zastupitele se odmítne. Riziko: pokud by se materiál týkal samostatné působnosti a nebyl řádně podřaditelný pod katalog, jeho klasifikace by neobstála (viz NSS 10 As 91/2023).

**6. Varianty.** (a) Materiál vznikl při výkonu samostatné působnosti → kraj není orgánem státu podle písm. d) a klasifikace dle ZOÚI je vyloučena (ochrana jen jako jiná chráněná informace). (b) Subjektem by byl podnikatel — PO s více statutáry → odpovědnou osobou je člen statutárního orgánu určený pro věci ZOÚI (písm. e bod 13).

#### G. Protiargumenty a rizika

- *Protiargument 1:* „Označení stupněm utajení samo zakládá utajovanou informaci." Neutralizace: definice písm. a) je trojkonjunktivní; chybí-li materiální způsobilost nebo katalogová podřaditelnost, jde o vadné označení, jež soud zruší (NSS 10 As 91/2023).
- *Protiargument 2:* „Zastupitel má právo na informace ze své funkce." Neutralizace: oprávnění z mandátu (zákon o krajích) neprolamuje need-to-know ani požadavek oprávnění podle ZOÚI; jde o lex specialis pro utajované informace.
- *Slabé místo:* hranice mezi samostatnou a přenesenou působností bývá v praxi neostrá; je nutné doložit, při výkonu jaké působnosti materiál vznikl — bez toho je určení orgánu státu i odpovědné osoby sporné.

#### H. Praktický závěr

§ 2 je definiční páteří zákona; jeho pojmy (zejm. utajovaná informace, zájem ČR, orgán státu, odpovědná osoba) se uplatní napříč celým předpisem. V praxi je klíčové netříštit definici utajované informace — všechny tři znaky písm. a) musí být splněny současně a jejich naplnění musí být přezkoumatelně odůvodněno.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Splňuje informace všechny tři znaky § 2 písm. a) (označení + způsobilost újmy + katalog)?
- [ ] Spadá ohrožený zájem do uzavřeného výčtu šesti hodnot písm. b)?
- [ ] Jedná subjekt jako orgán státu (jen při výkonu státní správy — písm. d)?
- [ ] Je správně identifikována odpovědná osoba podle příslušného bodu písm. e)?
- [ ] Je naplnění definice odůvodněno konkrétně, ne paušálně?

**Typicky rozhodné důkazy / podklady:** klasifikační doklad, doklad o podřaditelnosti pod katalog § 139, organizační řád subjektu (určení odpovědné osoby), doklad o tom, při výkonu jaké působnosti informace vznikla.

---


<!-- LEGAL-REVISION:BEGIN id=0d2bc673ee3d6e3498a0 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 2 — Vymezení pojmů

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> Pro účely tohoto zákona se rozumí
>
> - a) utajovanou informací informace v jakékoliv podobě označená stupněm utajení podle tohoto zákona, jejíž vyzrazení nebo zneužití může způsobit újmu zájmu České republiky nebo může být pro tento zájem nevýhodné, a kterou lze podřadit pod položku uvedenou v katalogu oblastí utajovaných informací ([[#§ 139|§ 139]]),
>
> - b) zájmem České republiky zachování její ústavnosti, svrchovanosti a územní celistvosti, zajištění vnitřního pořádku a bezpečnosti, mezinárodních závazků a obrany, ochrana ekonomiky a ochrana života nebo zdraví fyzických osob,
>
> - c) porušením povinnosti při ochraně utajované informace porušení povinnosti uložené tímto zákonem nebo na základě tohoto zákona,
>
> - d) orgánem státu organizační složka státu podle zvláštního právního předpisu1), kraj2), hlavní město Praha3), městská část hlavního města Prahy a obec4) při výkonu státní správy ve věcech, které stanoví zvláštní právní předpis; orgánem státu se rozumí i zpravodajské služby56) a Česká národní banka7),
>
> - e) odpovědnou osobou
>
> - 1. u ministerstva ministr,
>
> - 2. u jiného ústředního správního úřadu ten, kdo stojí v jeho čele; jde-li o kolektivní orgán, je odpovědnou osobou pouze ta fyzická osoba, která řídí činnost tohoto orgánu,
>
> - 3. u organizační složky státu, zřízené jinou organizační složkou státu, ten, kdo je odpovědnou osobou u organizační složky státu vykonávající funkci jejího zřizovatele,
>
> - 4. u dalších organizačních složek státu ten, kdo stojí v jejich čele,
>
> - 5. u zpravodajské služby ředitel,
>
> - 6. u České národní banky guvernér,
>
> - 7. u kraje ředitel krajského úřadu,
>
> - 8. u hlavního města Prahy ředitel Magistrátu hlavního města Prahy,
>
> - 9. u městské části hlavního města Prahy tajemník úřadu městské části, a není-li jej, starosta městské části,
>
> - 10. u statutárního města tajemník magistrátu,
>
> - 11. u dalších měst a obcí tajemník jejich úřadu, a není-li jej, starosta,
>
> - 12. u organizační složky územního samosprávného celku ten, kdo je odpovědnou osobou u územního samosprávného celku vykonávajícího funkci jejího zřizovatele,
>
> - 13. u podnikatele podle [[#§ 15|§ 15]], který je právnickou osobou, a u jiné právnické osoby neuvedené v bodech 6 až 11 fyzická osoba, která je jejím individuálním statutárním orgánem, nebo v případě, že má právnická osoba více individuálních statutárních orgánů nebo je statutární orgán této právnické osoby kolektivní, člen statutárního orgánu, který je fyzickou osobou a je určen pro jednání ve věcech upravených tímto zákonem,
>
> - 14. u podnikatele podle [[#§ 15|§ 15]], který je fyzickou osobou, a u jiné podnikající fyzické osoby tato fyzická osoba,
>
> - 15. u Poslanecké sněmovny vedoucí Kanceláře Poslanecké sněmovny, a
>
> - 16. u Senátu vedoucí Kanceláře Senátu,
>
> - f) původcem utajované informace orgán státu, právnická osoba podle [[#§ 60b|§ 60b]] nebo podnikatel, u nichž utajovaná informace vznikla, nebo Úřad průmyslového vlastnictví podle § 70 odst. 4,
>
> - g) cizí mocí cizí stát nebo jeho orgán anebo nadnárodní nebo mezinárodní organizace nebo její orgán,
>
> - h) neoprávněnou osobou osoba, která nesplňuje podmínky přístupu k utajované informaci stanovené tímto zákonem,
>
> - i) poučením písemný záznam o seznámení fyzické osoby s jejími právy a povinnostmi v oblasti ochrany utajovaných informací a s následky jejich porušení,
>
> - j) bezpečnostním standardem utajovaný soubor pravidel, ve kterém se stanoví postupy, technická řešení, bezpečnostní parametry a organizační opatření pro zajištění nejmenší možné míry ochrany utajovaných informací,
>
> - k) bezpečnostním provozním módem prostředí, ve kterém informační systém pracuje, charakterizované stupněm utajení zpracovávané utajované informace a úrovněmi oprávnění uživatelů.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 139, § 15, § 60b, § 70

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=0d2bc673ee3d6e3498a0 -->

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

#### F. Kazuistika

**1. Modelová situace.** Zpravodajská služba zpracuje analýzu o plánované operaci. Původce zvažuje, zda hrozící následek vyzrazení (odhalení metody práce a ohrožení jednoho zdroje) zakládá „mimořádně vážnou újmu" (→ Přísně tajné), „vážnou újmu" (→ Tajné), nebo „prostou újmu" (→ Důvěrné). Účastníci: původce informace (zpravodajská služba), adresát klasifikace (kontrolní orgán, soud při pozdějším přezkumu). Důkazy: popis konkrétního chráněného zájmu (§ 2 písm. b), odhad intenzity a rozsahu následku, doklad o jedinečnosti zdroje.

**2. Právní otázka.** Podle jakého kritéria se na klouzavé škále § 3 určí, zda jde o mimořádně vážnou, vážnou, nebo prostou újmu — a je toto určení přezkoumatelné?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 3 — trojstupňová škála újmy (odst. 2–4) plus kategorie nevýhodnosti (odst. 5); pojmy poškození a ohrožení (odst. 1).
- *Související ustanovení téhož zákona:* § 4 odst. 1 (navázání stupňů utajení na stupně újmy), § 4 odst. 2 (pravidlo nejvyššího stupně při agregaci), § 22 odst. 4, 5 (revize a periodická prověrka), § 2 písm. b) (zájem ČR).
- *Související předpisy:* § 14 odst. 3 TZ (zvlášť závažný zločin — distinkce prostá újma vs. nevýhodnost u vyšetřování), nařízení vlády č. 522/2005 Sb. (katalog).
- *Judikatura:* judikatura NSS k přezkoumatelnosti klasifikace (utajení musí být odůvodněné a opřené o konkrétní zjištění, nestačí paušální odkaz na bezpečnostní riziko/újmu).

**4. Subsumpce.** Následek = ohrožení (reálné nebezpečí), nikoli již realizované poškození → naplněn odst. 1. Intenzita: ohrožení jediné metody a jednoho zdroje typicky odpovídá „vážnému ohrožení zpravodajské operace" (odst. 3) → Tajné; „mimořádně vážné" (odst. 2) by vyžadovalo ohrožení operace zásadního významu nebo rozsáhlejší dopad. Sporné je posouzení významu zdroje, jež je interpretačně otevřené.

**5. Řešení.** Původce klasifikuje stupněm odpovídajícím nejpravděpodobnější intenzitě následku; volba musí být odůvodnitelná a doložitelná pro pozdější přezkum (§ 22 odst. 9, soud). Při pochybnosti mezi dvěma stupni je namístě volit nižší přiměřený stupeň (zásada proporcionality klasifikace — § 22 odst. 4). Riziko nadklasifikace: zbytečné náklady ochrany a riziko zrušení stupně při prověrce; riziko podklasifikace: nedostatečná ochrana a odpovědnost za porušení.

**6. Varianty.** (a) Analýza by ohrožovala pouze vyšetřování běžného (nikoli zvlášť závažného) trestného činu → nejde o újmu, nýbrž o nevýhodnost (odst. 5) → Vyhrazené. (b) Analýza by spojovala více dílčích informací, jejichž souhrn ohrožuje celou síť zdrojů → uplatní se § 4 odst. 2 a stupeň se zvýší (agregační efekt).

#### G. Protiargumenty a rizika

- *Protiargument 1:* „Intenzita újmy je natolik neurčitá, že klasifikace je nepřezkoumatelná." Neutralizace: klouzavá škála je interpretačně otevřená, avšak kvalifikátory (mimořádně vážný/vážný/prostý) a typové katalogy odst. 2–5 poskytují měřítka; soud přezkoumá odůvodněnost a proporcionalitu, nikoli vhodnost.
- *Protiargument 2:* „Postačí potenciální způsobilost újmy, takže lze utajit cokoli." Neutralizace: modalita „může" se váže na konkrétní chráněný zájem z uzavřeného výčtu § 2 písm. b) a na podřaditelnost pod katalog; abstraktní možnost újmy bez vazby na tyto prvky nestačí.
- *Slabé místo:* hranice mezi sousedními stupni (zejm. Tajné/Přísně tajné) je v praxi obtížně doložitelná; chybí-li doklad o intenzitě a rozsahu následku, klasifikace neobstojí.

#### H. Praktický závěr

§ 3 je materiálním kritériem klasifikace — určuje „jak vážná" újma hrozí, a tím i stupeň utajení podle § 4. V praxi je nutné ke každé klasifikaci připojit odůvodnění intenzity následku a jeho vazby na konkrétní chráněný zájem; jen tak obstojí při periodické prověrce i soudním přezkumu.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Jde o poškození (realizovaný následek), nebo ohrožení (nebezpečí následku)?
- [ ] Který konkrétní zájem ČR (§ 2 písm. b) je dotčen?
- [ ] Odpovídá intenzita následku kvalifikátoru zvoleného stupně (mimořádně vážná/vážná/prostá újma)?
- [ ] Nejde o pouhou nevýhodnost (odst. 5 → Vyhrazené)?
- [ ] Není namístě zvýšení stupně agregací (§ 4 odst. 2)?

**Typicky rozhodné důkazy / podklady:** odůvodnění klasifikace s popisem následku, doklad o významu a jedinečnosti dotčeného zájmu/zdroje, katalogová položka § 139, podklady k periodické prověrce (§ 22 odst. 5).

---


<!-- LEGAL-REVISION:BEGIN id=377cf40a164330fa7d1f generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 3 — Újma zájmu České republiky a nevýhodnost pro zájmy České republiky

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Újmou zájmu České republiky se pro účely tohoto zákona rozumí poškození nebo ohrožení zájmu České republiky. Podle závažnosti poškození nebo ohrožení zájmu České republiky se újma člení na mimořádně vážnou újmu, vážnou újmu a prostou újmu.
>
> (2) Mimořádně vážná újma zájmu České republiky vznikne vyzrazením utajované informace neoprávněné osobě nebo zneužitím utajované informace, které může mít za následek
>
> - a) bezprostřední ohrožení svrchovanosti, územní celistvosti nebo demokratických základů České republiky,
>
> - b) rozsáhlé ztráty na lidských životech nebo rozsáhlé ohrožení zdraví obyvatel,
>
> - c) mimořádně vážné nebo dlouhodobé poškození ekonomiky České republiky,
>
> - d) značné narušení vnitřního pořádku a bezpečnosti České republiky,
>
> - e) mimořádně vážné ohrožení významných bezpečnostních operací nebo činnosti zpravodajských služeb,
>
> - f) mimořádně vážné ohrožení činnosti Organizace Severoatlantické smlouvy, Evropské unie nebo členského státu,
>
> - g) mimořádně vážné ohrožení bojeschopnosti ozbrojených sil České republiky, Organizace Severoatlantické smlouvy nebo jejího členského státu nebo členského státu Evropské unie, nebo
>
> - h) mimořádně vážné poškození diplomatických nebo jiných vztahů České republiky k Organizaci Severoatlantické smlouvy, Evropské unii nebo členskému státu.
>
> (3) Vážná újma zájmu České republiky vznikne vyzrazením utajované informace neoprávněné osobě nebo zneužitím utajované informace, které může mít za následek
>
> - a) ohrožení svrchovanosti, územní celistvosti a demokratických základů České republiky,
>
> - b) značnou škodu České republiky ve finanční, měnové nebo hospodářské oblasti,
>
> - c) ztráty na lidských životech nebo ohrožení zdraví obyvatel,
>
> - d) narušení vnitřního pořádku a bezpečnosti České republiky,
>
> - e) vážné ohrožení bojeschopnosti ozbrojených sil České republiky, Organizace Severoatlantické smlouvy nebo jejího členského státu nebo členského státu Evropské unie,
>
> - f) vážné ohrožení významných bezpečnostních operací nebo činnosti zpravodajských služeb,
>
> - g) vážné ohrožení činnosti Organizace Severoatlantické smlouvy, Evropské unie nebo členského státu,
>
> - h) vážné narušení diplomatických vztahů České republiky k Organizaci Severoatlantické smlouvy, Evropské unii nebo členskému státu nebo jinému státu, nebo
>
> - i) vážné zvýšení mezinárodního napětí.
>
> (4) Prostá újma zájmu České republiky vznikne vyzrazením utajované informace neoprávněné osobě nebo zneužitím utajované informace, které může mít za následek
>
> - a) zhoršení vztahů České republiky s cizí mocí,
>
> - b) ohrožení bezpečnosti jednotlivce,
>
> - c) ohrožení bojeschopnosti ozbrojených sil České republiky, Organizace Severoatlantické smlouvy nebo jejího členského státu nebo členského státu Evropské unie,
>
> - d) ohrožení bezpečnostních operací nebo činnosti zpravodajských služeb,
>
> - e) ohrožení činnosti Organizace Severoatlantické smlouvy, Evropské unie nebo jejich členského státu,
>
> - f) zmaření, ztížení anebo ohrožení prověřování nebo vyšetřování zvlášť závažných zločinů10) nebo usnadnění jejich páchání,
>
> - g) vznik nezanedbatelné škody České republice, nebo
>
> - h) závažné narušení ekonomických zájmů České republiky.
>
> (5) Nevýhodné pro zájmy České republiky je vyzrazení utajované informace neoprávněné osobě nebo zneužití utajované informace, které může mít za následek
>
> - a) narušení činnosti ozbrojených sil České republiky, Organizace Severoatlantické smlouvy nebo jejího členského státu nebo členského státu Evropské unie,
>
> - b) zmaření, ztížení anebo ohrožení prověřování nebo vyšetřování ostatních trestných činů než uvedených v odstavci 4 písm. f) nebo usnadnění jejich páchání,
>
> - c) poškození významných ekonomických zájmů České republiky nebo Evropské unie nebo jejího členského státu,
>
> - d) narušení důležitých obchodních nebo politických jednání České republiky s cizí mocí, nebo
>
> - e) narušení bezpečnostních operací nebo činnosti zpravodajských služeb.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Místní znění neobsahuje výslovný vnitřní odkaz.

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=377cf40a164330fa7d1f -->

### § 4 — Stupně utajení

> **§ 4**
>
> *(1) Informaci, jejíž vyzrazení nebo zneužití může způsobit újmu zájmu České republiky nebo může být pro tento zájem nevýhodné a kterou lze podřadit pod položku uvedenou v katalogu oblastí utajovaných informací, klasifikuje a označí původce stupněm utajení*
>
> *- a) Přísně tajné, jestliže její vyzrazení neoprávněné osobě nebo zneužití může způsobit mimořádně vážnou újmu zájmu České republiky,*
>
> *- b) Tajné, jestliže její vyzrazení neoprávněné osobě nebo zneužití může způsobit vážnou újmu zájmu České republiky,*
>
> *- c) Důvěrné, jestliže její vyzrazení neoprávněné osobě nebo zneužití může způsobit prostou újmu zájmu České republiky, nebo*
>
> *- d) Vyhrazené, jestliže její vyzrazení neoprávněné osobě nebo zneužití může být nevýhodné pro zájem České republiky.*
>
> *(2) Pokud je utajovaná informace tvořena dílčími utajovanými informacemi různého stupně utajení, klasifikuje se a označí se stupněm utajení podle nejvyššího stupně utajení dílčí utajované informace nebo vyšším.*
>
> *(3) Utajovaná informace se při ústním, obrazovém nebo zvukovém zpřístupnění označí ústním prohlášením nebo jiným vhodným způsobem, kterým se dá na vědomí, že jde o utajovanou informaci příslušného stupně utajení.*
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

#### F. Kazuistika

**1. Modelová situace.** Ministerstvo připraví prezentaci pro mezirezortní jednání. Tři snímky obsahují informace stupně Důvěrné, zbytek je neutajovaný. Prezentující na úvod ústně prohlásí, že jednání je „důvěrné", ale prezentaci nikde graficky neoznačí; soubor následně rozešle účastníkům e-mailem bez elektronického labelu. Jeden účastník informaci přepošle dál. Účastníci: původce (ministerstvo), prezentující, příjemci. Důkazy: zápis z jednání, znění úvodního ústního prohlášení, e-mailová hlavička bez značení, obsah dotčených snímků.

**2. Právní otázka.** Byla informace platně klasifikována a označena podle § 4 odst. 3–5, a jakým stupněm měla být označena celá prezentace podle § 4 odst. 2?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 4 odst. 1 (konstitutivní klasifikace původcem podle stupně újmy), odst. 2 (nejvyšší stupeň při agregaci), odst. 3 (ústní/obrazové/zvukové zpřístupnění), odst. 4 (analogová podoba), odst. 5 (elektronická podoba).
- *Související ustanovení téhož zákona:* § 2 písm. a) (definice), § 3 (stupně újmy), § 22 (změna a revize stupně), § 21 (manipulace, evidence).
- *Související předpisy:* vyhláška č. 529/2005 Sb. o administrativní bezpečnosti (grafické značení); rozhodnutí Rady 2013/488/EU (převody EU); § 23 odst. 4 ZOÚI (převodní tabulky NATO/EU).
- *Judikatura:* nález ÚS Pl. ÚS 11/2000 (přípustnost utajení); judikatura NSS k nutnosti formálního označení jakožto znaku utajované informace.

**4. Subsumpce.** Pro elektronický soubor platí odst. 5 — měl být elektronicky označen; nebylo-li to možné, mělo nastoupit ústní označení podle odst. 3. Úvodní ústní prohlášení „důvěrné jednání" může naplnit odst. 3 jako „jiný vhodný způsob", ale rozeslání souboru bez značení je porušením povinnosti označení. Podle odst. 2 měla být celá prezentace (obsahující dílčí informaci Důvěrné) označena nejvýše stupněm Důvěrné.

**5. Řešení.** Klasifikace materiálně existuje (původce informaci určil jako Důvěrné), ale označení bylo provedeno vadně (chybí značení souboru). To zakládá porušení povinnosti při ochraně UI (§ 2 písm. c) na straně původce/prezentujícího a může vést ke správní odpovědnosti (§ 148 a násl.). Přeposlání neoprávněnou osobou samostatně zakládá odpovědnost příjemce, byl-li si vědom úvodního prohlášení. Procesní kroky: dodatečné řádné označení (§ 22), poučení účastníků, prošetření úniku.

**6. Varianty.** (a) Informace by byla COSMIC TOP SECRET dle NATO → v ČR se automaticky chrání jako Přísně tajné (převodní tabulky, § 23 odst. 4). (b) Šlo by o EU LIMITE → nejde o utajovanou informaci ve smyslu ZOÚI a režim § 4 se neuplatní.

#### G. Protiargumenty a rizika

- *Protiargument 1:* „Úvodní ústní prohlášení nahradilo označení i pro rozeslaný soubor." Neutralizace: odst. 3 dopadá na ústní/obrazové/zvukové zpřístupnění; pro elektronický soubor platí odst. 5 a značení musí být u souboru samotného, jinak ztrácí příjemce možnost rozpoznat stupeň.
- *Protiargument 2:* „Neoznačený soubor není utajovanou informací, takže žádné porušení nenastalo." Neutralizace: materiální klasifikace původcem existovala; vadné provedení označení nezbavuje původce povinnosti, naopak ji porušuje — a u příjemce vědomého ústního prohlášení vzniká povinnost mlčenlivosti.
- *Slabé místo:* dokazování obsahu úvodního ústního prohlášení (zda a jak byl stupeň sdělen) je obtížné bez zápisu; bez něj je sporné, zda byl naplněn odst. 3.

#### H. Praktický závěr

§ 4 spojuje materiální kritérium (§ 3) s formálním označením a stanoví pravidla značení ve všech formách. V praxi je rozhodující důsledné a formě odpovídající označení (graficky u analogu, elektronicky u souborů, ústně u jednání) a respektování pravidla nejvyššího stupně u smíšených dokumentů.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Odpovídá zvolený stupeň stupni hrozící újmy podle § 3?
- [ ] Je informace označena způsobem odpovídajícím její formě (odst. 3–5)?
- [ ] Je smíšený dokument označen nejvyšším stupněm dílčí informace (odst. 2)?
- [ ] U cizí klasifikace: byla použita správná převodní tabulka (§ 23 odst. 4)?
- [ ] Je vyznačena doba utajení / proběhla periodická prověrka (§ 22)?

**Typicky rozhodné důkazy / podklady:** označený dokument/soubor, zápis o ústním označení, klasifikační doklad původce, převodní tabulky NATO/EU, doklad o periodické revizi stupně.

---


<!-- LEGAL-REVISION:BEGIN id=f4f6a88fa4456e6e02c1 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 4 — Stupně utajení

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Informaci, jejíž vyzrazení nebo zneužití může způsobit újmu zájmu České republiky nebo může být pro tento zájem nevýhodné a kterou lze podřadit pod položku uvedenou v katalogu oblastí utajovaných informací, klasifikuje a označí původce stupněm utajení
>
> - a) Přísně tajné, jestliže její vyzrazení neoprávněné osobě nebo zneužití může způsobit mimořádně vážnou újmu zájmu České republiky,
>
> - b) Tajné, jestliže její vyzrazení neoprávněné osobě nebo zneužití může způsobit vážnou újmu zájmu České republiky,
>
> - c) Důvěrné, jestliže její vyzrazení neoprávněné osobě nebo zneužití může způsobit prostou újmu zájmu České republiky, nebo
>
> - d) Vyhrazené, jestliže její vyzrazení neoprávněné osobě nebo zneužití může být nevýhodné pro zájem České republiky.
>
> (2) Pokud je utajovaná informace tvořena dílčími utajovanými informacemi různého stupně utajení, klasifikuje se a označí se stupněm utajení podle nejvyššího stupně utajení dílčí utajované informace nebo vyšším.
>
> (3) Utajovaná informace se při ústním, obrazovém nebo zvukovém zpřístupnění označí ústním prohlášením nebo jiným vhodným způsobem, kterým se dá na vědomí, že jde o utajovanou informaci příslušného stupně utajení.
>
> (4) Utajovaná informace v analogové podobě se označí tak, že se na ní vyznačí stupeň utajení.
>
> (5) Utajovaná informace v elektronické podobě se před jejím zpřístupněním elektronicky označí stupněm utajení; není-li to možné, označí se při jejím zpřístupnění podle odstavce 3.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Místní znění neobsahuje výslovný vnitřní odkaz.

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=f4f6a88fa4456e6e02c1 -->

### § 5 — Druhy zajištění ochrany utajovaných informací

> **§ 5**
>
> *Ochrana utajovaných informací je zajišťována*
>
> *- a) personální bezpečností, kterou tvoří výběr fyzických osob, které mají mít přístup k utajovaným informacím, ověřování podmínek pro jejich přístup k utajovaným informacím, jejich výchova a ochrana,*
>
> *- b) průmyslovou bezpečností, kterou tvoří systém opatření k zjišťování a ověřování podmínek pro přístup podnikatele k utajovaným informacím a k zajištění nakládání s utajovanou informací u podnikatele v souladu s tímto zákonem,*
>
> *- c) administrativní bezpečností, kterou tvoří systém opatření při tvorbě, příjmu, evidenci, zpracování, odesílání, přepravě, přenášení, ukládání, skartačním řízení, archivaci, případně jiném nakládání s utajovanými informacemi,*
>
> *- d) fyzickou bezpečností, kterou tvoří systém opatření, která mají neoprávněné osobě zabránit nebo ztížit přístup k utajovaným informacím, popřípadě přístup nebo pokus o něj zaznamenat,*
>
> *- e) bezpečností informačních nebo komunikačních systémů, kterou tvoří systém opatření, jejichž cílem je zajistit důvěrnost, integritu a dostupnost utajovaných informací, s nimiž tyto systémy nakládají, a odpovědnost správy a uživatele za jejich činnost v informačním nebo komunikačním systému a*
>
> *- f) kryptografickou ochranou, kterou tvoří systém opatření na ochranu utajovaných informací použitím kryptografických metod a kryptografických materiálů při zpracování, přenosu nebo ukládání utajovaných informací.*

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

#### F. Kazuistika

**1. Modelová situace.** Podnikatel získá osvědčení pro přístup k informaci stupně Tajné formou, kdy informace fyzicky vzniká v jeho prostorách. Spoléhá výhradně na prověrku svých zaměstnanců (personální bezpečnost), avšak nezřídí zabezpečenou oblast, nemá certifikovaný IS ani administrativní evidenci dokumentů. Při kontrole Úřadu se zjistí, že utajované dokumenty jsou uloženy v běžné kanceláři. Účastníci: podnikatel (držitel osvědčení), Úřad (kontrolní orgán). Důkazy: protokol o kontrole, projekt fyzické bezpečnosti (chybějící), certifikace IS (chybějící), bezpečnostní dokumentace.

**2. Právní otázka.** Postačí k ochraně utajované informace zajištění jen některého z druhů ochrany podle § 5, nebo musí být kombinovány všechny relevantní pilíře podle stupně utajení a formy přístupu?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 5 — taxativní výčet šesti druhů zajištění ochrany (personální, průmyslová, administrativní, fyzická, IS/KS, kryptografická), tvořící vrstvenou architekturu.
- *Související ustanovení téhož zákona:* § 19 (způsobilost podnikatele zabezpečit ochranu podle § 5), § 20 (formy přístupu a jejich nároky), § 21 (administrativní bezpečnost), § 24 a násl. (fyzická bezpečnost), § 34 a násl. (IS/KS), § 37 a násl. (kryptografická ochrana).
- *Související předpisy:* vyhláška č. 528/2005 Sb. (fyzická bezpečnost), č. 523/2005 Sb. (bezpečnost IS), č. 529/2005 Sb. (administrativní bezpečnost).
- *Judikatura:* judikatura NSS k nepřevoditelnosti osvědčení a vázanosti ochrany na konkrétní podmínky podnikatele (sp. zn. 8 As 9/2010 — osvědčení deklaruje splnění podmínek u konkrétního subjektu).

**4. Subsumpce.** Forma přístupu, při níž UI fyzicky vzniká u podnikatele (§ 20 odst. 1 forma a), vyžaduje kombinaci personální, administrativní a fyzické bezpečnosti, případně IS/KS a kryptografické ochrany, je-li UI zpracovávána elektronicky. Podnikatel zajistil pouze personální složku → nesplnil způsobilost podle § 19 ve spojení s § 5. Sporné může být jen to, zda forma přístupu skutečně vyžadovala fyzickou bezpečnost, nebo zda šlo o formu b) (jen personální — § 20 odst. 2).

**5. Řešení.** Ochrana podle § 5 je vrstvená (defense-in-depth) — jednotlivé pilíře se nenahrazují, nýbrž doplňují podle stupně a formy. Podnikatel pochybil; Úřad může zahájit řízení o zrušení platnosti osvědčení (ztráta způsobilosti dle § 19) a uložit sankci za porušení povinnosti. Procesní kroky: dodatečné zřízení zabezpečené oblasti, schválení projektu fyzické bezpečnosti, certifikace IS, vedení evidence. Riziko: trvání závadného stavu = trvající porušení a možná kompromitace informace.

**6. Varianty.** (a) Šlo by o formu přístupu, kdy UI je přístupná jen zaměstnancům podnikatele mimo jeho prostory (§ 20 odst. 2) → postačila by personální bezpečnost a výtka by neobstála. (b) Stupeň by byl jen Vyhrazené s prohlášením podnikatele (§ 15a) → nároky na pilíře jsou nižší, odpovídající podmínkám pro Vyhrazené.

#### G. Protiargumenty a rizika

- *Protiargument 1:* „Zákon vyjmenovává druhy ochrany, ale neukládá kombinovat je všechny." Neutralizace: § 5 ve spojení s § 19 a § 20 a prováděcími vyhláškami stanoví, že rozsah pilířů se odvíjí od stupně a formy; relevantní pilíře jsou pro daný režim obligatorní, nikoli volitelné.
- *Protiargument 2:* „Personální prověrka zaměstnanců je dostatečná, protože k úniku dojde jen lidským faktorem." Neutralizace: architektura defense-in-depth počítá i s fyzickým a technickým vektorem útoku; vynechání fyzické a administrativní vrstvy ponechává informaci nechráněnou bez ohledu na spolehlivost osob.
- *Slabé místo:* § 5 je systematicko-definiční; sám neukládá konkrétní opatření — ta plynou z navazujících hlav a vyhlášek. Argumentace musí být vždy doplněna o konkrétní ustanovení příslušného pilíře.

#### H. Praktický závěr

§ 5 je organizační osou Části druhé — určuje šest pilířů, jejichž konkrétní obsah rozvádějí samostatné hlavy. V praxi je nutné podle stupně utajení a formy přístupu sestavit „matici" relevantních pilířů a každý z nich doložit odpovídající dokumentací a certifikací.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Které pilíře § 5 jsou pro daný stupeň a formu přístupu relevantní?
- [ ] Je personální bezpečnost (prověření osob) zajištěna (§ 6–14)?
- [ ] Je zajištěna fyzická bezpečnost a administrativní evidence, vzniká-li UI u subjektu (§ 21, § 24)?
- [ ] Je IS certifikován a kryptoochrana zajištěna, je-li UI zpracovávána elektronicky (§ 34, § 37)?
- [ ] Odpovídá zvolená forma přístupu (§ 20) skutečnému způsobu nakládání?

**Typicky rozhodné důkazy / podklady:** bezpečnostní dokumentace subjektu, projekt fyzické bezpečnosti, certifikáty IS/kryptoprostředků, evidence dokumentů, doklad o prověření osob, protokol o kontrole Úřadu.

---


<!-- LEGAL-REVISION:BEGIN id=df27f172b6cb584dba3c generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 5 — Druhy zajištění ochrany utajovaných informací

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> Ochrana utajovaných informací je zajišťována
>
> - a) personální bezpečností, kterou tvoří výběr fyzických osob, které mají mít přístup k utajovaným informacím, ověřování podmínek pro jejich přístup k utajovaným informacím, jejich výchova a ochrana,
>
> - b) průmyslovou bezpečností, kterou tvoří systém opatření k zjišťování a ověřování podmínek pro přístup podnikatele k utajovaným informacím a k zajištění nakládání s utajovanou informací u podnikatele v souladu s tímto zákonem,
>
> - c) administrativní bezpečností, kterou tvoří systém opatření při tvorbě, příjmu, evidenci, zpracování, odesílání, přepravě, přenášení, ukládání, skartačním řízení, archivaci, případně jiném nakládání s utajovanými informacemi,
>
> - d) fyzickou bezpečností, kterou tvoří systém opatření, která mají neoprávněné osobě zabránit nebo ztížit přístup k utajovaným informacím, popřípadě přístup nebo pokus o něj zaznamenat,
>
> - e) bezpečností informačních nebo komunikačních systémů, kterou tvoří systém opatření, jejichž cílem je zajistit důvěrnost, integritu a dostupnost utajovaných informací, s nimiž tyto systémy nakládají, a odpovědnost správy a uživatele za jejich činnost v informačním nebo komunikačním systému a
>
> - f) kryptografickou ochranou, kterou tvoří systém opatření na ochranu utajovaných informací použitím kryptografických metod a kryptografických materiálů při zpracování, přenosu nebo ukládání utajovaných informací.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Místní znění neobsahuje výslovný vnitřní odkaz.

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=df27f172b6cb584dba3c -->

### Hlava II — Personální bezpečnost

### Podmínky přístupu fyzické osoby k utajované informaci stupně utajení Vyhrazené (§§ 6–10)

### § 6 — Podmínky přístupu k Vyhrazené informaci a oznámení

> **§ 6**
>
> *(1) Fyzické osobě lze umožnit přístup k utajované informaci stupně utajení Vyhrazené, jestliže jej nezbytně potřebuje k výkonu své funkce, pracovní nebo jiné činnosti, je držitelem oznámení o splnění podmínek pro přístup k utajované informaci stupně utajení Vyhrazené (dále jen „oznámení“), osvědčení fyzické osoby (§ 54) nebo dokladu (§ 80) a je poučena, nestanoví-li tento zákon nebo zvláštní právní předpis jinak (§ 58 až 62).*
>
> *(2) Oznámení se vydá fyzické osobě, která*
>
> *- a) je plně svéprávná,*
>
> *- b) dosáhla alespoň 18 let věku,*
>
> *- c) je bezúhonná podle § 8.*
>
> *(3) Splnění podmínek podle odstavce 2 ověřuje a oznámení fyzické osobě vydává ten, kdo je vůči ní v rámci služebního poměru nebo pracovněprávního, členského či obdobného vztahu odpovědnou osobou, nebo jí určená osoba. Jde-li o fyzickou osobu, vůči níž není odpovědná osoba podle věty první, splnění podmínek podle odstavce 2 ověřuje a oznámení fyzické osobě vydává odpovědná osoba nebo jí určená osoba toho, kdo umožní fyzické osobě přístup k utajované informaci stupně utajení Vyhrazené. V ostatních případech splnění podmínek podle odstavce 2 ověřuje a oznámení fyzické osobě vydává Národní bezpečnostní úřad (dále jen „Úřad“) na základě odůvodněné písemné žádosti.*

**Výklad:**

**Judikatura (z místních zdrojů):**

- *NSS* [8 A 40/2017 - 52](https://vyhledavac.nssoud.cz/DokumentOriginal/Text/424096) — 12. 3. 2020
  > „je v každém konkrétním případě potřeba posoudit, zda podnikatel tuto informaci ve smyslu § 6 odst. 1 a § 15 písm. a) zákona č. 412/2005 Sb., potřebuje nezbytně znát pro účely své činnosti (jde tzv. princip need to know). Jakýkoliv jiný výklad by vedl k absurdním důsledkům, kdy by se každý držitel bezpečnostní prověrky mohl automaticky seznámit s každou utajovanou informací v držení orgánů České republiky, která stupněm svého utajení odpovídá jeho prověření"

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

#### F. Kazuistika

**1. Modelová situace.** Externí IT konzultant má pro orgán státu nasadit software v prostředí, kde se ojediněle vyskytují informace stupně Vyhrazené. Konzultant nemá ke orgánu žádný pracovní ani služební vztah (fakturuje jako OSVČ). Odpovědná osoba orgánu mu chce umožnit přístup. Konzultant je svéprávný, 35 let, bez záznamu v rejstříku trestů. Účastníci: konzultant (FO usilující o přístup), orgán státu (subjekt umožňující přístup), jeho odpovědná osoba. Důkazy: doklad o potřebě přístupu (smlouva o dílo vymezující úkol), výpis z RT, OP, prohlášení o svéprávnosti, poučení.

**2. Právní otázka.** Kdo je oprávněn vydat konzultantovi oznámení podle § 6 odst. 3, splňuje-li hmotné podmínky odst. 2, a je vůbec přístup potřebný (need-to-know)?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 6 odst. 1 (need-to-know + oprávnění + poučení), odst. 2 (svéprávnost, věk 18+, bezúhonnost), odst. 3 (hierarchie vydavatelů oznámení).
- *Související ustanovení téhož zákona:* § 7 (prokazování podmínek), § 8 (bezúhonnost), § 9 (poučení a platnost), § 54 (osvědčení FO jako alternativa), § 80 (doklad).
- *Související předpisy:* zákon č. 269/1994 Sb., o Rejstříku trestů; občanský zákoník (svéprávnost).
- *Judikatura:* rozsudek NSS sp. zn. 8 A 40/2017 — přístup k UI je vázán na nezbytnou potřebu znát informaci (need-to-know); držitel oprávnění se nemůže automaticky seznámit s každou informací odpovídajícího stupně.

**4. Subsumpce.** Konzultant nemá ke orgánu žádný stabilní vztah → nepoužije se věta první odst. 3 (vydavatelem není „jeho" odpovědná osoba). Použije se věta druhá: oznámení vydá odpovědná osoba (či jí určená) toho, kdo přístup umožní — tedy orgánu státu. Need-to-know je naplněn, je-li přístup nezbytný k provedení konkrétního úkolu ze smlouvy o dílo. Hmotné podmínky odst. 2 jsou splněny (svéprávnost, věk, bezúhonnost).

**5. Řešení.** Oznámení vydá odpovědná osoba orgánu státu (jako subjektu umožňujícího přístup), nikoli Úřad — subsidiarita Úřadu nastupuje teprve, není-li žádná z předchozích cest možná. Před prvním přístupem orgán zajistí poučení (§ 9). Procesní kroky: ověření tří podmínek (doklady dle § 7), vydání oznámení, poučení s podpisem. Riziko: pokud by přístup nebyl pro úkol nezbytný (např. konzultant by mohl pracovat na anonymizovaných datech), need-to-know chybí a oznámení by nemělo být vydáno.

**6. Varianty.** (a) Konzultant by byl ve stabilním pracovněprávním vztahu k subdodavateli, který přístup umožňuje → oznámení vydá odpovědná osoba subdodavatele (věta první). (b) Úkol by vyžadoval i přístup k informaci stupně Důvěrné → oznámení nestačí, je nutné osvědčení FO (§ 11, § 54).

#### G. Protiargumenty a rizika

- *Protiargument 1:* „Konzultant má prověrku z jiného angažmá, takže přístup mu náleží automaticky." Neutralizace: oprávnění bez aktuálního need-to-know nestačí (NSS 8 A 40/2017); věcný důvod musí existovat ke konkrétnímu úkolu, ne obecně.
- *Protiargument 2:* „Oznámení musí vždy vydat Úřad, jde-li o osobu bez vztahu k orgánu." Neutralizace: Úřad je až subsidiární (věta třetí odst. 3); přednost má odpovědná osoba toho, kdo přístup umožní (věta druhá).
- *Slabé místo:* doložení need-to-know u externí osoby bývá sporné; bez přesného vymezení úkolu ve smlouvě je obtížné prokázat nezbytnost přístupu a hrozí jeho nadbytečné rozšíření.

#### H. Praktický závěr

§ 6 stanoví trojici kumulativních podmínek pro přístup k Vyhrazené (need-to-know + oprávnění v jedné ze tří forem + poučení) a decentralizovanou hierarchii vydavatelů oznámení. V praxi je rozhodné správně určit vydavatele a poctivě posoudit nezbytnost přístupu, nikoli jej odvozovat z pouhého držení oprávnění.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Je přístup nezbytný k výkonu konkrétní funkce/činnosti (need-to-know)?
- [ ] Je FO svéprávná, starší 18 let a bezúhonná podle § 8?
- [ ] Kdo je správným vydavatelem oznámení podle hierarchie § 6 odst. 3?
- [ ] Bylo provedeno poučení před prvním přístupem (§ 9)?
- [ ] Nevyžaduje úkol vyšší stupeň, tj. osvědčení FO (§ 11)?

**Typicky rozhodné důkazy / podklady:** doklad o potřebě přístupu (smlouva/popis úkolu), výpis z RT, OP nebo cestovní doklad, prohlášení o svéprávnosti, podepsané poučení, vydané oznámení.

---


<!-- LEGAL-REVISION:BEGIN id=4bc01aa9bcb6a03950e4 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 6

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Fyzické osobě lze umožnit přístup k utajované informaci stupně utajení Vyhrazené, jestliže jej nezbytně potřebuje k výkonu své funkce, pracovní nebo jiné činnosti, je držitelem oznámení o splnění podmínek pro přístup k utajované informaci stupně utajení Vyhrazené (dále jen „oznámení“), osvědčení fyzické osoby ([[#§ 54|§ 54]]) nebo dokladu ([[#§ 80|§ 80]]) a je poučena, nestanoví-li tento zákon nebo zvláštní právní předpis jinak (§ 58 až 62).
>
> (2) Oznámení se vydá fyzické osobě, která
>
> - a) je plně svéprávná,
>
> - b) dosáhla alespoň 18 let věku,
>
> - c) je bezúhonná podle [[#§ 8|§ 8]].
>
> (3) Splnění podmínek podle odstavce 2 ověřuje a oznámení fyzické osobě vydává ten, kdo je vůči ní v rámci služebního poměru nebo pracovněprávního, členského či obdobného vztahu odpovědnou osobou, nebo jí určená osoba. Jde-li o fyzickou osobu, vůči níž není odpovědná osoba podle věty první, splnění podmínek podle odstavce 2 ověřuje a oznámení fyzické osobě vydává odpovědná osoba nebo jí určená osoba toho, kdo umožní fyzické osobě přístup k utajované informaci stupně utajení Vyhrazené. V ostatních případech splnění podmínek podle odstavce 2 ověřuje a oznámení fyzické osobě vydává Národní bezpečnostní úřad (dále jen „Úřad“) na základě odůvodněné písemné žádosti.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 54, § 80, § 58, § 8

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=4bc01aa9bcb6a03950e4 -->

### § 7 — Prokazování podmínek

> **§ 7**
>
> *(1) Podmínka svéprávnosti se prokazuje prohlášením fyzické osoby o svéprávnosti. Podmínka věku se prokazuje občanským průkazem nebo cestovním dokladem fyzické osoby. Podmínka bezúhonnosti se prokazuje výpisem z evidence Rejstříku trestů11) a v případě cizince i obdobným dokladem státu, jehož je cizinec státním příslušníkem, pokud v něm pobýval i po dosažení věku 15 let nepřetržitě po dobu delší než 6 měsíců, jakož i státu, v němž cizinec pobýval v posledních 10 letech nepřetržitě po dobu delší než 6 měsíců, anebo výpisem z evidence Rejstříku trestů s přílohou obsahující informace, které jsou zapsané v evidenci trestů takového státu. V případě, že cizí stát doklad obdobný výpisu z rejstříku trestů nevydává, prokazuje se podmínka bezúhonnosti čestným prohlášením. Doklady k ověření bezúhonnosti nesmějí být starší než 3 měsíce od jejich vydání.*
>
> *(2) Doklady podle odstavce 1 předkládá fyzická osoba; pokud bezúhonnost posuzuje orgán státu, vyžádá si výpis z evidence Rejstříku trestů11). Žádost o vydání výpisu z evidence Rejstříků trestů a výpis z evidence Rejstříku trestů se předávají v elektronické podobě způsobem umožňujícím dálkový přístup. Jiné doklady prokazující bezúhonnost cizince předkládá cizinec.*
>
> *(3) Prováděcí právní předpis stanoví vzor prohlášení fyzické osoby o svéprávnosti.*

**Výklad:**

Procesní pravidla pro prokazování. Klíčové aspekty:
- **Svéprávnost** — čestné prohlášení (FO ručí pravdivostí).
- **Věk** — OP nebo cestovní pas.
- **Bezúhonnost** — výpis z RT, u cizinců navíc obdobný doklad státu, kde po 15. roce věku pobývali souvisle déle než 6 měsíců, nebo státu, kde za posledních 10 let pobývali souvisle déle než 6 měsíců. Pokud daný stát doklad nevydává, lze nahradit čestným prohlášením.
- **Maximální stáří dokladu** — 3 měsíce.

V odst. 2 je upraveno, že je-li ověřovatelem orgán státu, vyžádá si výpis z RT sám (princip jednotlivého kontaktu — citizen-friendly e-Government). Jinak doklady předkládá FO.

#### F. Kazuistika

**1. Modelová situace.** O oznámení pro přístup k Vyhrazené žádá německý státní příslušník, který v posledních letech pracoval střídavě v ČR, Rakousku a SRN. V ČR doloží výpis z RT s přílohou, k pobytu v SRN doloží Führungszeugnis, avšak k pobytu v Rakousku (kde po 15. roce věku žil souvisle 8 měsíců) nedoloží nic s tvrzením, že „to není podstatné". Předložené doklady jsou 5 měsíců staré. Účastníci: cizinec (žadatel), ověřovatel (odpovědná osoba orgánu státu). Důkazy: výpis z RT s přílohou, rakouský a německý doklad o bezúhonnosti, prohlášení o svéprávnosti, OP/pas.

**2. Právní otázka.** Splnil cizinec důkazní povinnost k podmínce bezúhonnosti podle § 7 odst. 1, chybí-li doklad státu, kde po 15. roce věku souvisle pobýval déle než 6 měsíců, a lze přijmout doklady starší 3 měsíců?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 7 odst. 1 (způsoby prokázání svéprávnosti, věku, bezúhonnosti; cizinecké doklady; maximální stáří 3 měsíce), odst. 2 (kdo doklady předkládá; vyžádání výpisu orgánem státu).
- *Související ustanovení téhož zákona:* § 6 odst. 2 (hmotné podmínky), § 8 (definice bezúhonnosti), § 9 (poučení a periodická reverifikace).
- *Související předpisy:* zákon č. 269/1994 Sb., o Rejstříku trestů (výpis a jeho příloha pro cizince); rozhodnutí Rady 2009/315/SVV (ECRIS — výměna informací z rejstříků trestů v EU).
- *Judikatura:* obecné zásady správního řízení k unesení důkazního břemene žadatelem; judikatura k formálním náležitostem podkladů bezpečnostního řízení.

**4. Subsumpce.** Cizinec po 15. roce věku pobýval v Rakousku souvisle déle než 6 měsíců → § 7 odst. 1 vyžaduje i obdobný doklad rakouského státu (nebo přílohu výpisu z RT s rakouskými údaji). Doklad chybí → podmínka bezúhonnosti není prokázána. Doklady starší než 3 měsíce nelze akceptovat → vada i u jinak předložených dokladů. Sporné je jen to, zda Rakousko doklad vydává — pokud ano, čestné prohlášení jej nenahradí.

**5. Řešení.** Ověřovatel musí vyzvat žadatele k doplnění rakouského dokladu a aktuálních (ne starších než 3 měsíce) podkladů; do té doby nelze oznámení vydat, neboť bezúhonnost není prokázána. Čestné prohlášení je přípustné jen tehdy, daný stát doklad nevydává — což u Rakouska neplatí. Procesní kroky: výzva k doplnění, stanovení lhůty, nové posouzení. Riziko: vydání oznámení na neúplných podkladech by bylo vadné a zakládalo by důvod jeho zpochybení při kontrole.

**6. Varianty.** (a) Rakousko by obdobný doklad nevydávalo → bezúhonnost by se prokázala čestným prohlášením (odst. 1 in fine). (b) Ověřovatelem by byl orgán státu posuzující bezúhonnost → výpis z RT (ČR) by si vyžádal sám elektronicky (odst. 2), cizinec by však i tak musel předložit zahraniční doklady.

#### G. Protiargumenty a rizika

- *Protiargument 1:* „Stačí výpis z RT z ČR, protože tam žadatel nyní žije." Neutralizace: § 7 odst. 1 výslovně rozšiřuje povinnost na doklady států pobytu po 15. roce věku (déle než 6 měsíců) i států pobytu v posledních 10 letech (déle než 6 měsíců); jediný český výpis nepostačuje.
- *Protiargument 2:* „Stáří dokladů je formalita, kterou lze prominout." Neutralizace: limit 3 měsíců je zákonný a zajišťuje aktuálnost; jeho překročení činí podklad nezpůsobilým, prominutí zákon neumožňuje.
- *Slabé místo:* zjištění všech států relevantního pobytu závisí na pravdivosti údajů žadatele; bez součinnosti (a případně prohlášení o pobytech) nelze rozsah povinných dokladů spolehlivě určit.

#### H. Praktický závěr

§ 7 je ryze procesní normou o dokazování tří podmínek oznámení. V praxi je kritické u cizinců mapovat všechny státy relevantního pobytu a vyžadovat doklady ne starší 3 měsíců; čestné prohlášení je krajní řešení vázané na to, že daný stát doklad nevydává.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Je doloženo prohlášení o svéprávnosti a doklad totožnosti k věku?
- [ ] Je předložen výpis z RT (a u orgánu státu vyžádán sám)?
- [ ] U cizince: jsou doloženy doklady všech států pobytu nad 6 měsíců (po 15. roce / posledních 10 let)?
- [ ] Nejsou doklady starší než 3 měsíce?
- [ ] Je čestné prohlášení použito jen tam, kde stát doklad nevydává?

**Typicky rozhodné důkazy / podklady:** výpis z RT a jeho příloha, zahraniční doklady o bezúhonnosti (ECRIS / Führungszeugnis apod.), prohlášení o svéprávnosti, OP/cestovní doklad, přehled států pobytu žadatele.

---


<!-- LEGAL-REVISION:BEGIN id=f472a4c24aeb63bb6652 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 7

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Podmínka svéprávnosti se prokazuje prohlášením fyzické osoby o svéprávnosti. Podmínka věku se prokazuje občanským průkazem nebo cestovním dokladem fyzické osoby. Podmínka bezúhonnosti se prokazuje výpisem z evidence Rejstříku trestů11) a v případě cizince i obdobným dokladem státu, jehož je cizinec státním příslušníkem, pokud v něm pobýval i po dosažení věku 15 let nepřetržitě po dobu delší než 6 měsíců, jakož i státu, v němž cizinec pobýval v posledních 10 letech nepřetržitě po dobu delší než 6 měsíců, anebo výpisem z evidence Rejstříku trestů s přílohou obsahující informace, které jsou zapsané v evidenci trestů takového státu. V případě, že cizí stát doklad obdobný výpisu z rejstříku trestů nevydává, prokazuje se podmínka bezúhonnosti čestným prohlášením. Doklady k ověření bezúhonnosti nesmějí být starší než 3 měsíce od jejich vydání.
>
> (2) Doklady podle odstavce 1 předkládá fyzická osoba; pokud bezúhonnost posuzuje orgán státu, vyžádá si výpis z evidence Rejstříku trestů11). Žádost o vydání výpisu z evidence Rejstříků trestů a výpis z evidence Rejstříku trestů se předávají v elektronické podobě způsobem umožňujícím dálkový přístup. Jiné doklady prokazující bezúhonnost cizince předkládá cizinec.
>
> (3) Prováděcí právní předpis stanoví vzor prohlášení fyzické osoby o svéprávnosti.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Místní znění neobsahuje výslovný vnitřní odkaz.

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=f472a4c24aeb63bb6652 -->

### § 8 — Bezúhonnost pro oznámení

> **§ 8**
>
> *Podmínku bezúhonnosti pro účely vydání oznámení splňuje fyzická osoba, která nebyla pravomocně odsouzena za spáchání úmyslného trestného činu nebo trestného činu vztahujícího se k ochraně utajovaných informací, anebo se na ni hledí, jako by odsouzena nebyla.*

**Výklad:**

#### Bezúhonnost — užší než pro osvědčení (§ 13)

Pro úroveň Vyhrazené je bezúhonnost definována poměrně **úzce**: nezpůsobuje ji jakékoliv pravomocné odsouzení za **úmyslný trestný čin** nebo za **trestný čin vztahující se k ochraně UI**. Z výčtu je vyloučeno odsouzení za nedbalostní trestný čin (s výjimkou těch vztahujících se k UI — typicky § 318 TZ — ohrožení UI z nedbalosti).

Bezúhonnost se „obnovuje" zahlazením odsouzení (§ 105 TZ) — zákon používá formulaci „nebo se na ni hledí, jako by odsouzena nebyla", tedy zahlazení působí ex lege.

Pro vyšší stupně (Důvěrné, Tajné, Přísně tajné) je bezúhonnost rozšířena v § 13 o postupy v případech podmíněného zastavení trestního stíhání nebo schválení narovnání — tam ochranná doba 5 let od právní moci.

#### F. Kazuistika

**1. Modelová situace.** Zaměstnanec orgánu státu byl před třemi lety pravomocně odsouzen za nedbalostní ublížení na zdraví při dopravní nehodě (§ 148 TZ); trest již vykonal, odsouzení dosud nebylo zahlazeno. Nyní žádá o oznámení pro přístup k Vyhrazené. Odpovědná osoba váhá, zda jej odsouzení diskvalifikuje. Účastníci: zaměstnanec (žadatel), odpovědná osoba (ověřovatel). Důkazy: výpis z RT s daným záznamem, povaha trestného činu (úmyslný/nedbalostní; vztah k ochraně UI).

**2. Právní otázka.** Brání bezúhonnosti podle § 8 pravomocné odsouzení za nedbalostní trestný čin, který se nevztahuje k ochraně utajovaných informací?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 8 — bezúhonnost je vyloučena odsouzením za úmyslný trestný čin nebo trestný čin vztahující se k ochraně UI; jinak (a po zahlazení) je splněna.
- *Související ustanovení téhož zákona:* § 6 odst. 2 písm. c) (bezúhonnost jako podmínka oznámení), § 7 (prokazování), § 13 (širší bezúhonnost pro osvědčení FO — odlišení).
- *Související předpisy:* § 318 TZ (ohrožení utajované informace z nedbalosti — příklad nedbalostního činu, který se k ochraně UI vztahuje), § 105 TZ (zahlazení odsouzení).
- *Judikatura:* ustálený výklad, že fikce neodsouzení (§ 105 TZ) působí ex lege; rozhodnutí k povaze trestného činu jako úmyslného vs. nedbalostního.

**4. Subsumpce.** Odsouzení je za nedbalostní trestný čin (§ 148 TZ) → nespadá pod kategorii „úmyslný trestný čin". Současně se čin nevztahuje k ochraně UI (nejde o § 318 TZ ani obdobný) → nespadá ani pod druhou kategorii. Bezúhonnost podle § 8 tedy není vyloučena. Není sporu o povaze činu (nedbalostní) ani o jeho nesouvislosti s UI.

**5. Řešení.** Zaměstnanec splňuje podmínku bezúhonnosti podle § 8, neboť výčet diskvalifikujících odsouzení je užší než u osvědčení FO — nedbalostní čin nevztahující se k UI nepřekáží. Odpovědná osoba může (při splnění ostatních podmínek a need-to-know) oznámení vydat. Procesní krok: ověřit, že nejde o úmyslný čin a že čin nesouvisí s UI. Riziko nezamění s § 13: pro vyšší stupně (D/T/PT) by se posuzovala širší bezúhonnost a navíc bezpečnostní spolehlivost (§ 14), kde by okolnosti nehody mohly být relevantní jinak.

**6. Varianty.** (a) Odsouzení by bylo za § 318 TZ (ohrožení UI z nedbalosti) → bezúhonnost vyloučena, byť jde o nedbalostní čin, neboť se vztahuje k ochraně UI. (b) Odsouzení by již bylo zahlazeno (§ 105 TZ) → na osobu se hledí, jako by odsouzena nebyla, a překážka by odpadla i u úmyslného činu.

#### G. Protiargumenty a rizika

- *Protiargument 1:* „Jakékoli odsouzení v RT brání bezúhonnosti." Neutralizace: § 8 je selektivní — diskvalifikuje jen úmyslné činy a činy vztahující se k UI; ostatní (vč. nedbalostních mimo UI) bezúhonnost neruší.
- *Protiargument 2:* „Dopravní nehoda svědčí o nespolehlivosti, takže přístup nelze umožnit." Neutralizace: u Vyhrazené se posuzuje pouze bezúhonnost dle § 8, nikoli bezpečnostní spolehlivost (§ 14); důvody spolehlivosti jsou vyhrazeny řízení o osvědčení FO, ne oznámení.
- *Slabé místo:* hranice mezi úmyslem a nedbalostí může být u některých skutkových podstat sporná; rozhodující je právní kvalifikace ve výroku odsuzujícího rozsudku, kterou je třeba ověřit.

#### H. Praktický závěr

§ 8 definuje bezúhonnost pro nejnižší stupeň úzce — překáží jen úmyslné trestné činy a činy vztahující se k ochraně UI; po zahlazení odsouzení překážka odpadá. V praxi je nutné nezaměňovat tuto úzkou bezúhonnost se širší bezúhonností (§ 13) a se spolehlivostí (§ 14) platnými pro osvědčení.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Jde o odsouzení za úmyslný trestný čin?
- [ ] Vztahuje se čin k ochraně utajovaných informací (např. § 318 TZ)?
- [ ] Bylo odsouzení zahlazeno nebo se na osobu hledí, jako by odsouzena nebyla (§ 105 TZ)?
- [ ] Nejde o stupeň vyžadující osvědčení FO (pak § 13 + § 14)?

**Typicky rozhodné důkazy / podklady:** výpis z RT, odsuzující rozsudek s právní kvalifikací činu, doklad o zahlazení odsouzení, posouzení vztahu činu k ochraně UI.

---


<!-- LEGAL-REVISION:BEGIN id=ed62d162531a44ce5e28 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 8

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> Bezúhonnost pro účely vydání oznámení
>
> Podmínku bezúhonnosti pro účely vydání oznámení splňuje fyzická osoba, která nebyla pravomocně odsouzena za spáchání úmyslného trestného činu nebo trestného činu vztahujícího se k ochraně utajovaných informací, anebo se na ni hledí, jako by odsouzena nebyla.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Místní znění neobsahuje výslovný vnitřní odkaz.

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=ed62d162531a44ce5e28 -->

### § 9 — Poučení a platnost oznámení

> **§ 9**
>
> *(1) Před prvním přístupem k utajované informaci stupně utajení Vyhrazené ten, kdo je vůči fyzické osobě v rámci služebního poměru nebo pracovněprávního, členského či obdobného vztahu osobou odpovědnou, zajistí její poučení. Jde-li o fyzickou osobu, vůči níž není odpovědná osoba podle věty první, zajistí poučení odpovědná osoba toho, kdo přístup k utajované informaci umožní. Poučení podepisuje fyzická osoba a ten, kdo poučení provedl; jeden výtisk poučení jí předá a jeden výtisk uloží12).*
>
> *(2) Ten, kdo vydal oznámení, je povinen každých 5 let ode dne jeho vydání ověřovat splnění podmínek stanovených v § 6 odst. 2 písm. a) a c); ověřovat splnění těchto podmínek je oprávněn i před uplynutím této lhůty, existují-li důvodné pochybnosti o tom, že osoba přestala některou z nich splňovat. Výtisk oznámení a poučení a podklady pro ověření splnění podmínek podle § 6 odst. 2 písm. a) a c) lze uchovávat nejdéle 5 let ode dne zániku platnosti oznámení.*
>
> *(3) Platnost oznámení zaniká*
>
> *- a) doručením písemného vyrozumění toho, kdo oznámení vydal, že fyzická osoba přestala splňovat podmínku uvedenou v § 6 odst. 2 písm. a) nebo c),*
>
> *- b) skončením služebního poměru nebo pracovněprávního, členského či obdobného vztahu, ve kterém byl fyzické osobě umožněn přístup k utajovaným informacím,*
>
> *- c) vznikem služebního poměru nebo pracovněprávního, členského či obdobného vztahu, ve kterém má být fyzické osobě umožněn přístup k utajovaným informacím, pokud bylo oznámení vydáno odpovědnou osobou nebo jí určenou osobou toho, kdo umožnil fyzické osobě přístup k utajované informaci stupně utajení Vyhrazené, nebo Úřadem podle § 6 odst. 3,*
>
> *- d) úmrtím nebo prohlášením osoby za mrtvou,*
>
> *- e) ohlášením jeho odcizení nebo ztráty,*
>
> *- f) ohlášením takového poškození, že zápisy v něm uvedené jsou nečitelné nebo je porušena jeho celistvost,*
>
> *- g) doručením písemného vyrozumění toho, kdo oznámení vydal, že fyzická osoba nesplnila ve stanovené lhůtě povinnost podle § 10 odst. 2 písm. b),*
>
> *- h) vrácením oznámení tomu, kdo jej vydal, a není-li jej, tak Úřadu,*
>
> *- i) patnáctým dnem od doručení osvědčení fyzické osoby nebo dokladu, nebo*
>
> *- j) změnou některého z údajů v něm obsažených.*
>
> *(4) Při zániku platnosti oznámení podle odstavce 3 písm. a) a g) je ten, kdo oznámení vydal, povinen zajistit, aby fyzická osoba neměla přístup k utajované informaci, a o tomto zániku je povinen fyzickou osobu písemně vyrozumět. V písemném vyrozumění uvede důvod zániku platnosti oznámení. Při zániku platnosti oznámení podle odstavce 3 písm. b) až d), f), h) nebo i) je ten, kdo oznámení vydal, povinen o tomto zániku učinit písemný záznam, který uloží12).*
>
> *(5) Pokud držitel oznámení do 15 dnů ode dne zániku jeho platnosti podle odstavce 3 písm. e) nebo f) a do 30 dnů ode dne zániku jeho platnosti podle odstavce 3 písm. j) požádá písemně toho, kdo oznámení vydal, o vydání oznámení nového, přístup fyzické osoby k utajované informaci není zánikem platnosti původního oznámení dotčen; ten, kdo oznámení vydal, vydá do 5 dnů od doručení žádosti oznámení nové, které nahrazuje původní.*
>
> *(6) Při zániku platnosti oznámení podle odstavce 3 písm. a) nebo g) je fyzická osoba povinna odevzdat oznámení do 15 dnů ode dne doručení písemného vyrozumění, v případě zániku platnosti oznámení podle odstavce 3 písm. b), c) nebo i) do 15 dnů ode dne tohoto zániku a v případě zániku platnosti oznámení podle odstavce 3 písm. j) do 30 dnů ode dne tohoto zániku tomu, kdo oznámení vydal.*
>
> *(7) V případě zániku platnosti oznámení se má za to, že fyzická osoba poučena není.*
>
> *(8) Prováděcí právní předpis stanoví vzor oznámení a poučení.*

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

#### F. Kazuistika

**1. Modelová situace.** Držitelce oznámení skončí dnem 30. 6. pracovní poměr u orgánu státu A. Od 1. 7. nastupuje k orgánu státu B, kde má rovněž pracovat s informacemi stupně Vyhrazené. Oznámení jí původně vydala odpovědná osoba orgánu A. Orgán B chce, aby používala dosavadní oznámení. Mezitím držitelka oznámení nahlásí, že jí byl doklad odcizen. Účastníci: držitelka oznámení, odpovědné osoby orgánů A a B. Důkazy: pracovní smlouvy (skončení/vznik vztahu), původní oznámení, hlášení o odcizení, případná žádost o nové oznámení.

**2. Právní otázka.** Kdy zaniká platnost oznámení podle § 9 odst. 3 (skončením vztahu? vznikem nového? odcizením?) a zachová se přístup, požádá-li držitelka o nové oznámení ve lhůtě?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 9 odst. 3 (deset důvodů zániku — zejm. písm. b) skončení vztahu, e) odcizení/ztráta), odst. 4 (procedurální následky), odst. 5 (zachování přístupu při včasné žádosti o nové oznámení), odst. 7 (fikce nepoučenosti).
- *Související ustanovení téhož zákona:* § 6 odst. 3 (vydavatel oznámení), § 10 odst. 2 (oznamovací povinnosti), § 11 (osvědčení FO pro vyšší stupně).
- *Související předpisy:* GDPR / zákon č. 110/2019 Sb. (limit uchovávání podkladů 5 let — odst. 2).
- *Judikatura:* obecné zásady k vázanosti oprávnění na trvání zákonných podmínek; přiměřeně judikatura k zániku oprávnění při změně rozhodných skutečností.

**4. Subsumpce.** Oznámení vydala odpovědná osoba orgánu A vůči vztahu u orgánu A. Skončením tohoto vztahu (30. 6.) zaniká platnost podle § 9 odst. 3 písm. b). Vznik nového vztahu u orgánu B by zakládal zánik podle písm. c) jen u oznámení vydaného odpovědnou osobou toho, kdo přístup umožnil, nebo Úřadem — což zde není rozhodné, neboť platnost již zanikla podle písm. b). Nezávisle nastupuje zánik podle písm. e) (ohlášení odcizení). U písm. e) lze přístup zachovat včasnou žádostí (odst. 5), u písm. b) nikoli.

**5. Řešení.** Oznámení z orgánu A nelze „přenést" do orgánu B — zaniklo skončením vztahu (písm. b). Orgán B musí vydat (cestou své odpovědné osoby) oznámení nové. Zánik podle písm. e) (odcizení) sám o sobě by umožnil zachovat přístup, požádá-li držitelka do 15 dnů o nové oznámení (odst. 5), avšak souběžný zánik podle písm. b) tento účinek vylučuje. Po zániku platí fikce nepoučenosti (odst. 7) — před dalším přístupem je nutné nové poučení. Procesní kroky: nové oznámení a poučení u orgánu B; písemný záznam/vyrozumění podle odst. 4.

**6. Varianty.** (a) Držitelka by zůstala u orgánu A a oznámení by jí bylo jen odcizeno → včasná žádost (15 dní) zachová přístup, nové oznámení nahradí původní (odst. 5). (b) Místo Vyhrazené by šlo o stupeň Důvěrné → oznámení nestačí; platnost a zánik se řídí osvědčením FO (§ 11, § 56), nikoli § 9.

#### G. Protiargumenty a rizika

- *Protiargument 1:* „Oznámení je doklad o osobě, takže platí i po změně zaměstnavatele." Neutralizace: oznámení je vázáno na konkrétní vztah; § 9 odst. 3 písm. b) výslovně váže zánik na skončení vztahu, v němž byl přístup umožněn.
- *Protiargument 2:* „Po odcizení stačí počkat na nový doklad, přístup trvá automaticky." Neutralizace: přístup se zachová jen při včasné písemné žádosti ve lhůtě dle odst. 5; bez ní (nebo při souběžném jiném důvodu zániku) přístup končí.
- *Slabé místo:* souběh více důvodů zániku (písm. b i e) je v praxi přehlížen; je nutné identifikovat všechny a posoudit, který vylučuje zachování přístupu podle odst. 5.

#### H. Praktický závěr

§ 9 upravuje poučení, periodickou reverifikaci (5 let) a zejména taxativní katalog deseti důvodů zániku platnosti oznámení s navazujícími procedurami. V praxi je nutné při každé personální změně zánik vyhodnotit, oznámení nepřenášet mezi vztahy a po zániku vždy provést nové poučení (fikce nepoučenosti).

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Nastal některý z deseti důvodů zániku podle § 9 odst. 3 (a jejich souběh)?
- [ ] Byla provedena periodická reverifikace po 5 letech (odst. 2)?
- [ ] Lze přístup zachovat včasnou žádostí o nové oznámení (odst. 5 — jen u písm. e, f, j)?
- [ ] Byl po zániku splněn procedurální následek (vyrozumění/záznam — odst. 4) a odevzdáno oznámení (odst. 6)?
- [ ] Bylo před dalším přístupem provedeno nové poučení (odst. 7)?

**Typicky rozhodné důkazy / podklady:** vydané oznámení a poučení, doklady o vzniku/skončení vztahu, hlášení o odcizení/ztrátě/poškození, žádost o nové oznámení a doklad o její včasnosti, záznamy o periodické reverifikaci.

---


<!-- LEGAL-REVISION:BEGIN id=4832f47b7fe204a3a64e generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 9

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Před prvním přístupem k utajované informaci stupně utajení Vyhrazené ten, kdo je vůči fyzické osobě v rámci služebního poměru nebo pracovněprávního, členského či obdobného vztahu osobou odpovědnou, zajistí její poučení. Jde-li o fyzickou osobu, vůči níž není odpovědná osoba podle věty první, zajistí poučení odpovědná osoba toho, kdo přístup k utajované informaci umožní. Poučení podepisuje fyzická osoba a ten, kdo poučení provedl; jeden výtisk poučení jí předá a jeden výtisk uloží12).
>
> (2) Ten, kdo vydal oznámení, je povinen každých 5 let ode dne jeho vydání ověřovat splnění podmínek stanovených v § 6 odst. 2 písm. a) a c); ověřovat splnění těchto podmínek je oprávněn i před uplynutím této lhůty, existují-li důvodné pochybnosti o tom, že osoba přestala některou z nich splňovat. Výtisk oznámení a poučení a podklady pro ověření splnění podmínek podle § 6 odst. 2 písm. a) a c) lze uchovávat nejdéle 5 let ode dne zániku platnosti oznámení.
>
> (3) Platnost oznámení zaniká
>
> - a) doručením písemného vyrozumění toho, kdo oznámení vydal, že fyzická osoba přestala splňovat podmínku uvedenou v § 6 odst. 2 písm. a) nebo c),
>
> - b) skončením služebního poměru nebo pracovněprávního, členského či obdobného vztahu, ve kterém byl fyzické osobě umožněn přístup k utajovaným informacím,
>
> - c) vznikem služebního poměru nebo pracovněprávního, členského či obdobného vztahu, ve kterém má být fyzické osobě umožněn přístup k utajovaným informacím, pokud bylo oznámení vydáno odpovědnou osobou nebo jí určenou osobou toho, kdo umožnil fyzické osobě přístup k utajované informaci stupně utajení Vyhrazené, nebo Úřadem podle § 6 odst. 3,
>
> - d) úmrtím nebo prohlášením osoby za mrtvou,
>
> - e) ohlášením jeho odcizení nebo ztráty,
>
> - f) ohlášením takového poškození, že zápisy v něm uvedené jsou nečitelné nebo je porušena jeho celistvost,
>
> - g) doručením písemného vyrozumění toho, kdo oznámení vydal, že fyzická osoba nesplnila ve stanovené lhůtě povinnost podle § 10 odst. 2 písm. b),
>
> - h) vrácením oznámení tomu, kdo jej vydal, a není-li jej, tak Úřadu,
>
> - i) patnáctým dnem od doručení osvědčení fyzické osoby nebo dokladu, nebo
>
> - j) změnou některého z údajů v něm obsažených.
>
> (4) Při zániku platnosti oznámení podle odstavce 3 písm. a) a g) je ten, kdo oznámení vydal, povinen zajistit, aby fyzická osoba neměla přístup k utajované informaci, a o tomto zániku je povinen fyzickou osobu písemně vyrozumět. V písemném vyrozumění uvede důvod zániku platnosti oznámení. Při zániku platnosti oznámení podle odstavce 3 písm. b) až d), f), h) nebo i) je ten, kdo oznámení vydal, povinen o tomto zániku učinit písemný záznam, který uloží12).
>
> (5) Pokud držitel oznámení do 15 dnů ode dne zániku jeho platnosti podle odstavce 3 písm. e) nebo f) a do 30 dnů ode dne zániku jeho platnosti podle odstavce 3 písm. j) požádá písemně toho, kdo oznámení vydal, o vydání oznámení nového, přístup fyzické osoby k utajované informaci není zánikem platnosti původního oznámení dotčen; ten, kdo oznámení vydal, vydá do 5 dnů od doručení žádosti oznámení nové, které nahrazuje původní.
>
> (6) Při zániku platnosti oznámení podle odstavce 3 písm. a) nebo g) je fyzická osoba povinna odevzdat oznámení do 15 dnů ode dne doručení písemného vyrozumění, v případě zániku platnosti oznámení podle odstavce 3 písm. b), c) nebo i) do 15 dnů ode dne tohoto zániku a v případě zániku platnosti oznámení podle odstavce 3 písm. j) do 30 dnů ode dne tohoto zániku tomu, kdo oznámení vydal.
>
> (7) V případě zániku platnosti oznámení se má za to, že fyzická osoba poučena není.
>
> (8) Prováděcí právní předpis stanoví vzor oznámení a poučení.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 6, § 10

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=4832f47b7fe204a3a64e -->

### § 10 — Trvalé plnění podmínek a oznamovací povinnosti

§ 10 stanoví, že FO musí podmínky svéprávnosti a bezúhonnosti plnit **po celou dobu** přístupu k Vyhrazené informaci. Současně ukládá oznamovací povinnost ve lhůtě **15 dnů** (resp. 30 dnů u změny údaje v oznámení) ohledně:
- změny týkající se svéprávnosti / bezúhonnosti,
- odcizení / ztráty / poškození oznámení,
- doručení osvědčení FO nebo dokladu,
- skutečností podle § 9 odst. 3 písm. c), f) a j).

Nesplnění této oznamovací povinnosti je samostatným důvodem zániku platnosti oznámení podle § 9 odst. 3 písm. g).

#### F. Kazuistika

**1. Modelová situace.** Držitel oznámení k Vyhrazené se po vydání oznámení dostal do předlužení a bylo proti němu zahájeno trestní stíhání pro úmyslný trestný čin podvodu. Změnu (zahájení stíhání) odpovědné osobě nenahlásí. Odpovědná osoba se o stíhání dozví z jiného zdroje až po čtyřech měsících. Účastníci: držitel oznámení, odpovědná osoba (vydavatel oznámení). Důkazy: usnesení o zahájení trestního stíhání, doklad o tom, kdy se držitel o skutečnosti dozvěděl, evidence o (ne)splnění oznamovací povinnosti.

**2. Právní otázka.** Porušil držitel oznamovací povinnost podle § 10 odst. 2 a jaký to má následek pro platnost oznámení, zohledníme-li, že zatím nejde o pravomocné odsouzení?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 10 — povinnost plnit podmínky (svéprávnost, bezúhonnost) po celou dobu přístupu a oznamovat ve lhůtě 15 dnů (30 dnů u změny údaje) rozhodné skutečnosti.
- *Související ustanovení téhož zákona:* § 9 odst. 3 písm. g) (nesplnění povinnosti dle § 10 jako důvod zániku) a písm. a) (ztráta podmínky), § 8 (bezúhonnost — pravomocné odsouzení), § 6 odst. 2.
- *Související předpisy:* § 160 TŘ (zahájení trestního stíhání); presumpce neviny (čl. 40 odst. 2 Listiny).
- *Judikatura:* obecné zásady k tomu, že pro bezúhonnost je rozhodné pravomocné odsouzení, nikoli probíhající stíhání; význam součinnostních povinností držitele.

**4. Subsumpce.** Zahájení trestního stíhání pro úmyslný čin samo o sobě bezúhonnost podle § 8 neruší (vyžaduje se pravomocné odsouzení). Avšak § 10 ukládá oznamovat rozhodné skutečnosti; je-li probíhající stíhání takovou skutečností dle nastavení oznamovací povinnosti, jejím nesplněním ve lhůtě nastává zánik platnosti oznámení podle § 9 odst. 3 písm. g) — bez ohledu na to, že odsouzení dosud nepadlo. Sporné je, zda konkrétní změna spadá pod oznamovací povinnost dle odst. 2.

**5. Řešení.** Rozhodným následkem zde není ztráta bezúhonnosti (ta nastane teprve pravomocným odsouzením — pak zánik dle písm. a), nýbrž porušení oznamovací povinnosti, vede-li k zániku podle § 9 odst. 3 písm. g). Odpovědná osoba po zjištění zajistí, aby držitel neměl přístup, a písemně jej vyrozumí (§ 9 odst. 4). Procesní kroky: vyhodnotit, zda šlo o oznamovanou skutečnost; doručit vyrozumění o zániku; vyžádat odevzdání oznámení (§ 9 odst. 6). Riziko: předčasné odepření přístupu jen pro zahájení stíhání bez opory v oznamovací povinnosti by mohlo být nepřiměřené (presumpce neviny).

**6. Varianty.** (a) Držitel by byl pravomocně odsouzen za úmyslný čin → zaniká bezúhonnost (§ 8) a platnost oznámení podle § 9 odst. 3 písm. a) bez ohledu na oznamovací povinnost. (b) Šlo by o pouhou změnu údaje v oznámení (např. příjmení) → lhůta je 30 dnů a zánik nastává podle § 9 odst. 3 písm. j), nikoli g).

#### G. Protiargumenty a rizika

- *Protiargument 1:* „Zahájení stíhání automaticky ruší bezúhonnost, takže oznámení padá ihned." Neutralizace: § 8 váže ztrátu bezúhonnosti na pravomocné odsouzení; do té doby platí presumpce neviny — zánik může nastat jen z titulu porušení oznamovací povinnosti (písm. g), ne ztráty bezúhonnosti (písm. a).
- *Protiargument 2:* „Držitel nic porušit nemohl, dokud nebyl odsouzen." Neutralizace: oznamovací povinnost (§ 10 odst. 2) je samostatná a předchází odsouzení; její smysl je umožnit vydavateli včasnou reverifikaci, proto její nesplnění sankcionuje § 9 odst. 3 písm. g).
- *Slabé místo:* rozsah oznamovaných skutečností závisí na přesném znění odst. 2 a na tom, zda probíhající stíhání pod něj spadá; bez jasného zařazení je závěr o zániku podle písm. g) sporný.

#### H. Praktický závěr

§ 10 zakládá trvalé plnění podmínek a aktivní oznamovací povinnost držitele (15 dnů, resp. 30 dnů u změny údaje), jejíž porušení je samostatným důvodem zániku oznámení (§ 9 odst. 3 písm. g). V praxi je nutné odlišovat zánik pro ztrátu podmínky (pravomocné odsouzení) od zániku pro porušení oznamovací povinnosti a respektovat presumpci neviny.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Plní držitel podmínky svéprávnosti a bezúhonnosti i nadále?
- [ ] Nastala skutečnost podléhající oznamovací povinnosti podle § 10 odst. 2?
- [ ] Byla oznámena ve lhůtě 15 dnů (30 dnů u změny údaje)?
- [ ] Jde o zánik pro ztrátu podmínky (§ 9 odst. 3 písm. a), nebo pro porušení oznamovací povinnosti (písm. g)?
- [ ] Byl proveden procedurální následek zániku (vyrozumění, odevzdání)?

**Typicky rozhodné důkazy / podklady:** evidence oznámení a poučení, doklad o rozhodné skutečnosti (např. usnesení o zahájení stíhání, pravomocný rozsudek), doklad o (ne)splnění oznamovací povinnosti a jejích lhůtách, vyrozumění o zániku.

---


<!-- LEGAL-REVISION:BEGIN id=5514084fc49f6a08b15c generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 10

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Podmínky uvedené v § 6 odst. 2 písm. a) a c) musí fyzická osoba, která je držitelem oznámení, splňovat po celou dobu přístupu k utajované informaci stupně utajení Vyhrazené.
>
> (2) Fyzická osoba podle odstavce 1 je povinna
>
> - a) písemně sdělovat tomu, kdo vydal oznámení,
>
> - 1. změnu týkající se podmínek uvedených v § 6 odst. 2 písm. a) a c),
>
> - 2. odcizení, ztrátu nebo poškození oznámení,
>
> - 3. den doručení osvědčení fyzické osoby nebo dokladu,
>
> - 4. skutečnosti uvedené v § 9 odst. 3 písm. c), f) a j),
>
> a to ve lhůtě 15 dnů ode dne, kdy tato změna nebo skutečnost nastala, nebo se o ní fyzická osoba dozvěděla, a v případě zániku platnosti oznámení podle § 9 odst. 3 písm. j) do 30 dnů,
>
> - b) v případech podle § 9 odst. 2 předložit ve stanovené lhůtě na žádost toho, kdo vydal oznámení,
>
> - 1. výpis z evidence Rejstříku trestů11), v případě cizince i obdobný doklad státu, jehož je cizinec státním příslušníkem, jakož i státu, v němž cizinec pobýval nepřetržitě po dobu delší než 6 měsíců v posledních 5 letech, anebo výpisem z evidence Rejstříku trestů s přílohou obsahující informace, které jsou zapsané v evidenci trestů takového státu; v případě, že cizí stát doklad obdobný výpisu z rejstříku trestů nevydává, čestné prohlášení, a
>
> - 2. prohlášení fyzické osoby o svéprávnosti;
>
> tyto doklady nesmějí být starší než 3 měsíce.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 6, § 9

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=5514084fc49f6a08b15c -->

### Podmínky přístupu k Přísně tajné, Tajné nebo Důvěrné informaci (§§ 11–14)

### § 11 — Osvědčení fyzické osoby a poučení

> **§ 11**
>
> *(1) Fyzické osobě lze umožnit přístup k utajované informaci stupně utajení Přísně tajné, Tajné nebo Důvěrné, jestliže jej nezbytně potřebuje k výkonu své funkce, pracovní nebo jiné činnosti, je držitelem platného osvědčení fyzické osoby (§ 54) příslušného stupně utajení a je poučena, nestanoví-li tento zákon nebo zvláštní právní předpis jinak (§ 58 až 62).*
>
> *(2) Před prvním přístupem k utajované informaci stupně utajení Přísně tajné, Tajné nebo Důvěrné ten, kdo je vůči fyzické osobě v rámci služebního poměru nebo pracovněprávního, členského či obdobného vztahu osobou odpovědnou, zajistí její poučení. Jde-li o fyzickou osobu ve vztahu, vůči níž není odpovědná osoba podle věty první, zajistí poučení odpovědná osoba toho, kdo fyzické osobě přístup k utajované informaci umožní. Poučení podepisuje fyzická osoba a ten, kdo poučení provedl; jeden výtisk poučení jí předá, jeden výtisk uloží12) a kopii zašle Úřadu; kopii poučení lze Úřadu zaslat i elektronicky. Povinnost zaslání kopie poučení Úřadu se nevztahuje na zpravodajské služby v případech podle § 140 odst. 1 písm. a) a na Ministerstvo vnitra v případech podle § 141 odst 1.*
>
> *(3) Poučení ředitele Úřadu a ředitele Bezpečnostní informační služby provede předseda vlády, poučení ředitele Úřadu pro zahraniční styky a informace provede ministr vnitra a poučení ředitele Vojenského zpravodajství provede ministr obrany; pro podpis, předání a uložení výtisku poučení platí odstavec 2 obdobně.*
>
> *(4) V případě zániku platnosti osvědčení fyzické osoby (§ 56 odst. 1) nebo skončení služebního poměru nebo pracovněprávního, členského či obdobného vztahu, ve kterém byl fyzické osobě umožněn přístup k utajované informaci, se má za to, že fyzická osoba poučena není.*

**Výklad:**

**Judikatura (z místních zdrojů):**

- *NS* [21 Cdo 2558/2011](https://rozhodnuti.nsoud.cz/Judikatura/judikatura_ns.nsf/WebSearch/B8A26545967270EFC1257AC20055DDA8?openDocument) — 6. 11. 2012, kat. A
  > „Stav v době dání výpovědi z pracovního poměru je pro posouzení její platnosti rozhodující též, spočívá-li důvod výpovědi podle § 46 odst. 1 písm. e) zák. práce (ve znění účinném do 31. 12. 2006)* v nesplňování předpokladů stanovených předpisy o ochraně utajovaných informací a o bezpečnostní způsobilosti z hlediska platnosti posuzované výpovědi nejsou zásadně významné okolnosti (výsledek bezpečností prověrky), které nastaly později"

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

#### F. Kazuistika

**1. Modelová situace.** Zaměstnanci orgánu státu, který pracoval s informacemi stupně Tajné na základě osvědčení FO, Úřad zahájí řízení o zrušení platnosti osvědčení. Zaměstnavatel dá zaměstnanci výpověď pro nesplňování předpokladů (§ 46 odst. 1 písm. e), resp. obdobné ustanovení zákoníku práce) ještě dříve, než řízení skončí, a opírá ji o očekávaný negativní výsledek prověrky. Účastníci: zaměstnanec (držitel osvědčení), zaměstnavatel (orgán státu), Úřad (vede řízení o osvědčení). Důkazy: osvědčení FO a jeho stav v době výpovědi, doklad o zahájení a stavu řízení Úřadu, výpověď a její odůvodnění.

**2. Právní otázka.** Lze platnost výpovědi pro nesplňování předpokladů opřít o skutečnosti (výsledek prověrky), které nastaly až po dání výpovědi, jestliže v době výpovědi zaměstnanec ještě platné osvědčení měl?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 11 odst. 1 (přístup k D/T/PT jen s platným osvědčením FO + need-to-know + poučení), odst. 4 (fikce nepoučenosti při zániku osvědčení nebo skončení vztahu).
- *Související ustanovení téhož zákona:* § 54 (osvědčení FO), § 56 (zánik platnosti osvědčení), § 12–14 (podmínky a spolehlivost), § 11a (trvající mlčenlivost).
- *Související předpisy:* zákoník práce — výpovědní důvod nesplňování předpokladů stanovených předpisy o ochraně UI; čl. 40 odst. 2 Listiny (presumpce neviny analogicky k posouzení rozhodného stavu).
- *Judikatura:* rozsudek NS sp. zn. 21 Cdo 2558/2011 — pro platnost výpovědi pro nesplňování předpokladů je rozhodný stav v době dání výpovědi; okolnosti (výsledek prověrky), které nastaly později, zásadně nejsou významné.

**4. Subsumpce.** V době dání výpovědi měl zaměstnanec platné osvědčení (řízení o jeho zrušení teprve probíhalo) → předpoklad pro přístup k UI byl formálně splněn. Pozdější (očekávaný) negativní výsledek prověrky nastal až po výpovědi → podle NS 21 Cdo 2558/2011 je pro platnost výpovědi nevýznamný. Sporné může být jen to, zda už v době výpovědi existoval jiný, samostatně postačující důvod nesplňování předpokladů.

**5. Řešení.** Výpověď opřená o budoucí výsledek prověrky je neplatná, trvalo-li v době jejího dání platné osvědčení; zaměstnavatel měl vyčkat pravomocného zrušení osvědčení. Procesní kroky pro zaměstnavatele: dát výpověď až po zániku platnosti osvědčení (§ 56), nebo doložit jiný v té době existující důvod. Riziko: předčasná výpověď vede k její neplatnosti a nárokům zaměstnance (náhrada mzdy). Pro přístup k UI ovšem platí, že po zániku osvědčení nastupuje fikce nepoučenosti (odst. 4) a přístup musí být fakticky znemožněn.

**6. Varianty.** (a) Osvědčení by v době výpovědi již bylo pravomocně zrušeno → předpoklad odpadl k tomuto okamžiku a výpověď by obstála. (b) Zaměstnanec by nepotřeboval UI k výkonu práce (odpadl by need-to-know) → samotný zánik osvědčení by nemusel zakládat nesplňování předpokladů pro danou pozici.

#### G. Protiargumenty a rizika

- *Protiargument 1:* „Jakmile je zahájeno řízení o zrušení osvědčení, zaměstnanec již předpoklady nesplňuje." Neutralizace: zahájení řízení není zánikem osvědčení; do pravomocného zrušení osvědčení platí a předpoklad je splněn (NS 21 Cdo 2558/2011).
- *Protiargument 2:* „Bezpečnostní zájem převažuje, proto lze výpověď dát preventivně." Neutralizace: bezpečnostní zájem se chrání faktickým odepřením přístupu k UI (fikce nepoučenosti, odnětí need-to-know), nikoli neplatnou výpovědí opřenou o budoucí skutečnost.
- *Slabé místo:* odlišení „přístupu k UI" (veřejnoprávní rovina) od „trvání pracovního poměru" (pracovněprávní rovina) bývá smíšeno; zánik osvědčení nemusí automaticky znamenat výpovědní důvod, není-li UI pro danou pozici nezbytná.

#### H. Praktický závěr

§ 11 zavádí pro tři vyšší stupně kvalitativně přísnější režim — osvědčení FO vydávané výlučně Úřadem po bezpečnostním řízení — a fikci nepoučenosti při zániku osvědčení či skončení vztahu. V praxi je nutné oddělovat veřejnoprávní zánik oprávnění od pracovněprávních důsledků a vázat je na rozhodný okamžik (pravomocné zrušení osvědčení).

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Má FO platné osvědčení odpovídajícího stupně (§ 54)?
- [ ] Je dán need-to-know a provedeno poučení (s kopií Úřadu — odst. 2)?
- [ ] Jaký je rozhodný okamžik (stav osvědčení v době relevantního úkonu)?
- [ ] Nastala fikce nepoučenosti zánikem osvědčení nebo skončením vztahu (odst. 4)?
- [ ] U vedoucích představitelů: poučil je správný činitel (odst. 3)?

**Typicky rozhodné důkazy / podklady:** osvědčení FO a doklad o jeho platnosti/zániku, podepsané poučení a doklad o zaslání kopie Úřadu, doklad o stavu řízení o osvědčení, pracovněprávní dokumentace (výpověď a její odůvodnění).

---


<!-- LEGAL-REVISION:BEGIN id=c450952a853d4460ff08 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 11

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Fyzické osobě lze umožnit přístup k utajované informaci stupně utajení Přísně tajné, Tajné nebo Důvěrné, jestliže jej nezbytně potřebuje k výkonu své funkce, pracovní nebo jiné činnosti, je držitelem platného osvědčení fyzické osoby ([[#§ 54|§ 54]]) příslušného stupně utajení a je poučena, nestanoví-li tento zákon nebo zvláštní právní předpis jinak (§ 58 až 62).
>
> (2) Před prvním přístupem k utajované informaci stupně utajení Přísně tajné, Tajné nebo Důvěrné ten, kdo je vůči fyzické osobě v rámci služebního poměru nebo pracovněprávního, členského či obdobného vztahu osobou odpovědnou, zajistí její poučení. Jde-li o fyzickou osobu ve vztahu, vůči níž není odpovědná osoba podle věty první, zajistí poučení odpovědná osoba toho, kdo fyzické osobě přístup k utajované informaci umožní. Poučení podepisuje fyzická osoba a ten, kdo poučení provedl; jeden výtisk poučení jí předá, jeden výtisk uloží12) a kopii zašle Úřadu; kopii poučení lze Úřadu zaslat i elektronicky. Povinnost zaslání kopie poučení Úřadu se nevztahuje na zpravodajské služby v případech podle § 140 odst. 1 písm. a) a na Ministerstvo vnitra v případech podle [[#§ 141|§ 141]] odst 1.
>
> (3) Poučení ředitele Úřadu a ředitele Bezpečnostní informační služby provede předseda vlády, poučení ředitele Úřadu pro zahraniční styky a informace provede ministr vnitra a poučení ředitele Vojenského zpravodajství provede ministr obrany; pro podpis, předání a uložení výtisku poučení platí odstavec 2 obdobně.
>
> (4) V případě zániku platnosti osvědčení fyzické osoby (§ 56 odst. 1) nebo skončení služebního poměru nebo pracovněprávního, členského či obdobného vztahu, ve kterém byl fyzické osobě umožněn přístup k utajované informaci, se má za to, že fyzická osoba poučena není.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 54, § 58, § 140, § 141, § 56

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=c450952a853d4460ff08 -->

### § 11a — Trvající povinnost mlčenlivosti

> **§ 11a**
>
> *V případě skončení služebního poměru nebo pracovněprávního, členského či obdobného vztahu nebo při změně služebního úřadu, ve kterém byl fyzické osobě umožněn přístup k utajovaným informacím, je tato osoba povinna písemně potvrdit, že si je vědoma povinnosti zachovávat mlčenlivost o utajovaných informacích, ke kterým měla přístup, a neumožnit k nim přístup neoprávněné osobě. Odpovědná osoba je povinna zajistit provedení tohoto úkonu.*

**Výklad:**

Klíčová **doživotní (resp. trvající) povinnost mlčenlivosti** — povinnost neskončí spolu se vztahem, jenž byl důvodem přístupu. FO je při ukončení vztahu povinna **písemně potvrdit** své vědomí o této povinnosti; provedení úkonu zajišťuje odpovědná osoba. Porušení této povinnosti zakládá:
- správní odpovědnost podle Části páté ZOÚI (přestupky a správní delikty — § 148 a násl.),
- v kvalifikovaných případech trestní odpovědnost podle § 316 nebo § 317 TZ.

Mlčenlivost trvá tak dlouho, dokud trvá stupeň utajení informace; zrušením stupně utajení podle § 22 odst. 4 (např. odtajnění historických spisů) zaniká i povinnost mlčenlivosti.

#### F. Kazuistika

**1. Modelová situace.** Bývalý analytik orgánu státu, který měl po léta přístup k informacím stupně Tajné, odejde do soukromé sféry. Při skončení služebního poměru odmítne podepsat potvrzení o vědomí trvající mlčenlivosti s tím, že „už pro stát nepracuje". Po dvou letech v médiích popíše dříve utajovanou metodu práce zpravodajské služby, která je stále klasifikovaná. Účastníci: bývalý analytik, odpovědná osoba (měla zajistit úkon), poškozený původce informace. Důkazy: záznam o (ne)podepsání potvrzení, doklad o trvajícím stupni utajení sdělené informace, obsah mediálního výstupu.

**2. Právní otázka.** Trvá povinnost mlčenlivosti i po skončení vztahu a bez ohledu na (ne)podepsání potvrzení, a jaké jsou následky jejího porušení?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 11a — trvající povinnost mlčenlivosti po skončení/změně vztahu; povinnost FO písemně potvrdit vědomí povinnosti; povinnost odpovědné osoby zajistit úkon.
- *Související ustanovení téhož zákona:* § 22 odst. 4 (zrušení stupně utajení → zánik mlčenlivosti), § 2 písm. a) (utajovaná informace), § 148 a násl. (přestupky/správní delikty).
- *Související předpisy:* § 316 TZ (vyzvědačství), § 317 TZ (ohrožení utajované informace) — trestněprávní rovina porušení.
- *Judikatura:* obecné zásady, že potvrzení podle § 11a je deklaratorní (povinnost mlčenlivosti plyne přímo ze zákona, nikoli z podpisu); přiměřeně judikatura k trvání povinnosti mlčenlivosti i po skončení funkce.

**4. Subsumpce.** Povinnost mlčenlivosti vzniká ze zákona a trvá tak dlouho, dokud trvá stupeň utajení informace; není závislá na podpisu potvrzení (ten má jen důkazní/upomínací funkci). Skončení vztahu povinnost neukončuje. Sdělená metoda byla stále klasifikovaná → porušení povinnosti mlčenlivosti je dáno. (Ne)podepsání potvrzení nemá na existenci povinnosti vliv; odpovědná osoba však porušila povinnost úkon zajistit.

**5. Řešení.** Bývalý analytik porušil trvající povinnost mlčenlivosti; odpovídá správně (§ 148 a násl.) a při naplnění znaků i trestněprávně (§ 316/317 TZ). Odmítnutí podpisu jej nezbavuje povinnosti — naopak by mohlo svědčit o vědomém postoji. Procesní kroky: prošetření úniku, posouzení trvání stupně utajení k okamžiku sdělení, oznámení podezření orgánům činným v trestním řízení. Riziko: pokud byla informace mezitím odtajněna (§ 22 odst. 4), povinnost mlčenlivosti zanikla a odpovědnost odpadá.

**6. Varianty.** (a) Informace byla před mediálním výstupem řádně odtajněna → mlčenlivost zanikla, jednání není postižitelné. (b) Analytik by potvrzení podepsal, ale informaci přesto vyzradil → existence i porušení povinnosti jsou stejné; podpis jen usnadní dokazování jeho vědomí.

#### G. Protiargumenty a rizika

- *Protiargument 1:* „Bez podpisu potvrzení mlčenlivost nevznikla." Neutralizace: § 11a stanoví povinnost potvrdit vědomí povinnosti, nikoli povinnost konstituovat; mlčenlivost plyne ze zákona a trvá nezávisle na podpisu.
- *Protiargument 2:* „Po skončení poměru už bývalý zaměstnanec není vázán." Neutralizace: povinnost je koncipována jako trvající (přežívá vztah) a váže se na trvání stupně utajení informace, nikoli na trvání pracovního/služebního poměru.
- *Slabé místo:* prokázání, že informace byla v době sdělení stále klasifikovaná (a nebyla odtajněna), nese ten, kdo porušení tvrdí; bez dokladu o trvání stupně utajení je odpovědnost obtížně udržitelná.

#### H. Praktický závěr

§ 11a zakládá trvající (de facto časově neomezenou, dokud trvá utajení) povinnost mlčenlivosti, nezávislou na podpisu potvrzení; podpis má jen důkazní a připomínací funkci. V praxi je nutné zajistit úkon při každém skončení/změně vztahu a u úniků nejprve ověřit, zda informace v rozhodné době stále byla utajovaná.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Byl při skončení/změně vztahu zajištěn úkon potvrzení vědomí mlčenlivosti?
- [ ] Trvá u dotčené informace stupeň utajení, nebo byla odtajněna (§ 22 odst. 4)?
- [ ] Došlo ke sdělení/zpřístupnění UI neoprávněné osobě?
- [ ] Naplňuje jednání znaky správního deliktu (§ 148 a násl.) či trestného činu (§ 316/317 TZ)?

**Typicky rozhodné důkazy / podklady:** podepsané (či záznam o nepodepsaném) potvrzení podle § 11a, doklad o trvání stupně utajení informace v rozhodné době, obsah sdělení/výstupu, evidence přístupů dotčené osoby.

---


<!-- LEGAL-REVISION:BEGIN id=f6320b60c11d7b714800 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 11a

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> V případě skončení služebního poměru nebo pracovněprávního, členského či obdobného vztahu nebo při změně služebního úřadu, ve kterém byl fyzické osobě umožněn přístup k utajovaným informacím, je tato osoba povinna písemně potvrdit, že si je vědoma povinnosti zachovávat mlčenlivost o utajovaných informacích, ke kterým měla přístup, a neumožnit k nim přístup neoprávněné osobě. Odpovědná osoba je povinna zajistit provedení tohoto úkonu.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Místní znění neobsahuje výslovný vnitřní odkaz.

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=f6320b60c11d7b714800 -->

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

**Judikatura (z místních zdrojů):**

- *ÚS* [II.ÚS 2893/14](https://nalus.usoud.cz/Search/GetText.aspx?sz=2-2893-14_1) — usnesení, 16. 12. 2014
  > „Jejich zjištění o existenci bezpečnostního rizika pro zájem České republiky, za které lze považovat chování stěžovatele, mající vliv na důvěryhodnost nebo ovlivnitelnost jeho osoby ve vztahu k utajovaným informacím a jež bylo vyhodnoceno tak, že stěžovatel přestal splňovat podmínku § 12 odst. 1 písm. d) zákona č. 412/2005 Sb., nutnou pro udělení osvědčení Národního bezpečnostního úřadu … oproti zájmům stěžovatele coby osoby, o níž existují důvodné pochybnosti, zda je bezpečnostně spolehlivou osobou, stojí veřejný zájem na tom, aby nedošlo k ohrožení či vážnému narušení činnosti zpravodajských služeb nebo policie"

#### Čtyři kumulativní podmínky — pětistupňový test

Pro osvědčení FO (D/T/PT) zákon klade **čtyři kumulativní podmínky**:

1. **Státní občanství ČR / EU / NATO** — zákon č. 412/2005 Sb. tradičně omezuje ochranu UI na občany ČR, ale s ohledem na členství v EU a NATO byla podmínka rozšířena. **Cizí mocnost mimo NATO/EU** (typicky občané USA, jež nejsou v EU ani NATO současně, byť USA jsou v NATO; nebo občané třetích zemí) jsou z přístupu **zcela vyloučeni**, ovšem cizí moc může požadovat speciální osvědčení pro přístup k její vlastní informaci (§ 57 — viz dále).
2. **Svéprávnost a věk 18+** (převzato z § 6).
3. **Bezpečnostní spolehlivost** (§ 14) — nepřítomnost bezpečnostního rizika.
4. **Bezúhonnost** (§ 13) — širší než pro Vyhrazené.

Trvání podmínek je vyžadováno po celou dobu platnosti osvědčení (odst. 2). Při ztrátě jakékoliv z nich Úřad zahájí řízení o zrušení platnosti osvědčení (§ 101 a násl., zejm. § 123).

#### F. Kazuistika

**1. Modelová situace.** O osvědčení FO pro stupeň Tajné žádá uchazeč o místo u zpravodajské služby. Je svéprávný, 40 let, bezúhonný a je státním občanem ČR. V průběhu bezpečnostního řízení však Úřad zjistí opakované intenzivní styky uchazeče s osobou napojenou na zájmy cizí moci a jeho zatajované hazardní dluhy. Úřad osvědčení nevydá pro nesplnění podmínky bezpečnostní spolehlivosti. Účastníci: uchazeč (žadatel), Úřad (orgán bezpečnostního řízení). Důkazy: doklady o občanství a bezúhonnosti, zjištění o stycích a dluzích, vyjádření uchazeče.

**2. Právní otázka.** Lze osvědčení nevydat, splňuje-li uchazeč podmínky občanství, věku a bezúhonnosti, avšak je zjištěno bezpečnostní riziko ohrožující jeho důvěryhodnost a ovlivnitelnost?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 12 odst. 1 — čtyři kumulativní podmínky osvědčení FO: písm. a) občanství ČR/EU/NATO, písm. b) svéprávnost a věk (odkaz na § 6 odst. 2), písm. c) bezpečnostní spolehlivost, písm. d) bezúhonnost (§ 13).
- *Související ustanovení téhož zákona:* § 14 (bezpečnostní riziko a spolehlivost), § 13 (bezúhonnost), § 54 (osvědčení FO), § 101 a násl. (řízení, zrušení platnosti).
- *Související předpisy:* SŘS (správní soudnictví — přezkum), zákon č. 153/1994 Sb. (zpravodajské služby — zvláštní oprávnění).
- *Judikatura:* usnesení ÚS sp. zn. II.ÚS 2893/14 — existence bezpečnostního rizika ovlivňujícího důvěryhodnost a ovlivnitelnost osoby může vést k závěru, že přestala splňovat podmínku § 12 odst. 1, přičemž veřejný zájem na ochraně činnosti zpravodajských služeb převažuje nad zájmem osoby, o jejíž spolehlivosti jsou důvodné pochybnosti.

**4. Subsumpce.** Podmínky písm. a), b) a d) jsou splněny. Podmínka písm. c) (bezpečnostní spolehlivost) však splněna není — zjištěné styky a skrývané dluhy zakládají bezpečnostní riziko podle § 14 odst. 3 (negativní vliv na důvěryhodnost a ovlivnitelnost; styky s rizikovou osobou). Protože podmínky jsou kumulativní, nesplnění jediné z nich (písm. c) brání vydání osvědčení. Sporné je posouzení intenzity a aktuálnosti rizika (§ 14 odst. 5).

**5. Řešení.** Úřad osvědčení nevydá — kumulativnost podmínek znamená, že bezvadné splnění občanství, věku a bezúhonnosti nepostačí, je-li dáno bezpečnostní riziko. Rozhodnutí musí být odůvodněné, proporční a opřené o konkrétní zjištění (nikoli paušální). Procesní kroky: provedení dokazování, umožnění vyjádření, řádné odůvodnění. Riziko: nedostatečně odůvodněné rozhodnutí je v správním soudnictví zrušitelné; naopak řádně doložené riziko obstojí i v ústavní rovině (II.ÚS 2893/14).

**6. Varianty.** (a) Zjištěné styky by byly ojedinělé a dávné, dnes bez vlivu na ovlivnitelnost → při komplexním posouzení (§ 14 odst. 5) by riziko nemuselo dosáhnout intenzity bránící vydání. (b) Uchazeč by byl státním příslušníkem třetí země mimo EU/NATO → nesplnil by již podmínku písm. a) a osvědčení by nešlo vydat bez ohledu na spolehlivost.

#### G. Protiargumenty a rizika

- *Protiargument 1:* „Splnění objektivních podmínek (občanství, věk, bezúhonnost) zakládá nárok na osvědčení." Neutralizace: podmínky jsou kumulativní; bezpečnostní spolehlivost (písm. c) je samostatná a její nesplnění brání vydání bez ohledu na ostatní (II.ÚS 2893/14).
- *Protiargument 2:* „Bez pravomocného odsouzení nelze dovozovat nespolehlivost." Neutralizace: bezpečnostní riziko (§ 14) je širší než trestní bezúhonnost a nevyžaduje odsouzení; postačí důvodné, prokázané pochybnosti o důvěryhodnosti a ovlivnitelnosti.
- *Slabé místo:* mnohá zjištění pocházejí z utajovaných podkladů, do nichž žadatel nemá plný přístup; tím je oslabena jeho obrana a o to vyšší jsou nároky na odůvodněnost a soudní přezkoumatelnost rozhodnutí.

#### H. Praktický závěr

§ 12 stanoví čtyři kumulativní podmínky osvědčení FO, mezi nimiž je klíčová a nejcitlivější bezpečnostní spolehlivost (§ 14). V praxi nestačí splnit objektivní podmínky — rozhoduje komplexní a doložené posouzení rizik; rozhodnutí Úřadu musí být proporční a plně přezkoumatelné.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Je žadatel státním občanem ČR / EU / NATO (písm. a)?
- [ ] Je svéprávný a starší 18 let (písm. b ve spojení s § 6 odst. 2)?
- [ ] Je bezpečnostně spolehlivý — bez rizika podle § 14 (písm. c)?
- [ ] Je bezúhonný podle § 13 (písm. d)?
- [ ] Je případné rozhodnutí o nevydání odůvodněné, proporční a soudně přezkoumatelné?

**Typicky rozhodné důkazy / podklady:** doklad o státním občanství, OP/pas (věk), prohlášení o svéprávnosti, opis z RT (§ 13), bezpečnostní dotazníky a zjištění k riziku (§ 14), vyjádření žadatele.

---


<!-- LEGAL-REVISION:BEGIN id=cb1c787f4e397bc53119 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 12 — Podmínky pro vydání osvědčení fyzické osoby

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Osvědčení fyzické osoby Úřad vydá fyzické osobě, která
>
> - a) je státním občanem České republiky nebo státním příslušníkem členského státu Evropské unie nebo Organizace Severoatlantické smlouvy,
>
> - b) splňuje podmínky uvedené v § 6 odst. 2 písm. a) a b),
>
> - c) je bezpečnostně spolehlivá a
>
> - d) je bezúhonná podle [[#§ 13|§ 13]].
>
> (2) Podmínky uvedené v odstavci 1 musí fyzická osoba splňovat po celou dobu platnosti osvědčení fyzické osoby ([[#§ 55|§ 55]]).

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 6, § 13, § 55

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=cb1c787f4e397bc53119 -->

### § 13 — Bezúhonnost pro osvědčení FO

> **§ 13 odst. 1**
>
> *Podmínku bezúhonnosti pro účely vydání osvědčení fyzické osoby splňuje fyzická osoba, která nebyla pravomocně odsouzena za spáchání úmyslného trestného činu nebo trestného činu vztahujícího se k ochraně utajovaných informací, nebo se na ni hledí, jako by odsouzena nebyla. Jestliže trestní stíhání pro takový trestný čin bylo podmíněně zastaveno nebo bylo podmíněně odloženo podání návrhu na potrestání, je podmínka bezúhonnosti splněna až poté, co se fyzická osoba osvědčila podle jiného právního předpisu. V případě rozhodnutí o schválení narovnání v trestním řízení o úmyslném trestném činu je podmínka bezúhonnosti splněna, pokud od právní moci takového rozhodnutí uplynula doba alespoň 5 let.*

**Výklad:**

**Judikatura (z místních zdrojů):**

- *NSS* [2 As 83/2008 - 124](https://vyhledavac.nssoud.cz/DokumentOriginal/Text/614839) — 25. 3. 2009
  > „Co se rozumí osobnostní způsobilostí je stanoveno v § 13 zákona č. 412/2005 Sb., jehož odst. 1 uvádí, že „podmínku osobnostní způsobilosti splňuje fyzická osoba, která netrpí poruchou či obtížemi, které mohou mít vliv na její spolehlivost nebo schopnost utajovat informace“"

#### Rozšíření o podmíněné zastavení a narovnání

Oproti § 8 (bezúhonnost pro oznámení) zákon rozlišuje tři speciální procesní situace, jež bezúhonnost dočasně narušují:
- **podmíněné zastavení trestního stíhání** (§ 307 TŘ) — bezúhonnost se obnovuje, až se FO osvědčí (po uplynutí zkušební doby — § 308 TŘ),
- **podmíněné odložení návrhu na potrestání** (§ 179g TŘ),
- **schválení narovnání** (§ 309–314 TŘ) — bezúhonnost se obnovuje **až po 5 letech** od právní moci.

Bezúhonnost se ověřuje **opisem z RT** (nikoli pouze výpisem) — tj. včetně všech zahlazených odsouzení (§ 22 odst. 4 zákona o RT) — a u cizinců obdobnými doklady.

#### F. Kazuistika

**1. Modelová situace.** Žadatel o osvědčení FO byl před dvěma lety stíhán pro úmyslný trestný čin; trestní stíhání bylo podmíněně zastaveno (§ 307 TŘ) a zkušební doba dosud běží. Ve výpisu z RT nemá záznam o odsouzení. Tvrdí, že je tedy bezúhonný. Účastníci: žadatel, Úřad. Důkazy: opis z RT, rozhodnutí o podmíněném zastavení stíhání, doklad o (ne)uplynutí zkušební doby a osvědčení se.

**2. Právní otázka.** Splňuje žadatel podmínku bezúhonnosti podle § 13, bylo-li jeho trestní stíhání pro úmyslný čin podmíněně zastaveno a zkušební doba ještě neuplynula?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 13 odst. 1 — bezúhonnost je vyloučena odsouzením za úmyslný čin či čin vztahující se k UI; při podmíněném zastavení/odložení je splněna až po osvědčení se; u narovnání až po 5 letech od právní moci.
- *Související ustanovení téhož zákona:* § 8 (užší bezúhonnost pro oznámení — srovnání), § 12 odst. 1 písm. d) (bezúhonnost jako podmínka osvědčení), § 14 (spolehlivost).
- *Související předpisy:* § 307–308 TŘ (podmíněné zastavení a osvědčení se), § 179g TŘ (podmíněné odložení návrhu), § 309–314 TŘ (narovnání); § 22 odst. 4 zákona o RT (opis vč. zahlazených odsouzení).
- *Judikatura:* judikatura k tomu, že pro účely osvědčení se bezúhonnost prokazuje opisem (nikoli výpisem) z RT a posuzuje se i s ohledem na probíhající zkušební dobu; rozhodnutí NSS k širšímu pojetí osobnostní/bezpečnostní způsobilosti (sp. zn. 2 As 83/2008).

**4. Subsumpce.** Trestní stíhání pro úmyslný čin bylo podmíněně zastaveno → podle § 13 odst. 1 věty druhé je bezúhonnost splněna teprve poté, co se žadatel osvědčil. Zkušební doba dosud běží → žadatel se zatím neosvědčil → podmínka bezúhonnosti není (zatím) splněna. Absence záznamu ve výpisu z RT je nerozhodná, neboť se posuzuje opis a samotný procesní stav. Sporné může být jen běh/skončení zkušební doby.

**5. Řešení.** Po dobu běhu zkušební doby žadatel nesplňuje bezúhonnost podle § 13; osvědčení nelze vydat (kumulativní podmínka § 12 odst. 1 písm. d). Po úspěšném osvědčení se (rozhodnutí podle § 308 TŘ) podmínka bude splněna. Procesní kroky: vyžádat opis z RT a rozhodnutí o (ne)osvědčení; případně řízení přerušit/zamítnout. Riziko: vydání osvědčení v běhu zkušební doby by bylo v rozporu s § 13 a důvodem k pozdějšímu zrušení.

**6. Varianty.** (a) Šlo by o schválené narovnání pro úmyslný čin → bezúhonnost je splněna až po 5 letech od právní moci rozhodnutí. (b) Trestní stíhání by se týkalo nedbalostního činu nevztahujícího se k UI → bezúhonnost by nebyla dotčena vůbec (mimo výčet § 13 odst. 1).

#### G. Protiargumenty a rizika

- *Protiargument 1:* „Čistý výpis z RT prokazuje bezúhonnost." Neutralizace: pro osvědčení se posuzuje opis z RT a procesní stavy (podmíněné zastavení, odložení, narovnání); čistý výpis nevylučuje překážku podle § 13 odst. 1 věty druhé a třetí.
- *Protiargument 2:* „Podmíněné zastavení znamená, že se na osobu hledí jako na netrestanou ihned." Neutralizace: § 13 výslovně odkládá splnění bezúhonnosti až na okamžik osvědčení se, resp. uplynutí 5 let u narovnání; do té doby podmínka splněna není.
- *Slabé místo:* informace o stavu zkušební doby a o (ne)osvědčení se nemusí být z RT zřejmá; je nutné si vyžádat příslušná trestní rozhodnutí, jinak je posouzení neúplné.

#### H. Praktický závěr

§ 13 rozšiřuje bezúhonnost oproti § 8 o tři procesní situace (podmíněné zastavení, odložení návrhu, narovnání) a posouvá splnění podmínky do budoucna; prokazuje se opisem z RT. V praxi je nutné u žadatelů o osvědčení vždy zkoumat i probíhající nebo odklonem ukončená trestní řízení, nejen pravomocná odsouzení.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Je k dispozici opis z RT (nikoli jen výpis)?
- [ ] Nebyl žadatel odsouzen za úmyslný čin nebo čin vztahující se k UI?
- [ ] Neprobíhá podmíněné zastavení/odložení — osvědčil se již žadatel?
- [ ] Nejde o narovnání, u nějž neuplynulo 5 let od právní moci?
- [ ] U cizince: jsou doloženy obdobné zahraniční doklady?

**Typicky rozhodné důkazy / podklady:** opis z RT, rozhodnutí o podmíněném zastavení/odložení/narovnání a doklad o (ne)osvědčení se či o uplynutí 5 let, zahraniční doklady o bezúhonnosti u cizinců.

---


<!-- LEGAL-REVISION:BEGIN id=773b7a906dd1944dc65f generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 13 — Bezúhonnost pro účely vydání osvědčení fyzické osoby

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Podmínku bezúhonnosti pro účely vydání osvědčení fyzické osoby splňuje fyzická osoba, která nebyla pravomocně odsouzena za spáchání úmyslného trestného činu nebo trestného činu vztahujícího se k ochraně utajovaných informací, nebo se na ni hledí, jako by odsouzena nebyla. Jestliže trestní stíhání pro takový trestný čin bylo podmíněně zastaveno nebo bylo podmíněně odloženo podání návrhu na potrestání, je podmínka bezúhonnosti splněna až poté, co se fyzická osoba osvědčila podle jiného právního předpisu57). V případě rozhodnutí o schválení narovnání v trestním řízení o úmyslném trestném činu je podmínka bezúhonnosti splněna, pokud od právní moci takového rozhodnutí uplynula doba alespoň 5 let.
>
> (2) Podmínka bezúhonnosti se ověřuje opisem z evidence Rejstříku trestů11) a v případě cizince dokladem obdobným výpisu z evidence Rejstříku trestů státu, jehož je cizinec státním příslušníkem, jakož i státu, v němž cizinec pobýval po dosažení věku 15 let nepřetržitě po dobu delší než 6 měsíců, anebo výpisem z evidence Rejstříku trestů s přílohou obsahující informace, které jsou zapsané v evidenci trestů takového státu. V případě, že cizí stát doklad obdobný výpisu z rejstříku trestů nevydává, prokazuje se podmínka bezúhonnosti čestným prohlášením. Doklady k ověření bezúhonnosti nesmějí být starší než 3 měsíce.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Místní znění neobsahuje výslovný vnitřní odkaz.

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=773b7a906dd1944dc65f -->

### § 14 — Bezpečnostní spolehlivost

> **§ 14 odst. 1**
>
> *Podmínku bezpečnostní spolehlivosti splňuje fyzická osoba, u níž není zjištěno bezpečnostní riziko.*

**Výklad:**

**Judikatura (z místních zdrojů):**

- *NSS* [10 A 160/2015 - 137](https://vyhledavac.nssoud.cz/DokumentOriginal/Text/433905) — 1. 10. 2019
  > „Posuzování informační hodnoty určitého zjištění je nutně vždy úvahou pravděpodobnostní, založenou v určité míře na odhadu. Proto někdy pro závěr o existenci bezpečnostního rizika (§ 14 odst. 3 zákona č. 412/2005 Sb., o ochraně utajovaných informací a o bezpečnostní způsobilosti) postačí zjištění, že je pravděpodobné, že příslušná zákonem předvídaná skutková podstata byla naplněna. Může tomu tak být ovšem pouze v případě, že taková eventualita je nejpravděpodobnějším vysvětlením skutkových zjištění a že se na základě dostupných údajů jeví být významně pravděpodobnější než jiná v úvahu připadající vysvětlení"

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

#### F. Kazuistika

**1. Modelová situace.** Úřad v řízení o osvědčení FO pro stupeň Tajné získá ze zpravodajských zdrojů zjištění, že žadatel pravděpodobně dlouhodobě poskytuje informace osobě napojené na cizí zpravodajskou službu. Zjištění není stoprocentně prokázané, ale jeví se jako nejpravděpodobnější vysvětlení dostupných údajů. Žadatel vše popírá a tvrdí, že riziko musí být prokázáno „nade vši pochybnost". Účastníci: žadatel, Úřad (případně zpravodajská služba u svých příslušníků). Důkazy: zpravodajská zjištění, vyhodnocení jejich informační hodnoty, vyjádření žadatele.

**2. Právní otázka.** Jaký důkazní standard platí pro závěr o existenci bezpečnostního rizika podle § 14 — je nutné riziko prokázat jistotou, nebo postačí pravděpodobnostní úvaha?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 14 odst. 1 (spolehlivost = absence rizika), odst. 2 (tvrdá rizika — automatická nezpůsobilost), odst. 3 (měkká rizika — kontextuální posouzení), odst. 4 (časový rozsah ověřování), odst. 5 (komplexní posouzení), odst. 6 (fyziodetekční/psychologické/lékařské vyšetření).
- *Související ustanovení téhož zákona:* § 12 (podmínky osvědčení), § 2 písm. b) (zájem ČR — vztah k odst. 2 písm. a), § 107 odst. 4 (součinnost — odst. 2 písm. d), § 133 a násl. (přezkum).
- *Související předpisy:* § 65 a násl. SŘS (soudní přezkum); zákon č. 153/1994 Sb. (zpravodajské služby — odst. 6).
- *Judikatura:* rozsudek NSS sp. zn. 10 A 160/2015 — pro závěr o existenci bezpečnostního rizika (§ 14 odst. 3) postačí pravděpodobnostní úvaha; eventualita naplnění skutkové podstaty musí být nejpravděpodobnějším vysvětlením a významně pravděpodobnější než jiná v úvahu připadající vysvětlení.

**4. Subsumpce.** Zjištění o poskytování informací cizí službě spadá pod měkká rizika odst. 3 (styky s rizikovou osobou; negativní vliv na ovlivnitelnost), případně pod tvrdé riziko odst. 2 písm. a) (činnost proti zájmu ČR), je-li doloženo dostatečně. Důkazní standard není „nade vši pochybnost", nýbrž pravděpodobnostní (NSS 10 A 160/2015) — postačí, je-li riziková verze nejpravděpodobnějším a významně převažujícím vysvětlením. Sporné je, zda zjištění této míry pravděpodobnosti dosahuje.

**5. Řešení.** Úřad může uzavřít existenci bezpečnostního rizika i bez jistoty, je-li riziková verze významně nejpravděpodobnější; pak osvědčení nevydá (spolehlivost není dána — § 12 odst. 1 písm. c). Posouzení musí respektovat odst. 5 (rozsah, charakter, doba, vliv na schopnost utajovat) a být odůvodněné a proporční. Procesní kroky: vyhodnocení informační hodnoty zjištění, umožnění vyjádření, odůvodnění pravděpodobnostní úvahy. Riziko: paušální odkaz na „bezpečnostní riziko" bez konkretizace je v soudním přezkumu neudržitelný.

**6. Varianty.** (a) Zjištění by bylo jen jednou z více rovnocenných hypotéz → pravděpodobnostní standard NSS by nebyl naplněn a riziko by nebylo prokázáno. (b) Šlo by o příslušníka zpravodajské služby → ta může u svých příslušníků provést fyziodetekční vyšetření (odst. 6), které Úřad v běžném řízení použít nesmí.

#### G. Protiargumenty a rizika

- *Protiargument 1:* „Bezpečnostní riziko musí být prokázáno s jistotou jako v trestním řízení." Neutralizace: § 14 je preventivní a operuje s pravděpodobností; NSS 10 A 160/2015 připouští závěr, je-li riziková verze nejpravděpodobnějším a významně převažujícím vysvětlením.
- *Protiargument 2:* „Měkká rizika nemohou sama o sobě vést k nevydání osvědčení." Neutralizace: měkká rizika se sice posuzují v kontextu (odst. 5), avšak při dostatečné intenzitě a aktuálnosti k nevydání vést mohou; rozhodující je komplexní vyhodnocení.
- *Slabé místo:* opora rozhodnutí v utajovaných zpravodajských zdrojích omezuje kontradiktornost; soud sice přezkoumává i utajované podklady, ale obrana žadatele je fakticky ztížena, což zvyšuje nároky na odůvodnění.

#### H. Praktický závěr

§ 14 je dogmaticky nejcitlivějším ustanovením personální bezpečnosti — rozlišuje tvrdá (automatická) a měkká (kontextuální) rizika a umožňuje pravděpodobnostní závěr o nespolehlivosti. V praxi musí být každý závěr o riziku konkrétní, časově ukotvený (odst. 4), komplexně posouzený (odst. 5) a soudně přezkoumatelný.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Jde o tvrdé riziko (odst. 2 — automatická nezpůsobilost), nebo měkké (odst. 3)?
- [ ] Je dodržen časový rozsah ověřování podle stupně a typu rizika (odst. 4)?
- [ ] Bylo provedeno komplexní posouzení (rozsah, charakter, doba, vliv — odst. 5)?
- [ ] Dosahuje zjištění pravděpodobnostního standardu (nejpravděpodobnější a významně převažující verze)?
- [ ] Je rozhodnutí odůvodněné, proporční a přezkoumatelné, ne paušální?

**Typicky rozhodné důkazy / podklady:** bezpečnostní dotazníky, zpravodajská a lustrační zjištění s vyhodnocením informační hodnoty, majetkové podklady (odst. 2 písm. c), případně psychologické/lékařské vyšetření (odst. 3 písm. f, odst. 6), vyjádření žadatele.

---


<!-- LEGAL-REVISION:BEGIN id=1404bf83d1168107de00 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 14 — Bezpečnostní spolehlivost

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Podmínku bezpečnostní spolehlivosti splňuje fyzická osoba, u níž není zjištěno bezpečnostní riziko.
>
> (2) Bezpečnostním rizikem je
>
> - a) činnost proti zájmu České republiky,
>
> - b) činnost spočívající v potlačování základních práv a svobod, anebo podpora takové činnosti,
>
> - c) skutečnost, že jsou majetkové poměry zjevně nepřiměřené řádně přiznaným příjmům fyzické osoby, nebo
>
> - d) opakované neposkytnutí nezbytné součinnosti nebo neudělení souhlasu podle § 107 odst. 4 v probíhajícím řízení o zrušení platnosti osvědčení fyzické osoby, pokud bez poskytnutí součinnosti nelze ve věci rozhodnout.
>
> (3) Za bezpečnostní riziko lze též považovat
>
> - a) zařazení do složky bývalé Státní bezpečnosti s rozvědným nebo kontrarozvědným zaměřením, zpravodajské správy Generálního štábu Československé lidové armády nebo odboru vnitřní ochrany Sboru nápravné výchovy anebo prokazatelnou spolupráci s bývalou Státní bezpečností nebo zpravodajskou správou Generálního štábu Československé lidové armády nebo odborem vnitřní ochrany Sboru nápravné výchovy,
>
> - b) úmyslné porušení právních předpisů, na jehož základě může nastat újma zájmu České republiky,
>
> - c) chování, které má negativní vliv na důvěryhodnost nebo ovlivnitelnost fyzické osoby,
>
> - d) styky s osobou, která vyvíjí nebo vyvíjela činnost proti zájmu České republiky,
>
> - e) porušení podmínek přístupu k utajovaným informacím nebo jiné povinnosti při ochraně utajovaných informací, nebo
>
> - f) skutečnost, že fyzická osoba trpí takovou poruchou zdraví nebo se ve struktuře její osobnosti vyskytují takové charakteristiky, které mohou mít negativní vliv na její schopnost utajovat informace.
>
> (4) Bezpečnostní rizika uvedená v odstavci 2 písm. a) až c) a v odstavci 3 písm. a) se v řízení zjišťují za období od 15 let věku. Bezpečnostní riziko uvedené v odstavci 2 písm. d) se zjišťuje pouze v probíhajícím řízení o zrušení platnosti osvědčení fyzické osoby. Bezpečnostní rizika uvedená v odstavci 3 písm. b) až e) se zjišťují za období 10 let pro stupeň utajení Důvěrné, 15 let pro stupeň utajení Tajné a 20 let pro stupeň utajení Přísně tajné předcházejících dni zahájení řízení nebo za období od 15 let věku podle toho, které z nich je kratší.
>
> (5) Při posuzování, zda skutečnost uvedená v odstavci 3 je bezpečnostním rizikem, se přihlíží k tomu, do jaké míry může ovlivnit schopnost utajovat informace, k době jejího výskytu, k jejímu rozsahu, charakteru a k chování fyzické osoby v období uvedeném v odstavci 4.
>
> (6) Zpravodajská služba u svých příslušníků, zaměstnanců a uchazečů o přijetí do služebního poměru nebo základního pracovněprávního vztahu může při ověřování podmínky bezpečnostní spolehlivosti provést fyziodetekční vyšetření. Zpravodajská služba u svých příslušníků, zaměstnanců a uchazečů o přijetí do služebního poměru nebo základního pracovněprávního vztahu v případech podle § 140 odst. 1 písm. a) a Ministerstvo vnitra v případech podle § 141 odst. 1 může při zjišťování a posuzování skutečností podle odstavce 3 písm. f) provést psychologické nebo lékařské vyšetření odborným pracovištěm zpravodajské služby nebo Ministerstva vnitra.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 107, § 140, § 141

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=1404bf83d1168107de00 -->

### Hlava III — Průmyslová bezpečnost

### § 15 — Podmínky přístupu podnikatele k UI a formy přístupu

> **§ 15**
>
> *Přístup k utajované informaci lze umožnit podnikateli, který je fyzickou osobou s trvalým pobytem na území České republiky zapsanou do živnostenského rejstříku, obchodního rejstříku nebo jiné evidence vedené podle jiného zákona registrující osoby a provozuje podnikatelskou činnost nebo právnickou osobou se sídlem v České republice zapsanou v obchodním rejstříku, jejíž hlavní činností je podnikatelská činnost, jestliže jej nezbytně potřebuje k výkonu své činnosti, a pokud při přístupu k utajované informaci*
>
> *- a) stupně utajení Vyhrazené*
>
> *- 1. doloží písemným prohlášením svou schopnost zabezpečit ochranu utajovaných informací (dále jen „prohlášení podnikatele“), nebo*
>
> *- 2. je držitelem platného osvědčení podnikatele, nebo*
>
> *- b) stupně utajení Důvěrné a vyšší je držitelem platného osvědčení podnikatele příslušného stupně utajení,*
>
> *není-li stanoveno v § 58 až 62 jinak.*

**Výklad:**

**Judikatura (z místních zdrojů):**

- *NSS* [8 A 40/2017 - 52](https://vyhledavac.nssoud.cz/DokumentOriginal/Text/424096) — 12. 3. 2020
  > „je v každém konkrétním případě potřeba posoudit, zda podnikatel tuto informaci ve smyslu § 6 odst. 1 a § 15 písm. a) zákona č. 412/2005 Sb., potřebuje nezbytně znát pro účely své činnosti (jde tzv. princip need to know). Jakýkoliv jiný výklad by vedl k absurdním důsledkům, kdy by se každý držitel bezpečnostní prověrky mohl automaticky seznámit s každou utajovanou informací v držení orgánů České republiky, která stupněm svého utajení odpovídá jeho prověření"
- *NSS* [8 As 9/2010 - 98](https://vyhledavac.nssoud.cz/DokumentOriginal/Text/620091) — 27. 10. 2010
  > „Z ustanovení § 15, § 16 a § 54 odst. 3 zákona č. 412/2005 Sb. vyplývá, že osvědčení je vydáváno vždy konkrétnímu podnikateli, u kterého jsou splněny podmínky pro jeho vydání, a osvědčení je tudíž nepřevoditelné na jiný subjekt. … Předmětné osvědčení deklaruje oprávnění … subjektu, který vydaným osvědčením disponuje, seznamovat se s utajovanými informacemi"

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

#### F. Kazuistika

**1. Modelová situace.** Společnost A, s. r. o., je držitelem osvědčení podnikatele pro stupeň Tajné. Vyhraje veřejnou zakázku, k jejímuž plnění potřebuje přístup k utajovaným informacím stupně Důvěrné. Poté A prodá svůj závod (včetně lidí a vybavení) společnosti B, s. r. o., a tvrdí, že na B přešlo i osvědčení. B se na jeho základě domáhá přístupu k UI. Zadavatel to odmítá. Účastníci: A (původní držitel), B (nabyvatel závodu), zadavatel/poskytovatel UI, Úřad. Důkazy: osvědčení podnikatele A, smlouva o prodeji závodu, doklad o splnění podmínek u B, doložení need-to-know.

**2. Právní otázka.** Přechází osvědčení podnikatele převodem závodu na jiný subjekt, nebo je nepřevoditelné a vázané na konkrétního podnikatele?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 15 — kdo je podnikatelem pro účely zákona; need-to-know; dvojí režim u Vyhrazené (prohlášení nebo osvědčení) vs. nutné osvědčení u Důvěrné a vyšší.
- *Související ustanovení téhož zákona:* § 16 (podmínky osvědčení podnikatele), § 17–19a (ekonomická stabilita, spolehlivost, způsobilost, bezúhonnost), § 20 (formy přístupu), § 54 odst. 3 (osvědčení vázané na konkrétní subjekt).
- *Související předpisy:* § 2175 a násl. obč. zák. (koupě závodu — přechod práv a povinností), zákon o veřejných zakázkách (kvalifikační podmínky).
- *Judikatura:* rozsudek NSS sp. zn. 8 As 9/2010 — osvědčení se vydává vždy konkrétnímu podnikateli, u nějž jsou splněny podmínky, a je nepřevoditelné na jiný subjekt; deklaruje oprávnění toho subjektu, který jím disponuje. Dále NSS sp. zn. 8 A 40/2017 (need-to-know).

**4. Subsumpce.** Pro stupeň Důvěrné je podle § 15 písm. b) nutné platné osvědčení podnikatele příslušného stupně. Osvědčení je vázáno na konkrétního podnikatele (A) a je nepřevoditelné (NSS 8 As 9/2010) → na B nepřešlo ani převodem závodu. B by musel mít vlastní osvědčení. Současně musí B doložit need-to-know. Sporné je nanejvýš to, zda B mezitím sám nepožádal a nezískal vlastní osvědčení.

**5. Řešení.** B nemá přístup k UI jen z titulu nabytí závodu — osvědčení A je nepřevoditelné; B musí absolvovat vlastní řízení u Úřadu a doložit splnění podmínek § 16. Procesní kroky: podání žádosti B, prověření jeho ekonomické stability, spolehlivosti, způsobilosti a bezúhonnosti; do vydání osvědčení nelze B přístup umožnit. Riziko pro zakázku: bez včasného osvědčení B nemůže plnit část vyžadující UI; je třeba řešit smluvně (poddodávka přes osvědčený subjekt nebo forma přístupu dle § 20).

**6. Varianty.** (a) Šlo by jen o stupeň Vyhrazené → B by mohl postačit prohlášením podnikatele (§ 15a), aniž by potřeboval osvědčení. (b) B by byl zahraniční PO bez sídla v ČR → nespadal by pod pojem podnikatele dle § 15 a uplatnil by se režim § 60a (zpracování UI pro zahraniční subjekt).

#### G. Protiargumenty a rizika

- *Protiargument 1:* „Koupí závodu přešla všechna práva, tedy i osvědčení." Neutralizace: osvědčení je veřejnoprávní deklarace vázaná na splnění podmínek u konkrétního subjektu, nikoli majetková hodnota; je nepřevoditelné (NSS 8 As 9/2010), bez ohledu na soukromoprávní přechod závodu.
- *Protiargument 2:* „Personál i vybavení zůstaly stejné, takže podmínky jsou splněny i u B." Neutralizace: shoda faktického zázemí nenahrazuje vlastní řízení a posouzení podmínek § 16 u nového subjektu (spolehlivost, vlastnická struktura, bezúhonnost se posuzují u B, ne u A).
- *Slabé místo:* časová prodleva řízení o osvědčení může ohrozit plnění zakázky; argumentace musí včas nabídnout alternativní formu přístupu (§ 20) nebo poddodavatelské řešení.

#### H. Praktický závěr

§ 15 vymezuje podnikatele úžeji než soukromé právo a zavádí dvojí režim (Vyhrazené — prohlášení nebo osvědčení; Důvěrné a vyšší — vždy osvědčení). Klíčové je, že osvědčení je nepřevoditelné a vázané na konkrétní subjekt a že i podnikatel musí splňovat need-to-know.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Je subjekt podnikatelem ve smyslu § 15 (sídlo/pobyt v ČR, zápis, podnikatelská činnost)?
- [ ] Jaký stupeň UI je potřeba — postačí prohlášení (Vyhrazené), nebo je nutné osvědčení (Důvěrné a vyšší)?
- [ ] Má konkrétní subjekt vlastní platné osvědčení (nepřevoditelné — NSS 8 As 9/2010)?
- [ ] Je doložen need-to-know k dané informaci?
- [ ] Která forma přístupu podle § 20 se uplatní?

**Typicky rozhodné důkazy / podklady:** výpis z OR/ŽR, platné osvědčení podnikatele konkrétního subjektu, doklad o need-to-know (smlouva/zakázka), bezpečnostní dokumentace, podklady k podmínkám § 16 u nového subjektu.

---


<!-- LEGAL-REVISION:BEGIN id=0838ca299e887c5d1501 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 15

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> Přístup k utajované informaci lze umožnit podnikateli, který je fyzickou osobou s trvalým pobytem na území České republiky zapsanou do živnostenského rejstříku, obchodního rejstříku nebo jiné evidence vedené podle jiného zákona registrující osoby a provozuje podnikatelskou činnost nebo právnickou osobou se sídlem v České republice zapsanou v obchodním rejstříku, jejíž hlavní činností je podnikatelská činnost, jestliže jej nezbytně potřebuje k výkonu své činnosti, a pokud při přístupu k utajované informaci
>
> - a) stupně utajení Vyhrazené
>
> - 1. doloží písemným prohlášením svou schopnost zabezpečit ochranu utajovaných informací (dále jen „prohlášení podnikatele“), nebo
>
> - 2. je držitelem platného osvědčení podnikatele, nebo
>
> - b) stupně utajení Důvěrné a vyšší je držitelem platného osvědčení podnikatele příslušného stupně utajení,
>
> není-li stanoveno v § 58 až 62 jinak.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 58

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=0838ca299e887c5d1501 -->

### § 15a — Prohlášení podnikatele

> **§ 15a odst. 1**
>
> *Podnikatel je oprávněn učinit prohlášení podnikatele, pokud*
>
> *- a) má pro ochranu utajované informace stupně utajení Vyhrazené vytvořeny podmínky odpovídající formě přístupu k této informaci (§ 20) a příslušnému druhu zajištění její ochrany (§ 5),*
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

#### F. Kazuistika

**1. Modelová situace.** Malá projekční kancelář (s. r. o.) má pro orgán státu zpracovat dílčí dokumentaci stupně Vyhrazené, která vznikne přímo u ní. Aby si ušetřila náročné řízení o osvědčení, učiní prohlášení podnikatele. V něm deklaruje, že má vytvořeny podmínky ochrany. Ve skutečnosti odpovědná osoba (jednatel) není držitelem oznámení ani osvědčení FO a kancelář nemá zřízeno odpovídající zabezpečení dle formy přístupu. Účastníci: podnikatel (s. r. o.), jeho odpovědná osoba, poskytovatel vyhrazené informace, Úřad (kopie prohlášení, dohled). Důkazy: prohlášení podnikatele, doklad o (ne)držení oznámení odpovědnou osobou, stav zabezpečení, doklad o formě přístupu (§ 20).

**2. Právní otázka.** Bylo prohlášení podnikatele učiněno oprávněně podle § 15a odst. 1, není-li odpovědná osoba držitelem oznámení/osvědčení/dokladu a nejsou-li vytvořeny podmínky odpovídající formě přístupu?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 15a odst. 1 — podmínky oprávněnosti prohlášení: písm. a) vytvořené podmínky odpovídající formě přístupu (§ 20) a druhu ochrany (§ 5), písm. b) odpovědná osoba je držitelem oznámení/osvědčení FO/dokladu; odst. 5 (důvody zániku platnosti prohlášení).
- *Související ustanovení téhož zákona:* § 15 (dvojí režim u Vyhrazené), § 20 (formy přístupu), § 5 (druhy ochrany), § 6 (oznámení), § 16 (osvědčení podnikatele jako alternativa).
- *Související předpisy:* vyhlášky k jednotlivým druhům ochrany (č. 528/2005 Sb., č. 529/2005 Sb.); § 148 a násl. ZOÚI (odpovědnost za nepravdivé prohlášení).
- *Judikatura:* přiměřeně NSS sp. zn. 8 As 9/2010 (vázanost oprávnění na splnění podmínek u konkrétního subjektu) a 8 A 40/2017 (need-to-know).

**4. Subsumpce.** Prohlášení je sebedeklaratorní instrument, jeho oprávněnost je však zákonem podmíněna. Podmínka písm. b) (odpovědná osoba držitelem oznámení/osvědčení/dokladu) splněna není → prohlášení nelze oprávněně učinit. Současně není splněna ani podmínka písm. a) (chybí podmínky odpovídající formě přístupu). Prohlášení je tedy obsahově nepravdivé. Sporné je nanejvýš to, zda forma přístupu skutečně vyžadovala fyzické zabezpečení.

**5. Řešení.** Prohlášení učiněné bez splnění podmínek § 15a odst. 1 je neúčinné a zakládá odpovědnost podnikatele (nepravdivé prohlášení — § 148 a násl.); přestal-li podnikatel splňovat podmínky, platnost prohlášení zaniká (odst. 5 písm. e). Procesní kroky: odpovědná osoba musí nejprve získat oznámení (§ 6) a podnikatel zajistit podmínky podle § 20/§ 5; teprve poté lze prohlášení platně učinit, případně místo něj požádat o osvědčení (§ 16). Úřad může na základě kopie provést dohlížecí kontrolu. Riziko: faktický přístup k UI bez splnění podmínek = porušení a možná kompromitace.

**6. Varianty.** (a) Odpovědná osoba by oznámení měla a podmínky by byly vytvořeny → prohlášení by bylo oprávněné a postačilo by pro Vyhrazené bez osvědčení. (b) Informace by byla stupně Důvěrné → prohlášení nelze použít vůbec, je nutné osvědčení podnikatele (§ 15 písm. b).

#### G. Protiargumenty a rizika

- *Protiargument 1:* „Prohlášení je jen sebedeklarace, takže stačí ho učinit." Neutralizace: § 15a odst. 1 váže oprávněnost prohlášení na splnění dvou hmotných podmínek; bez nich je prohlášení nepravdivé a sankcionovatelné, byť není správním aktem Úřadu.
- *Protiargument 2:* „Úřad prohlášení neschvaluje, tedy ho nemůže zpochybnit." Neutralizace: Úřad sice prohlášení nevydává, dostává však jeho kopii a může provést dohlížecí kontrolu; zjistí-li nesplnění podmínek, navazují důsledky (zánik platnosti, odpovědnost).
- *Slabé místo:* posouzení, zda jsou „vytvořeny podmínky odpovídající formě přístupu", je skutkově náročné a závisí na správném určení formy podle § 20; chybné určení formy podkopává celé prohlášení.

#### H. Praktický závěr

§ 15a umožňuje u stupně Vyhrazené nahradit osvědčení zjednodušeným prohlášením podnikatele, avšak jen při splnění dvou hmotných podmínek (vytvořené podmínky dle formy přístupu a kvalifikovaná odpovědná osoba). V praxi je třeba prohlášení nepodceňovat — nepravdivé prohlášení zakládá odpovědnost a Úřad je oprávněn kontrolovat jeho podklady.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Jde skutečně jen o stupeň Vyhrazené (jinak je nutné osvědčení — § 15 písm. b)?
- [ ] Jsou vytvořeny podmínky odpovídající formě přístupu (§ 20) a druhu ochrany (§ 5)?
- [ ] Je odpovědná osoba držitelem oznámení / osvědčení FO / dokladu (písm. b)?
- [ ] Byla kopie prohlášení předána příslušnému subjektu / Úřadu?
- [ ] Nenastal některý z důvodů zániku platnosti prohlášení (odst. 5)?

**Typicky rozhodné důkazy / podklady:** text prohlášení podnikatele, doklad o oprávnění odpovědné osoby, doklad o formě přístupu a o vytvořených podmínkách ochrany, kopie předaná Úřadu, případný protokol dohlížecí kontroly.

---


<!-- LEGAL-REVISION:BEGIN id=2491ba2d20f4319f99cf generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 15a — Prohlášení podnikatele

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Podnikatel je oprávněn učinit prohlášení podnikatele, pokud
>
> - a) má pro ochranu utajované informace stupně utajení Vyhrazené vytvořeny podmínky odpovídající formě přístupu k této informaci ([[#§ 20|§ 20]]) a příslušnému druhu zajištění její ochrany ([[#§ 5|§ 5]]),
>
> - b) odpovědná osoba je držitelem oznámení, osvědčení fyzické osoby nebo dokladu.
>
> (2) Splnění podmínek pro přístup k utajované informaci podle § 15 písm. a) bodu 1 prokazuje podnikatel poskytovateli utajované informace stupně utajení Vyhrazené (dále jen „poskytovatel vyhrazené informace“) předáním prohlášení podnikatele před prvním přístupem k této informaci; ten je oprávněn od podnikatele požadovat předložení bezpečnostní dokumentace podnikatele. Poskytovatel vyhrazené informace zašle kopii prohlášení podnikatele neprodleně Úřadu.
>
> (3) Podnikatel, u něhož utajovaná informace stupně utajení Vyhrazené bude pouze vznikat, zašle prohlášení podnikatele neprodleně poté, co ho učiní, Úřadu.
>
> (4) Podnikatel, který ukončuje přístup k utajované informaci stupně utajení Vyhrazené, neprodleně písemně oznámí tuto skutečnost tomu, komu podle odstavce 2 nebo [[#§ 3|3]] předal nebo zaslal prohlášení podnikatele; to neplatí, došlo-li k zániku prohlášení podnikatele podle odstavce 5 písm. a).
>
> (5) Platnost prohlášení podnikatele zaniká
>
> - a) uplynutím 5 let ode dne, kdy bylo učiněno,
>
> - b) dnem doručení písemného oznámení podnikatele podle odstavce 4 poskytovateli vyhrazené informace nebo Úřadu,
>
> - c) dnem doručení osvědčení podnikatele pro formu přístupu podle § 20 odst. 1 písm. a) nebo pro stejnou formu přístupu podnikatele k utajované informaci,
>
> - d) zrušením nebo zánikem podnikatele,
>
> - e) přestal-li podnikatel splňovat některou z podmínek uvedených v odstavci 1, nebo
>
> - f) změnou některého z údajů uvedených v prohlášení podnikatele.
>
> (6) Podnikatel neprodleně písemně oznámí zánik platnosti prohlášení podnikatele podle odstavce 5 písm. c), e) a f) tomu, komu podle odstavce 2 nebo [[#§ 3|3]] předal nebo zaslal prohlášení podnikatele.
>
> (7) Náležitosti prohlášení podnikatele stanoví prováděcí právní předpis.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 20, § 5, § 15, § 3

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=2491ba2d20f4319f99cf -->

### § 16 — Podmínky pro vydání osvědčení podnikatele

Osvědčení podnikatele Úřad vydá podnikateli, který:
- **a) je ekonomicky stabilní** (§ 17),
- **b) je bezpečnostně spolehlivý** (§ 18),
- **c) je způsobilý zabezpečit ochranu** UI (§ 19),
- **d) odpovědná osoba je držitelem platného osvědčení FO** nejméně pro stejný stupeň,
- **e) je bezúhonný** (§ 19a).

Pět kumulativních podmínek. Zánik nebo nesplnění kterékoliv vede k zahájení řízení o zrušení platnosti.

#### F. Kazuistika

**1. Modelová situace.** Podnikatel (a. s.) žádá o osvědčení podnikatele pro stupeň Tajné. Splňuje ekonomickou stabilitu, bezpečnostní spolehlivost i způsobilost zabezpečit ochranu a je bezúhonný. Jediným předsedou představenstva (odpovědnou osobou) je však FO, která dosud nemá osvědčení FO pro stupeň Tajné, ale jen pro Důvěrné. Účastníci: podnikatel (a. s.), odpovědná osoba (předseda představenstva), Úřad. Důkazy: doklady k ekonomice, spolehlivosti, způsobilosti a bezúhonnosti; osvědčení FO odpovědné osoby a jeho stupeň.

**2. Právní otázka.** Lze podnikateli vydat osvědčení pro stupeň Tajné, jestliže jeho odpovědná osoba má osvědčení FO jen pro nižší stupeň (Důvěrné)?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 16 — pět kumulativních podmínek osvědčení podnikatele: a) ekonomická stabilita (§ 17), b) bezpečnostní spolehlivost (§ 18), c) způsobilost zabezpečit ochranu (§ 19), d) odpovědná osoba držitelem osvědčení FO nejméně pro stejný stupeň, e) bezúhonnost (§ 19a).
- *Související ustanovení téhož zákona:* § 11–14 (osvědčení FO), § 54 (osvědčení), § 2 písm. e) (odpovědná osoba), § 101 a násl. (zrušení platnosti).
- *Související předpisy:* zákon o obchodních korporacích (statutární orgán a. s.).
- *Judikatura:* rozsudek NSS sp. zn. 8 As 9/2010 — osvědčení je vázáno na konkrétní subjekt a deklaruje splnění podmínek u něj; přiměřeně k provázanosti osvědčení podnikatele a osvědčení odpovědné osoby.

**4. Subsumpce.** Podmínky a), b), c) a e) jsou splněny. Podmínka d) však vyžaduje, aby odpovědná osoba měla osvědčení FO nejméně pro stejný stupeň (Tajné). Předseda představenstva má pouze osvědčení pro Důvěrné → podmínka d) splněna není. Kumulativnost podmínek znamená, že nesplnění jediné brání vydání osvědčení pro Tajné. Sporné není nic — stupeň osvědčení odpovědné osoby je doložen.

**5. Řešení.** Úřad osvědčení pro Tajné nevydá, dokud odpovědná osoba nezíská osvědčení FO pro stupeň Tajné. Procesní kroky: odpovědná osoba podá vlastní žádost o osvědčení FO vyššího stupně; do jeho vydání lze podnikateli vydat osvědčení nanejvýš pro stupeň Důvěrné (pokrytý osvědčením odpovědné osoby), je-li to předmětem žádosti. Riziko: vydání osvědčení podnikateli pro Tajné při nesplnění podmínky d) by bylo vadné a důvodem k pozdějšímu zrušení (§ 101 a násl.).

**6. Varianty.** (a) Odpovědná osoba by získala osvědčení FO pro Přísně tajné → podmínka d) by byla splněna i pro Tajné (vyšší zahrnuje nižší). (b) Šlo by o PO s více statutáry, z nichž jen jeden (určený pro věci ZOÚI) by měl osvědčení Tajné → rozhodující je, kdo je odpovědnou osobou podle § 2 písm. e) bodu 13.

#### G. Protiargumenty a rizika

- *Protiargument 1:* „Pro osvědčení podnikatele postačí ekonomické a bezpečnostní podmínky firmy, osoba statutára je podružná." Neutralizace: podmínka d) je samostatná a kumulativní; odpovědná osoba je nositelem klíčových povinností, proto musí mít osvědčení FO nejméně pro týž stupeň.
- *Protiargument 2:* „Osvědčení odpovědné osoby pro Důvěrné stačí, vyšší stupeň lze doplnit později." Neutralizace: osvědčení podnikatele se vydává pro stupeň, pro nějž jsou splněny všechny podmínky k okamžiku rozhodnutí; nižší stupeň osvědčení FO nepokrývá vyšší stupeň osvědčení podnikatele.
- *Slabé místo:* u PO s kolektivním nebo více statutárními orgány je nutné správně určit odpovědnou osobu (§ 2 písm. e bod 13); chybné určení vede k chybnému posouzení podmínky d).

#### H. Praktický závěr

§ 16 stanoví pět kumulativních podmínek osvědčení podnikatele a propojuje je s osvědčením FO odpovědné osoby (nejméně pro stejný stupeň). V praxi je nutné synchronizovat řízení o osvědčení podnikatele s prověrkou odpovědné osoby a každou z pěti podmínek samostatně doložit.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Je podnikatel ekonomicky stabilní (§ 17)?
- [ ] Je bezpečnostně spolehlivý (§ 18)?
- [ ] Je způsobilý zabezpečit ochranu UI (§ 19)?
- [ ] Má odpovědná osoba osvědčení FO nejméně pro týž stupeň (písm. d)?
- [ ] Je podnikatel bezúhonný (§ 19a)?

**Typicky rozhodné důkazy / podklady:** účetní a finanční podklady (§ 17), podklady ke spolehlivosti a vlastnické struktuře (§ 18), bezpečnostní dokumentace a doklad o způsobilosti (§ 19), osvědčení FO odpovědné osoby s uvedením stupně, doklad o bezúhonnosti (§ 19a).

---


<!-- LEGAL-REVISION:BEGIN id=7f3bde17cff7b3740e21 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 16 — Podmínky pro vydání osvědčení podnikatele

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Osvědčení podnikatele Úřad vydá podnikateli,
>
> - a) který je ekonomicky stabilní,
>
> - b) který je bezpečnostně spolehlivý,
>
> - c) který je způsobilý zabezpečit ochranu utajovaných informací,
>
> - d) pokud odpovědná osoba je držitelem platného osvědčení fyzické osoby nejméně pro takový stupeň utajení, pro který žádá podnikatel o vydání osvědčení podnikatele,
>
> - e) který je bezúhonný.
>
> (2) Podmínky uvedené v odstavci 1 musí podnikatel splňovat po celou dobu platnosti osvědčení podnikatele ([[#§ 55|§ 55]]).

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 55

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=7f3bde17cff7b3740e21 -->

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

#### F. Kazuistika

**1. Modelová situace.** Strojírenský podnikatel (s. r. o.) usiluje o osvědčení podnikatele pro stupeň Důvěrné. Vykázal v posledních pěti účetních obdobích třikrát účetní ztrátu a má jeden splatný, dosud neuhrazený nedoplatek na pojistném; vlastní kapitál je však kladný, není v úpadku ani v moratoriu a žádné rozhodnutí o úpadku nebylo vydáno. Účastníci: podnikatel (s. r. o.), Úřad. Důkazy: účetní závěrky za 5 období, potvrzení správy sociálního zabezpečení o nedoplatku, doklad o (ne)existenci insolvenčního řízení, výpočet vlastního kapitálu.

**2. Právní otázka.** Brání ekonomické stabilitě podle § 17 opakovaná účetní ztráta a dílčí nedoplatek na pojistném, není-li dán žádný z tvrdých důvodů (úpadek, moratorium, nucená správa, dlouhodobě záporný kapitál)?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 17 odst. 1 (tvrdé důvody — automatická diskvalifikace: moratorium, rozhodnutí o úpadku, nucená/dočasná správa, záporný vlastní kapitál v posledních 5 obdobích), odst. 2 (měkké důvody — diskreční posouzení: nedoplatky, exekuce, opakovaná ztráta, jednorázová záporná kapitálová pozice).
- *Související ustanovení téhož zákona:* § 16 písm. a) (ekonomická stabilita jako podmínka osvědčení), § 18 (spolehlivost), § 101 a násl. (řízení).
- *Související předpisy:* insolvenční zákon č. 182/2006 Sb. (moratorium, úpadek), zákon č. 374/2015 Sb. (opatření k řešení krize na finančním trhu).
- *Judikatura:* přiměřeně judikatura k diskrečnímu posouzení ekonomických rizik a k požadavku odůvodněnosti a proporcionality rozhodnutí Úřadu.

**4. Subsumpce.** Žádný tvrdý důvod (odst. 1) není dán — není úpadek, moratorium, nucená správa ani záporný kapitál po 5 období. Opakovaná ztráta ve 3 z 5 období (odst. 2 písm. e) a nedoplatek na pojistném (odst. 2 písm. a) jsou měkké důvody, jež se posuzují diskrečně podle jejich rozsahu, charakteru a trvalosti. Sporné je, zda tyto okolnosti dosahují intenzity zakládající ekonomickou nestabilitu.

**5. Řešení.** Měkké důvody nezakládají automatickou diskvalifikaci; Úřad je posoudí v kontextu — dílčí nedoplatek a část ztrát při kladném vlastním kapitálu a absenci tvrdých důvodů zpravidla ekonomickou stabilitu nevylučují, zejména jde-li o přechodný a vysvětlitelný stav. Rozhodnutí (vyhovět/nevyhovět) musí být odůvodněné a proporční. Procesní kroky: vyžádat vysvětlení příčin ztrát a doklad o (ne)uhrazení nedoplatku; zohlednit trend. Riziko: paušální zamítnutí jen pro účetní ztrátu bez posouzení kontextu by bylo nepřiměřené a přezkoumatelně vadné.

**6. Varianty.** (a) Vlastní kapitál by byl záporný ve všech 5 obdobích → naplněn tvrdý důvod odst. 1 písm. d) a osvědčení nelze vydat bez ohledu na ostatní. (b) Proti podnikateli by bylo vydáno rozhodnutí o úpadku → automatická diskvalifikace dle odst. 1 písm. b).

#### G. Protiargumenty a rizika

- *Protiargument 1:* „Opakovaná ztráta sama o sobě znamená ekonomickou nestabilitu." Neutralizace: ztráta je měkkým důvodem (odst. 2), který se posuzuje diskrečně; bez tvrdého důvodu a při kladném kapitálu nemusí stabilitu vyloučit — rozhoduje kontext a trend.
- *Protiargument 2:* „Jakýkoli nedoplatek znamená nedůvěryhodnost a tedy ekonomickou nestabilitu." Neutralizace: dílčí nedoplatek je třeba vážit dle rozsahu a trvalosti (odst. 2 písm. a); jednorázový a vysvětlitelný nedoplatek zpravidla diskvalifikaci nezakládá.
- *Slabé místo:* hranice mezi „přechodnými obtížemi" a „ekonomickou nestabilitou" je neostrá; rozhodnutí stojí a padá s kvalitou odůvodnění a doložením finančního vývoje.

#### H. Praktický závěr

§ 17 dělí důvody ekonomické nestability na tvrdé (automatická diskvalifikace) a měkké (diskreční posouzení) a má protikorupční účel — bránit přístupu subjektů v ekonomické tísni. V praxi je nutné nejprve vyloučit tvrdé důvody a teprve poté kontextuálně vážit měkké, vždy s řádným odůvodněním.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Je dán některý tvrdý důvod odst. 1 (moratorium, úpadek, nucená/dočasná správa, záporný kapitál 5 období)?
- [ ] Existují měkké důvody odst. 2 (nedoplatky, exekuce, opakovaná ztráta, jednorázově záporný kapitál)?
- [ ] Byly měkké důvody posouzeny dle rozsahu, charakteru a trvalosti?
- [ ] Je závěr o (ne)stabilitě odůvodněný a proporční?
- [ ] Je posouzení podloženo finančními doklady za rozhodná období?

**Typicky rozhodné důkazy / podklady:** účetní závěrky za posledních 5 období, potvrzení o nedoplatcích (daň, clo, pojistné), výpis z insolvenčního rejstříku, doklady o exekucích, výpočet vlastního kapitálu, vysvětlení příčin ztrát.

---


<!-- LEGAL-REVISION:BEGIN id=05a3dad2d81efd49ea7b generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 17 — Ekonomická stabilita

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Podmínku ekonomické stability nesplňuje podnikatel,
>
> - a) u kterého soud vyhlásil moratorium15),
>
> - b) vůči jehož majetku je vydáno rozhodnutí o úpadku15),
>
> - c) u kterého byla zavedena nucená správa nebo v posledních 3 letech dočasná správa anebo na něj v posledních 3 letech bylo uplatněno opatření k řešení krize podle zákona upravujícího ozdravné postupy a řešení krize na finančním trhu, nebo
>
> - d) který na základě řádných účetních závěrek v posledních 5 po sobě jdoucích účetních obdobích vykazuje záporný vlastní kapitál.
>
> (2) Za ekonomicky nestabilního lze též považovat podnikatele,
>
> - a) který má evidován nedoplatek na pojistném na sociální zabezpečení, na příspěvku na státní politiku zaměstnanosti nebo na pojistném na veřejné zdravotní pojištění, včetně penále,
>
> - b) který má evidován nedoplatek na dani z příjmů, na dani z přidané hodnoty nebo na jiné dani, nedoplatek na cle nebo nedoplatek na příslušenství daně nebo cla,
>
> - c) který trvale či opakovaně neplní finanční povinnosti vůči státu, fyzickým nebo právnickým osobám,
>
> - d) u něhož bylo rozhodnuto o exekuci na jeho majetek,
>
> - e) u kterého je po dobu nejméně 5 posledních po sobě jdoucích zdaňovacích období výsledkem podnikatelské činnosti ztráta, nebo
>
> - f) který na základě řádné účetní závěrky vykazuje záporný vlastní kapitál.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Místní znění neobsahuje výslovný vnitřní odkaz.

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=05a3dad2d81efd49ea7b -->

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

#### F. Kazuistika

**1. Modelová situace.** O osvědčení podnikatele pro stupeň Tajné žádá česká s. r. o., která je ekonomicky stabilní a způsobilá zajistit ochranu. Jejím jediným společníkem (se 100% podílem a rozhodujícím vlivem) je však offshore společnost, jejíž skutečný majitel není dohledatelný a jejíž vlastnickou strukturu nelze ověřit. Účastníci: žadatel (česká s. r. o.), zahraniční vlastník, jeho neznámý skutečný majitel, Úřad. Důkazy: výpis z evidence skutečných majitelů, řetězec vlastnické struktury, doklady o (ne)ověřitelnosti zahraničního vlastníka.

**2. Právní otázka.** Lze podnikateli vydat osvědčení, je-li ekonomicky stabilní a způsobilý, avšak jeho vlastnickou strukturu (zahraničního vlastníka s rozhodujícím vlivem) nelze ověřit a skutečného majitele nelze zjistit?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 18 — bezpečnostní spolehlivost podnikatele; tvrdá rizika (odst. 2), měkká rizika (odst. 3, vč. písm. týkajícího se zahraničního vlastníka, jehož strukturu nelze ověřit, a zahraniční osoby ve struktuře, již nelze prověřit), rozhodující vliv (odst. 4 — i nepřímý), posouzení měkkých rizik (odst. 5).
- *Související ustanovení téhož zákona:* § 16 písm. b) (spolehlivost jako podmínka osvědčení), § 14 (paralela pro FO), § 2 písm. b) (zájem ČR).
- *Související předpisy:* zákon č. 37/2021 Sb., o evidenci skutečných majitelů; nařízení EU 2019/452 o screeningu přímých zahraničních investic.
- *Judikatura:* usnesení ÚS sp. zn. II.ÚS 2893/14 (převaha veřejného zájmu nad zájmem osoby, o jejíž spolehlivosti jsou důvodné pochybnosti); rozsudek NSS sp. zn. 10 A 160/2015 (pravděpodobnostní standard prokazování rizika).

**4. Subsumpce.** Zahraniční vlastník má rozhodující vliv (odst. 4 — 100% podíl, schopnost prosadit obsazení orgánů), a to případně i nepřímo. Nemožnost ověřit jeho vlastnickou strukturu a zjistit skutečného majitele naplňuje měkké riziko podle § 18 odst. 3 (neprůhledný/neověřitelný zahraniční vlastník). Při komplexním posouzení (odst. 5) tato neprůhlednost zpravidla zakládá bezpečnostní riziko bránící vydání osvědčení pro vyšší stupeň. Sporné je, zda se neprůhlednost nepodaří dodatečně odstranit doložením struktury.

**5. Řešení.** Neověřitelnost vlastnické struktury zahraničního vlastníka s rozhodujícím vlivem je typickým bezpečnostním rizikem; Úřad zpravidla osvědčení pro Tajné nevydá, dokud nebude struktura a skutečný majitel řádně doložen a prověřitelný. Posouzení musí být odůvodněné a proporční (II.ÚS 2893/14) a může vycházet z pravděpodobnostního standardu (NSS 10 A 160/2015). Procesní kroky: vyžádat úplný řetězec vlastnictví a doklad o skutečném majiteli; umožnit doplnění; při přetrvávající neprůhlednosti rozhodnout o nevydání. Riziko: vydání osvědčení neprůhledně vlastněnému subjektu ohrožuje zájem ČR a otevírá prostor pro vliv cizí moci.

**6. Varianty.** (a) Zahraniční vlastník by doložil úplnou a ověřitelnou strukturu i skutečného majitele bez vazby na rizikové zájmy → riziko by mohlo odpadnout a osvědčení by bylo možné vydat. (b) Bylo by zjištěno, že skutečný majitel vyvíjí činnost proti zájmu ČR → naplněno tvrdé riziko (odst. 2) a osvědčení nelze vydat bez diskrece.

#### G. Protiargumenty a rizika

- *Protiargument 1:* „Žadatelem je česká firma, vlastník je nepodstatný." Neutralizace: § 18 výslovně zohledňuje vlastnickou strukturu vč. zahraničních vlastníků s rozhodujícím (i nepřímým) vlivem (odst. 3 a 4); spolehlivost se posuzuje na úrovni celé struktury, ne jen formálního žadatele.
- *Protiargument 2:* „Nemožnost ověřit strukturu nelze klást k tíži žadatele." Neutralizace: břemeno doložit ověřitelnost a odstranit pochybnosti nese podnikatel; neodstraněná neprůhlednost je sama o sobě rizikem (možnost skrytého vlivu cizí moci), jak reflektují i akty EU (2019/452).
- *Slabé místo:* posouzení vychází zčásti z neveřejných zjištění a z odhadu pravděpodobnosti; o to vyšší jsou nároky na odůvodnění a soudní přezkoumatelnost, aby rozhodnutí nebylo libovůlí.

#### H. Praktický závěr

§ 18 je paralelou § 14 pro podnikatele, avšak významně širší — zohledňuje agregované riziko celé vlastnické a řídicí struktury vč. skutečných majitelů a zahraničních vlastníků. V praxi je klíčové prověřit průhlednost a ověřitelnost vlastnictví; neodstraněná neprůhlednost zahraničního vlastníka s rozhodujícím vlivem zpravidla brání vydání osvědčení vyššího stupně.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Je dáno některé tvrdé riziko odst. 2 (činnost proti zájmu ČR, potlačování práv, neposkytnutí součinnosti)?
- [ ] Je vlastnická a řídicí struktura průhledná a ověřitelná, vč. skutečných majitelů?
- [ ] Má některá osoba rozhodující (i nepřímý) vliv podle odst. 4 a je prověřitelná?
- [ ] Byla měkká rizika posouzena komplexně (rozsah, charakter, doba — odst. 5)?
- [ ] Je rozhodnutí odůvodněné, proporční a přezkoumatelné?

**Typicky rozhodné důkazy / podklady:** výpis z evidence skutečných majitelů, úplný řetězec vlastnické struktury (vč. zahraničních článků), doklady o osobách s rozhodujícím vlivem, zjištění ke spolehlivosti statutárů/prokuristů/skutečných majitelů, podklady ke screeningu zahraničních investic.

---


<!-- LEGAL-REVISION:BEGIN id=88b743028408c8c59d43 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 18 — Bezpečnostní spolehlivost

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Podmínku bezpečnostní spolehlivosti nesplňuje podnikatel, u něhož bylo zjištěno bezpečnostní riziko.
>
> (2) Bezpečnostním rizikem je
>
> - a) skutečnost, že podnikatel, člen jeho statutárního nebo kontrolního orgánu, prokurista nebo fyzická osoba s rozhodujícím vlivem na podnikatele vyvíjela nebo vyvíjí činnost proti zájmu České republiky,
>
> - b) činnost podnikatele, člena jeho statutárního nebo kontrolního orgánu, prokuristy nebo fyzické osoby s rozhodujícím vlivem na podnikatele spočívající v potlačování základních práv a svobod nebo podpora takové činnosti,
>
> - c) skutečnost, že práva společníka nebo člena obchodní korporace s nejméně 10% podílem na základním kapitálu nebo na hlasovacích právech, a to i prostřednictvím jiných právnických osob, vykonává svěřenský správce a že zakladatel svěřenského fondu, správce svěřenského fondu nebo osoba obmyšlená, jež má být příjemcem plnění z tohoto svěřenského fondu, vyvíjí nebo vyvíjela činnost proti zájmu České republiky nebo činnost spočívající v potlačování základních práv a svobod nebo takovou činnost podporovala, nebo
>
> - d) opakované neposkytnutí nezbytné součinnosti nebo neudělení souhlasu podle § 108 odst. 7 v probíhajícím řízení o zrušení platnosti osvědčení podnikatele, pokud bez poskytnutí součinnosti nelze ve věci rozhodnout.
>
> (3) Za bezpečnostní riziko lze též považovat
>
> - a) kapitálové, finanční nebo obchodní vztahy k jiným fyzickým nebo právnickým osobám anebo k cizí moci, které vyvíjejí nebo vyvíjely činnost proti zájmu České republiky,
>
> - b) personální nestabilitu ve statutárním nebo v kontrolním orgánu nebo v osobách prokuristů,
>
> - c) chování nebo činnost podnikatele, člena jeho statutárního nebo kontrolního orgánu nebo prokuristy, které má negativní vliv na podnikatele nebo může negativně ovlivňovat důvěryhodnost podnikatele,
>
> - d) porušení povinnosti při ochraně utajovaných informací,
>
> - e) pravomocné odsouzení společníka nebo člena obchodní korporace s rozhodujícím vlivem na podnikatele pro úmyslný trestný čin,
>
> - f) úmyslné porušení právních předpisů společníkem nebo členem obchodní korporace nebo jinou osobou, která má rozhodující vliv na podnikatele,
>
> - g) úmyslné porušení právních předpisů osobami oprávněnými jménem podnikatele nebo za podnikatele jednat, na jehož základě může nastat újma zájmu České republiky,
>
> - h) vztah osoby, která má vliv na jednání podnikatele, k fyzickým osobám nebo právnickým osobám nebo k cizí moci, které vyvíjely nebo vyvíjejí činnost proti zájmu České republiky,
>
> - i) skutečnost, že členem statutárního nebo kontrolního orgánu podnikatele je právnická osoba,
>
> - j) pravomocné odsouzení podnikatele pro trestný čin,
>
> - k) skutečnost, že podnikatel nehradí své peněžité dluhy, přestože mu v tom nebrání jiným právním předpisem předvídané okolnosti, pro které tyto dluhy nelze hradit,
>
> - l) skutečnost, že společníkem nebo členem obchodní korporace s rozhodujícím vlivem na podnikatele je zahraniční právnická osoba, u které nelze úkony v řízení zjistit nebo ověřit vlastnickou strukturu, nebo
>
> - m) skutečnost, že není možné ověřit bezpečnostní spolehlivost podnikatele, protože společníkem nebo členem obchodní korporace s rozhodujícím vlivem na podnikatele, a to i prostřednictvím jiných právnických osob, je zahraniční osoba.
>
> (4) Rozhodujícím vlivem podle odstavce 2 písm. a) a b) a odstavce 3 písm. e), f), l) a m) je možnost prosadit fakticky nebo na základě práva jmenování, odvolání nebo volbu osoby, která je členem individuálního statutárního nebo kontrolního orgánu, nebo většiny osob, které jsou členy kolektivního statutárního nebo kontrolního orgánu podnikatele, a to i prostřednictvím jiných právnických osob. Vlivem podle odstavce 3 písm. h) je schopnost ovlivnit přímo či nepřímo jednání podnikatele.
>
> (5) Při posuzování, zda skutečnost uvedená v odstavci 3 je bezpečnostním rizikem, se přihlíží k jejímu rozsahu a charakteru, k době jejího výskytu a k tomu, do jaké míry může ovlivnit schopnost podnikatele utajovat informace.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 108

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=88b743028408c8c59d43 -->

### § 19 — Způsobilost zabezpečit ochranu UI

Podnikatel splňuje podmínku **způsobilosti zabezpečit ochranu UI**, je-li schopen zajistit a dodržovat jednotlivé druhy ochrany podle § 5 — odstupňováno podle stupně utajení a formy přístupu (§ 20). Konkrétně musí mít odpovídající personální obsazení, prostory, IS, kryptografická řešení (jsou-li relevantní), bezpečnostní dokumentaci.

#### F. Kazuistika

**1. Modelová situace.** Strojírenský podnik se uchází o zakázku Ministerstva obrany na vývoj a výrobu komponent zbraňového systému, při níž bude zpracovávat technickou dokumentaci stupně utajení Tajné, a žádá o vydání osvědčení podnikatele pro formu přístupu podle § 20 odst. 1 písm. a). Účastníci: žadatel (podnikatel — PO), Úřad (NBÚ) jako orgán prověřující průmyslovou bezpečnost, MO jako budoucí původce UI. Při bezpečnostním řízení Úřad zjistí, že podnik sice má bezpečnostního ředitele a vyhovující trezory, avšak nedisponuje certifikovaným informačním systémem pro zpracování dokumentace stupně Tajné a jeho výrobní hala leží mimo zabezpečenou oblast. Důkazy: projekt fyzické bezpečnosti, certifikáty IS (§ 46), bezpečnostní dokumentace, doklady o personálním obsazení (osvědčení FO zaměstnanců podle § 11).

**2. Právní otázka.** Je podnikatel způsobilý zabezpečit ochranu UI ve smyslu § 19, jestliže k požadovanému stupni utajení a formě přístupu nedisponuje všemi druhy zajištění ochrany podle § 5 v rozsahu odpovídajícím stupni Tajné?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 19 — způsobilost zabezpečit ochranu UI jako schopnost zajistit a dodržovat jednotlivé druhy ochrany podle § 5, odstupňovaná podle stupně utajení a formy přístupu (§ 20).
- *Související ustanovení téhož zákona:* § 5 (druhy zajištění ochrany — personální, administrativní, fyzická, IS/KS, kryptografická), § 16 odst. 1 (podmínky pro vydání osvědčení podnikatele, jehož je způsobilost součástí), § 20 (formy přístupu — určuje rozsah požadavků), § 24 a násl. (fyzická bezpečnost), § 34 (certifikace IS).
- *Související předpisy:* vyhláška č. 528/2005 Sb. (fyzická bezpečnost), vyhláška o průmyslové bezpečnosti — konkretizují, co znamená „být schopen zajistit a dodržovat".
- *Judikatura:* obecně platí, že posouzení splnění bezpečnostních podmínek je věcí odborného uvážení Úřadu, soudně přezkoumatelného toliko v mezích zákonnosti a nepřekročení správního uvážení; nosný závěr o přednosti zájmu na ochraně UI plyne i z judikatury NSS k § 21 (rozhodnutí o utajení).

**4. Subsumpce.** Znak „schopen zajistit a dodržovat jednotlivé druhy ochrany podle § 5" se posuzuje ve vztahu ke konkrétnímu stupni (Tajné) a formě (písm. a — UI fyzicky u podnikatele). Splněno: personální bezpečnost (bezpečnostní ředitel, osvědčení FO), administrativní bezpečnost (trezory). Sporné/neprokázané: chybí certifikovaný IS pro Tajné a fyzická bezpečnost výrobní haly (není ZO příslušné kategorie). Pro formu a) jsou přitom všechny druhy ochrany obligatorní — způsobilost tedy není naplněna.

**5. Řešení.** Úřad nemůže osvědčení vydat pro stupeň Tajné a formu a), dokud podnikatel nedoplní chybějící druhy ochrany. Správně postupuje tak, že žadateli umožní zjednání nápravy (doplnění certifikovaného IS, zřízení ZO, schválení projektu fyzické bezpečnosti) a teprve poté osvědčení vydá; jinak žádost zamítne. Procesní kroky: výzva k odstranění nedostatků, případně přerušení řízení. Riziko/alternativa: podnikatel může požádat o osvědčení jen pro nižší stupeň (Důvěrné/Vyhrazené) nebo pro formu přístupu b) podle § 20 (pak postačí jen personální bezpečnost), čímž se rozsah požadované způsobilosti zúží.

**6. Varianty.** (a) Pokud by UI byla u podnikatele pouze projednávána ústně v jednací oblasti bez fyzického nosiče, požadavky na IS by odpadly a způsobilost by se posuzovala jen vůči fyzické a personální bezpečnosti. (b) Pokud by zaměstnanci podnikatele přistupovali k UI výhradně u zadavatele (forma b dle § 20), postačila by personální bezpečnost a způsobilost by byla naplněna i bez vlastního IS a ZO.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Způsobilost lze osvědčit i při dílčích nedostatcích, doplní se za provozu."* Neutralizace: § 19 váže způsobilost na schopnost ochranu reálně zajistit a dodržovat; certifikace IS a ZO jsou vstupní, nikoli dodatečné podmínky — bez nich nelze s UI příslušného stupně vůbec nakládat (§ 34 odst. 5, § 24 odst. 5 a 6).
- *Protiargument 2: „Postačí formální existence dokumentace."* Neutralizace: zákon žádá faktickou schopnost (materiálně-funkční test), nikoli pouhé papírové doložení; Úřad ověřuje skutečný stav prostor, systémů a personálu.
- *Slabé místo:* hranice mezi „nedostatkem bránícím vydání" a „nedostatkem řešitelným podmínkou" není v zákoně ostrá; rozhodující je odborné uvážení Úřadu, jehož přezkoumatelnost je omezená.

#### H. Praktický závěr

Způsobilost podle § 19 je relativní vůči stupni utajení a formě přístupu (§ 20): rozsah požadovaných druhů ochrany podle § 5 se mění. Před podáním žádosti je třeba namapovat, jaké druhy ochrany konkrétní zakázka vyžaduje, a doložit jejich reálné zajištění.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Určit nejvyšší stupeň utajení UI a formu přístupu podle § 20.
- [ ] Ověřit pokrytí všech relevantních druhů ochrany podle § 5 (personální, administrativní, fyzická, IS/KS, krypto).
- [ ] Doložit certifikace IS (§ 46), projekt fyzické bezpečnosti (§ 32), bezpečnostní dokumentaci.
- [ ] Zvážit volbu formy b) nebo nižšího stupně, je-li plné zajištění nedosažitelné.

**Typicky rozhodné důkazy / podklady:** projekt fyzické bezpečnosti, certifikáty IS a technických prostředků, bezpečnostní dokumentace, doklady o personálním obsazení a osvědčeních FO zaměstnanců.

---


<!-- LEGAL-REVISION:BEGIN id=11318749a6546569ccfe generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 19 — Způsobilost zabezpečit ochranu utajovaných informací

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> Podmínku způsobilosti zabezpečit ochranu utajovaných informací nesplňuje podnikatel, který není schopen zajistit a dodržovat jednotlivé druhy zajištění ochrany utajovaných informací podle tohoto zákona v závislosti na příslušném stupni utajení a formě přístupu k utajované informaci.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Místní znění neobsahuje výslovný vnitřní odkaz.

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=11318749a6546569ccfe -->

### § 19a — Bezúhonnost podnikatele

Obdobně § 13 — bezúhonnost neporušuje pravomocné odsouzení za úmyslný TČ nebo TČ vztahující se k ochraně UI; podmíněné zastavení (až po osvědčení podle TŘ) a narovnání (5 let od právní moci) řeší obdobně. Posuzuje se **samotný podnikatel — PO/FO**, nikoli jeho statutáři (ti jsou prověřováni samostatně přes § 14 jako FO ucházející se o osvědčení FO).

#### F. Kazuistika

**1. Modelová situace.** Akciová společnost žádá o osvědčení podnikatele. Sama společnost (jako PO) nikdy odsouzena nebyla, avšak její předseda představenstva byl před třemi lety pravomocně odsouzen pro úmyslný trestný čin podvodu. Úřad v bezpečnostním řízení zvažuje, zda odsouzení statutára brání vydání osvědčení z titulu (ne)bezúhonnosti podnikatele. Účastníci: žadatel (PO), Úřad, dotčený statutární orgán (FO). Důkazy: výpis z evidence Rejstříku trestů PO i FO, případně cizozemský rejstřík, doklad o právní moci a o případném zahlazení.

**2. Právní otázka.** Lze podnikateli (PO) upřít bezúhonnost podle § 19a z důvodu pravomocného odsouzení jeho statutárního orgánu (FO), nebo se bezúhonnost posuzuje výlučně u podnikatele samotného a statutáři se prověřují samostatně?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 19a — bezúhonnost podnikatele (PO/FO); neporušuje ji odsouzení za úmyslný TČ nebo TČ vztahující se k ochraně UI; obdobně se řeší podmíněné zastavení a narovnání.
- *Související ustanovení téhož zákona:* § 13 (bezúhonnost FO pro osvědčení FO — vzor, na nějž § 19a odkazuje), § 14 (bezpečnostní spolehlivost — sem patří prověření statutárů jako FO), § 16 (podmínky pro vydání osvědčení podnikatele).
- *Související předpisy:* zákon č. 269/1994 Sb., o Rejstříku trestů; trestní řád (institut podmíněného zastavení trestního stíhání a narovnání); trestní zákoník (vymezení úmyslného TČ).
- *Judikatura:* obecně přijímaný závěr, že bezúhonnost PO a bezúhonnost/spolehlivost jejích orgánů jsou samostatné kategorie posuzované odděleně; pochybení statutára se promítá do prověrky FO, nikoli automaticky do bezúhonnosti PO.

**4. Subsumpce.** Znak „podnikatel" v § 19a = samotná PO/FO žadatele. Odsouzení statutára je skutečností týkající se jiného subjektu (FO statutára), který se prověřuje vlastní cestou podle § 14. Bezúhonnost PO tedy odsouzením statutára porušena není; relevantní by bylo jen odsouzení samotné PO (např. podle zákona o trestní odpovědnosti PO). Skutečnost odsouzení statutára se však promítne do posouzení bezpečnostní spolehlivosti podle § 14.

**5. Řešení.** Úřad nemůže zamítnout osvědčení podnikatele s odůvodněním, že statutár není bezúhonný podle § 19a — toto ustanovení míří na podnikatele samého. Odsouzení statutára Úřad zohlední v rámci § 14 (bezpečnostní spolehlivost): zkoumá, zda statutár představuje bezpečnostní riziko, případně zda lze podmínku splnit jeho nahrazením či omezením přístupu. Procesní krok: oddělené hodnocení bezúhonnosti PO (§ 19a) a spolehlivosti orgánů (§ 14). Riziko/alternativa: trvá-li riziko plynoucí z osoby statutára, osvědčení může být odepřeno z titulu § 14, nikoli § 19a.

**6. Varianty.** (a) Byla-li by pravomocně odsouzena samotná PO (např. pro úmyslný TČ podle zákona o trestní odpovědnosti PO), bezúhonnost podle § 19a by porušena byla a osvědčení by nebylo možné vydat až do zahlazení. (b) Bylo-li by trestní stíhání statutára podmíněně zastaveno a osvědčilo se, hledí se na něj, jako by odsouzen nebyl — překážka by odpadla i v rovině § 14 (pokud jinak nevyplyne riziko).

#### G. Protiargumenty a rizika

- *Protiargument 1: „Statutár jedná za PO, proto jeho odsouzení diskvalifikuje i PO."* Neutralizace: zákon rozlišuje subjekty řízení; § 19a se týká podnikatele, kdežto osoby jednající za podnikatele se prověřují podle § 14 — jde o dvě nezávislé podmínky podle § 16.
- *Protiargument 2: „Posuzování statutárů přes § 14 obchází přísnost § 19a."* Neutralizace: § 14 (bezpečnostní spolehlivost) je svým rozsahem širší než bezúhonnost a umožní postihnout i jednání, které do bezúhonnosti nespadá; ochrana zájmu státu tím není oslabena.
- *Slabé místo:* prolínání osoby a podniku u jednočlenných PO/OSVČ, kde se FO podnikatel a jeho osoba fakticky kryjí — pak se § 19a a § 13/§ 14 mohou vztahovat na tutéž osobu.

#### H. Praktický závěr

Bezúhonnost podle § 19a se posuzuje u podnikatele (PO/FO), nikoli u jeho statutárů; ti se prověřují samostatně jako FO podle § 14. Tyto roviny je třeba v řízení i v argumentaci důsledně oddělovat.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Odlišit subjekt podnikatele (§ 19a) od osob jednajících za podnikatele (§ 14).
- [ ] Opatřit výpis z Rejstříku trestů PO i relevantních FO, doklad o právní moci a zahlazení.
- [ ] Posoudit běh lhůt u podmíněného zastavení (osvědčení dle TŘ) a narovnání (5 let od právní moci).
- [ ] Odsouzení statutára vyhodnotit v režimu § 14, nikoli jako překážku podle § 19a.

**Typicky rozhodné důkazy / podklady:** výpisy z evidence Rejstříku trestů PO i FO, rozhodnutí soudu s doložkou právní moci, doklady o zahlazení odsouzení, případně cizozemské rejstříky.

---


<!-- LEGAL-REVISION:BEGIN id=d93a8a11d16df831a02b generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 19a — Bezúhonnost pro účely vydání osvědčení podnikatele

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> Podmínku bezúhonnosti pro účely vydání osvědčení podnikatele splňuje podnikatel, který nebyl pravomocně odsouzen za spáchání úmyslného trestného činu nebo trestného činu vztahujícího se k ochraně utajovaných informací nebo se na něj hledí, jako by odsouzen nebyl. Jestliže trestní stíhání pro takový trestný čin bylo podmíněně zastaveno nebo bylo podmíněně odloženo podání návrhu na potrestání, je podmínka bezúhonnosti splněna až poté, co se podnikatel osvědčil podle jiného právního předpisu57). V případě rozhodnutí o schválení narovnání v trestním řízení o úmyslném trestném činu je podmínka bezúhonnosti splněna, pokud od nabytí právní moci takového rozhodnutí uplynula doba alespoň 5 let.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Místní znění neobsahuje výslovný vnitřní odkaz.

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=d93a8a11d16df831a02b -->

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

#### F. Kazuistika

**1. Modelová situace.** Poradenská společnost uzavře s ministerstvem smlouvu, podle níž její konzultanti budou docházet do prostor ministerstva a tam pracovat s UI stupně Důvěrné; UI nebude společnosti nikdy předána ani u ní vznikat. Společnost má osvědčení podnikatele vystavené pro formu přístupu podle § 20 odst. 1 písm. b). Po roce ministerstvo navrhne, aby společnost převzala část dokumentace do vlastního datového úložiště kvůli efektivitě. Účastníci: podnikatel (poradenská společnost), ministerstvo (původce a zadavatel), Úřad (vydal osvědčení). Důkazy: smlouva o poskytování služeb, osvědčení podnikatele s vyznačenou formou, evidence přístupů zaměstnanců, prohlášení o poučení podle personální bezpečnosti.

**2. Právní otázka.** Postačuje osvědčení vystavené pro formu přístupu podle § 20 odst. 1 písm. b) (zaměstnanci přistupují k UI v cizím prostředí) k tomu, aby podnikatel mohl převzít UI do vlastních systémů, kde by u něj fakticky vznikala či mu byla poskytnuta [forma a)]?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 20 odst. 1 písm. a) a b) a odst. 2 — dvě formy přístupu podnikatele; u formy b) postačí zajištění ochrany personální bezpečností [§ 5 písm. a)], u formy a) je nutná plná škála ochrany.
- *Související ustanovení téhož zákona:* § 5 (druhy zajištění ochrany), § 16 odst. 1 písm. c) (podmínka, jejíž rozsah § 20 odst. 2 zužuje), § 19 (způsobilost zabezpečit ochranu UI), § 54 odst. 3 písm. c) (vyznačení formy v osvědčení).
- *Související předpisy:* vyhláška o průmyslové bezpečnosti; vyhlášky o fyzické bezpečnosti (č. 528/2005 Sb.) a administrativní bezpečnosti (č. 529/2005 Sb.) — relevantní pro formu a).
- *Judikatura:* obecně přijímaná zásada, že rozsah oprávnění plynoucího z bezpečnostního osvědčení je vázán na podmínky, za nichž bylo vydáno; překročení vyznačeného rozsahu je nakládáním s UI bez splnění zákonných podmínek.

**4. Subsumpce.** Osvědčení vystavené pro formu b) pokrývá pouze situaci, kdy zaměstnanci přistupují k UI bez její fyzické přítomnosti u podnikatele a zajištěna je toliko personální bezpečnost. Převzetí UI do vlastního úložiště naplňuje znaky formy a) („vzniká u něho / je mu poskytnuta") — vyžaduje fyzickou, administrativní a IS bezpečnost. Stávající osvědčení tyto znaky nepokrývá; rozsah oprávnění je překročen.

**5. Řešení.** Podnikatel nesmí UI převzít do vlastních systémů, dokud nedojde ke změně formy přístupu a vydání nového osvědčení pro formu a) (osvědčení nelze pouze „rozšířit" — § 20 váže formu na konkrétní osvědčení, jež se mění). Postup: podnikatel požádá Úřad o nové osvědčení pro formu a), doloží zajištění plné škály ochrany podle § 5 (ZO, certifikovaný IS, administrativní bezpečnost). Do té doby zůstává u modelu, kdy zaměstnanci pracují s UI v prostorách ministerstva. Riziko/alternativa: faktické převzetí UI bez nového osvědčení zakládá porušení zákona a možnou odpovědnost.

**6. Varianty.** (a) Kdyby zaměstnanci nadále přistupovali k UI jen u ministerstva a do vlastních systémů by se nic nepřenášelo, postačila by personální bezpečnost a forma b) by nadále vyhovovala. (b) Kdyby šlo o UI stupně Vyhrazené, vstupovala by do hry i vazba na prohlášení podnikatele (§ 15a) a schvalování IS/KS na dobu jeho platnosti (§ 34 odst. 3, § 35 odst. 5).

#### G. Protiargumenty a rizika

- *Protiargument 1: „Osvědčení podnikatele je univerzální, forma je jen poznámka."* Neutralizace: forma se podle § 54 odst. 3 písm. c) povinně vyznačuje a podle § 20 odst. 2 přímo určuje rozsah povinných druhů ochrany; není to bezvýznamný údaj, ale obsahové vymezení oprávnění.
- *Protiargument 2: „Personální bezpečnost je dostatečná i pro UI v systémech podnikatele."* Neutralizace: § 20 odst. 2 zužuje povinnost na personální bezpečnost výslovně jen pro formu b); jakmile UI vzniká u podnikatele nebo mu je poskytnuta, nastupuje plná škála podle § 5.
- *Slabé místo:* hranice mezi „přístupem v cizím prostředí" a „poskytnutím UI" může být u cloudových a vzdálených řešení nezřetelná — rozhodující je, kde UI fakticky vzniká, je ukládána a zpracovávána.

#### H. Praktický závěr

§ 20 rozlišuje dvě formy přístupu podnikatele: u formy b) (zaměstnanci přistupují k UI mimo podnikatele) postačí personální bezpečnost, u formy a) je nutná plná ochrana podle § 5. Forma je vyznačena v osvědčení a její změna vyžaduje nové osvědčení.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Určit, zda UI u podnikatele vzniká / je mu poskytnuta (forma a), nebo k ní jen přistupují zaměstnanci v cizím prostředí (forma b).
- [ ] Ověřit formu vyznačenou v osvědčení (§ 54 odst. 3 písm. c)).
- [ ] U formy b) zajistit a doložit personální bezpečnost [§ 5 písm. a)] — poučení a výběr zaměstnanců.
- [ ] Při změně modelu nakládání s UI včas požádat o nové osvědčení pro odpovídající formu.

**Typicky rozhodné důkazy / podklady:** smlouva o výkonu činnosti pro podnikatele, osvědčení podnikatele s vyznačenou formou, evidence přístupů zaměstnanců a jejich osvědčení/poučení, dokumentace IS a fyzické bezpečnosti (u formy a).

---


<!-- LEGAL-REVISION:BEGIN id=8931e7048115affc422b generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 20 — Formy přístupu podnikatele k utajované informaci

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Podnikatel má přístup k utajované informaci,
>
> - a) která u něho vzniká, nebo je mu poskytnuta, nebo
>
> - b) ke které mají přístup zaměstnanci podnikatele nebo osoby jednající jménem podnikatele nebo za podnikatele, a to v souvislosti s výkonem pracovní nebo jiné činnosti pro podnikatele na základě smlouvy, aniž by byla podnikateli poskytnuta nebo u něho vznikala.
>
> (2) V případě přístupu podle odstavce 1 písm. b) musí podnikatel splňovat podmínku podle § 16 odst. 1 písm. c) pouze zajištěním ochrany utajované informace personální bezpečností [§ 5 písm. a)].

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 16, § 5

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=8931e7048115affc422b -->

### Hlava IV — Administrativní bezpečnost

### § 21 — Vyznačování údajů, evidence, manipulace, přeprava, skartace

> **§ 21 odst. 1**
>
> *Na utajovanou informaci je původce povinen vyznačit svůj název, stupeň jejího utajení, její evidenční označení a datum jejího vzniku, není-li dále stanoveno jinak.*

**Výklad:**

**Judikatura (z místních zdrojů):**

- *NSS* [7 As 276/2019 - 41](https://vyhledavac.nssoud.cz/DokumentOriginal/Text/658845) — 29. 4. 2021
  > „Je výhradně na původci informace, aby rozhodl o jejím utajení a v souladu s § 21 odst. 1 zákona č. 412/2005 Sb. o ochraně utajovaných informací a o bezpečnostní způsobilosti … vyznačil stupeň jejího utajení, případně jej podle § 22 odst. 4 téhož zákona změnil či zrušil. Byť je takovým postupem nepochybně zasaženo do procesních práv účastníka řízení, jedná se o zásah odůvodněný zájmem na ochraně utajovaných informací"

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

#### F. Kazuistika

**1. Modelová situace.** Referent odboru ministerstva vytvoří analytický materiál stupně Tajné. Při jeho rozmnožení pro poradu nechá zhotovit tři kopie, aniž si vyžádá písemný souhlas přímo nadřízené osoby; jednu kopii následně přepraví na jiné pracoviště v běžné aktovce bez kurýrního režimu. Po reorganizaci se materiál nedohledá. Účastníci: původce (ministerstvo), referent (zaměstnanec), odpovědná osoba, Úřad (kontrola). Důkazy: podací deník UI, evidence pohybu, kurýrní list (chybí), záznamy o souhlasu s reprodukcí (chybí), výslech zúčastněných osob.

**2. Právní otázka.** Byly porušeny povinnosti administrativní bezpečnosti podle § 21 — konkrétně podmínky reprodukce (odst. 6) a přepravy (odst. 7) — a jaké z toho plynou důsledky pro nakládání s UI stupně Tajné?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 21 — vyznačování identifikačních údajů (odst. 1), evidence v administrativních pomůckách (odst. 5), reprodukce dle stupně utajení (odst. 6), přeprava jen v uzavřeném obalu kurýrem/držitelem poštovní licence (odst. 7).
- *Související ustanovení téhož zákona:* § 22 (vyznačování a změna stupně), § 4 (stupně utajení), § 37 odst. 5 (evidenční pomůcky kryptomateriálu), § 69 a násl. (přestupky a kontrola — porušení povinností).
- *Související předpisy:* vyhláška č. 529/2005 Sb., o administrativní bezpečnosti a o registrech UI (pečetě, kurýrní listy, přebírací protokoly); zákon č. 499/2004 Sb. (skartace — odst. 10); rozhodnutí Rady 2013/488/EU (EUCI — odst. 11).
- *Judikatura:* NSS 7 As 276/2019 (29. 4. 2021) — je výhradně na původci, aby rozhodl o utajení a v souladu s § 21 odst. 1 vyznačil stupeň, případně jej podle § 22 odst. 4 změnil; takový zásah do procesních práv je odůvodněn zájmem na ochraně UI.

**4. Subsumpce.** Reprodukce UI stupně Tajné je podle odst. 6 přípustná jen s písemným souhlasem přímo nadřízené osoby — souhlas chyběl, znak porušen. Přeprava podle odst. 7 musí probíhat v přenosné schránce/uzavřeném obalu a prostřednictvím kurýra či držitele poštovní licence — přeprava v běžné aktovce mimo kurýrní režim tyto znaky nenaplňuje, znak porušen. Vyznačení identifikátorů (odst. 1) bylo splněno. Evidence pohybu (odst. 5) nebyla řádně vedena, došlo ke ztrátě sledovatelnosti.

**5. Řešení.** Jde o porušení povinností administrativní bezpečnosti se vznikem bezpečnostního incidentu (ztráta UI stupně Tajné). Správný postup: neprodlené ohlášení kompromitace/úniku odpovědné osobě a Úřadu, šetření okolností, vyvození odpovědnosti zaměstnance (kárná/přestupková rovina), nápravná opatření v evidenci a režimu reprodukce/přepravy. Procesně: rekonstrukce pohybu UI z podacího deníku, prošetření, zda nedošlo k vyzrazení. Riziko/alternativa: pokud by se prokázalo zpřístupnění neoprávněné osobě, hrozí trestněprávní rovina (ohrožení utajované informace).

**6. Varianty.** (a) Šlo-li by o UI stupně Vyhrazené, reprodukce by zákonem omezena nebyla a odpovědná osoba by mohla u podkladových materiálů vyloučit i evidenci (odst. 5) — porušení by se redukovalo na vadnou přepravu. (b) Šlo-li by o UI stupně Přísně tajné, reprodukce by vyžadovala písemný souhlas přímo původce a porušení by bylo závažnější.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Interní přeprava mezi pracovišti téhož orgánu nepodléhá kurýrnímu režimu."* Neutralizace: odst. 7 nerozlišuje interní a externí přepravu UI v listinné podobě; požaduje uzavřený obal a kvalifikovaného přepravce vždy, bez ohledu na vzdálenost.
- *Protiargument 2: „Souhlas s reprodukcí byl dán ústně, což postačí."* Neutralizace: odst. 6 výslovně žádá písemný souhlas (u T/D přímo nadřízené osoby); ústní souhlas zákonný požadavek nesplňuje a nelze jej dodatečně nahradit.
- *Slabé místo:* jednotlivé povinnosti § 21 jsou rozdrobeny do mnoha odstavců s odlišnými adresáty (původce, odpovědná osoba, kurýr); v praxi hrozí, že se některá povinnost přehlédne — proto je klíčová provázanost s prováděcí vyhláškou.

#### H. Praktický závěr

§ 21 tvoří jádro administrativní bezpečnosti: každá UI musí nést čtyři identifikátory, být evidována (vč. pohybu) a reprodukce, přeprava i skartace probíhají v zákonem odstupňovaném režimu podle stupně utajení. Detaily upravuje vyhláška č. 529/2005 Sb.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Ověřit vyznačení všech čtyř identifikátorů (název původce, stupeň, evidenční označení, datum vzniku).
- [ ] Doložit evidenci UI a jejího pohybu v administrativních pomůckách (podací deník UI).
- [ ] U reprodukce zajistit písemný souhlas dle stupně (PT — původce; T/D — přímo nadřízená osoba).
- [ ] Přepravu provést v uzavřeném obalu kurýrem/držitelem poštovní licence s kurýrním listem a přebíracím protokolem.
- [ ] Skartaci provést podle zákona č. 499/2004 Sb. způsobem znemožňujícím obnovení; u EUCI dodržet nouzový režim (odst. 11).

**Typicky rozhodné důkazy / podklady:** podací deník UI a evidence pohybu, kurýrní listy a přebírací protokoly, písemné souhlasy s reprodukcí, skartační protokoly, oznámení Úřadu o incidentu.

---


<!-- LEGAL-REVISION:BEGIN id=b14fcac09e6a38977733 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 21

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Na utajovanou informaci je původce povinen vyznačit svůj název, stupeň jejího utajení, její evidenční označení a datum jejího vzniku, není-li dále stanoveno jinak.
>
> (2) Na utajované informaci poskytnuté České republice cizí mocí vyznačí orgán státu, právnická osoba podle [[#§ 60b|§ 60b]] nebo podnikatel, pokud tuto utajovanou informaci evidují jako první (§ 77 až 79), stupeň utajení, který je uveden v [[#§ 4|§ 4]], a to v souladu s mezinárodní smlouvou, kterou je Česká republika vázána a na jejímž základě je utajovaná informace poskytována, včetně případné zkratky podle této smlouvy (například zkratka „EU“, „EURA“ nebo „NATO“), nebo v souladu s požadavkem cizí moci nebo se stupněm utajení cizí mocí na poskytnuté utajované informaci vyznačeným; název původce a datum vzniku utajované informace se nevyznačuje.
>
> (3) Na utajované informaci, která vyžaduje zpřísněné podmínky při zajišťování jednotlivých druhů ochrany utajovaných informací (dále jen „zvláštní režim nakládání“) v oblastech stanovených zejména mezinárodní smlouvou, kterou je Česká republika vázána, nebo předpisy mezinárodní organizace, jíž je Česká republika členem, se vyznačí též příslušné doplňující označení (například označení „KRYPTO“, jde-li o utajovanou informaci z oblasti kryptografické ochrany, a označení „ATOMAL“, jde-li o utajovanou informaci z oblasti zbraní hromadného ničení).
>
> (4) Nelze-li na informaci údaje podle odstavců 1 až 3 vyznačit, uvedou se tak, aby je bylo možné kdykoliv zjistit.
>
> (5) Utajovaná informace se eviduje v administrativních pomůckách určených prováděcím právním předpisem a způsobem tam stanoveným; to neplatí, pokud u podkladových materiálů stupně utajení Vyhrazené k utajované informaci stupně utajení Vyhrazené odpovědná osoba stanoví, že se neevidují. V administrativních pomůckách se zaznamenává též předávání, přebírání nebo jiný pohyb utajované informace nebo seznámení se s jejím obsahem.
>
> (6) Opis, kopie nebo překlad utajované informace stupně utajení Přísně tajné nebo výpis z ní mohou být vyhotoveny pouze na základě písemného souhlasu původce; jde-li o utajovanou informaci stupně utajení Tajné nebo Důvěrné, mohou být vyhotoveny pouze s písemným souhlasem přímo nadřízené osoby.
>
> (7) Utajovanou informaci lze přepravovat nebo přenášet pouze v přenosných schránkách nebo v uzavřeném obalu v závislosti na jejím stupni utajení a na jejím nosiči; přepravovat ji lze pouze prostřednictvím kurýra nebo držitele poštovní licence17).
>
> (8) Převzetí utajované informace příjemce potvrdí, nestanoví-li tento zákon jinak (§ 23 odst. 1).
>
> (9) Uloženou utajovanou informaci lze zapůjčit pouze fyzickým osobám, které jsou k orgánu státu, právnické osobě podle [[#§ 60b|§ 60b]] nebo podnikateli ve služebním poměru nebo v pracovněprávním, členském či obdobném vztahu.
>
> (10) Při vyřazování utajované informace ve skartačním řízení se postupuje podle zvláštního právního předpisu18).
>
> (11) V případě, kdy hrozí bezprostřední riziko vyzrazení utajované informace Evropské unie, původce, kurýr nebo adresát utajovanou informaci zničí způsobem, který znemožní její obnovení nebo obnovení její části; adresát nebo kurýr oznámí neprodleně tuto skutečnost písemně původci a Úřadu.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 60b, § 77, § 4, § 23

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=b14fcac09e6a38977733 -->

### § 22 — Vyznačování a změna stupně utajení

> **§ 22**
>
> *(1) Stupeň utajení na utajované informaci vyznačí původce při jejím vzniku, nestanoví-li tento zákon jinak (§ 70).*
>
> *(2) Vyznačení stupně utajení na utajované informaci musí být zachováno po celou dobu trvání důvodů utajení. Bez souhlasu původce nebo poskytující cizí moci nesmí být stupeň utajení změněn nebo zrušen.*
>
> *(3) Vyžaduje-li to charakter utajované informace, musí původce vyznačit na utajované informaci dobu, po kterou bude informace utajována; stupeň utajení zaniká uplynutím vyznačené doby.*
>
> *(4) Stupeň utajení původce neprodleně zruší nebo změní po zjištění, že pominul důvod pro utajení informace, důvody pro utajení neodpovídají stanovenému stupni utajení nebo byl-li stupeň utajení stanoven neoprávněně anebo po obdržení výzvy podle odstavce 9, a na utajované informaci toto zrušení nebo změnu jejího stupně utajení vyznačí.*
>
> *(5) Původce je povinen prověřit, zda důvod pro utajení informace trvá, a to nejméně jednou za pět let ode dne jejího vzniku.*
>
> *(6) Provedl-li původce zrušení nebo změnu stupně utajení podle odstavce 4, oznámí tuto skutečnost neprodleně písemně adresátům utajované informace. Adresáti utajované informace oznámí neprodleně písemně tuto skutečnost všem dalším adresátům, kterým utajovanou informaci zpřístupnili.*
>
> *(7) Adresát po obdržení oznámení podle odstavce 6 na utajované informaci zrušení nebo změnu stupně utajení vyznačí.*
>
> *(8) Zanikl-li původce, provede zrušení nebo změnu stupně utajení podle odstavce 4 a oznámení podle odstavce 6 jeho právní nástupce, a není-li jej, nebo nesplňuje-li právní nástupce podmínky přístupu k utajované informaci, Úřad.*
>
> *(9) Úřad na žádost orgánu státu, který vede řízení, v němž se nakládá s utajovanou informací, bez zbytečného odkladu ověří, zda důvody pro utajení odpovídají stanovenému stupni utajení nebo zda byl stupeň utajení stanoven oprávněně. Pokud Úřad po konzultaci s původcem utajované informace shledá, že důvody pro utajení neodpovídají stanovenému stupni utajení nebo že byl stupeň utajení stanoven neoprávněně, vyzve původce, aby v případě posuzované utajované informace postupoval podle odstavců 4 a 5 v souladu se zjištěním Úřadu. Je-li původcem utajované informace zpravodajská služba, ověření podle věty první se v případě správního řízení neprovede; pro jiné řízení jej provede příslušná zpravodajská služba.*

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

#### F. Kazuistika

**1. Modelová situace.** Účastník správního řízení vedeného před stavebním úřadem se domáhá nahlédnutí do podkladu, jejž do spisu vložil jiný orgán státu a označil jej stupněm Důvěrné. Účastník namítá, že informace je utajena neoprávněně a brání mu v obraně. Orgán státu vedoucí řízení proto požádá Úřad o ověření, zda důvody utajení odpovídají stupni a zda byl stupeň stanoven oprávněně. Účastníci: účastník řízení, orgán vedoucí řízení, původce UI, Úřad. Důkazy: samotná UI a její odůvodnění utajení, žádost orgánu podle odst. 9, stanovisko původce, doklad o periodické pětileté prověrce (odst. 5).

**2. Právní otázka.** Za jakých podmínek a jakým postupem lze dosáhnout přezkumu a změny/zrušení stupně utajení podle § 22, je-li klasifikace zpochybněna účastníkem řízení, a kdo je k jejímu zrušení oprávněn?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 22 — vyznačení stupně původcem (odst. 1), zákaz změny bez souhlasu původce (odst. 2), povinnost neprodleně zrušit/změnit stupeň po odpadnutí důvodu (odst. 4), pětiletá prověrka (odst. 5), notifikace adresátům (odst. 6, 7), kontrolní oprávnění Úřadu na žádost orgánu vedoucího řízení (odst. 9).
- *Související ustanovení téhož zákona:* § 21 (vyznačování údajů), § 4 (stupně utajení), § 3 (újma a nevýhodnost — materiální kritérium utajení), § 70 (výjimky z vyznačení při vzniku).
- *Související předpisy:* správní řád (§ 38 — nahlížení do spisu, omezení u UI); soudní řád správní; zákon č. 106/1999 Sb. (vztah k poskytování informací).
- *Judikatura:* NSS 7 As 276/2019 (29. 4. 2021) — je výhradně na původci, aby rozhodl o utajení a podle § 21 odst. 1 vyznačil stupeň, případně jej podle § 22 odst. 4 změnil či zrušil; zásah do procesních práv účastníka je odůvodněn zájmem na ochraně UI.

**4. Subsumpce.** Účastník sám klasifikaci měnit nemůže (odst. 2 — to přísluší původci/nástupci/cizí moci). Orgán vedoucí řízení je však aktivně legitimován požádat Úřad podle odst. 9 o ověření správnosti klasifikace. Shledá-li Úřad po konzultaci s původcem, že důvody neodpovídají stupni nebo byl stanoven neoprávněně, vyzve původce k postupu podle odst. 4 a 5. Původce má pak nepřenosnou povinnost stupeň neprodleně změnit/zrušit a vyznačit to na UI.

**5. Řešení.** Správný postup: orgán vedoucí řízení podá Úřadu žádost podle odst. 9. Úřad provede ověření, konzultuje původce a případně jej vyzve k přehodnocení. Vyhoví-li původce (nebo je-li klasifikace shledána oprávněnou), výsledek se promítne do možnosti účastníka nahlížet. Je-li původcem zpravodajská služba a jde o správní řízení, ověření Úřad neprovádí — provede je sama zpravodajská služba. Procesní kroky: žádost, ověření, výzva, změna/zrušení a notifikace adresátům (odst. 6, 7). Riziko/alternativa: setrvá-li původce na klasifikaci a Úřad ji shledá oprávněnou, omezení nahlížení trvá; přezkum zákonnosti je možný ve správním soudnictví.

**6. Varianty.** (a) Zanikl-li by původce bez právního nástupce, přešla by pravomoc zrušit/změnit stupeň na Úřad (odst. 8). (b) Byl-li by původcem zpravodajská služba a nešlo by o správní řízení, ověření by provedla příslušná zpravodajská služba (odst. 9 in fine), nikoli Úřad.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Úřad může stupeň utajení sám zrušit."* Neutralizace: odst. 9 dává Úřadu jen pravomoc ověřit a vyzvat původce; samotné zrušení/změna náleží původci (odst. 2 a 4) — Úřad klasifikaci nenahrazuje.
- *Protiargument 2: „Účastník řízení může klasifikaci napadnout přímo."* Neutralizace: účastník nemá aktivní legitimaci ke změně stupně; iniciovat ověření může orgán vedoucí řízení (odst. 9), případně se účastník brání zákonností omezení nahlížení v rámci řízení a jeho soudního přezkumu.
- *Slabé místo:* asymetrie utajování a odtajňování — pětiletá prověrka (odst. 5) je v praxi slabě vymáhána a dokumenty zůstávají utajeny déle, než věcně třeba; výjimka pro zpravodajské služby (odst. 9) navíc oslabuje vnější kontrolu.

#### H. Praktický závěr

Klasifikační autonomie náleží původci; měnit/rušit stupeň smí jen původce, jeho nástupce nebo cizí moc, nikoli adresát. Vnější korekci umožňuje kontrolní oprávnění Úřadu na žádost orgánu vedoucího řízení (odst. 9), s výjimkou pro zpravodajské služby ve správním řízení.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Ověřit, zda stupeň vyznačil původce při vzniku a zda trvá důvod utajení (§ 3, § 4).
- [ ] Při pochybnostech o klasifikaci využít žádost orgánu vedoucího řízení Úřadu podle § 22 odst. 9.
- [ ] Doložit splnění pětileté prověrky (odst. 5) a notifikaci adresátům při změně/zrušení (odst. 6, 7).
- [ ] U zaniklého původce řešit příslušnost právního nástupce, jinak Úřadu (odst. 8).
- [ ] Respektovat zvláštní režim zpravodajských služeb (odst. 9 in fine).

**Typicky rozhodné důkazy / podklady:** samotná UI s vyznačeným stupněm a odůvodněním utajení, žádost a odpověď podle odst. 9, stanovisko původce, doklady o periodické prověrce a o notifikaci adresátům.

---


<!-- LEGAL-REVISION:BEGIN id=739e99ab8bb037a45358 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 22

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Stupeň utajení na utajované informaci vyznačí původce při jejím vzniku, nestanoví-li tento zákon jinak ([[#§ 70|§ 70]]).
>
> (2) Vyznačení stupně utajení na utajované informaci musí být zachováno po celou dobu trvání důvodů utajení. Bez souhlasu původce nebo poskytující cizí moci nesmí být stupeň utajení změněn nebo zrušen.
>
> (3) Vyžaduje-li to charakter utajované informace, musí původce vyznačit na utajované informaci dobu, po kterou bude informace utajována; stupeň utajení zaniká uplynutím vyznačené doby.
>
> (4) Stupeň utajení původce neprodleně zruší nebo změní po zjištění, že pominul důvod pro utajení informace, důvody pro utajení neodpovídají stanovenému stupni utajení nebo byl-li stupeň utajení stanoven neoprávněně anebo po obdržení výzvy podle odstavce 9, a na utajované informaci toto zrušení nebo změnu jejího stupně utajení vyznačí.
>
> (5) Původce je povinen prověřit, zda důvod pro utajení informace trvá, a to nejméně jednou za pět let ode dne jejího vzniku.
>
> (6) Provedl-li původce zrušení nebo změnu stupně utajení podle odstavce 4, oznámí tuto skutečnost neprodleně písemně adresátům utajované informace. Adresáti utajované informace oznámí neprodleně písemně tuto skutečnost všem dalším adresátům, kterým utajovanou informaci zpřístupnili.
>
> (7) Adresát po obdržení oznámení podle odstavce 6 na utajované informaci zrušení nebo změnu stupně utajení vyznačí.
>
> (8) Zanikl-li původce, provede zrušení nebo změnu stupně utajení podle odstavce 4 a oznámení podle odstavce 6 jeho právní nástupce, a není-li jej, nebo nesplňuje-li právní nástupce podmínky přístupu k utajované informaci, Úřad.
>
> (9) Úřad na žádost orgánu státu, který vede řízení, v němž se nakládá s utajovanou informací, bez zbytečného odkladu ověří, zda důvody pro utajení odpovídají stanovenému stupni utajení nebo zda byl stupeň utajení stanoven oprávněně. Pokud Úřad po konzultaci s původcem utajované informace shledá, že důvody pro utajení neodpovídají stanovenému stupni utajení nebo že byl stupeň utajení stanoven neoprávněně, vyzve původce, aby v případě posuzované utajované informace postupoval podle odstavců 4 a [[#§ 5|5]] v souladu se zjištěním Úřadu. Je-li původcem utajované informace zpravodajská služba, ověření podle věty první se v případě správního řízení neprovede; pro jiné řízení jej provede příslušná zpravodajská služba.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 70, § 5

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=739e99ab8bb037a45358 -->

### § 23 — Specifické situace a zmocňovací ustanovení

§ 23 obsahuje:
- **odst. 1** — výjimky z povinnosti potvrzení převzetí (např. mezi zpravodajskými službami při operativní spolupráci),
- **odst. 2** — zmocnění pro prováděcí předpis (vyhláška č. 529/2005 Sb., o administrativní bezpečnosti),
- **odst. 3** — speciální režim **elektronického systému spisové služby** (eSSL) — pro UI v eSSL splňujícím národní standard se použijí ustanovení obdobně,
- **odst. 4** — **převodní tabulky** mezinárodních stupňů utajení (Úřad je publikuje sdělením ve Sbírce zákonů).

#### F. Kazuistika

**1. Modelová situace.** Orgán státu zavádí elektronický systém spisové služby (eSSL) a hodlá v něm vést také UI stupně Důvěrné. Vedoucí spisové služby řeší, zda lze v eSSL UI evidovat a manipulovat s ní bez samostatného certifikovaného IS, a jaká pravidla administrativní bezpečnosti se uplatní. Současně přijímá UI od zahraničního partnera označenou stupněm „NATO CONFIDENTIAL" a potřebuje určit český ekvivalent. Účastníci: orgán státu (provozovatel eSSL), Úřad (gestor administrativní bezpečnosti, vydavatel převodních tabulek), zahraniční původce. Důkazy: doklad o splnění národního standardu eSSL, sdělení Úřadu s převodní tabulkou, evidenční pomůcky.

**2. Právní otázka.** Lze UI vést a manipulovat s ní v eSSL podle § 23 odst. 3 a jak se podle § 23 odst. 4 určí český ekvivalent zahraničního stupně utajení?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 23 — výjimky z potvrzení převzetí (odst. 1), zmocnění k vyhlášce o administrativní bezpečnosti (odst. 2), zvláštní režim eSSL splňujícího národní standard (odst. 3), převodní tabulky mezinárodních stupňů utajení publikované Úřadem (odst. 4).
- *Související ustanovení téhož zákona:* § 21 (administrativní bezpečnost — evidence, manipulace), § 22 (vyznačování stupně), § 4 (stupně utajení), § 77–79 (UI cizí moci a její evidence), § 34 (IS — odlišení od eSSL).
- *Související předpisy:* vyhláška č. 529/2005 Sb. (administrativní bezpečnost); zákon č. 499/2004 Sb. a předpisy o eSSL (národní standard pro elektronické systémy spisové služby); mezinárodní bezpečnostní smlouvy (NATO, EU).
- *Judikatura:* judikatura NSS k § 21/§ 22 (např. 7 As 276/2019) potvrzuje primát původce při klasifikaci; pro převod zahraničních stupňů je rozhodný akt Úřadu (sdělení), nikoli volná úvaha adresáta.

**4. Subsumpce.** Splňuje-li eSSL národní standard, použijí se podle odst. 3 ustanovení o administrativní bezpečnosti obdobně — eSSL pak může sloužit k evidenci a manipulaci s UI, aniž by šlo o samostatný certifikovaný IS podle § 34. Pro zahraniční stupeň „NATO CONFIDENTIAL" se český ekvivalent určí podle převodní tabulky publikované Úřadem sdělením ve Sbírce zákonů (odst. 4); orgán jej nestanovuje vlastní úvahou.

**5. Řešení.** Orgán doloží splnění národního standardu eSSL a uplatní obdobně pravidla administrativní bezpečnosti (§ 21); samostatná certifikace IS podle § 34 se pro tento režim nevyžaduje, jde-li o naplnění výjimky odst. 3 (nutno odlišit od plnohodnotného nakládání s UI v IS, kde certifikace nutná je). Zahraniční UI vyznačí příslušnou zkratkou a českým ekvivalentem podle převodní tabulky (odst. 4). Procesní kroky: ověření standardu, nastavení evidenčních pomůcek, aplikace převodní tabulky. Riziko/alternativa: nesplňuje-li eSSL standard, výjimka odst. 3 se neuplatní a manipulace s UI v něm je nepřípustná.

**6. Varianty.** (a) Nesplňuje-li eSSL národní standard, musel by orgán pro UI použít samostatný certifikovaný IS podle § 34. (b) Jde-li o operativní spolupráci mezi zpravodajskými službami, mohou se uplatnit výjimky z potvrzení převzetí podle odst. 1, takže formální potvrzovací režim se neaplikuje.

#### G. Protiargumenty a rizika

- *Protiargument 1: „eSSL je vždy IS, proto vyžaduje certifikaci podle § 34."* Neutralizace: § 23 odst. 3 zakládá zvláštní režim — pro eSSL splňující národní standard se použijí ustanovení o administrativní bezpečnosti obdobně; jde o samostatnou úpravu odlišnou od certifikačního režimu IS.
- *Protiargument 2: „Český ekvivalent zahraničního stupně lze dovodit výkladem."* Neutralizace: odst. 4 svěřuje stanovení převodních tabulek Úřadu, jenž je publikuje sdělením ve Sbírce zákonů; adresát se řídí tímto aktem, nikoli vlastní úvahou.
- *Slabé místo:* odst. 1 (výjimky z potvrzení převzetí) a odst. 3 (eSSL) jsou rámcové a odkazují na prováděcí předpis a národní standard; bez znalosti aktuální vyhlášky a standardu hrozí chybná aplikace.

#### H. Praktický závěr

§ 23 doplňuje administrativní bezpečnost o tři praktické pilíře: výjimky z potvrzení převzetí, zvláštní režim eSSL při splnění národního standardu a převodní tabulky zahraničních stupňů utajení vydávané Úřadem. Konkrétní pravidla nese vyhláška č. 529/2005 Sb. a standard eSSL.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Ověřit, zda eSSL splňuje národní standard, má-li v něm být nakládáno s UI (odst. 3).
- [ ] Pro zahraniční UI použít aktuální převodní tabulku publikovanou Úřadem (odst. 4).
- [ ] Posoudit, zda se uplatní výjimky z potvrzení převzetí (odst. 1).
- [ ] Nastavit evidenční pomůcky a manipulaci podle vyhlášky č. 529/2005 Sb.

**Typicky rozhodné důkazy / podklady:** doklad o splnění národního standardu eSSL, sdělení Úřadu s převodními tabulkami, evidenční pomůcky a doklady o manipulaci, případně mezinárodní bezpečnostní smlouva.

---


<!-- LEGAL-REVISION:BEGIN id=b5ae6a8e0279033ba168 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 23

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Nejde-li o utajovanou informaci vyžadující zvláštní režim nakládání, nevztahuje se povinnost stanovená v § 21 odst. 8 na předávání utajované informace
>
> - a) do stupně utajení Tajné mezi zpravodajskými službami a obdobnými službami cizí moci, uskutečňované v rámci spolupráce podle zvláštního právního předpisu19) v případech, kdy postup podle § 21 odst. 8 nelze dodržet,
>
> - b) stupně utajení Vyhrazené, stanoví-li tak odpovědná osoba a nepožaduje-li výslovně cizí moc nebo původce utajované informace potvrzení jejího převzetí.
>
> (2) Prováděcí právní předpis stanoví
>
> - a) způsob vyznačování náležitostí na utajované informaci podle § 21 odst. 1 až 4 a § 22 odst. 1, [[#§ 3|3]], [[#§ 4|4]] a [[#§ 7|7]], zejména ve vazbě na stupeň utajení utajované informace a nosič utajované informace,
>
> - b) druhy administrativních pomůcek uvedených v § 21 odst. 5, jejich náležitosti a organizační a technické požadavky na jejich vedení, a rozsah podkladových materiálů stupně utajení Vyhrazené k utajované informaci stupně utajení Vyhrazené,
>
> - c) náležitosti souhlasu k pořizování opisu, kopie, výpisu a překladu utajované informace (§ 21 odst. 6), způsob vyznačování náležitostí na nich a způsob pořizování výpisu,
>
> - d) podrobnosti k přepravě, přenášení, převzetí a zapůjčování utajované informace podle § 21 odst. 7 až 9 a § 77 odst. 6 a [[#§ 8|8]] a k další s tím související manipulaci s ní, včetně organizačního zajištění těchto činností, požadavků na přenosné schránky a obaly a vyznačování příslušných náležitostí na nich, a to zejména ve vazbě na stupeň utajení utajované informace a nosič utajované informace.
>
> (3) Na zpracování a přenos utajované informace zpracovávané v elektronickém systému spisové služby, který je součástí informačního systému nakládajícího s utajovanými informacemi a splňuje požadavky stanovené národním standardem pro elektronické systémy spisové služby, s výjimkou těch požadavků, jejichž užití vylučuje splnění podmínek certifikace informačního systému pro nakládání s utajovanými informacemi nebo jejichž užití vylučuje zvláštní povaha působnosti původce55), se použijí odstavec 1, § 21 odst. 1 až 4, § 21 odst. 5, s výjimkou části věty první za středníkem, § 21 odst. 6, pokud jde o překlad, § 21 odst. 8 až 10 a [[#§ 22|§ 22]] obdobně. V ostatních případech se ustanovení této hlavy na zpracování a přenos utajovaných informací v informačních a komunikačních systémech, zařízeních podle [[#§ 36|§ 36]] a kryptografických prostředcích nepoužijí.
>
> (4) Úřad vyhlašuje sdělením ve Sbírce zákonů a mezinárodních smluv převodní tabulky stupňů utajení podle mezinárodních smluv, kterými je Česká republika vázána.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 21, § 22, § 3, § 4, § 7, § 77, § 8, § 36

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=b5ae6a8e0279033ba168 -->

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

#### F. Kazuistika

**1. Modelová situace.** Ředitelství orgánu státu chce pravidelně pořádat porady, na nichž budou ústně projednávány informace stupně Tajné, a to ve své standardní zasedací místnosti, která je součástí běžných kancelářských prostor (objekt), nikoli vyhrazenou jednací oblastí. Současně hodlá UI stupně Tajné ukládat v uzamykatelné kartotéce v běžné kanceláři. Účastníci: odpovědná osoba, bezpečnostní ředitel, Úřad (kontrola fyzické bezpečnosti). Důkazy: projekt fyzické bezpečnosti (§ 32), určení objektu, ZO a JO, parametry trezoru/skříně podle vyhlášky, plán prostor.

**2. Právní otázka.** Lze UI stupně Tajné pravidelně projednávat v běžné zasedací místnosti a ukládat v uzamykatelné kartotéce v kanceláři, nebo § 24 vyžaduje k projednávání jednací oblast a k ukládání zabezpečenou oblast příslušné kategorie?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 24 — trojí topologie (objekt, zabezpečená oblast, jednací oblast); UI stupně PT/T lze pravidelně projednávat pouze v JO (odst. 4); místa zpracování UI (odst. 5); ukládání UI v ZO příslušné kategorie a v trezoru/uzamykatelné skříni (odst. 6).
- *Související ustanovení téhož zákona:* § 25 (kategorie a třídy ZO), § 26 (projednávání v JO, antiodposlechové prověření), § 27–31 (opatření fyzické bezpečnosti a bodové hodnocení), § 32 (projekt fyzické bezpečnosti).
- *Související předpisy:* vyhláška č. 528/2005 Sb., o fyzické bezpečnosti (parametry ZO, JO, trezorů, schránek).
- *Judikatura:* k fyzické bezpečnosti chybí výrazná publikovaná judikatura; rozhodné jsou kontrolní závěry Úřadu a soulad s vyhláškou — nosné je pravidlo, že nakládání s UI mimo prostor příslušné kategorie je porušením zákona.

**4. Subsumpce.** Pravidelné ústní projednávání UI stupně Tajné je podle odst. 4 přípustné pouze v jednací oblasti — běžná zasedací místnost, není-li určena a zabezpečena jako JO, tento znak nenaplňuje. Ukládání UI stupně Tajné je podle odst. 6 přípustné v ZO příslušné kategorie (nebo vyšší) a v trezoru/uzamykatelné skříni splňující parametry vyhlášky — uzamykatelná kartotéka v běžné kanceláři mimo ZO příslušné kategorie tyto znaky nesplňuje.

**5. Řešení.** Orgán musí pro pravidelné projednávání UI stupně Tajné zřídit a v projektu fyzické bezpečnosti určit jednací oblast (§ 24 odst. 4, § 26) a pro ukládání zřídit ZO příslušné kategorie s trezorem/skříní podle vyhlášky (odst. 6). Procesní kroky: zpracování/aktualizace projektu fyzické bezpečnosti (§ 32), určení hranic a kategorií/tříd, pořízení certifikovaných úložišť. Riziko/alternativa: pro jednorázové (nikoli pravidelné) projednání by JO nutná nebyla; zpracovávat UI lze i v objektu příslušné kategorie (odst. 5 písm. b), je-li zajištěno, že k ní nemá přístup neoprávněná osoba.

**6. Varianty.** (a) Šlo-li by o UI stupně Vyhrazené, nebyla by pro projednávání JO obligatorně vyžadována (odst. 4 míří jen na PT/T) a režim ukládání by byl mírnější. (b) Mělo-li by jít o ojedinělé projednání UI stupně Tajné, postačilo by zajištění proti přístupu neoprávněné osoby bez zřízení trvalé JO.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Uzamčená kancelář postačí jako úložiště UI."* Neutralizace: odst. 6 žádá ZO příslušné kategorie a navíc trezor/uzamykatelnou skříň s parametry podle vyhlášky č. 528/2005 Sb.; běžná kancelář tyto požadavky nesplňuje.
- *Protiargument 2: „Projednávat UI lze kdekoli v objektu."* Neutralizace: pro pravidelné projednávání UI stupně PT/T odst. 4 výslovně vyžaduje jednací oblast; jiné prostory jsou přípustné jen pro ojedinělé případy a při zajištění proti přístupu neoprávněné osoby.
- *Slabé místo:* zákon používá pojmy objekt/ZO/JO, jejichž konkrétní parametry jsou až ve vyhlášce; bez ní nelze posoudit, zda prostor „příslušné kategorie" odpovídá — rozhodující je bodové hodnocení podle § 31.

#### H. Praktický závěr

§ 24 zavádí tři vrstvy prostorové ochrany: objekt (perimetr), zabezpečenou oblast (zpracování a ukládání) a jednací oblast (projednávání PT/T pouze zde). Ukládání UI vyžaduje ZO příslušné kategorie a certifikované úložiště. Vše se promítá do projektu fyzické bezpečnosti.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Určit, zda jde o zpracování, ukládání nebo projednávání UI, a podle toho zvolit prostor (ZO/JO).
- [ ] Pro pravidelné projednávání UI stupně PT/T zřídit jednací oblast (odst. 4).
- [ ] UI ukládat v ZO příslušné kategorie a v trezoru/uzamykatelné skříni dle vyhlášky (odst. 6).
- [ ] Určení objektu, ZO a JO promítnout do projektu fyzické bezpečnosti (§ 32).

**Typicky rozhodné důkazy / podklady:** projekt fyzické bezpečnosti, určení a plán objektu/ZO/JO, certifikáty trezorů a úložišť, doklady o parametrech podle vyhlášky č. 528/2005 Sb.

---


<!-- LEGAL-REVISION:BEGIN id=52b8ce087a3fdc12efb4 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 24

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Pro zabezpečení ochrany utajovaných informací v rámci fyzické bezpečnosti se určují objekty, zabezpečené oblasti a jednací oblasti.
>
> (2) Objektem je budova nebo jiný ohraničený prostor, ve kterém se zpravidla nachází zabezpečená oblast nebo jednací oblast.
>
> (3) Zabezpečenou oblastí je ohraničený prostor v objektu.
>
> (4) Jednací oblastí je ohraničený prostor v objektu. Utajovanou informaci stupně utajení Přísně tajné nebo Tajné lze pravidelně projednávat pouze v jednací oblasti.
>
> (5) Utajovaná informace se zpracovává
>
> - a) v zabezpečené oblasti příslušné kategorie nebo vyšší,
>
> - b) v objektu příslušné kategorie nebo vyšší, pokud je zajištěno, že k utajované informaci nemá přístup neoprávněná osoba,
>
> - c) v odůvodněných případech s písemným souhlasem odpovědné osoby nebo bezpečnostního ředitele v objektu nižší kategorie, než je stupeň utajení zpracovávané utajované informace, pokud je zajištěno, že k utajované informaci nemá přístup neoprávněná osoba, nebo
>
> - d) v odůvodněných případech s písemným souhlasem odpovědné osoby nebo bezpečnostního ředitele mimo objekt, pokud je zajištěno, že k utajované informaci nemá přístup neoprávněná osoba.
>
> (6) Utajovaná informace se ukládá v zabezpečené oblasti příslušné kategorie nebo vyšší a v ní popřípadě v trezoru, uzamykatelné skříni nebo jiné schránce za podmínek stanovených prováděcím právním předpisem.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Místní znění neobsahuje výslovný vnitřní odkaz.

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=52b8ce087a3fdc12efb4 -->

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

#### F. Kazuistika

**1. Modelová situace.** V zabezpečené oblasti kategorie Tajné, třídy I (na pracovních stolech jsou viditelné UI stupně Tajné), je třeba provést servisní zásah na klimatizaci externím technikem, který nesplňuje podmínky přístupu k UI stupně Tajné. Bezpečnostní ředitel zvažuje, jak technikovi umožnit vstup, aniž by došlo ke zpřístupnění UI neoprávněné osobě. Účastníci: odpovědná osoba/bezpečnostní ředitel, externí technik (neoprávněná osoba), doprovázející zaměstnanec s oprávněním. Důkazy: záznam o vstupu, písemný souhlas s dočasnou změnou třídy (odst. 4), evidence pohybu v ZO, doklad o uložení UI do trezoru.

**2. Právní otázka.** Lze do zabezpečené oblasti třídy I umožnit vstup neoprávněné osobě (technikovi) a za jakých podmínek — postačí doprovod, nebo je nutné prostor dočasně přeřadit do třídy II podle § 25 odst. 4?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 25 — kategorie ZO podle nejvyššího stupně utajení (odst. 1), třídy I a II podle možnosti přístupu (odst. 2), vstup neoprávněné osoby do třídy II jen s doprovázející oprávněnou osobou (odst. 3 in fine), dočasné přeřazení třídy I do třídy II (odst. 4).
- *Související ustanovení téhož zákona:* § 24 (ZO a její ukládací funkce), § 26 (obdobný princip doprovodu u JO), § 27–31 (opatření a bodové hodnocení), § 29 (režimová opatření — manipulace s klíči, kontrola vstupů).
- *Související předpisy:* vyhláška č. 528/2005 Sb., o fyzické bezpečnosti (parametry tříd, podmínky přeřazení).
- *Judikatura:* publikovaná judikatura k tomuto ustanovení je sporá; rozhodující je soulad s vyhláškou a kontrolními standardy Úřadu — nosné je pravidlo, že do třídy I nesmí vstoupit osoba bez oprávnění, dokud je UI fakticky vnímatelná.

**4. Subsumpce.** Ve třídě I vstup = seznámení s UI (UI je viditelná), proto do ní smí jen osoba splňující podmínky přístupu příslušného stupně; technik je neoprávněná osoba a vstup do třídy I za stávajícího stavu mu nelze umožnit. Řešením je dočasné přeřazení třídy I do třídy II podle odst. 4 (uložení UI do trezoru tak, aby vstup neumožňoval její faktické vnímání) na nezbytně nutnou dobu, s písemným souhlasem odpovědné osoby; ve třídě II pak technik vstoupí pouze s doprovázející oprávněnou osobou (odst. 3).

**5. Řešení.** Bezpečnostní ředitel zajistí uklizení/uzamčení veškeré UI do trezorů, vyžádá písemný souhlas odpovědné osoby (nebo jí pověřené osoby) s dočasným přeřazením do třídy II na dobu zásahu a zajistí, aby technika po celou dobu doprovázela oprávněná osoba. Po skončení prací se prostor vrátí do třídy I. Procesní kroky: souhlas, záznam o přeřazení, doprovod, kontrola vynášení. Riziko/alternativa: nebude-li UI fyzicky odstraněna z dohledu, přeřazení do třídy II nelze provést a vstup technika by byl nepřípustný.

**6. Varianty.** (a) Šlo-li by od počátku o ZO třídy II (UI trvale v trezoru), postačil by doprovod oprávněnou osobou bez nutnosti přeřazení (odst. 3). (b) Měl-li by technik vlastní platné osvědčení FO pro stupeň Tajné a poučení, mohl by do třídy I vstoupit i bez přeřazení a bez doprovodu.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Krátký servisní vstup nevyžaduje formality."* Neutralizace: odst. 4 váže přeřazení třídy na písemný souhlas odpovědné osoby a zajištění proti přístupu neoprávněné osoby; absence formálního souhlasu činí vstup neoprávněný bez ohledu na délku.
- *Protiargument 2: „Doprovod stačí i ve třídě I."* Neutralizace: princip doprovodu (vstup neoprávněné osoby s oprávněnou) platí pro třídu II; ve třídě I, kde je UI vnímatelná, by doprovod sám nezabránil seznámení — proto je nutné přeřazení do třídy II.
- *Slabé místo:* posouzení, zda je UI ve třídě II skutečně „nevnímatelná", závisí na faktickém uložení; ledabylé přeřazení (UI zůstane na stole) je jen formální a riziko vyzrazení trvá.

#### H. Praktický závěr

§ 25 kategorizuje ZO podle nejvyššího stupně utajení a třídí je podle toho, zda vstup znamená seznámení s UI (třída I), nebo nikoli (třída II). Do třídy II smí neoprávněná osoba jen s doprovodem; vstup do třídy I vyžaduje oprávnění, nebo dočasné přeřazení do třídy II.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Určit kategorii ZO (nejvyšší stupeň UI) a třídu (I/II) podle faktické vnímatelnosti UI.
- [ ] Pro vstup neoprávněné osoby do třídy I zajistit dočasné přeřazení do třídy II (písemný souhlas, odst. 4).
- [ ] Zajistit doprovod oprávněnou osobou při vstupu neoprávněné osoby do třídy II (odst. 3).
- [ ] Vést záznam o přeřazení třídy a o pohybu osob v ZO.

**Typicky rozhodné důkazy / podklady:** písemný souhlas odpovědné osoby s dočasným přeřazením třídy, záznamy o vstupu a doprovodu, doklad o uložení UI do trezoru, evidence pohybu v ZO.

---


<!-- LEGAL-REVISION:BEGIN id=c12112f46d77a3f51396 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 25

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Zabezpečené oblasti se podle nejvyššího stupně utajení utajované informace, která se v nich ukládá, a objekty se podle nejvyššího stupně utajení utajované informace, která se v nich zpracovává, zařazují do kategorií
>
> - a) Přísně tajné,
>
> - b) Tajné,
>
> - c) Důvěrné, nebo
>
> - d) Vyhrazené.
>
> (2) Zabezpečené oblasti se podle možnosti přístupu k utajované informaci zařazují do tříd
>
> - a) třída I, kdy vstupem do této oblasti dochází k seznámení s utajovanou informací,
>
> - b) třída II, kdy vstupem do této oblasti nedochází k seznámení s utajovanou informací.
>
> (3) Vstup do zabezpečené oblasti a výstup z ní musí být kontrolovány opatřeními podle [[#§ 27|§ 27]]. Neoprávněná osoba může vstoupit pouze do zabezpečené oblasti třídy II, a to s osobou, která má do této oblasti vstup povolen.
>
> (4) V odůvodněných případech s písemným souhlasem odpovědné osoby nebo jí pověřené osoby lze na dobu nezbytně nutnou změnit třídu I na třídu II, pokud je zajištěno, že k utajované informaci nemá přístup neoprávněná osoba.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 27

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=c12112f46d77a3f51396 -->

### § 26 — Projednávání UI v jednací oblasti

> **§ 26**
>
> *(1) Odpovědná osoba je povinna zajistit, aby v jednací oblasti podle § 24 odst. 4 nedocházelo k ohrožení nebo úniku projednávaných utajovaných informací.*
>
> *(2) Ke splnění povinnosti podle odstavce 1 je odpovědná osoba povinna požádat Národní úřad pro kybernetickou a informační bezpečnost o prověření, zda v jednací oblasti nedochází k nedovolenému použití technických prostředků určených k získávání informací; o prověření může odpovědná osoba požádat rovněž u zabezpečené oblasti kategorie Tajné nebo Přísně tajné. O této žádosti Národní úřad pro kybernetickou a informační bezpečnost informuje Úřad. Prověření Národní úřad pro kybernetickou a informační bezpečnost zajistí v součinnosti se zpravodajskými službami a Policií České republiky (dále jen „policie“) a o provedeném prověření informuje Úřad. Pro své potřeby si zpravodajské služby a policie prověření provádějí samy.*
>
> *(3) Vstup do jednací oblasti a výstup z ní musí být kontrolován opatřeními podle § 27. Neoprávněná osoba může vstoupit do jednací oblasti pouze s osobou, která má do této oblasti vstup povolen.*

**Výklad:**

#### Aktivní antiodposlechová ochrana jednacích oblastí

Odpovědná osoba **musí** požádat NÚKIB o prověření (anti-bugging sweep) jednací oblasti — povinný preventivní úkon. U ZO kategorií T a PT je tato žádost fakultativní. **Prověřování** zajišťuje NÚKIB ve spolupráci se zpravodajskými službami a Policií ČR; **pro vlastní potřeby** si zpravodajské služby a policie prověření provádějí samy.

Tato povinnost je důsledkem zkušeností s odposlechovými kauzami (např. odposlech sekretariátu předsedy vlády 2012 — kauza „Nagyová") a snahou zákonodárce systémově zajistit, aby kruciální jednání byla chráněna proti elektronickému odposlechu.

#### Vstup neoprávněných osob (odst. 3)

NO může do jednací oblasti vstoupit pouze **s osobou, která má vstup povolen** — obdobně jako u ZO třídy II.

#### F. Kazuistika

**1. Modelová situace.** Orgán státu zřídil jednací oblast pro pravidelné porady ke krizovému řízení, na nichž se projednávají UI stupně Tajné. Odpovědná osoba prostor vybavila a uvedla do provozu, aniž požádala NÚKIB o prověření, zda v JO nedochází k nedovolenému použití technických prostředků k získávání informací (antiodposlechové prověření). Po úniku obsahu jednání do médií vyvstává otázka odpovědnosti. Účastníci: odpovědná osoba, NÚKIB, zpravodajské služby a policie (součinnost při prověření), Úřad (je informován). Důkazy: žádost o prověření (chybí), protokol o prověření, projekt fyzické bezpečnosti, záznamy o vstupech.

**2. Právní otázka.** Porušila odpovědná osoba povinnost podle § 26 tím, že před zahájením pravidelného projednávání UI stupně Tajné v jednací oblasti nepožádala NÚKIB o antiodposlechové prověření, a jaké to má důsledky?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 26 — povinnost odpovědné osoby zajistit, aby v JO nedocházelo k ohrožení/úniku UI (odst. 1), povinnost požádat NÚKIB o prověření nedovoleného použití odposlechových prostředků (odst. 2), kontrola vstupu a vstup neoprávněné osoby jen s doprovodem (odst. 3).
- *Související ustanovení téhož zákona:* § 24 odst. 4 (definice JO a pravidlo projednávání PT/T jen v JO), § 25 (třídy ZO — analogie doprovodu), § 27 (opatření fyzické bezpečnosti pro kontrolu vstupu), § 30 odst. 1 písm. h) (zařízení proti odposlechu), § 33a (příslušnost NÚKIB).
- *Související předpisy:* vyhláška č. 528/2005 Sb. (fyzická bezpečnost); zákony o zpravodajských službách a o policii (součinnost při prověření).
- *Judikatura:* k antiodposlechovému prověřování chybí publikovaná judikatura; rozhodné jsou kontrolní standardy NÚKIB. Kontext kauzy odposlechu sekretariátu předsedy vlády (2012) ilustruje účel ustanovení.

**4. Subsumpce.** Jde o jednací oblast s pravidelným projednáváním UI stupně Tajné. Podle odst. 2 je u JO prověření NÚKIB povinné (nikoli fakultativní — fakultativnost se týká jen ZO kategorií T a PT). Odpovědná osoba o prověření nepožádala, čímž nesplnila zákonnou povinnost a nedostála ani obecné povinnosti podle odst. 1 zajistit, aby nedocházelo k úniku UI. Vstupní kontrola podle odst. 3 byla formálně zachována, sama o sobě však riziko odposlechu nepokrývá.

**5. Řešení.** Správný postup: před zahájením pravidelného projednávání měla odpovědná osoba požádat NÚKIB o prověření; NÚKIB by je provedl v součinnosti se zpravodajskými službami a policií a informoval Úřad. Nápravně je nutné prověření bezodkladně doplnit, prošetřit příčinu úniku a přijmout opatření. Procesní kroky: podání žádosti, prověření, vyhodnocení a dokumentace. Riziko/alternativa: prokáže-li se únik v důsledku zanedbání prověření, hrozí odpovědnost odpovědné osoby a bezpečnostní incident s případnou trestněprávní dimenzí.

**6. Varianty.** (a) Šlo-li by o zabezpečenou oblast kategorie Tajné (nikoli JO), bylo by prověření NÚKIB pouze fakultativní (odst. 2 věta za středníkem) a jeho neprovedení by samo o sobě porušení nezakládalo. (b) Provádějí-li prověření zpravodajská služba či policie pro vlastní potřeby, činí tak samy (odst. 2 in fine) a režim žádosti adresované NÚKIB se neuplatní.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Prověření je vždy fakultativní."* Neutralizace: u jednací oblasti je podle odst. 2 prověření povinné („je povinna požádat"); fakultativní je jen u ZO kategorií T a PT.
- *Protiargument 2: „Stačí kontrola vstupu podle odst. 3."* Neutralizace: kontrola vstupu chrání před fyzickým průnikem osob, nikoli před technickým odposlechem; odst. 1 a 2 ukládají samostatnou povinnost zajistit prostor proti získávání informací technickými prostředky.
- *Slabé místo:* periodicita prověřování není v § 26 výslovně určena (jednorázové vs. opakované); v praxi je nutné prověření obnovovat, zejména po servisních zásazích a změnách vybavení — jinak ochrana zastarává.

#### H. Praktický závěr

§ 26 ukládá odpovědné osobě zajistit jednací oblast proti úniku UI, zejména povinným antiodposlechovým prověřením NÚKIB; u ZO kategorií T/PT je prověření fakultativní. Vstup neoprávněné osoby je možný jen s doprovodem.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Před pravidelným projednáváním UI v JO požádat NÚKIB o antiodposlechové prověření (odst. 2).
- [ ] Zajistit kontrolu vstupu a výstupu opatřeními podle § 27 (odst. 3).
- [ ] Umožnit vstup neoprávněné osoby do JO jen s doprovázející oprávněnou osobou.
- [ ] Prověření opakovat po servisních zásazích a změnách vybavení; vést protokoly.

**Typicky rozhodné důkazy / podklady:** žádost o prověření a protokol NÚKIB, projekt fyzické bezpečnosti (JO), záznamy o vstupech a doprovodu, dokumentace technických prostředků v JO.

---


<!-- LEGAL-REVISION:BEGIN id=ff3416bad256bec248bc generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 26 — Projednávání utajovaných informací

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Odpovědná osoba je povinna zajistit, aby v jednací oblasti podle § 24 odst. 4 nedocházelo k ohrožení nebo úniku projednávaných utajovaných informací.
>
> (2) Ke splnění povinnosti podle odstavce 1 je odpovědná osoba povinna požádat Národní úřad pro kybernetickou a informační bezpečnost o prověření, zda v jednací oblasti nedochází k nedovolenému použití technických prostředků určených k získávání informací; o prověření může odpovědná osoba požádat rovněž u zabezpečené oblasti kategorie Tajné nebo Přísně tajné. O této žádosti Národní úřad pro kybernetickou a informační bezpečnost informuje Úřad. Prověření Národní úřad pro kybernetickou a informační bezpečnost zajistí v součinnosti se zpravodajskými službami a Policií České republiky (dále jen „policie“) a o provedeném prověření informuje Úřad. Pro své potřeby si zpravodajské služby a policie prověření provádějí samy.
>
> (3) Vstup do jednací oblasti a výstup z ní musí být kontrolován opatřeními podle [[#§ 27|§ 27]]. Neoprávněná osoba může vstoupit do jednací oblasti pouze s osobou, která má do této oblasti vstup povolen.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 24, § 27

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=ff3416bad256bec248bc -->

### § 27 — Opatření fyzické bezpečnosti (taxativní výčet)

Tři kategorie:
- **a) ostraha** (lidská přítomnost — § 28),
- **b) režimová opatření** (administrativní pravidla — § 29),
- **c) technické prostředky** (fyzické a elektronické zařízení — § 30).

Tyto tři pilíře musí být **kombinovány** tak, aby dosáhly **bodové hodnoty** odpovídající kategorii ZO/objektu (§ 31).

#### F. Kazuistika

**1. Modelová situace.** Podnikatel zřizuje zabezpečenou oblast kategorie Důvěrné a v projektu fyzické bezpečnosti spoléhá výhradně na technické prostředky (kvalitní trezor, kamerový systém, alarm), ostrahu i režimová opatření však zcela vynechává s tím, že technika sama dosáhne potřebné úrovně. Úřad při kontrole posuzuje, zda je výčet opatření podle § 27 naplněn. Účastníci: podnikatel (odpovědná osoba/bezpečnostní ředitel), Úřad. Důkazy: projekt fyzické bezpečnosti, bodové vyhodnocení (§ 31), provozní řád, certifikáty technických prostředků.

**2. Právní otázka.** Lze požadovanou míru zabezpečení dosáhnout pouze jednou ze tří kategorií opatření podle § 27 (zde technickými prostředky), nebo je nutná jejich kombinace tak, aby v součtu dosáhly bodové hodnoty odpovídající kategorii ZO?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 27 — taxativní výčet tří kategorií opatření fyzické bezpečnosti: ostraha [písm. a) — § 28], režimová opatření [písm. b) — § 29], technické prostředky [písm. c) — § 30], jež se kombinují k dosažení bodové hodnoty (§ 31).
- *Související ustanovení téhož zákona:* § 28 (ostraha podle kategorie), § 29 (režimová opatření), § 30 (technické prostředky), § 31 (bodové vyjádření míry zabezpečení), § 32 (projekt fyzické bezpečnosti).
- *Související předpisy:* vyhláška č. 528/2005 Sb., o fyzické bezpečnosti (přílohy s bodovými hodnotami a minimálními požadavky).
- *Judikatura:* publikovaná judikatura chybí; rozhodující je soulad s vyhláškou a bodovým systémem — nosné je pravidlo, že nedosažení nejnižší míry zabezpečení je porušením bez ohledu na to, která opatření byla zvolena.

**4. Subsumpce.** § 27 vymezuje tři kategorie opatření, jejichž smyslem je dosažení bodové hodnoty podle § 31. Zákon nestanoví, že každá kategorie musí být užita vždy v plném rozsahu, avšak u kategorie Důvěrné předepisuje § 28 minimální ostrahu (nejméně jedna osoba s rychlým zásahem na poplach). Úplné vynechání ostrahy proto naráží na minimální požadavek § 28; samotné technické prostředky nemohou tento minimální standard nahradit (mimo krizové režimy podle § 30 odst. 3, jež jsou opačné povahy — nahrazení techniky ostrahou).

**5. Řešení.** Podnikatel musí doplnit ostrahu odpovídající kategorii Důvěrné (§ 28) a stanovit režimová opatření (§ 29) jako součást provozního řádu; teprve kombinace všech tří pilířů, doložená bodovým vyhodnocením podle § 31, dosáhne požadované míry zabezpečení. Procesní kroky: úprava projektu fyzické bezpečnosti, bodový propočet, certifikace/schválení technických prostředků. Riziko/alternativa: bez minimální ostrahy a režimových opatření Úřad shledá nedostatečné zabezpečení a ZO nelze provozovat.

**6. Varianty.** (a) V krizovém režimu (válečný/nouzový stav, mise) lze podle § 30 odst. 3 technické prostředky nahradit zvýšenou ostrahou — poměr opatření se obrací. (b) U ZO kategorie Vyhrazené stanoví rozsah ostrahy odpovědná osoba (§ 28), takže váha technických a režimových opatření může být relativně vyšší.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Stačí jediná kategorie opatření, je-li dostatečně silná."* Neutralizace: § 27 ve spojení s § 28 předepisuje pro vyšší kategorie minimální ostrahu; bodový systém § 31 navíc předpokládá kombinaci opatření k dosažení nejnižší míry zabezpečení.
- *Protiargument 2: „Výčet v § 27 je demonstrativní, lze zvolit i jiná opatření."* Neutralizace: § 27 je taxativní co do kategorií (ostraha, režim, technika); demonstrativní je až výčet jednotlivých technických prostředků v § 30 — kategorie samy doplňovat nelze.
- *Slabé místo:* § 27 sám neurčuje váhy ani minima — ty jsou v § 28, § 31 a ve vyhlášce; izolované čtení § 27 svádí k podcenění minimálních požadavků na ostrahu.

#### H. Praktický závěr

§ 27 taxativně vymezuje tři pilíře fyzické bezpečnosti — ostrahu, režimová opatření a technické prostředky — které se kombinují tak, aby v součtu (§ 31) dosáhly bodové hodnoty odpovídající kategorii ZO/objektu. Žádný pilíř nelze u vyšších kategorií zcela pominout pod minimální zákonné požadavky.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Pokrýt všechny tři kategorie opatření podle § 27 v rozsahu odpovídajícím kategorii ZO.
- [ ] Dodržet minimální ostrahu podle § 28 a stanovit režimová opatření podle § 29.
- [ ] Doložit dosažení nejnižší míry zabezpečení bodovým vyhodnocením (§ 31).
- [ ] Promítnout zvolená opatření do projektu fyzické bezpečnosti (§ 32).

**Typicky rozhodné důkazy / podklady:** projekt fyzické bezpečnosti, bodové vyhodnocení podle § 31, provozní řád s režimovými opatřeními, certifikáty/schválení technických prostředků a doklady o ostraze.

---


<!-- LEGAL-REVISION:BEGIN id=9c233628568c1034a70f generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 27

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> Opatřeními fyzické bezpečnosti jsou
>
> - a) ostraha,
>
> - b) režimová opatření,
>
> - c) technické prostředky.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Místní znění neobsahuje výslovný vnitřní odkaz.

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=9c233628568c1034a70f -->

### § 28 — Ostraha podle kategorie

| Kategorie ZO | Minimální ostraha |
|---|---|
| **Přísně tajné** | Nejméně **2 osoby** u objektu (nepřetržitě) |
| **Tajné** | Nejméně **1 osoba** u objektu + 1 osoba s rychlým zásahem na poplach |
| **Důvěrné** | Nejméně **1 osoba** s rychlým zásahem na poplach |
| **Vyhrazené** / bez ZO | Rozsah stanoví odp. osoba |

Pro **jednací oblasti** s pravidelným projednáváním PT: nejméně 2 osoby; pro T: 1 osoba u objektu + 1 osoba s rychlým zásahem.

Personál ostrahy: zaměstnanci orgánu/PO/podnikatele, příslušníci ozbrojených sil nebo OBS, příslušníci ozbrojených sil cizí moci, **zaměstnanci bezpečnostní ochranné služby** (BOS — soukromé bezpečnostní agentury podle zákona č. 229/2024 Sb. o BOS).

#### F. Kazuistika

**1. Modelová situace.** Orgán státu provozuje objekt se zabezpečenou oblastí kategorie Přísně tajné. Z úsporných důvodů zajišťuje noční ostrahu jediným pracovníkem soukromé bezpečnostní agentury, který obchází celý areál. Úřad při kontrole posuzuje, zda je ostraha objektu s ZO kategorie PT dostatečná. Účastníci: odpovědná osoba, poskytovatel ostrahy (BOS), Úřad. Důkazy: smlouva o ostraze, rozpis směn, projekt fyzické bezpečnosti, doklady o oprávnění a poučení strážných.

**2. Právní otázka.** Splňuje ostraha objektu s ZO kategorie Přísně tajné zajištěná v noci jediným strážným minimální požadavek § 28, který pro PT vyžaduje nejméně dvě osoby u objektu nepřetržitě?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 28 — minimální ostraha odstupňovaná podle kategorie ZO: PT nejméně 2 osoby u objektu nepřetržitě; T 1 osoba u objektu + 1 osoba s rychlým zásahem; D 1 osoba s rychlým zásahem; V/bez ZO dle odpovědné osoby; vymezení okruhu personálu ostrahy (vč. BOS podle zákona č. 229/2024 Sb.).
- *Související ustanovení téhož zákona:* § 27 (ostraha jako jeden z pilířů), § 29 (režimová opatření), § 30 (technické prostředky), § 31 (bodové hodnocení), § 24 odst. 4 / § 26 (ostraha JO).
- *Související předpisy:* vyhláška č. 528/2005 Sb. (fyzická bezpečnost); zákon č. 229/2024 Sb., o bezpečnostní ochranné službě (BOS).
- *Judikatura:* publikovaná judikatura chybí; rozhodující jsou kontrolní standardy Úřadu a soulad s § 28 a vyhláškou — nosné je, že nedosažení minimálního počtu osob ostrahy je porušením bez ohledu na technické vybavení.

**4. Subsumpce.** Objekt obsahuje ZO kategorie Přísně tajné, pro niž § 28 stanoví minimální ostrahu nejméně dvěma osobami u objektu nepřetržitě. Noční zajištění jediným strážným tento minimální požadavek nenaplňuje. Okruh personálu (zaměstnanec BOS) je přípustný, problémem je počet, nikoli kvalifikace ostrahy.

**5. Řešení.** Odpovědná osoba musí ostrahu objektu s ZO kategorie PT posílit nejméně na dvě osoby nepřetržitě (po celých 24 hodin), jinak je požadavek § 28 porušen. Technické prostředky či režimová opatření tento minimální početní standard nahradit nemohou (mimo krizové režimy § 30 odst. 3, jež jdou opačným směrem). Procesní kroky: úprava rozpisu směn a smlouvy o ostraze, promítnutí do projektu fyzické bezpečnosti. Riziko/alternativa: trvá-li podstavový stav, Úřad shledá nedostatečné zabezpečení a provoz ZO kategorie PT je vadný.

**6. Varianty.** (a) Šlo-li by o ZO kategorie Tajné, postačila by 1 osoba u objektu a 1 osoba s rychlým zásahem na poplach. (b) Šlo-li by o ZO kategorie Vyhrazené, rozsah ostrahy by stanovila odpovědná osoba a jediný pracovník by mohl postačovat.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Silný kamerový a poplachový systém nahradí druhou osobu ostrahy."* Neutralizace: § 28 stanoví minimální počet osob ostrahy přímo a nezávisle na technice; technické prostředky se započítávají do bodů (§ 31), nemohou však snížit početní minimum ostrahy pod zákonnou hranici.
- *Protiargument 2: „Stačí jedna osoba s pohotovostí zásahové skupiny."* Neutralizace: model „1 osoba + rychlý zásah" zákon připouští pro kategorii Tajné, nikoli pro Přísně tajné, kde žádá dvě osoby u objektu nepřetržitě.
- *Slabé místo:* pojem „nepřetržitě" a „rychlý zásah" zákon blíže nekvantifikuje (dojezdové časy upřesňuje vyhláška); bez její znalosti hrozí podcenění reálných požadavků.

#### H. Praktický závěr

§ 28 stanoví minimální početní a kvalitativní požadavky na ostrahu podle kategorie ZO: PT — 2 osoby u objektu nepřetržitě, T — 1 + rychlý zásah, D — rychlý zásah, V — dle odpovědné osoby. Tato minima nelze nahradit technikou ani režimem.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Určit kategorii ZO a podle ní minimální rozsah ostrahy podle § 28.
- [ ] Zajistit u PT nepřetržitou přítomnost nejméně dvou osob u objektu.
- [ ] Ověřit oprávněnost personálu ostrahy (vč. BOS podle zákona č. 229/2024 Sb.).
- [ ] Promítnout rozsah ostrahy do projektu fyzické bezpečnosti a bodového hodnocení (§ 31, § 32).

**Typicky rozhodné důkazy / podklady:** smlouva o ostraze a rozpis směn, projekt fyzické bezpečnosti, doklady o oprávnění a poučení strážných, bodové vyhodnocení míry zabezpečení.

---


<!-- LEGAL-REVISION:BEGIN id=06a02e0b225996453497 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 28

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Ostraha se nepřetržitě zajišťuje u objektu, ve kterém se nachází zabezpečená oblast kategorie
>
> - a) Přísně tajné, nejméně 2 osobami u objektu,
>
> - b) Tajné, nejméně 1 osobou u objektu a 1 další osobou, které poplachové hlášení technických prostředků umožní rychlý zásah, je-li provádění ochrany utajovaných informací narušeno,
>
> - c) Důvěrné, nejméně 1 osobou, které poplachové hlášení technických prostředků umožní rychlý zásah, je-li provádění ochrany utajovaných informací narušeno.
>
> (2) U objektu, ve kterém se nachází zabezpečená oblast nejvýše kategorie Vyhrazené, a u objektu bez zabezpečené oblasti nebo jednací oblasti, se ostraha zajišťuje v rozsahu stanoveném odpovědnou osobou.
>
> (3) U objektu, ve kterém se nachází jednací oblast, v níž se pravidelně projednávají utajované informace stupně utajení Přísně tajné, se ostraha zajišťuje nejméně 2 osobami u objektu; u objektu, ve kterém se nachází jednací oblast, v níž se pravidelně projednávají utajované informace stupně utajení Tajné, nejméně 1 osobou u objektu a 1 další osobou, které poplachové hlášení technických prostředků umožní rychlý zásah, je-li provádění ochrany utajovaných informací narušeno.
>
> (4) Ostraha se zabezpečuje zaměstnanci orgánu státu, právnické osoby podle [[#§ 60b|§ 60b]] nebo podnikatele, o jejichž objekt jde, příslušníky ozbrojených sil nebo ozbrojených bezpečnostních sborů nebo příslušníky ozbrojených sil cizí moci anebo zaměstnanci bezpečnostní ochranné služby.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 60b

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=06a02e0b225996453497 -->

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

#### F. Kazuistika

**1. Modelová situace.** V zabezpečené oblasti kategorie Tajné dojde k podezření na únik UI. Vyšetřování ukáže, že klíče od ZO byly volně dostupné na recepci, identifikační karty si zaměstnanci běžně půjčovali a chyběla kontrola vynášení nosičů. Provozní řád objektu sice formálně existoval, ale tyto otázky neupravoval. Účastníci: odpovědná osoba, zaměstnanci, Úřad (kontrola). Důkazy: provozní řád objektu, evidence výdeje klíčů a karet, záznamy o vstupech/výstupech, výslechy.

**2. Právní otázka.** Byla porušena povinnost stanovit a dodržovat režimová opatření podle § 29 — zejména manipulaci s klíči a identifikačními prostředky a kontrolu vynášení UI — a jak se to promítá do odpovědnosti za bezpečnostní incident?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 29 — režimová opatření jako administrativní pravidla (oprávnění ke vstupu/vjezdu, kontrola oprávnění, manipulace s klíči a identifikačními prostředky, manipulace s technickými prostředky, výstup a kontrola, pohyb osob, kontrola vynášení UI), jež jsou součástí provozního řádu objektu (§ 32).
- *Související ustanovení téhož zákona:* § 27 (režimová opatření jako pilíř), § 28 (ostraha), § 30 odst. 1 písm. b) (systémy kontroly vstupů — identifikační prostředky), § 31 (bodové hodnocení), § 32 (projekt fyzické bezpečnosti, provozní řád).
- *Související předpisy:* vyhláška č. 528/2005 Sb., o fyzické bezpečnosti (obsah provozního řádu a režimových opatření).
- *Judikatura:* publikovaná judikatura chybí; rozhodující je soulad s vyhláškou — nosné pravidlo zní, že absence funkčních režimových opatření je porušením povinností fyzické bezpečnosti i tehdy, jsou-li technické prostředky jinak dostatečné.

**4. Subsumpce.** § 29 vyžaduje, aby provozní řád upravil manipulaci s klíči a identifikačními prostředky, kontrolu oprávnění a kontrolu vynášení UI. Volně dostupné klíče na recepci, půjčování identifikačních karet a absence kontroly vynášení nosičů znamenají, že tyto obligatorní prvky režimových opatření chyběly nebo nebyly dodržovány — znaky § 29 nenaplněny. Existence formálního provozního řádu bez těchto úprav nestačí.

**5. Řešení.** Odpovědná osoba musí doplnit a fakticky vynutit režimová opatření: zavést evidovaný výdej a kontrolu klíčů a identifikačních prostředků (zákaz jejich půjčování), kontrolu oprávnění při vstupu a kontrolu vynášení UI. Incident je nutné prošetřit a promítnout do aktualizace provozního řádu a projektu fyzické bezpečnosti. Procesní kroky: revize provozního řádu, proškolení osob, kontrola plnění. Riziko/alternativa: prokáže-li se příčinná souvislost mezi absencí režimových opatření a únikem, hrozí odpovědnost odpovědné osoby a hodnocení ZO jako nedostatečně zabezpečené.

**6. Varianty.** (a) Kdyby byla režimová opatření řádně nastavena a dodržována (evidence klíčů, zákaz půjčování karet, kontrola vynášení), incident by buď nenastal, nebo by bylo snazší dohledat jeho původ. (b) U ZO kategorie Vyhrazené je rozsah opatření mírnější, přesto kontrola vynášení UI a manipulace s klíči zůstávají standardem provozního řádu.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Režimová opatření jsou jen doporučení, podstatná je technika a ostraha."* Neutralizace: § 27 řadí režimová opatření mezi tři rovnocenné pilíře fyzické bezpečnosti; § 29 jejich obsah vymezuje závazně a jsou povinnou součástí provozního řádu (§ 32).
- *Protiargument 2: „Existence písemného provozního řádu sama o sobě postačuje."* Neutralizace: zákon žádá nejen stanovení, ale i dodržování režimových opatření; formální dokument bez faktického vynucení (volné klíče, půjčování karet) povinnost nesplňuje.
- *Slabé místo:* § 29 obsahuje široký výčet oblastí, jejichž konkrétní parametry stanoví až vyhláška a interní akty; bez provázání s vyhláškou č. 528/2005 Sb. hrozí mezery v provozním řádu.

#### H. Praktický závěr

§ 29 vymezuje režimová opatření — administrativní pravidla pro vstup, kontrolu oprávnění, manipulaci s klíči a identifikačními prostředky a kontrolu vynášení UI — jako povinnou součást provozního řádu objektu a jeden z pilířů fyzické bezpečnosti. Musí být nejen stanovena, ale i dodržována.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Zpracovat provozní řád objektu pokrývající všechny oblasti podle § 29.
- [ ] Zavést evidovanou manipulaci s klíči a identifikačními prostředky a zákaz jejich neoprávněného předávání.
- [ ] Nastavit kontrolu oprávnění při vstupu/výstupu a kontrolu vynášení UI.
- [ ] Zajistit faktické dodržování a pravidelnou revizi režimových opatření (§ 31, § 32).

**Typicky rozhodné důkazy / podklady:** provozní řád objektu, evidence výdeje klíčů a identifikačních prostředků, záznamy o vstupech/výstupech a kontrole vynášení, doklady o proškolení osob.

---


<!-- LEGAL-REVISION:BEGIN id=9c83fe31c95069042d34 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 29

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> Režimová opatření stanoví oprávnění osob a dopravních prostředků pro vstup a vjezd do objektu, oprávnění osob pro vstup do zabezpečené oblasti a jednací oblasti a způsob kontroly těchto oprávnění a dále způsob manipulace s klíči a identifikačními prostředky, které se používají pro systémy zabezpečení vstupů podle § 30 odst. 1 písm. b), a způsob manipulace s technickými prostředky a jejich používání. Režimová opatření stanoví též oprávnění při výstupu osob a výjezdu dopravních prostředků z objektu a pro jejich kontrolu, podmínky a způsob kontroly pohybu osob v objektu, zabezpečené oblasti a jednací oblasti a způsob kontroly a vynášení utajovaných informací z objektu, zabezpečené oblasti a jednací oblasti.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 30

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=9c83fe31c95069042d34 -->

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

#### F. Kazuistika

**1. Modelová situace.** Podnikatel vybavuje zabezpečenou oblast kategorie Důvěrné poplachovým zabezpečovacím systémem a systémem kontroly vstupů od dodavatele, jehož zařízení nejsou certifikována podle § 46. Podnikatel chce, aby se těmto prostředkům přiznala bodová hodnota podle § 31. Úřad posuzuje, zda lze necertifikovaným prostředkům body přiznat. Účastníci: podnikatel (odpovědná osoba/bezpečnostní ředitel), Úřad. Důkazy: certifikáty technických prostředků (chybí), písemné schválení odpovědnou osobou, projekt fyzické bezpečnosti, bodové vyhodnocení.

**2. Právní otázka.** Lze necertifikovaným technickým prostředkům podle § 30 přiznat bodovou hodnotu, a za jakých podmínek — postačí jejich schválení odpovědnou osobou, nebo je nutná certifikace podle § 46?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 30 — demonstrativní výčet technických prostředků (osm typů, vč. zařízení proti odposlechu); bodová hodnota se přiznává certifikovaným prostředkům [§ 46 odst. 1 písm. a)] a necertifikovaným prostředkům schváleným odpovědnou osobou nebo její pověřenou osobou (odst. 2); nouzové nahrazení techniky zvýšenou ostrahou v krizových režimech (odst. 3).
- *Související ustanovení téhož zákona:* § 27 (technické prostředky jako pilíř), § 31 (bodové vyjádření míry zabezpečení), § 46 odst. 1 písm. a) (certifikace technického prostředku), § 47 (certifikace Úřadem), § 32 (projekt fyzické bezpečnosti).
- *Související předpisy:* vyhláška č. 528/2005 Sb., o fyzické bezpečnosti (bodové hodnoty, požadavky na technické prostředky).
- *Judikatura:* publikovaná judikatura chybí; rozhodné jsou kontrolní standardy Úřadu a vyhláška — nosné je pravidlo, že bodovou hodnotu lze přiznat jen prostředku certifikovanému, anebo necertifikovanému, jejž schválila odpovědná osoba.

**4. Subsumpce.** Podle odst. 2 se bodová hodnota přiznává buď certifikovaným prostředkům podle § 46 odst. 1 písm. a), nebo necertifikovaným prostředkům schváleným odpovědnou osobou (či její pověřenou osobou). Zařízení podnikatele certifikována nejsou; bodovou hodnotu jim tedy lze přiznat jen tehdy, pokud je odpovědná osoba (nebo pověřená osoba) výslovně schválí. Bez tohoto schválení body přiznat nelze.

**5. Řešení.** Podnikatel zajistí, aby odpovědná osoba (nebo jí pověřená osoba) necertifikované technické prostředky písemně schválila; teprve poté lze jim v bodovém vyhodnocení podle § 31 přiznat hodnotu a započítat je do dosažení nejnižší míry zabezpečení. Alternativně pořídí prostředky certifikované podle § 46/§ 47. Procesní kroky: schválení odpovědnou osobou, promítnutí do projektu fyzické bezpečnosti a bodového propočtu. Riziko/alternativa: nebudou-li prostředky certifikovány ani schváleny, jejich body se nezapočtou a může nastat nedosažení požadované míry zabezpečení.

**6. Varianty.** (a) Šlo-li by o zařízení proti odposlechu [písm. h)] v jednací oblasti, uplatnila by se navíc povinnost prověření NÚKIB podle § 26 a samotné schválení odpovědnou osobou by nepostačovalo k pokrytí antiodposlechové ochrany. (b) V krizovém režimu (odst. 3) by bylo možné technické prostředky nahradit zvýšenou ostrahou ozbrojených sil/BOS, takže otázka certifikace techniky by ustoupila.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Bodovou hodnotu má jen certifikovaný prostředek."* Neutralizace: odst. 2 výslovně připouští i necertifikované prostředky, pokud je schválí odpovědná osoba nebo její pověřená osoba — certifikace není jedinou cestou.
- *Protiargument 2: „Výčet technických prostředků je taxativní."* Neutralizace: výčet v § 30 odst. 1 je demonstrativní (osm typů jako příklady); lze použít i jiné technické prostředky, je-li jim po certifikaci či schválení přiznána bodová hodnota.
- *Slabé místo:* schválení necertifikovaného prostředku odpovědnou osobou je do jisté míry subjektivní; bez opory ve vyhlášce a v bodovém systému hrozí nadhodnocení reálné ochranné funkce zařízení.

#### H. Praktický závěr

§ 30 podává demonstrativní výčet technických prostředků fyzické bezpečnosti; bodovou hodnotu mají prostředky certifikované podle § 46, anebo necertifikované schválené odpovědnou osobou. V krizových režimech lze techniku nahradit zvýšenou ostrahou (odst. 3).

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Zvolit technické prostředky pokrývající identifikovaná rizika (vstupy, alarm, CCTV, EPS, detekce, ničení nosičů, antiodposlech).
- [ ] Pro přiznání bodů zajistit certifikaci (§ 46) nebo písemné schválení odpovědnou osobou (odst. 2).
- [ ] U zařízení proti odposlechu v JO doplnit prověření NÚKIB (§ 26).
- [ ] Promítnout prostředky do projektu fyzické bezpečnosti a bodového hodnocení (§ 31, § 32).

**Typicky rozhodné důkazy / podklady:** certifikáty technických prostředků nebo doklad o jejich schválení odpovědnou osobou, projekt fyzické bezpečnosti, bodové vyhodnocení, případně protokol o antiodposlechovém prověření.

---


<!-- LEGAL-REVISION:BEGIN id=e65eee48f57004761dee generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 30

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Technickými prostředky jsou zejména
>
> - a) mechanické zábranné prostředky,
>
> - b) elektrická zámková zařízení a systémy pro kontrolu vstupů,
>
> - c) poplachové zabezpečovací a tísňové systémy,
>
> - d) dohledové videosystémy,
>
> - e) zařízení elektrické požární signalizace,
>
> - f) zařízení sloužící k vyhledávání nebezpečných látek nebo předmětů,
>
> - g) zařízení fyzického ničení nosičů informací,
>
> - h) zařízení proti pasivnímu a aktivnímu odposlechu utajované informace.
>
> (2) Bodové ohodnocení (§ 31 odst. 1) se přiřazuje certifikovaným technickým prostředkům [§ 46 odst. 1 písm. a)] a odpovědnou osobou nebo jí pověřenou osobou schváleným necertifikovaným technickým prostředkům.
>
> (3) Technické prostředky uvedené v odstavci 1 lze v případě účasti České republiky v mezinárodním ozbrojeném konfliktu, mezinárodní záchranné nebo humanitární akci, v dalších zahraničních misích, v případě vyhlášení válečného stavu, v případě stavu nebezpečí, nouzového stavu nebo stavu ohrožení státu20), v případě zpravodajských operací zpravodajských služeb a při činnostech ozbrojených sil České republiky v rámci vojenského cvičení a praktického vojenského výcviku s vojenskou technikou a vojenskou výzbrojí mimo místa stálé dislokace vojenského útvaru nahradit zvýšenou ostrahou, než jaká je uvedena v [[#§ 28|§ 28]], prováděnou příslušníky ozbrojených sil nebo ozbrojených bezpečnostních sborů na základě zvláštních právních předpisů21), příslušníky ozbrojených sil cizí moci nebo zaměstnanci bezpečnostní ochranné služby cizí moci.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 31, § 46, § 28

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=e65eee48f57004761dee -->

### § 31 — Bodové vyjádření míry zabezpečení

§ 31 zavádí **bodové hodnocení**: každé opatření má bodovou hodnotu, jejich součet musí dosáhnout **nejnižší míry zabezpečení** stanovené prováděcím předpisem (vyhláška č. 528/2005 Sb., přílohy). Výsledek závisí na:
- **vyhodnocení rizik** (threat assessment) — odst. 1,
- **kategorii ZO** nebo **stupni utajení** UI projednávaných v JO,
- **typu prostoru**.

Hodnocení rizik je **průběžné** (odst. 4) — mění se hrozby (od kybernetických po fyzické), opatření se upravují.

#### Pravidelné ověřování (odst. 5)

Orgán státu / PO / podnikatel je povinen **pravidelně ověřovat**, zda opatření odpovídají projektu a předpisům. Periodicita podle vyhlášky.

#### F. Kazuistika

**1. Modelová situace.** Orgán státu zřídil zabezpečenou oblast kategorie Tajné před deseti lety a bodové vyhodnocení od té doby neaktualizoval. Mezitím se v okolí objektu zvýšila rizika (nová zástavba umožňující odposlech, opakované pokusy o neoprávněný vstup), avšak opatření zůstala beze změny. Při kontrole Úřad zjišťuje, zda součet bodů stále odpovídá nejnižší míře zabezpečení a zda orgán plnil povinnost průběžného hodnocení rizik a ověřování. Účastníci: odpovědná osoba, Úřad. Důkazy: vyhodnocení rizik, bodové propočty, projekt fyzické bezpečnosti, protokoly o pravidelném ověřování.

**2. Právní otázka.** Splňuje zabezpečená oblast požadavek § 31, je-li bodové hodnocení statické a neaktualizované, ačkoli se rizika prokazatelně změnila a orgán neprováděl pravidelné ověřování podle odst. 5?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 31 — bodové hodnocení opatření, jejichž součet musí dosáhnout nejnižší míry zabezpečení podle vyhlášky; závislost na vyhodnocení rizik (odst. 1), kategorii ZO/stupni utajení a typu prostoru; průběžnost hodnocení rizik (odst. 4); pravidelné ověřování souladu opatření s projektem a předpisy (odst. 5).
- *Související ustanovení téhož zákona:* § 27 (tři pilíře opatření), § 28–30 (ostraha, režim, technika), § 32 (projekt fyzické bezpečnosti), § 26 (antiodposlech v JO — reakce na rizika).
- *Související předpisy:* vyhláška č. 528/2005 Sb., o fyzické bezpečnosti (přílohy s bodovými hodnotami, nejnižší míry zabezpečení, periodicita ověřování).
- *Judikatura:* publikovaná judikatura chybí; rozhodné jsou kontrolní standardy Úřadu a vyhláška — nosné je, že bezpečnost je průběžně udržovaný stav, nikoli jednorázové dosažení bodové hranice.

**4. Subsumpce.** Bodový součet musí trvale odpovídat nejnižší míře zabezpečení (odst. 1). Hodnocení rizik je podle odst. 4 průběžné a podle odst. 5 je orgán povinen pravidelně ověřovat soulad opatření s projektem a předpisy. Statické, deset let neaktualizované hodnocení při prokazatelné změně hrozeb tyto povinnosti nenaplňuje; navíc hrozí, že po zvýšení rizik již součet bodů nejnižší míru zabezpečení nesplňuje.

**5. Řešení.** Orgán musí provést aktuální vyhodnocení rizik, přepočítat bodovou hodnotu opatření a doplnit je tak, aby součet odpovídal nejnižší míře zabezpečení pro kategorii Tajné; současně zavést pravidelné ověřování v periodicitě dle vyhlášky a promítnout změny do projektu fyzické bezpečnosti (§ 32) a do antiodposlechové ochrany (§ 26). Procesní kroky: revize rizik, přepočet bodů, aktualizace projektu, protokol o ověření. Riziko/alternativa: bez aktualizace Úřad shledá nedosažení míry zabezpečení a porušení povinnosti průběžného hodnocení.

**6. Varianty.** (a) Kdyby rizika klesla (např. zrušení sousední zástavby), bylo by možné po novém hodnocení některá opatření přiměřeně redukovat při zachování nejnižší míry zabezpečení. (b) Šlo-li by o jednací oblast, projevila by se změna rizik i v povinnosti zopakovat antiodposlechové prověření NÚKIB (§ 26).

#### G. Protiargumenty a rizika

- *Protiargument 1: „Jednou dosažená bodová hranice platí trvale."* Neutralizace: odst. 4 a 5 zakládají průběžnost hodnocení rizik a pravidelné ověřování; bezpečnost je dynamický stav, nikoli jednorázový certifikát bodů.
- *Protiargument 2: „Změna okolních hrozeb se ZO netýká, pokud opatření zůstala."* Neutralizace: bodové hodnocení je podle odst. 1 navázáno na vyhodnocení rizik; rostou-li hrozby, může táž sada opatření přestat dosahovat nejnižší míry zabezpečení.
- *Slabé místo:* § 31 odkazuje na bodové hodnoty a periodicitu ve vyhlášce; bez její aktuální znalosti nelze spolehlivě určit, zda je míra zabezpečení splněna — riziko formálního, neaktuálního propočtu.

#### H. Praktický závěr

§ 31 zavádí bodové vyjádření míry zabezpečení: součet hodnot opatření musí dosáhnout nejnižší míry podle vyhlášky a navazuje na průběžné vyhodnocení rizik. Orgán je povinen pravidelně ověřovat soulad opatření s projektem a předpisy.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Provést a průběžně aktualizovat vyhodnocení rizik (odst. 1, 4).
- [ ] Zajistit, aby součet bodů opatření dosahoval nejnižší míry zabezpečení dle vyhlášky.
- [ ] Pravidelně ověřovat soulad opatření s projektem a předpisy (odst. 5) a vést protokoly.
- [ ] Promítnout změny rizik do projektu fyzické bezpečnosti (§ 32) a antiodposlechu (§ 26).

**Typicky rozhodné důkazy / podklady:** vyhodnocení rizik a jeho aktualizace, bodové propočty, projekt fyzické bezpečnosti, protokoly o pravidelném ověřování.

---


<!-- LEGAL-REVISION:BEGIN id=b2610d0371feda8abc33 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 31

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Míra zabezpečení jednací oblasti a zabezpečené oblasti opatřeními fyzické bezpečnosti se určuje pomocí bodových hodnot těchto opatření v závislosti na vyhodnocení rizik; bodové hodnoty a nejnižší míra zabezpečení jsou stanoveny prováděcím právním předpisem.
>
> (2) Opatření fyzické bezpečnosti nebo kombinace více těchto opatření musí odpovídat alespoň nejnižší míře zabezpečení jednací oblasti nebo zabezpečené oblasti a stanoví se v závislosti na vyhodnocení rizik a na stupni utajení utajovaných informací, které jsou v jednací oblasti pravidelně projednávány, nebo na kategorii zabezpečené oblasti.
>
> (3) Opatření podle odstavce 2 a opatření fyzické bezpečnosti objektu bez zabezpečené oblasti nebo jednací oblasti schvaluje a stanoví odpovědná osoba nebo jí pověřená osoba v projektu fyzické bezpečnosti.
>
> (4) Hodnocení rizik musí být prováděno průběžně a v případě potřeby musí být míra opatření fyzické bezpečnosti upravena.
>
> (5) Orgán státu, právnická osoba podle [[#§ 60b|§ 60b]] a podnikatel jsou povinni zajistit a pravidelně ověřovat, zda použitá opatření fyzické bezpečnosti odpovídají projektu fyzické bezpečnosti a právním předpisům v oblasti ochrany utajovaných informací.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 60b

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=b2610d0371feda8abc33 -->

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

#### F. Kazuistika

**1. Modelová situace.** Podnikatel provozuje objekt, v němž se nachází zabezpečená oblast kategorie Tajné. Jeho projekt fyzické bezpečnosti obsahuje určení objektu a ZO, způsob použití opatření a provozní řád, avšak chybí v něm vyhodnocení rizik [písm. b)] a plán zabezpečení objektu a ZO v krizových situacích [písm. e)]. Úřad při kontrole posuzuje úplnost projektu. Účastníci: podnikatel (odpovědná osoba/bezpečnostní ředitel), Úřad. Důkazy: samotný projekt fyzické bezpečnosti, jeho jednotlivé části, doklad o uložení, klasifikace projektu jako UI.

**2. Právní otázka.** Splňuje projekt fyzické bezpečnosti pro objekt se ZO kategorie Tajné požadavky § 32 odst. 1, postrádá-li vyhodnocení rizik [písm. b)] a krizový plán zabezpečení [písm. e)]?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 32 — diferencovaný obsah projektu fyzické bezpečnosti; pro objekty se ZO kategorie PT/T/D plný obsah pěti položek [odst. 1 písm. a)–e): určení objektu a ZO, vyhodnocení rizik, způsob použití opatření, provozní řád, krizový plán]; zjednodušený obsah pro objekty s ZO kategorie V (odst. 2) a pro objekty s JO (odst. 3); uložení projektu u odpovědné osoby/bezpečnostního ředitele (odst. 7).
- *Související ustanovení téhož zákona:* § 24–26 (objekt, ZO, JO), § 27–30 (opatření), § 31 (bodové hodnocení a vyhodnocení rizik), § 33 (zmocnění k vyhlášce).
- *Související předpisy:* vyhláška č. 528/2005 Sb., o fyzické bezpečnosti (náležitosti projektu a provozního řádu).
- *Judikatura:* publikovaná judikatura chybí; rozhodné jsou kontrolní standardy Úřadu a vyhláška — nosné je pravidlo, že projekt bez obligatorních náležitostí nesplňuje zákonný požadavek a ZO nelze řádně provozovat.

**4. Subsumpce.** Objekt obsahuje ZO kategorie Tajné, na niž dopadá odst. 1 vyžadující všech pět položek. Projekt postrádá vyhodnocení rizik [písm. b)] a krizový plán [písm. e)] — dvě z pěti obligatorních náležitostí. Tím projekt nesplňuje § 32 odst. 1; bez vyhodnocení rizik navíc nelze řádně provést bodové hodnocení podle § 31.

**5. Řešení.** Podnikatel musí projekt doplnit o vyhodnocení rizik a plán zabezpečení objektu a ZO v krizových situacích; teprve úplný projekt splňuje § 32 odst. 1. Projekt se uloží u odpovědné osoby/bezpečnostního ředitele (odst. 7) a vzhledem k tomu, že popisuje slabá místa, zpravidla se sám utají (typicky Vyhrazené či vyšší). Procesní kroky: doplnění chybějících částí, přepočet bodů (§ 31), uložení a klasifikace projektu. Riziko/alternativa: bez doplnění Úřad shledá projekt neúplným a fyzickou bezpečnost ZO za nedostatečně podloženou.

**6. Varianty.** (a) Šlo-li by o objekt jen se ZO kategorie Vyhrazené, postačil by zjednodušený obsah (odst. 2 — dvě položky) a absence krizového plánu by projekt nediskvalifikovala. (b) Šlo-li by o objekt s jednací oblastí, použil by se plný obsah s JO namísto ZO (odst. 3).

#### G. Protiargumenty a rizika

- *Protiargument 1: „Vyhodnocení rizik je součástí bodového hodnocení, do projektu nepatří."* Neutralizace: § 32 odst. 1 písm. b) výslovně řadí vyhodnocení rizik mezi obligatorní náležitosti projektu; jeho provázanost s § 31 jeho samostatné zařazení do projektu nevylučuje, naopak vyžaduje.
- *Protiargument 2: „Krizový plán je nadbytečný, pokud objekt nikdy nečelil krizi."* Neutralizace: písm. e) ukládá plán zabezpečení pro krizové situace bez ohledu na to, zda krize nastala; jde o preventivní obligatorní obsah projektu u kategorií PT/T/D.
- *Slabé místo:* diferenciace obsahu projektu podle odstavců 1–5 je členitá; záměna režimu (např. použití zjednodušeného obsahu na ZO kategorie Tajné) vede k neúplnému projektu — nutná pečlivá subsumpce typu objektu.

#### H. Praktický závěr

§ 32 odstupňovává obsah projektu fyzické bezpečnosti podle typu objektu a kategorie ZO/JO: pro PT/T/D plný obsah pěti náležitostí (vč. vyhodnocení rizik a krizového plánu), pro V zjednodušený. Projekt se ukládá u odpovědné osoby/bezpečnostního ředitele a sám bývá utajovanou informací.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Určit režim obsahu projektu podle typu objektu a kategorie ZO/JO (odst. 1–5).
- [ ] U PT/T/D zahrnout všech pět náležitostí, vč. vyhodnocení rizik [písm. b)] a krizového plánu [písm. e)].
- [ ] Provázat projekt s bodovým hodnocením (§ 31) a provozním řádem (§ 29).
- [ ] Projekt uložit u odpovědné osoby/bezpečnostního ředitele a zvážit jeho utajení.

**Typicky rozhodné důkazy / podklady:** úplný projekt fyzické bezpečnosti se všemi obligatorními částmi, vyhodnocení rizik, provozní řád, doklad o uložení a klasifikaci projektu.

---


<!-- LEGAL-REVISION:BEGIN id=5585e3abacdaa997979c generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 32 — Projekt fyzické bezpečnosti

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Projekt fyzické bezpečnosti v případech, kdy se v objektu nacházejí zabezpečené oblasti kategorie Přísně tajné, Tajné nebo Důvěrné, obsahuje
>
> - a) určení objektu a zabezpečených oblastí, včetně jejich hranic a určení kategorií a tříd zabezpečených oblastí,
>
> - b) vyhodnocení rizik,
>
> - c) způsob použití opatření fyzické bezpečnosti,
>
> - d) provozní řád objektu a
>
> - e) plán zabezpečení objektu a zabezpečených oblastí v krizových situacích.
>
> (2) Projekt fyzické bezpečnosti v případech, kdy se v objektu nachází zabezpečená oblast pouze kategorie Vyhrazené, obsahuje
>
> - a) určení objektu a zabezpečených oblastí, včetně jejich hranic a určení kategorií a tříd zabezpečených oblastí a
>
> - b) způsob použití opatření fyzické bezpečnosti.
>
> (3) Projekt fyzické bezpečnosti v případech, kdy se v objektu nachází jednací oblast, obsahuje
>
> - a) určení objektu a jednací oblasti, včetně jejich hranic,
>
> - b) vyhodnocení rizik,
>
> - c) způsob použití opatření fyzické bezpečnosti,
>
> - d) provozní řád objektu a
>
> - e) plán zabezpečení objektu a jednací oblasti v krizových situacích.
>
> (4) Projekt fyzické bezpečnosti objektu kategorie Přísně tajné, Tajné a Důvěrné bez zabezpečené oblasti nebo jednací oblasti obsahuje
>
> - a) určení objektu včetně jeho hranic,
>
> - b) způsob použití opatření fyzické bezpečnosti,
>
> - c) provozní řád objektu a
>
> - d) plán zabezpečení objektu v krizových situacích.
>
> (5) Projekt fyzické bezpečnosti objektu kategorie Vyhrazené bez zabezpečené oblasti obsahuje určení objektu včetně jeho hranic.
>
> (6) Na projekt fyzické bezpečnosti se v případech podle § 30 odst. 3 použijí ustanovení odstavců 1 až 5 přiměřeně; rozsah projektu schvaluje a stanoví odpovědná osoba nebo jí pověřená osoba.
>
> (7) Projekt fyzické bezpečnosti se ukládá u odpovědné osoby nebo bezpečnostního ředitele.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 30

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=5585e3abacdaa997979c -->

### § 33 — Zmocňovací ustanovení (fyzická bezpečnost)

Zmocnění k vydání prováděcí vyhlášky č. 528/2005 Sb., o fyzické bezpečnosti — stanovuje detailní požadavky na JO, způsob ukládání, ostrahu, režimová opatření, technické prostředky, bodové hodnocení, ověřování a obsah provozního řádu.

#### F. Kazuistika

**1. Modelová situace.** Podnikatel v řízení před Úřadem namítá, že konkrétní bodové hodnoty jednotlivých opatření a minimální dojezdové časy zásahové ostrahy nejsou stanoveny v zákoně, nýbrž jen ve vyhlášce č. 528/2005 Sb., a domnívá se, že proto pro něj nejsou závazné. Úřad posuzuje, zda jsou požadavky vyhlášky vydané na základě § 33 závazné a v mezích zákonného zmocnění. Účastníci: podnikatel, Úřad. Důkazy: text vyhlášky č. 528/2005 Sb. a jejích příloh, projekt fyzické bezpečnosti, bodové vyhodnocení.

**2. Právní otázka.** Jsou detailní požadavky stanovené prováděcí vyhláškou vydanou na základě zmocnění v § 33 závazné, ačkoli nejsou obsaženy přímo v zákoně, a v jakých mezích?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 33 — zmocnění k vydání prováděcí vyhlášky o fyzické bezpečnosti (požadavky na JO, ukládání, ostrahu, režimová opatření, technické prostředky, bodové hodnocení, ověřování, obsah provozního řádu).
- *Související ustanovení téhož zákona:* § 24–32 (hmotněprávní rámec fyzické bezpečnosti, jejž vyhláška konkretizuje), § 31 (bodové hodnocení), § 32 (projekt fyzické bezpečnosti).
- *Související předpisy:* vyhláška č. 528/2005 Sb., o fyzické bezpečnosti a certifikaci technických prostředků; čl. 79 odst. 3 Ústavy (ministerstva a jiné správní úřady mohou vydávat právní předpisy na základě a v mezích zákona, jsou-li k tomu zmocněny).
- *Judikatura:* obecná ústavní doktrína k podzákonným předpisům (sekundární normotvorba je vázána zmocněním — secundum et intra legem); prováděcí předpis nesmí překročit meze zákona ani stanovit primární povinnosti nad jeho rámec.

**4. Subsumpce.** § 33 zmocňuje k vydání vyhlášky upravující detailní požadavky fyzické bezpečnosti. Vyhláška č. 528/2005 Sb. tyto otázky (bodové hodnoty, dojezdové časy, parametry) konkretizuje v mezích zmocnění. Pohybuje-li se vyhláška uvnitř zákonného zmocnění a neukládá povinnosti nad rámec zákona, je závazná stejně jako zákon; námitka, že požadavky nejsou „přímo v zákoně", proto neobstojí.

**5. Řešení.** Úřad správně vychází z toho, že požadavky vyhlášky vydané na základě § 33 jsou závazné, neboť konkretizují hmotněprávní rámec § 24–32 a nepřekračují zmocnění. Podnikatel je povinen je splnit. Procesně: posouzení souladu konkrétního požadavku se zmocněním a se zákonem. Riziko/alternativa: pouze pokud by vyhláška překročila meze zmocnění (uložila by primární povinnost nad rámec zákona), bylo by možné namítat její neaplikovatelnost v dané části — to však není případ standardních parametrů fyzické bezpečnosti.

**6. Varianty.** (a) Kdyby vyhláška stanovila povinnost bez opory v zákoně (ultra vires), soud by k ní v rozsahu excesu nemusel přihlédnout. (b) Při novelizaci zákona rozšiřující zmocnění by se odpovídajícím způsobem mohl rozšířit i rozsah závazné prováděcí úpravy.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Co není v zákoně, není závazné."* Neutralizace: čl. 79 odst. 3 Ústavy umožňuje správním úřadům vydávat závazné předpisy na základě a v mezích zákona; vyhláška vydaná podle § 33 je v tomto rámci součástí platného práva.
- *Protiargument 2: „Zmocnění je příliš široké, a proto neústavní."* Neutralizace: § 33 zmocnění věcně vymezuje (JO, ukládání, ostraha, režim, technika, body, ověřování, provozní řád); jde o konkretizaci, nikoli o blanketní delegaci primárních povinností.
- *Slabé místo:* zmocňovací ustanovení samo nestanoví práva a povinnosti — jeho aplikace vždy vyžaduje znalost aktuálního znění vyhlášky; změny vyhlášky mohou modifikovat povinnosti, aniž se mění zákon.

#### H. Praktický závěr

§ 33 je zmocněním k vydání vyhlášky č. 528/2005 Sb., která závazně konkretizuje požadavky fyzické bezpečnosti (§ 24–32). Prováděcí úprava je závazná v mezích zmocnění; primární povinnosti nad rámec zákona stanovit nesmí.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Pracovat vždy s aktuálním zněním vyhlášky č. 528/2005 Sb. a jejích příloh.
- [ ] Ověřit, že konkrétní požadavek vyhlášky má oporu ve zmocnění § 33 a v zákoně.
- [ ] Při pochybnostech posoudit, zda vyhláška nepřekročila meze zmocnění (ultra vires).
- [ ] Detailní parametry (body, dojezdy, ukládání) promítnout do projektu a provozního řádu.

**Typicky rozhodné důkazy / podklady:** text vyhlášky č. 528/2005 Sb. a jejích příloh, projekt fyzické bezpečnosti, bodové vyhodnocení, případně analýza souladu vyhlášky se zákonným zmocněním.

---


<!-- LEGAL-REVISION:BEGIN id=8357757212e4fb77a964 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 33 — Zmocňovací ustanovení

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> Prováděcí právní předpis stanoví
>
> - a) požadavky na jednací oblasti z hlediska fyzické bezpečnosti a rizika úniku utajovaných informací formou kompromitujícího vyzařování,
>
> - b) způsob ukládání utajovaných informací v závislosti na stupni jejich utajení (§ 24 odst. 6),
>
> - c) organizační požadavky na provádění ostrahy ([[#§ 28|§ 28]]) a zabezpečení jednací oblasti nebo zabezpečené oblasti touto ostrahou, včetně určení kategorie osob uvedených v § 28 odst. 4, a to v závislosti na stupni utajení utajovaných informací, které jsou v jednací oblasti pravidelně projednávány, na kategorii objektu, nebo na kategorii zabezpečené oblasti,
>
> - d) podrobnosti režimových opatření ([[#§ 29|§ 29]]),
>
> - e) požadavky na technické prostředky, uvedené v § 30 odst. 1, a zabezpečení objektů, jednací oblasti nebo zabezpečené oblasti těmito prostředky, v závislosti na stupni utajení utajovaných informací, které jsou v jednací oblasti pravidelně projednávány, nebo na kategorii zabezpečené oblasti, anebo na kategorii objektu,
>
> - f) bodové ohodnocení jednotlivých opatření fyzické bezpečnosti a bodovou hodnotu nejnižší míry zabezpečení jednací oblasti nebo zabezpečené oblasti, včetně základní metody hodnocení rizik (§ 31 odst. 1 a [[#§ 2|2]]),
>
> - g) četnost a způsob zápisu o ověřování, zda použitá opatření fyzické bezpečnosti odpovídají projektu fyzické bezpečnosti a právním předpisům v oblasti ochrany utajovaných informací, v závislosti na stupni utajení utajovaných informací (§ 31 odst. 5),
>
> - h) obsah provozního řádu objektu a plánu zabezpečení objektů, zabezpečených oblastí a jednacích oblastí v krizových situacích [§ 32 odst. 1 písm. d) a e) a § 32 odst. 3 písm. d) a e)].

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 24, § 28, § 29, § 30, § 31, § 2, § 32

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=8357757212e4fb77a964 -->

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

#### F. Kazuistika

**1. Modelová situace.** Provozovatel certifikovaného informačního systému pro UI obdrží od Úřadu (NBÚ) výzvu k zavedení dalších bezpečnostních opatření v IS a současně řeší žádost o certifikaci nového IS. Provozovatel je na pochybách, zda je k těmto úkonům v oblasti IS příslušný Úřad, nebo NÚKIB. Účastníci: provozovatel IS, Úřad (NBÚ), NÚKIB. Důkazy: certifikát IS, výzva orgánu, organizační vymezení působnosti podle Hlavy VI, korespondence.

**2. Právní otázka.** Který orgán vykonává státní správu v oblasti bezpečnosti informačních a komunikačních systémů (Hlava VI) — Úřad, nebo NÚKIB — a jaké jsou důsledky úkonu učiněného nepříslušným orgánem?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 33a — státní správu v oblasti ochrany UI podle Hlavy VI vykonává NÚKIB, pokud zákon nestanoví jinak.
- *Související ustanovení téhož zákona:* § 34, § 35 (IS a KS — certifikace/schvalování NÚKIBem), § 46 odst. 1 písm. b) (certifikace IS), § 48, § 49 (certifikace IS a kryptoprostředků NÚKIB), § 35b, § 36a, § 37–45a (příslušnost NÚKIB v dalších hlavách).
- *Související předpisy:* zákon č. 181/2014 Sb., o kybernetické bezpečnosti (zřízení a působnost NÚKIB); zákon č. 205/2017 Sb. (přenos kompetencí na NÚKIB od 1. 8. 2017); správní řád (§ 10 a násl. — věcná příslušnost).
- *Judikatura:* obecná zásada správního práva, že k úkonu je oprávněn věcně příslušný orgán; úkon učiněný nepříslušným orgánem trpí vadou (zpravidla je nicotný či nezákonný) — promítá se do přezkumu rozhodnutí.

**4. Subsumpce.** Oblast IS/KS spadá pod Hlavu VI; podle § 33a v ní státní správu vykonává NÚKIB (nestanoví-li zákon jinak). Certifikace IS i ukládání dalších bezpečnostních opatření v IS jsou agendou Hlavy VI, tedy v působnosti NÚKIB, nikoli Úřadu. Výzva či certifikace vydaná v této oblasti Úřadem by byla úkonem věcně nepříslušného orgánu.

**5. Řešení.** Provozovatel se v záležitostech IS/KS obrací na NÚKIB; úkon, jejž ve věci IS učinil Úřad, je třeba posoudit jako vadný pro věcnou nepříslušnost a vyžádat si úkon od NÚKIB. Procesní kroky: ověření věcné příslušnosti, postoupení věci příslušnému orgánu, případně napadení úkonu nepříslušného orgánu. Riziko/alternativa: ponechání rozdělení působnosti bez povšimnutí může vést k neplatným/nicotným úkonům a procesním komplikacím; naopak v oblastech personální, administrativní a fyzické bezpečnosti zůstává příslušný Úřad.

**6. Varianty.** (a) Šlo-li by o objekt, ZO či JO (fyzická bezpečnost, § 24 a násl.), byl by příslušný Úřad, nikoli NÚKIB. (b) Stanovil-li by zákon pro určitý dílčí úkon Hlavy VI výjimku („pokud zákon nestanoví jinak"), mohla by příslušnost připadnout jinému orgánu.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Veškerou ochranu UI zajišťuje NBÚ."* Neutralizace: po novele zákonem č. 205/2017 Sb. byla agenda IS/KS, kryptografie a kompromitujícího vyzařování přenesena na NÚKIB; § 33a to pro Hlavu VI výslovně stanoví.
- *Protiargument 2: „Rozdělení působnosti je formalita bez vlivu na platnost úkonů."* Neutralizace: věcná příslušnost je podmínkou zákonnosti správních úkonů; úkon nepříslušného orgánu je stižen vadou a může být nicotný.
- *Slabé místo:* hranice mezi působností Úřadu a NÚKIB je rozdělena podle hlav zákona; ve smíšených případech (např. IS umístěný v ZO) je nutné odlišit fyzickou bezpečnost prostoru (Úřad) od bezpečnosti IS (NÚKIB).

#### H. Praktický závěr

§ 33a svěřuje výkon státní správy v oblasti bezpečnosti IS/KS (Hlava VI) NÚKIB, nestanoví-li zákon jinak. Úřad (NBÚ) si ponechává personální, administrativní a fyzickou bezpečnost a bezpečnostní způsobilost. Volba správného orgánu je podmínkou platnosti úkonů.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Určit, do které hlavy zákona agenda spadá, a podle toho příslušný orgán (Úřad vs. NÚKIB).
- [ ] V záležitostech IS/KS (Hlava VI) jednat s NÚKIB (certifikace IS, opatření v IS).
- [ ] U smíšených situací odlišit fyzickou bezpečnost prostoru (Úřad) od bezpečnosti IS (NÚKIB).
- [ ] Úkon nepříslušného orgánu napadnout, resp. iniciovat postoupení věci.

**Typicky rozhodné důkazy / podklady:** certifikáty a rozhodnutí v oblasti IS/KS, organizační vymezení působnosti podle hlav zákona, korespondence s Úřadem a NÚKIB.

---


<!-- LEGAL-REVISION:BEGIN id=336666367f0c512ef157 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 33a

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> Státní správu v oblasti ochrany utajovaných informací podle této hlavy vykonává Národní úřad pro kybernetickou a informační bezpečnost, pokud tento zákon nestanoví jinak.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Místní znění neobsahuje výslovný vnitřní odkaz.

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=336666367f0c512ef157 -->

### § 34 — Informační systém pro UI

> **§ 34**
>
> *(1) Informačním systémem nakládajícím s utajovanými informacemi se pro účely tohoto zákona rozumí jeden nebo více počítačů, jejich programové vybavení, k tomu patřící periferní zařízení, správa tohoto informačního systému a k tomuto systému se vztahující procesy nebo prostředky schopné provádět sběr, tvorbu, zpracování, ukládání, zobrazení nebo přenos utajovaných informací (dále jen „informační systém“).*
>
> *(2) Informační systém musí být certifikován Národním úřadem pro kybernetickou a informační bezpečnost [§ 46 odst. 1 písm. b)] a písemně schválen do provozu odpovědnou osobou nebo jí pověřenou osobou. Způsobilost informačního systému cizí moci k nakládání s utajovanými informacemi ověřuje formou akreditace Národní úřad pro kybernetickou a informační bezpečnost.*
>
> *(3) Informační systém podnikatele, který má přístup k utajovaným informacím stupně utajení Vyhrazené, může být schválen do provozu jen v době platnosti prohlášení podnikatele; zánikem platnosti prohlášení podnikatele zaniká též schválení informačního systému do provozu.*
>
> *(4) Národní úřad pro kybernetickou a informační bezpečnost může z důvodu identifikovaných hrozeb nebo rizik stanovit provozovateli certifikovaného informačního systému zavedení dalších nutných bezpečnostních funkcí nebo opatření. Zavedení dalších nutných bezpečnostních funkcí nebo opatření oznámí provozovatel Národnímu úřadu pro kybernetickou a informační bezpečnost.*
>
> *(5) Nakládat s utajovanou informací lze pouze v informačním systému splňujícím podmínky podle odstavce 2 až 4.*
>
> *(6) Schválení informačního systému do provozu podle odstavce 2 musí odpovědná osoba nebo jí pověřená osoba písemně oznámit Národnímu úřadu pro kybernetickou a informační bezpečnost do 30 dnů od tohoto schválení.*
>
> *(7) Prováděcí právní předpis stanoví*
>
> *- a) požadavky na informační systém a podmínky jeho bezpečného provozování v závislosti na stupni utajení utajovaných informací, s nimiž nakládá, a na bezpečnostním provozním módu,*
>
> *- b) obsah bezpečnostní dokumentace informačního systému a*
>
> *- c) náležitosti oznámení provozovatele certifikovaného informačního systému o zavedení dalších nutných bezpečnostních funkcí nebo opatření Národnímu úřadu pro kybernetickou a informační bezpečnost.*

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

#### F. Kazuistika

**1. Modelová situace.** Podnikatel s přístupem k UI stupně Vyhrazené nasadí pro jejich zpracování informační systém. Systém prošel certifikací NÚKIB, odpovědná osoba jej však dosud písemně neschválila do provozu a zaměstnanci v něm již UI zpracovávají. Současně podnikateli zanikne platnost prohlášení podnikatele. Účastníci: podnikatel (odpovědná osoba), NÚKIB (certifikační orgán), Úřad. Důkazy: certifikát IS, písemné schválení do provozu (chybí), oznámení NÚKIB do 30 dnů (chybí), doklad o platnosti prohlášení podnikatele.

**2. Právní otázka.** Lze v informačním systému nakládat s UI, jestliže je sice certifikován NÚKIB, ale chybí písemné schválení do provozu odpovědnou osobou, a jaký vliv má zánik platnosti prohlášení podnikatele u IS pro UI stupně Vyhrazené?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 34 — definice IS (odst. 1); dvojí podmínka uvedení do provozu: certifikace NÚKIB [§ 46 odst. 1 písm. b)] a písemné schválení odpovědnou osobou (odst. 2); vázanost schválení IS podnikatele s Vyhrazenými UI na platnost prohlášení podnikatele (odst. 3); možnost NÚKIB uložit další opatření (odst. 4); zákaz nakládat s UI mimo IS splňující odst. 2–4 (odst. 5); oznámení schválení NÚKIB do 30 dnů (odst. 6).
- *Související ustanovení téhož zákona:* § 35 (KS — obdobný režim), § 35a (taktická informace v IS/KS), § 46–48 (certifikace), § 15a (prohlášení podnikatele), § 33a (příslušnost NÚKIB).
- *Související předpisy:* vyhláška o bezpečnosti IS pro UI; zákon č. 181/2014 Sb. (NÚKIB).
- *Judikatura:* publikovaná judikatura k tomuto ustanovení je sporá; rozhodné jsou kontrolní standardy NÚKIB — nosné je pravidlo, že bez kumulativního splnění certifikace a schválení do provozu nelze UI v IS zpracovávat (odst. 5).

**4. Subsumpce.** K provozu IS pro UI jsou podle odst. 2 nutné dvě kumulativní podmínky: certifikace NÚKIB a písemné schválení do provozu odpovědnou osobou. Certifikace je splněna, schválení do provozu chybí — podmínky odst. 2 tedy naplněny nejsou a podle odst. 5 nesmí být UI v IS zpracovávána. Zpracování UI před schválením je porušením zákona. Zánik platnosti prohlášení podnikatele navíc podle odst. 3 ruší schválení IS pro UI stupně Vyhrazené.

**5. Řešení.** Podnikatel musí před zpracováním UI zajistit písemné schválení IS do provozu odpovědnou osobou (nebo jí pověřenou osobou) a do 30 dnů je oznámit NÚKIB (odst. 6); do té doby v IS s UI nakládat nelze. Zaniklo-li prohlášení podnikatele, zaniká i schválení IS (odst. 3) a provoz s Vyhrazenými UI je nutné přerušit do obnovení platnosti prohlášení. Procesní kroky: schválení do provozu, oznámení NÚKIB, kontrola platnosti prohlášení. Riziko/alternativa: pokračování v provozu bez schválení nebo po zániku prohlášení zakládá porušení zákona a bezpečnostní riziko.

**6. Varianty.** (a) Šlo-li by o IS cizí moci, neaplikovala by se certifikace, nýbrž akreditace prováděná NÚKIB (odst. 2 in fine). (b) Identifikuje-li NÚKIB nové hrozby, může podle odst. 4 uložit zavedení dalších bezpečnostních funkcí; jejich zavedení provozovatel NÚKIB oznámí.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Certifikace NÚKIB sama postačí k provozu IS."* Neutralizace: odst. 2 vyžaduje kumulativně i písemné schválení do provozu odpovědnou osobou; bez něj odst. 5 zpracování UI zakazuje.
- *Protiargument 2: „Zánik prohlášení podnikatele se IS netýká."* Neutralizace: odst. 3 výslovně váže schválení IS pro UI stupně Vyhrazené na platnost prohlášení podnikatele; jeho zánikem zaniká i schválení IS.
- *Slabé místo:* definice IS je široká (HW + SW + správa + procesy); v praxi může být sporné, kde končí „samostatné zařízení" (§ 36) a začíná IS — od toho se odvíjí, zda je nutná certifikace IS, nebo režim § 36.

#### H. Praktický závěr

§ 34 podmiňuje nakládání s UI v informačním systému kumulativně certifikací NÚKIB a písemným schválením odpovědnou osobou; u IS podnikatele s Vyhrazenými UI je schválení vázáno na platnost prohlášení podnikatele. Schválení se do 30 dnů oznamuje NÚKIB.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Zajistit certifikaci IS NÚKIB [§ 46 odst. 1 písm. b)] před zpracováním UI.
- [ ] Vydat písemné schválení IS do provozu odpovědnou osobou (odst. 2) a do 30 dnů je oznámit NÚKIB (odst. 6).
- [ ] U IS s Vyhrazenými UI hlídat platnost prohlášení podnikatele (odst. 3).
- [ ] Reagovat na případná dodatečná opatření uložená NÚKIB (odst. 4) a jejich zavedení oznámit.

**Typicky rozhodné důkazy / podklady:** certifikát IS, písemné schválení do provozu, oznámení NÚKIB do 30 dnů, doklad o platnosti prohlášení podnikatele, bezpečnostní dokumentace IS.

---


<!-- LEGAL-REVISION:BEGIN id=a0e8d7ae6ddd63f236ad generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 34 — Informační systém

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Informačním systémem nakládajícím s utajovanými informacemi se pro účely tohoto zákona rozumí jeden nebo více počítačů, jejich programové vybavení, k tomu patřící periferní zařízení, správa tohoto informačního systému a k tomuto systému se vztahující procesy nebo prostředky schopné provádět sběr, tvorbu, zpracování, ukládání, zobrazení nebo přenos utajovaných informací (dále jen „informační systém“).
>
> (2) Informační systém musí být certifikován Národním úřadem pro kybernetickou a informační bezpečnost [§ 46 odst. 1 písm. b)] a písemně schválen do provozu odpovědnou osobou nebo jí pověřenou osobou. Způsobilost informačního systému cizí moci k nakládání s utajovanými informacemi ověřuje formou akreditace Národní úřad pro kybernetickou a informační bezpečnost.
>
> (3) Informační systém podnikatele, který má přístup k utajovaným informacím stupně utajení Vyhrazené, může být schválen do provozu jen v době platnosti prohlášení podnikatele; zánikem platnosti prohlášení podnikatele zaniká též schválení informačního systému do provozu.
>
> (4) Národní úřad pro kybernetickou a informační bezpečnost může z důvodu identifikovaných hrozeb nebo rizik stanovit provozovateli certifikovaného informačního systému zavedení dalších nutných bezpečnostních funkcí nebo opatření. Zavedení dalších nutných bezpečnostních funkcí nebo opatření oznámí provozovatel Národnímu úřadu pro kybernetickou a informační bezpečnost.
>
> (5) Nakládat s utajovanou informací lze pouze v informačním systému splňujícím podmínky podle odstavce 2 až 4.
>
> (6) Schválení informačního systému do provozu podle odstavce 2 musí odpovědná osoba nebo jí pověřená osoba písemně oznámit Národnímu úřadu pro kybernetickou a informační bezpečnost do 30 dnů od tohoto schválení.
>
> (7) Prováděcí právní předpis stanoví
>
> - a) požadavky na informační systém a podmínky jeho bezpečného provozování v závislosti na stupni utajení utajovaných informací, s nimiž nakládá, a na bezpečnostním provozním módu,
>
> - b) obsah bezpečnostní dokumentace informačního systému a
>
> - c) náležitosti oznámení provozovatele certifikovaného informačního systému o zavedení dalších nutných bezpečnostních funkcí nebo opatření Národnímu úřadu pro kybernetickou a informační bezpečnost.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 46

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=a0e8d7ae6ddd63f236ad -->

### § 35 — Komunikační systém

> **§ 35**
>
> *(1) Komunikačním systémem nakládajícím s utajovanými informacemi (dále jen „komunikační systém“) se pro účely tohoto zákona rozumí systém zajišťující přenos těchto informací mezi koncovými uživateli a zahrnující koncové komunikační zařízení, periferní zařízení, přenosové prostředí, kryptografické prostředky, obsluhu a provozní podmínky a postupy.*
>
> *(2) Komunikační systém nelze provozovat bez projektu bezpečnosti komunikačního systému schváleného Národním úřadem pro kybernetickou a informační bezpečnost. O schválení projektu bezpečnosti komunikačního systému písemně žádá u Národního úřadu pro kybernetickou a informační bezpečnost orgán státu, právnická osoba podle § 60b nebo podnikatel, který jej bude provozovat.*
>
> *(3) Nakládat s utajovanou informací lze pouze v komunikačním systému splňujícím podmínky podle odstavce 2.*
>
> *(4) Komunikační systém musí být písemně schválen do provozu odpovědnou osobou nebo jí pověřenou osobou.*
>
> *(5) Komunikační systém podnikatele, který má přístup k utajovaným informacím stupně utajení Vyhrazené, může být schválen do provozu jen v době platnosti prohlášení podnikatele; zánikem platnosti prohlášení podnikatele zaniká též schválení komunikačního systému do provozu.*
>
> *(6) Prováděcí právní předpis stanoví*
>
> *- a) obsah žádosti o schválení projektu bezpečnosti komunikačního systému a*
>
> *- b) náležitosti projektu bezpečnosti komunikačního systému a způsob a podmínky jeho schvalování.*

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

#### F. Kazuistika

**1. Modelová situace.** Orgán státu chce zprovoznit komunikační systém pro přenos UI mezi dvěma pracovišti (kryptolinka). Pořídí koncová komunikační zařízení a kryptografické prostředky a začne UI přenášet, aniž NÚKIB schválil projekt bezpečnosti komunikačního systému. Odpovědná osoba KS rovněž písemně neschválila do provozu. Účastníci: orgán státu (provozovatel KS), NÚKIB (schvaluje projekt), Úřad. Důkazy: projekt bezpečnosti KS a žádost o jeho schválení (chybí), písemné schválení do provozu (chybí), dokumentace kryptoprostředků.

**2. Právní otázka.** Lze provozovat komunikační systém a přenášet v něm UI bez schválení projektu bezpečnosti KS Národním úřadem pro kybernetickou a informační bezpečnost a bez písemného schválení do provozu odpovědnou osobou?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 35 — definice KS jako systému zajišťujícího přenos UI mezi koncovými uživateli (odst. 1); zákaz provozu KS bez projektu bezpečnosti schváleného NÚKIB, o nějž žádá orgán státu, PO podle § 60b nebo podnikatel (odst. 2); zákaz nakládat s UI mimo takový KS (odst. 3); písemné schválení do provozu odpovědnou osobou (odst. 4); vázanost na platnost prohlášení podnikatele u Vyhrazených UI (odst. 5).
- *Související ustanovení téhož zákona:* § 34 (IS — paralelní režim, certifikace), § 35a (taktická informace), § 37 a násl. (kryptografická ochrana — kryptoprostředky v KS), § 49 (certifikace kryptoprostředku), § 33a (příslušnost NÚKIB), § 60b (PO podle § 60b).
- *Související předpisy:* vyhláška upravující obsah žádosti a náležitosti projektu bezpečnosti KS; zákon č. 181/2014 Sb. (NÚKIB).
- *Judikatura:* publikovaná judikatura je sporá; rozhodné jsou standardy NÚKIB — nosné je pravidlo, že bez schváleného projektu bezpečnosti KS nelze KS provozovat (odst. 2 a 3).

**4. Subsumpce.** KS je systém zajišťující přenos UI mezi koncovými uživateli (odst. 1) — daný systém tomu odpovídá. Podle odst. 2 nelze KS provozovat bez projektu bezpečnosti schváleného NÚKIB; tento projekt nebyl ani podán, natož schválen. Podle odst. 3 nelze v takovém KS nakládat s UI. Chybí též písemné schválení do provozu odpovědnou osobou (odst. 4). Znaky oprávněného provozu KS tedy naplněny nejsou.

**5. Řešení.** Orgán musí před zahájením přenosu UI požádat NÚKIB o schválení projektu bezpečnosti KS (odst. 2) a zajistit písemné schválení do provozu odpovědnou osobou (odst. 4); do té doby v KS s UI nakládat nelze (odst. 3). Procesní kroky: zpracování projektu bezpečnosti KS, žádost NÚKIB, schválení do provozu. Riziko/alternativa: přenos UI v neschváleném KS je porušením zákona a bezpečnostním incidentem; u podnikatele s Vyhrazenými UI je nutné navíc hlídat platnost prohlášení (odst. 5).

**6. Varianty.** (a) Šlo-li by jen o zpracování (nikoli přenos) UI, šlo by o IS (§ 34) s režimem certifikace, nikoli o KS se schvalováním projektu. (b) Měl-li by KS přenášet taktické informace do stupně Tajné, mohl by se uplatnit rizikově orientovaný režim podle § 35a namísto plné certifikace souvisejících prostředků.

#### G. Protiargumenty a rizika

- *Protiargument 1: „KS se schvaluje stejně jako IS certifikací."* Neutralizace: u KS zákon nevyžaduje certifikaci, nýbrž schválení projektu bezpečnosti KS NÚKIB (odst. 2); jde o odlišný akt než certifikace IS podle § 34/§ 48.
- *Protiargument 2: „Schválení do provozu odpovědnou osobou je nadbytečné, postačí schválení projektu NÚKIB."* Neutralizace: odst. 4 vyžaduje navíc písemné schválení do provozu odpovědnou osobou — jde o samostatnou podmínku vedle schválení projektu.
- *Slabé místo:* hranice mezi IS a KS může být v praxi neostrá (systémy zpracovávající i přenášející UI); od správného zařazení se odvíjí, zda se uplatní certifikace (IS), nebo schválení projektu bezpečnosti (KS).

#### H. Praktický závěr

§ 35 podmiňuje provoz komunikačního systému schválením projektu bezpečnosti KS Národním úřadem pro kybernetickou a informační bezpečnost a písemným schválením do provozu odpovědnou osobou; u podnikatele s Vyhrazenými UI je vázán na platnost prohlášení podnikatele. KS slouží k přenosu UI, na rozdíl od IS (zpracování).

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Odlišit KS (přenos UI) od IS (zpracování UI) a zvolit správný režim.
- [ ] Před provozem KS získat schválení projektu bezpečnosti KS od NÚKIB (odst. 2).
- [ ] Zajistit písemné schválení KS do provozu odpovědnou osobou (odst. 4).
- [ ] U KS s Vyhrazenými UI hlídat platnost prohlášení podnikatele (odst. 5).

**Typicky rozhodné důkazy / podklady:** projekt bezpečnosti KS a doklad o jeho schválení NÚKIB, písemné schválení do provozu, dokumentace kryptografických prostředků, doklad o platnosti prohlášení podnikatele.

---


<!-- LEGAL-REVISION:BEGIN id=54086e38e908633d2b5f generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 35 — Komunikační systém

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Komunikačním systémem nakládajícím s utajovanými informacemi (dále jen „komunikační systém“) se pro účely tohoto zákona rozumí systém zajišťující přenos těchto informací mezi koncovými uživateli a zahrnující koncové komunikační zařízení, periferní zařízení, přenosové prostředí, kryptografické prostředky, obsluhu a provozní podmínky a postupy.
>
> (2) Komunikační systém nelze provozovat bez projektu bezpečnosti komunikačního systému schváleného Národním úřadem pro kybernetickou a informační bezpečnost. O schválení projektu bezpečnosti komunikačního systému písemně žádá u Národního úřadu pro kybernetickou a informační bezpečnost orgán státu, právnická osoba podle [[#§ 60b|§ 60b]] nebo podnikatel, který jej bude provozovat.
>
> (3) Nakládat s utajovanou informací lze pouze v komunikačním systému splňujícím podmínky podle odstavce 2.
>
> (4) Komunikační systém musí být písemně schválen do provozu odpovědnou osobou nebo jí pověřenou osobou.
>
> (5) Komunikační systém podnikatele, který má přístup k utajovaným informacím stupně utajení Vyhrazené, může být schválen do provozu jen v době platnosti prohlášení podnikatele; zánikem platnosti prohlášení podnikatele zaniká též schválení komunikačního systému do provozu.
>
> (6) Prováděcí právní předpis stanoví
>
> - a) obsah žádosti o schválení projektu bezpečnosti komunikačního systému a
>
> - b) náležitosti projektu bezpečnosti komunikačního systému a způsob a podmínky jeho schvalování.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 60b

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=54086e38e908633d2b5f -->

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

#### F. Kazuistika

**1. Modelová situace.** Jednotka ozbrojených sil v zahraniční misi potřebuje v reálném čase přenášet polohové údaje a krátkodobá taktická hlášení stupně Tajné mezi mobilními prvky. Klasická certifikace IS/KS pro daný kontingent by trvala měsíce. Velitel s podporou bezpečnostního správce nasadí soubor opatření založený na vyhodnocení rizik podle bezpečnostního standardu NÚKIB a informace při přenosu chrání kryptografickou ochranou. Účastníci: provozovatel (ozbrojené síly), NÚKIB (vydavatel bezpečnostního standardu), Úřad. Důkazy: vyhodnocení rizik, bezpečnostní standard NÚKIB, doklad o kryptografické ochraně přenosu, určení doby trvání důvodu utajení.

**2. Právní otázka.** Lze pro taktickou informaci do stupně Tajné nahradit plnou certifikaci IS/KS souborem opatření na základě vyhodnocení rizik podle § 35a, a za jakých podmínek?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 35a — definice taktické informace jako UI s krátkou dobou trvání důvodu utajení; zpracuje se v IS/KS a při přenosu se chrání kryptografickou ochranou; pro taktickou informaci do stupně Tajné lze ochranu zajistit souborem opatření na základě vyhodnocení rizik podle bezpečnostního standardu NÚKIB.
- *Související ustanovení téhož zákona:* § 34 (IS), § 35 (KS), § 4 (stupně utajení), § 37 a násl. (kryptografická ochrana přenosu), § 33a (příslušnost NÚKIB), § 22 odst. 3 (doba utajení).
- *Související předpisy:* bezpečnostní standard NÚKIB pro taktické informace; vyhlášky k IS/KS a kryptografické ochraně; předpisy o působení ozbrojených sil v zahraničí.
- *Judikatura:* publikovaná judikatura chybí; jde o nové operativní ustanovení — nosné je pravidlo, že rizikově orientovaný režim je přípustný jen do stupně Tajné a v mezích standardu NÚKIB.

**4. Subsumpce.** Přenášené údaje mají krátkou dobu trvání důvodu utajení (polohy, krátkodobá hlášení) — naplňují znak taktické informace. Stupeň je Tajné, tedy v rozsahu, pro nějž § 35a připouští soubor opatření na základě vyhodnocení rizik místo plné certifikace. Podmínkou je zpracování v IS/KS, kryptografická ochrana při přenosu a postup podle bezpečnostního standardu NÚKIB. Jsou-li tyto podmínky splněny, je rizikově orientovaný režim přípustný.

**5. Řešení.** Velitel postupuje podle bezpečnostního standardu NÚKIB: provede vyhodnocení rizik, nasadí odpovídající soubor opatření a zajistí kryptografickou ochranu přenosu; tím legálně nahradí plnou certifikaci pro taktickou informaci do stupně Tajné. Procesní kroky: vyhodnocení rizik, dokumentace opatření, zajištění kryptoprostředků, určení krátké doby utajení. Riziko/alternativa: u informací nad stupeň Tajné nebo bez krátkodobé povahy utajení rizikově orientovaný režim nelze použít a je nutná plná certifikace IS/KS (§ 34, § 35).

**6. Varianty.** (a) Měla-li by informace stupeň Přísně tajné, § 35a by se neuplatnil a vyžadovala by se plná certifikace IS/KS. (b) Postrádala-li by informace krátkodobou povahu důvodu utajení (trvalé utajení), nešlo by o taktickou informaci a rizikově orientovaný režim by byl vyloučen.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Rizikově orientovaný režim lze použít pro jakoukoli operativní UI."* Neutralizace: § 35a jej omezuje na taktickou informaci s krátkou dobou trvání důvodu utajení a do stupně Tajné; nad tento rámec je nutná plná certifikace.
- *Protiargument 2: „Soubor opatření podle vyhodnocení rizik nahrazuje i kryptografickou ochranu přenosu."* Neutralizace: § 35a kryptografickou ochranu při přenosu vyžaduje výslovně — nejde o prvek, jejž by vyhodnocení rizik mohlo vyloučit.
- *Slabé místo:* obsah „souboru opatření" určuje bezpečnostní standard NÚKIB, nikoli přímo zákon; bez jeho znalosti nelze posoudit dostatečnost ochrany — riziko podcenění při operativním nasazení.

#### H. Praktický závěr

§ 35a zavádí pro taktické informace (UI s krátkodobým důvodem utajení) rizikově orientovaný režim: do stupně Tajné lze ochranu zajistit souborem opatření na základě vyhodnocení rizik podle standardu NÚKIB, vždy s kryptografickou ochranou přenosu. Umožňuje agilní operace bez paralyzující certifikace.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Ověřit, že jde o UI s krátkou dobou trvání důvodu utajení (taktickou informaci) a stupeň nepřevyšuje Tajné.
- [ ] Postupovat podle bezpečnostního standardu NÚKIB a doložit vyhodnocení rizik.
- [ ] Zajistit kryptografickou ochranu informace při přenosu.
- [ ] U informací nad stupeň Tajné nebo bez krátkodobé povahy utajení použít plnou certifikaci IS/KS (§ 34, § 35).

**Typicky rozhodné důkazy / podklady:** vyhodnocení rizik a dokumentace souboru opatření, bezpečnostní standard NÚKIB, doklad o kryptografické ochraně přenosu, určení doby trvání důvodu utajení.

---


<!-- LEGAL-REVISION:BEGIN id=6f08a82899f8074eb82e generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 35a — Manipulace s taktickou informací

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Taktickou informací se pro účely tohoto zákona rozumí utajovaná informace s krátkou dobou trvání důvodu utajení. Taktická informace se zpracovává v informačním nebo komunikačním systému a při přenosu se chrání kryptografickou ochranou.
>
> (2) Ochrana taktické informace do stupně utajení Tajné může být zabezpečena též souborem opatření stanovených na základě vyhodnocení rizik. Podmínky odlišné manipulace s taktickou informací upravuje bezpečnostní standard.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Místní znění neobsahuje výslovný vnitřní odkaz.

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=6f08a82899f8074eb82e -->

### Hlava VII — Ochrana UI při zpracování v zařízení mimo IS/KS

### § 35b — Příslušnost NÚKIB

Obdobně § 33a — pro Hlavu VII (kategorie zařízení mimo IS/KS) je gestorem NÚKIB.

#### F. Kazuistika

**1. Modelová situace.** Podnikatel pořídí multifunkční kopírku, na níž zaměstnanci kopírují dokumenty stupně Tajné (zařízení mimo IS/KS — Hlava VII). Při kontrole vznikne spor, zda dohled nad provozem a evidencí tohoto zařízení a metodikou jeho zabezpečení vykonává Úřad, nebo NÚKIB. Účastníci: podnikatel (provozovatel zařízení), NÚKIB (gestor Hlavy VII), Úřad. Důkazy: bezpečnostní provozní směrnice k zařízení (§ 36 odst. 2), korespondence s orgánem o příslušnosti, zápis z kontroly.

**2. Právní otázka.** Který orgán je věcně příslušný k výkonu státní správy a kontroly v oblasti ochrany UI při zpracování v zařízení mimo IS/KS podle Hlavy VII?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 35b — pro Hlavu VII (ochrana UI při zpracování v zařízení mimo IS/KS) je gestorem NÚKIB; obdobně jako § 33a u fyzické bezpečnosti IS.
- *Související ustanovení téhož zákona:* § 36 (zařízení mimo IS/KS — věcná úprava Hlavy VII), § 33a a § 36a (paralelní ustanovení o příslušnosti NÚKIB pro jiné hlavy), § 34, § 35 (vymezení IS/KS jako negativní hranice oboru Hlavy VII).
- *Související předpisy:* zákon č. 181/2014 Sb. (postavení a působnost NÚKIB); kompetenční zákon č. 2/1969 Sb.; prováděcí vyhláška o zařízeních mimo IS/KS.
- *Judikatura:* publikovaná judikatura k pravidlu příslušnosti chybí; nosné je systematické pravidlo, že kompetenční ustanovení (§ 35b) určuje výlučně věcně příslušný orgán pro celou hlavu, a podání adresované nepříslušnému orgánu se postoupí (§ 12 spr. ř.).

**4. Subsumpce.** Kopírka zpracovává UI v elektronické podobě a není součástí IS/KS — spadá pod Hlavu VII (§ 36). Pro tuto hlavu § 35b svěřuje výkon státní správy NÚKIB. Věcně příslušným orgánem ke kontrole, metodice a dohledu je tedy NÚKIB, nikoli Úřad.

**5. Řešení.** Provozovatel jedná ve věcech zařízení mimo IS/KS (směrnice, oznamovací povinnost podle § 36 odst. 2, kontrola) s NÚKIB. Podání chybně adresované Úřadu je nutné postoupit NÚKIB (§ 12 spr. ř.); úkon nepříslušného orgánu by byl vadou řízení. Procesní kroky: identifikovat gestora podle § 35b, směrovat veškerou agendu zařízení mimo IS/KS na NÚKIB.

**6. Varianty.** (a) Šlo-li by o technický prostředek fyzické bezpečnosti (zámek, trezor — § 30, § 47), gestorem certifikace by byl Úřad, nikoli NÚKIB. (b) Bylo-li by zařízení naopak součástí IS, uplatnil by se § 34 (certifikace IS NÚKIB), nikoli režim zařízení mimo IS/KS.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Pro samostatná zařízení je příslušný Úřad jako u klasické fyzické bezpečnosti."* Neutralizace: § 35b výslovně svěřuje Hlavu VII NÚKIB; příslušnost Úřadu se zúžila na technické prostředky fyzické bezpečnosti (§ 47).
- *Protiargument 2: „Příslušnost lze dohodnout nebo zvolit."* Neutralizace: věcná příslušnost je dána zákonem (§ 35b) a nelze ji měnit dohodou stran.
- *Slabé místo:* hranice mezi „zařízením mimo IS/KS" (§ 36) a součástí IS (§ 34) může být v praxi sporná; od zařazení se odvíjí nejen příslušnost, ale i to, zda je nutná certifikace IS.

#### H. Praktický závěr

§ 35b je kompetenční ustanovení: výkon státní správy v oblasti ochrany UI při zpracování v zařízení mimo IS/KS (Hlava VII) náleží NÚKIB. Veškerou agendu těchto zařízení proto směřujte na NÚKIB.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Ověřit, že jde o zařízení mimo IS/KS (§ 36), nikoli o součást IS/KS.
- [ ] Veškerou agendu (směrnice, oznámení, kontrola) směrovat na NÚKIB jako gestora Hlavy VII.
- [ ] Chybně adresované podání nechat postoupit věcně příslušnému NÚKIB (§ 12 spr. ř.).

**Typicky rozhodné důkazy / podklady:** bezpečnostní provozní směrnice k zařízení, doklad o oznámení NÚKIB, korespondence o příslušnosti, zápis z kontroly.


<!-- LEGAL-REVISION:BEGIN id=2c955cc5f61cdd31815a generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 35b

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> Státní správu v oblasti ochrany utajovaných informací podle této hlavy vykonává Národní úřad pro kybernetickou a informační bezpečnost, pokud tento zákon nestanoví jinak.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Místní znění neobsahuje výslovný vnitřní odkaz.

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=2c955cc5f61cdd31815a -->

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

#### F. Kazuistika

**1. Modelová situace.** Orgán státu používá k pořizování kopií dokumentů stupně Důvěrné multifunkční tiskárnu s vlastní pamětí (HDD), která není zapojena do žádného IS/KS. Zařízení provozuje bez vydané bezpečnostní provozní směrnice a NÚKIB o něm k 31. 12. neinformuje. Při výměně zařízení navíc nezajistí bezpečné vymazání paměti, v níž zůstaly otisky utajovaných dokumentů. Účastníci: orgán státu (provozovatel), NÚKIB (gestor), servisní firma. Důkazy: bezpečnostní provozní směrnice (chybí), oznámení NÚKIB do 1. 2. (chybí), protokol o sanitaci paměti při vyřazení.

**2. Právní otázka.** Jaké povinnosti má provozovatel při zpracování UI v zařízení mimo IS/KS (např. v multifunkční tiskárně s pamětí) a jaké jsou důsledky jejich nesplnění, zejména při vyřazení zařízení?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 36 — povinnost zajistit ochranu UI při jejím zpracování v elektronické podobě v zařízení mimo IS/KS, zejména v kopírkách, skenerech a zařízeních pro převod formátu (odst. 1); povinnost vydat bezpečnostní provozní směrnici a zasílat NÚKIB informace o zařízení (odst. 2).
- *Související ustanovení téhož zákona:* § 35b (příslušnost NÚKIB), § 34, § 35 (IS/KS — negativní vymezení), § 21 (manipulace, skartace, evidence UI), § 4 (stupně utajení), § 69 a násl. (kontrola a přestupky).
- *Související předpisy:* prováděcí vyhláška o ochraně UI v zařízeních mimo IS/KS; vyhláška o administrativní bezpečnosti; bezpečnostní standardy NÚKIB k sanitaci datových nosičů.
- *Judikatura:* publikovaná judikatura je sporá; rozhodné jsou kontrolní standardy NÚKIB — nosné je, že paměť zařízení mimo IS/KS je nositelem UI a při vyřazení vyžaduje bezpečné odstranění dat.

**4. Subsumpce.** Multifunkční tiskárna s pamětí, jež není součástí IS/KS, je zařízením podle § 36 odst. 1 — zpracovává UI v elektronické podobě (kopírování, záznam). Provozovatel proto měl podle odst. 2 vydat bezpečnostní provozní směrnici a informovat NÚKIB; obojí chybí, povinnosti odst. 2 tedy splněny nejsou. Paměť obsahující otisky UI je nositelem utajované informace, takže její nezabezpečené vyřazení ohrožuje ochranu UI.

**5. Řešení.** Provozovatel musí vydat bezpečnostní provozní směrnici, podle níž se v zařízení s UI nakládá, a k 31. 12. zaslat NÚKIB informace o zařízení (do 1. 2.). Před vyřazením či servisem zařízení je nutné bezpečně odstranit data z paměti (sanitace/likvidace nosiče) podle standardu. Procesní kroky: směrnice, oznámení NÚKIB, evidence zařízení, protokolovaná sanitace při vyřazení. Riziko/alternativa: provoz bez směrnice a nezabezpečené vyřazení zakládají porušení zákona a možný bezpečnostní incident (únik UI z paměti).

**6. Varianty.** (a) Bylo-li by zařízení připojeno do IS, neuplatnil by se § 36, nýbrž režim certifikovaného IS (§ 34). (b) Šlo-li by o zařízení bez schopnosti zpracovávat UI v elektronické podobě (např. prostý mechanický nástroj), § 36 by se neuplatnil.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Kopírka není informační systém, žádné zvláštní povinnosti se na ni nevztahují."* Neutralizace: § 36 dopadá právě na zařízení mimo IS/KS a ukládá vlastní povinnosti (směrnice, oznámení NÚKIB) i zde.
- *Protiargument 2: „Vymazání souboru tlačítkem stačí."* Neutralizace: paměť (HDD/SSD) zařízení uchovává otisky UI i po běžném smazání; bezpečná ochrana podle § 36 odst. 1 vyžaduje sanitaci či fyzickou likvidaci nosiče podle standardu.
- *Slabé místo:* výčet zařízení v odst. 1 je demonstrativní („zejména"); v praxi může být sporné, zda konkrétní přístroj (např. chytrá tabule, měřicí přístroj s pamětí) pod § 36 spadá — rozhoduje schopnost zpracovat UI v elektronické podobě.

#### H. Praktický závěr

§ 36 chrání UI zpracovávanou v zařízeních mimo IS/KS (kopírky, skenery, zařízení s pamětí). Provozovatel musí vydat bezpečnostní provozní směrnici a oznamovat zařízení NÚKIB; zvláštní pozor na sanitaci paměti při servisu a vyřazení.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Identifikovat všechna zařízení mimo IS/KS schopná zpracovat UI v elektronické podobě (kopírky, skenery, zařízení s pamětí).
- [ ] Vydat bezpečnostní provozní směrnici pro nakládání s UI v těchto zařízeních (odst. 2).
- [ ] K 31. 12. zaslat NÚKIB informace o zařízeních (do 1. 2.).
- [ ] Při servisu/vyřazení protokolovaně sanitovat nebo zlikvidovat paměť zařízení.

**Typicky rozhodné důkazy / podklady:** bezpečnostní provozní směrnice, doklad o oznámení NÚKIB, evidence zařízení, protokol o sanitaci/likvidaci paměti při vyřazení.

---


<!-- LEGAL-REVISION:BEGIN id=9959d52dc39fbb87f137 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 36

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Při zpracování utajované informace v elektronické podobě v zařízení, které není součástí informačního nebo komunikačního systému, zejména v psacím stroji s pamětí a v zařízení umožňujícím kopírování, záznam nebo zobrazení utajované informace anebo její převod do jiného datového formátu, musí být zajištěna ochrana této utajované informace.
>
> (2) Orgán státu, právnická osoba podle [[#§ 60b|§ 60b]] a podnikatel jsou povinni
>
> - a) pro jimi provozované zařízení uvedené v odstavci 1 vydat bezpečnostní provozní směrnici; pouze v souladu s ní lze zpracovávat utajovanou informaci a
>
> - b) zaslat o provozovaném zařízení uvedeném v odstavci 1 Národnímu úřadu pro kybernetickou a informační bezpečnost informace platné k 31. prosinci kalendářního roku nejpozději do 1. února následujícího kalendářního roku.
>
> (3) V bezpečnostní provozní směrnici podle odstavce 2 písm. a) se uvedou pro zařízení podle odstavce 1
>
> - a) způsob jeho bezpečného provozování,
>
> - b) provozní směrnice pro jeho uživatele.
>
> (4) Podmínky bezpečného provozování zařízení uvedeného v odstavci 1 v závislosti na stupni utajení v něm zpracovávaných utajovaných informací a rozsah požadovaných informací podle odstavce 2 písm. b) stanoví prováděcí právní předpis.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 60b

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=9959d52dc39fbb87f137 -->

### Hlava VIII — Kryptografická ochrana

### § 36a — Příslušnost NÚKIB

Stejně § 33a, § 35b — pro kryptografickou ochranu vykonává státní správu NÚKIB.

#### F. Kazuistika

**1. Modelová situace.** Podnikatel provozující kryptografické pracoviště podá žádost o certifikaci kryptografického prostředku a o povolení jeho vývozu. Žádosti omylem adresuje Úřadu, který agendu kryptografické ochrany dříve vykonával. Vznikne spor, zda je k rozhodnutí příslušný Úřad, nebo NÚKIB. Účastníci: podnikatel (žadatel), NÚKIB (gestor Hlavy VIII), Úřad. Důkazy: žádosti, doklad o doručení nepříslušnému orgánu, certifikační dokumentace.

**2. Právní otázka.** Který orgán je věcně příslušný k výkonu státní správy v oblasti kryptografické ochrany UI (certifikace kryptoprostředků a pracovišť, zkoušky, povolení vývozu)?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 36a — pro kryptografickou ochranu (Hlava VIII) vykonává státní správu NÚKIB; obdobně § 33a a § 35b u jiných hlav.
- *Související ustanovení téhož zákona:* § 37 a násl. (věcná úprava kryptografické ochrany — certifikace prostředku a pracoviště, zkoušky, vývoz), § 49 a § 50 (certifikace kryptoprostředku a kryptopracoviště NÚKIB), § 42 (povolení vývozu NÚKIB), § 33a a § 35b (paralelní kompetenční ustanovení).
- *Související předpisy:* zákon č. 181/2014 Sb. (působnost NÚKIB); vyhláška č. 432/2011 Sb. (kryptografická ochrana UI); kompetenční zákon č. 2/1969 Sb.
- *Judikatura:* publikovaná judikatura k pravidlu příslušnosti chybí; nosné je, že kompetenční ustanovení určuje výlučně věcně příslušný orgán a podání nepříslušnému orgánu se postoupí (§ 12 spr. ř.).

**4. Subsumpce.** Certifikace kryptoprostředku, schvalování kryptopracoviště i povolení vývozu spadají do kryptografické ochrany (Hlava VIII). Pro tuto hlavu § 36a svěřuje výkon státní správy NÚKIB. Věcně příslušným orgánem je tedy NÚKIB, nikoli Úřad; žádosti adresované Úřadu míří na nepříslušný orgán.

**5. Řešení.** Žadatel směřuje veškerou agendu kryptografické ochrany (certifikace, zkoušky, vývoz) na NÚKIB. Podání chybně doručené Úřadu je nutné postoupit NÚKIB (§ 12 spr. ř.); rozhodnutí nepříslušného orgánu by bylo vadou řízení. Procesní kroky: ověřit gestora podle § 36a, podat žádosti u NÚKIB.

**6. Varianty.** (a) Šlo-li by o certifikaci technického prostředku fyzické bezpečnosti (§ 47), gestorem by byl Úřad. (b) U kryptoprostředku/IS ve vlastnictví zpravodajských služeb provádějí dílčí úlohy samy zpravodajské služby (§ 46 odst. 17), byť při metodickém dohledu NÚKIB.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Kryptografii historicky spravoval Úřad (NBÚ), je tedy příslušný i nadále."* Neutralizace: § 36a výslovně svěřuje kryptografickou ochranu NÚKIB; jde o výsledek přesunu kompetencí z NBÚ na NÚKIB.
- *Protiargument 2: „Příslušnost lze zvolit podle toho, který orgán věc rychleji vyřídí."* Neutralizace: věcná příslušnost je dána zákonem (§ 36a) a nelze ji měnit volbou žadatele.
- *Slabé místo:* u zpravodajských služeb je působnost NÚKIB modifikována (§ 46 odst. 17 a 18) — bez zohlednění těchto výjimek hrozí chybné určení rozsahu pravomoci NÚKIB.

#### H. Praktický závěr

§ 36a je kompetenční ustanovení: výkon státní správy v oblasti kryptografické ochrany UI (Hlava VIII) náleží NÚKIB. Veškeré žádosti (certifikace, zkoušky, povolení vývozu) proto směřujte na NÚKIB.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] V agendě kryptografické ochrany (Hlava VIII) jednat výlučně s NÚKIB.
- [ ] Chybně adresované podání nechat postoupit věcně příslušnému NÚKIB (§ 12 spr. ř.).
- [ ] Zohlednit výjimky pro zpravodajské služby (§ 46 odst. 17 a 18).

**Typicky rozhodné důkazy / podklady:** žádosti adresované NÚKIB, doklad o doručení/postoupení, certifikační a kryptografická dokumentace.


<!-- LEGAL-REVISION:BEGIN id=465cce4e1561fd54c393 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 36a

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> Státní správu v oblasti ochrany utajovaných informací podle této hlavy vykonává Národní úřad pro kybernetickou a informační bezpečnost, pokud tento zákon nestanoví jinak.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Místní znění neobsahuje výslovný vnitřní odkaz.

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=465cce4e1561fd54c393 -->

### § 37 — Kryptografický materiál a pracoviště

> **§ 37**
>
> *(1) Kryptografickým materiálem je kryptografický prostředek, materiál k zajištění jeho funkce nebo kryptografický dokument.*
>
> *(2) Kryptografické prostředky používané pro kryptografickou ochranu utajovaných informací musí být certifikovány Národním úřadem pro kybernetickou a informační bezpečnost [§ 46 odst. 1 písm. c)]; v případě utajované informace poskytované cizí moci zpracovávané v akreditovaném nebo certifikovaném informačním systému lze použít i kryptografický prostředek schválený příslušným orgánem cizí moci, který je součástí akreditovaného nebo certifikovaného informačního systému.*
>
> *(3) Kryptografické pracoviště je pracoviště určené k zajištění výkonu kryptografické ochrany vždy nejméně v rozsahu bezpečnostní správy kryptografického materiálu nebo výroby a servisu kryptografického prostředku nebo materiálu k zajištění jeho funkce. Kryptografické pracoviště musí splňovat bezpečnostní standardy a musí být do provozu schváleno odpovědnou osobou nebo bezpečnostním ředitelem.*
>
> *(4) Kryptografické pracoviště určené k výrobě nebo testování materiálu k zajištění funkce kryptografického prostředku nebo které je centrálním distribučním a evidenčním místem kryptografického materiálu orgánu státu, právnické osoby podle § 60b nebo podnikatele, musí být před schválením do provozu odpovědnou osobou nebo bezpečnostním ředitelem certifikováno Národním úřadem pro kybernetickou a informační bezpečnost [§ 46 odst. 1 písm. d)].*
>
> *(5) Orgán státu, právnická osoba podle § 60b a podnikatel, kteří vykonávají kryptografickou ochranu, musí vést evidence kryptografického materiálu, pracovníků kryptografické ochrany, provozní obsluhy kryptografických prostředků, kurýrů kryptografického materiálu a osob, které nakládají s kryptografickým materiálem podle § 42a.*

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

#### F. Kazuistika

**1. Modelová situace.** Orgán státu zřídí pracoviště, které vyrábí a testuje klíčový materiál (key material) pro vlastní kryptografické prostředky a je centrálním distribučním a evidenčním místem kryptomateriálu. Pracoviště schválí do provozu odpovědná osoba, avšak NÚKIB jej před schválením necertifikoval. Současně pracoviště nasadí kryptografický prostředek, který NÚKIB necertifikoval. Účastníci: orgán státu (provozovatel kryptopracoviště), NÚKIB (certifikační orgán), odpovědná osoba. Důkazy: certifikace kryptoprostředku [§ 46 odst. 1 písm. c)], certifikace specializovaného kryptopracoviště [§ 46 odst. 1 písm. d)], schválení do provozu, evidence podle odst. 5.

**2. Právní otázka.** Smí být specializované kryptografické pracoviště (výroba/testování key materiálu, centrální distribuce) schváleno do provozu bez předchozí certifikace NÚKIB a lze používat necertifikovaný kryptografický prostředek?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 37 — vymezení kryptomateriálu (prostředek, materiál k zajištění funkce, dokument — odst. 1); povinná certifikace kryptoprostředku NÚKIB [§ 46 odst. 1 písm. c), odst. 2]; kryptografické pracoviště a jeho schválení do provozu odpovědnou osobou/bezpečnostním ředitelem (odst. 3); povinná certifikace NÚKIB u specializovaného pracoviště (výroba/testování key materiálu, centrální distribuce) před schválením do provozu [§ 46 odst. 1 písm. d), odst. 4]; povinné evidence (odst. 5).
- *Související ustanovení téhož zákona:* § 36a (příslušnost NÚKIB), § 38–42a (výkon kryptografické ochrany, manipulace), § 49 a § 50 (certifikace kryptoprostředku a kryptopracoviště), § 43 (kompromitace), § 43a (centrální distribuce NÚKIB/MO).
- *Související předpisy:* vyhláška č. 432/2011 Sb. (kryptografická ochrana UI); bezpečnostní standardy NÚKIB.
- *Judikatura:* publikovaná judikatura je sporá; rozhodné jsou standardy NÚKIB — nosné je pravidlo, že specializované kryptopracoviště nelze schválit do provozu bez předchozí certifikace NÚKIB a že kryptoprostředek pro ochranu UI musí být certifikován.

**4. Subsumpce.** Pracoviště vyrábí a testuje key material a je centrálním distribučním a evidenčním místem — naplňuje znaky specializovaného pracoviště podle odst. 4, jež musí být před schválením do provozu certifikováno NÚKIB [§ 46 odst. 1 písm. d)]. Certifikace chybí, schválení odpovědnou osobou ji nemůže nahradit. Nasazený kryptoprostředek pro ochranu UI musí být podle odst. 2 certifikován NÚKIB; certifikace chybí, prostředek tedy nelze použít.

**5. Řešení.** Orgán musí před schválením specializovaného kryptopracoviště do provozu zajistit jeho certifikaci NÚKIB (odst. 4); teprve poté smí odpovědná osoba pracoviště schválit do provozu. Použít lze jen kryptoprostředek certifikovaný NÚKIB (odst. 2), případně u UI poskytované cizí moci prostředek schválený cizí mocí v rámci akreditovaného/certifikovaného IS. Nutno vést evidence podle odst. 5. Procesní kroky: certifikace pracoviště, schválení do provozu, výměna necertifikovaného prostředku, vedení evidencí. Riziko/alternativa: provoz bez certifikace pracoviště a s necertifikovaným prostředkem je porušením zákona a bezpečnostním rizikem.

**6. Varianty.** (a) Šlo-li by o obecné kryptopracoviště (jen bezpečnostní správa, bez výroby/testování key materiálu a bez centrální distribuce), postačilo by schválení do provozu odpovědnou osobou/bezpečnostním ředitelem bez certifikace NÚKIB (odst. 3). (b) Šlo-li by o UI poskytovanou cizí moci v akreditovaném/certifikovaném IS, bylo by možné použít kryptoprostředek schválený příslušným orgánem cizí moci (odst. 2 in fine).

#### G. Protiargumenty a rizika

- *Protiargument 1: „Schválení pracoviště odpovědnou osobou postačí, certifikace NÚKIB je nadbytečná."* Neutralizace: u specializovaného pracoviště (odst. 4) je certifikace NÚKIB podmínkou předcházející schválení do provozu; obecné schválení podle odst. 3 ji nenahrazuje.
- *Protiargument 2: „Pro vlastní (in-house) kryptoprostředek certifikaci nepotřebujeme."* Neutralizace: odst. 2 vyžaduje certifikaci NÚKIB pro každý kryptoprostředek používaný k ochraně UI bez ohledu na původ; výjimkou je jen prostředek cizí moci v akreditovaném/certifikovaném IS.
- *Slabé místo:* hranice mezi obecným (odst. 3) a specializovaným (odst. 4) kryptopracovištěm rozhoduje o nutnosti certifikace NÚKIB; nesprávné zařazení vede buď k nezákonnému provozu, nebo ke zbytečné certifikační zátěži.

#### H. Praktický závěr

§ 37 vymezuje kryptomateriál a kryptopracoviště a stanoví dvě klíčová pravidla: kryptoprostředek pro ochranu UI musí být certifikován NÚKIB (odst. 2) a specializované kryptopracoviště musí být před schválením do provozu certifikováno NÚKIB (odst. 4). Provozovatel vede zákonné evidence (odst. 5).

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Ověřit certifikaci kryptoprostředku NÚKIB [§ 46 odst. 1 písm. c)] před jeho použitím k ochraně UI.
- [ ] Zařadit kryptopracoviště (obecné dle odst. 3 vs. specializované dle odst. 4) a u specializovaného zajistit certifikaci NÚKIB před schválením do provozu.
- [ ] Zajistit schválení kryptopracoviště do provozu odpovědnou osobou/bezpečnostním ředitelem.
- [ ] Vést evidence podle odst. 5 (materiál, pracovníci, obsluha, kurýři, osoby dle § 42a).

**Typicky rozhodné důkazy / podklady:** certifikát kryptoprostředku, certifikát specializovaného kryptopracoviště, doklad o schválení do provozu, zákonné evidence (odst. 5), bezpečnostní dokumentace pracoviště.

---


<!-- LEGAL-REVISION:BEGIN id=ee696f263f459c4e8dac generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 37

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Kryptografickým materiálem je kryptografický prostředek, materiál k zajištění jeho funkce nebo kryptografický dokument.
>
> (2) Kryptografické prostředky používané pro kryptografickou ochranu utajovaných informací musí být certifikovány Národním úřadem pro kybernetickou a informační bezpečnost [§ 46 odst. 1 písm. c)]; v případě utajované informace poskytované cizí moci zpracovávané v akreditovaném nebo certifikovaném informačním systému lze použít i kryptografický prostředek schválený příslušným orgánem cizí moci, který je součástí akreditovaného nebo certifikovaného informačního systému.
>
> (3) Kryptografické pracoviště je pracoviště určené k zajištění výkonu kryptografické ochrany vždy nejméně v rozsahu bezpečnostní správy kryptografického materiálu nebo výroby a servisu kryptografického prostředku nebo materiálu k zajištění jeho funkce. Kryptografické pracoviště musí splňovat bezpečnostní standardy a musí být do provozu schváleno odpovědnou osobou nebo bezpečnostním ředitelem.
>
> (4) Kryptografické pracoviště určené k výrobě nebo testování materiálu k zajištění funkce kryptografického prostředku nebo které je centrálním distribučním a evidenčním místem kryptografického materiálu orgánu státu, právnické osoby podle [[#§ 60b|§ 60b]] nebo podnikatele, musí být před schválením do provozu odpovědnou osobou nebo bezpečnostním ředitelem certifikováno Národním úřadem pro kybernetickou a informační bezpečnost [§ 46 odst. 1 písm. d)].
>
> (5) Orgán státu, právnická osoba podle [[#§ 60b|§ 60b]] a podnikatel, kteří vykonávají kryptografickou ochranu, musí vést evidence kryptografického materiálu, pracovníků kryptografické ochrany, provozní obsluhy kryptografických prostředků, kurýrů kryptografického materiálu a osob, které nakládají s kryptografickým materiálem podle [[#§ 42a|§ 42a]].

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 46, § 60b, § 42a

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=ee696f263f459c4e8dac -->

### § 37a — Kontrolovaná kryptografická položka (CCI)

CCI je **neutajované zařízení** (nebo jeho součást) na seznamu vedeném NÚKIB, jež slouží k ochraně **informací** (nikoliv nutně utajovaných) využitím kryptografických metod. Příklad — civilní šifrovací produkty s exportní kontrolou. Užití podle bezpečnostního standardu.

Zařazení na seznam — písemnou žádost výrobce/dovozce/distributora/uživatele, NÚKIB schvaluje, je-li to v souladu se záměry ČR v ochraně UI.

#### F. Kazuistika

**1. Modelová situace.** Výrobce civilního šifrovacího produktu (HW modul s kryptografickými funkcemi), který slouží k ochraně neutajovaných, ale citlivých informací, žádá NÚKIB o zařazení produktu na seznam kontrolovaných kryptografických položek (CCI), aby jej mohl využívat při plnění zakázek a vyvážet pod jednotným režimem. NÚKIB posuzuje, zda je zařazení v souladu se záměry ČR v ochraně UI. Účastníci: výrobce (žadatel), NÚKIB (vede seznam CCI), případně dovozce/uživatel. Důkazy: písemná žádost o zařazení, technická dokumentace produktu, bezpečnostní standard NÚKIB pro užívání CCI.

**2. Právní otázka.** Za jakých podmínek se zařízení zařadí na seznam kontrolovaných kryptografických položek (CCI) a jaký režim pak pro nakládání s ním platí?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 37a — CCI je neutajované zařízení (nebo jeho součást) na seznamu vedeném NÚKIB, sloužící k ochraně informací využitím kryptografických metod; zařazení na seznam na písemnou žádost výrobce/dovozce/distributora/uživatele, schvaluje NÚKIB, je-li to v souladu se záměry ČR v ochraně UI; užití podle bezpečnostního standardu.
- *Související ustanovení téhož zákona:* § 37b (kontrolovaná položka — obdobný režim mimo CCI), § 37 (kryptomateriál a kryptoprostředek), § 41 odst. 5 (manipulace s CCI podle standardu), § 42 (vývoz), § 36a (příslušnost NÚKIB).
- *Související předpisy:* bezpečnostní standard NÚKIB pro CCI; předpisy o kontrole vývozu zboží dvojího užití; vyhláška č. 432/2011 Sb.
- *Judikatura:* publikovaná judikatura chybí; jde o specializovaný technicko-bezpečnostní institut — nosné je pravidlo, že o zařazení rozhoduje NÚKIB diskrečně v souladu se záměry ČR v ochraně UI.

**4. Subsumpce.** Produkt je neutajované zařízení s kryptografickými funkcemi sloužící k ochraně informací — naplňuje pojmové znaky CCI podle § 37a. Zařazení je vázáno na písemnou žádost a na soulad se záměry ČR v ochraně UI, jejž posuzuje NÚKIB. Po zařazení se s položkou nakládá podle bezpečnostního standardu NÚKIB.

**5. Řešení.** Výrobce podá NÚKIB písemnou žádost o zařazení produktu na seznam CCI s technickou dokumentací; NÚKIB zařazení schválí, je-li v souladu se záměry ČR v ochraně UI. Po zařazení se nakládání řídí bezpečnostním standardem NÚKIB (manipulace, evidence, vývoz). Procesní kroky: žádost, doložení vlastností produktu, zařazení na seznam, dodržování standardu. Riziko/alternativa: nesplňuje-li produkt parametry CCI nebo není-li zařazení v souladu se záměry ČR, NÚKIB jej nezařadí.

**6. Varianty.** (a) Nejde-li o kryptografickou položku CCI, ale o jiné neutajované bezpečnostně relevantní zařízení, uplatní se režim kontrolované položky podle § 37b (vedlejší seznam). (b) Slouží-li zařízení přímo k ochraně utajovaných informací, nejde o CCI, nýbrž o kryptoprostředek vyžadující certifikaci NÚKIB (§ 37 odst. 2).

#### G. Protiargumenty a rizika

- *Protiargument 1: „Zařazení na seznam CCI je nárokové, splní-li produkt technické parametry."* Neutralizace: § 37a podmiňuje zařazení souladem se záměry ČR v ochraně UI — jde o diskreční posouzení NÚKIB, nikoli o nárok.
- *Protiargument 2: „CCI je utajované zařízení."* Neutralizace: CCI je z definice neutajované zařízení; utajení se týká informací, jež CCI chrání, nikoli samotné položky.
- *Slabé místo:* obsah povinností při nakládání s CCI určuje bezpečnostní standard NÚKIB, nikoli přímo zákon; bez jeho znalosti nelze posoudit rozsah povinností (manipulace, vývoz).

#### H. Praktický závěr

§ 37a zavádí institut kontrolované kryptografické položky (CCI): neutajovaného zařízení s kryptografickými funkcemi, jež NÚKIB na žádost zařadí na seznam, je-li to v souladu se záměry ČR v ochraně UI. Nakládání se řídí bezpečnostním standardem NÚKIB.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Posoudit, zda jde o CCI (§ 37a), kontrolovanou položku (§ 37b), nebo o kryptoprostředek (§ 37 odst. 2).
- [ ] Podat NÚKIB písemnou žádost o zařazení na seznam CCI s technickou dokumentací.
- [ ] Při nakládání s CCI dodržovat bezpečnostní standard NÚKIB (manipulace, evidence, vývoz).

**Typicky rozhodné důkazy / podklady:** písemná žádost o zařazení, technická dokumentace produktu, doklad o zařazení na seznam NÚKIB, bezpečnostní standard NÚKIB pro CCI.


<!-- LEGAL-REVISION:BEGIN id=a0f0d9bce68067130446 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 37a — Kontrolovaná kryptografická položka

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Kontrolovanou kryptografickou položkou se rozumí neutajované zařízení nebo jeho součást, zařazené do seznamu podle odstavce 3, sloužící k ochraně informací při jejich zpracování nebo přenosu a využívající kryptografických metod.
>
> (2) Kontrolovanou kryptografickou položku lze použít pouze v souladu s bezpečnostním standardem.
>
> (3) Zařízení uvedené v odstavci 1 nebo jeho součást na základě písemné žádosti jeho výrobce, dovozce, distributora nebo uživatele Národní úřad pro kybernetickou a informační bezpečnost schválí a zařadí do jím vedeného seznamu kontrolovaných kryptografických položek v případě, že je to v souladu se záměry České republiky v oblasti zajišťování ochrany utajovaných informací.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Místní znění neobsahuje výslovný vnitřní odkaz.

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=a0f0d9bce68067130446 -->

### § 37b — Kontrolovaná položka

Stejný režim jako CCI, ale pro **neutajované zařízení, jež není CCI**. Vede vedlejší seznam NÚKIB. Slouží k udržení přehledu o kryptografickém ekosystému ČR i pro neutajované, ale bezpečnostně relevantní produkty.

#### F. Kazuistika

**1. Modelová situace.** Distributor bezpečnostně relevantního, avšak nekryptografického zařízení (například specializovaného komponentu, jenž není kontrolovanou kryptografickou položkou) chce, aby NÚKIB udržoval přehled o jeho nasazení v ČR, a žádá o zařazení na vedlejší seznam kontrolovaných položek. Vznikne otázka, zda zařízení patří na seznam CCI (§ 37a), nebo na vedlejší seznam kontrolovaných položek (§ 37b). Účastníci: distributor (žadatel), NÚKIB (vede vedlejší seznam), uživatel. Důkazy: písemná žádost, technická specifikace zařízení, bezpečnostní standard NÚKIB.

**2. Právní otázka.** Které neutajované zařízení se zařadí na vedlejší seznam kontrolovaných položek podle § 37b a jak se tento režim liší od CCI podle § 37a?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 37b — kontrolovaná položka je neutajované zařízení, jež není CCI; režim obdobný § 37a, vede se vedlejší seznam NÚKIB; slouží k přehledu o kryptografickém/bezpečnostním ekosystému i pro neutajované, ale bezpečnostně relevantní produkty.
- *Související ustanovení téhož zákona:* § 37a (CCI — hlavní seznam, kryptografické položky), § 37 (kryptoprostředek), § 41 odst. 5 (manipulace dle standardu), § 36a (příslušnost NÚKIB).
- *Související předpisy:* bezpečnostní standard NÚKIB; předpisy o kontrole zboží dvojího užití; vyhláška č. 432/2011 Sb.
- *Judikatura:* publikovaná judikatura chybí; nosné je systematické rozlišení: CCI = kryptografická položka (§ 37a), kontrolovaná položka = ostatní bezpečnostně relevantní neutajované zařízení (§ 37b).

**4. Subsumpce.** Zařízení je neutajované a bezpečnostně relevantní, ale neplní funkce CCI (není kryptografickou položkou) — patří proto na vedlejší seznam kontrolovaných položek podle § 37b, nikoli na seznam CCI. Zařazení je vázáno na žádost a posouzení NÚKIB v režimu obdobném § 37a.

**5. Řešení.** Distributor podá NÚKIB písemnou žádost o zařazení na vedlejší seznam kontrolovaných položek; po zařazení se nakládání řídí bezpečnostním standardem NÚKIB. Procesní kroky: žádost, doložení vlastností zařízení, zařazení na vedlejší seznam, dodržování standardu. Riziko/alternativa: jde-li ve skutečnosti o kryptografickou položku, je správným režimem CCI (§ 37a); slouží-li k ochraně UI, jde o kryptoprostředek (§ 37 odst. 2).

**6. Varianty.** (a) Plní-li zařízení kryptografické funkce, zařadí se jako CCI na hlavní seznam podle § 37a. (b) Slouží-li přímo k ochraně utajovaných informací, jde o kryptoprostředek a vyžaduje certifikaci NÚKIB (§ 37 odst. 2), nikoli zařazení na seznam.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Kontrolovaná položka a CCI jsou totéž."* Neutralizace: § 37b se týká neutajovaných zařízení, jež nejsou CCI; vede se samostatný vedlejší seznam odlišný od seznamu CCI (§ 37a).
- *Protiargument 2: „Zařazení na vedlejší seznam ukládá tytéž povinnosti jako certifikace kryptoprostředku."* Neutralizace: § 37b je evidenčně-přehledový režim podle standardu, nikoli certifikační režim kryptoprostředku (§ 37 odst. 2).
- *Slabé místo:* rozhraní mezi CCI (§ 37a) a kontrolovanou položkou (§ 37b) je technicky určováno standardem NÚKIB; nesprávné zařazení vede k chybnému režimu manipulace a vývozu.

#### H. Praktický závěr

§ 37b zavádí vedlejší seznam kontrolovaných položek pro neutajovaná, bezpečnostně relevantní zařízení, jež nejsou CCI. Slouží k přehledu NÚKIB o bezpečnostním ekosystému ČR; nakládání se řídí bezpečnostním standardem.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Rozlišit, zda jde o CCI (§ 37a), kontrolovanou položku (§ 37b), nebo kryptoprostředek (§ 37 odst. 2).
- [ ] U kontrolované položky podat NÚKIB písemnou žádost o zařazení na vedlejší seznam.
- [ ] Při nakládání dodržovat bezpečnostní standard NÚKIB.

**Typicky rozhodné důkazy / podklady:** písemná žádost o zařazení, technická specifikace zařízení, doklad o zařazení na vedlejší seznam NÚKIB, bezpečnostní standard NÚKIB.

---


<!-- LEGAL-REVISION:BEGIN id=8ef8a56e030fe226ea5d generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 37b — Kontrolovaná položka

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Kontrolovanou položkou se rozumí neutajované zařízení nebo jeho součást, které není kontrolovanou kryptografickou položkou.
>
> (2) Pro kontrolovanou položku se uplatní užívání obdobných metod k ochraně informací jako u kontrolované kryptografické položky.
>
> (3) Kontrolovanou položku lze použít pouze v souladu s bezpečnostním standardem.
>
> (4) Zařízení uvedené v odstavci 1 nebo jeho součást na základě písemné žádosti jeho výrobce, dovozce, distributora nebo uživatele Národní úřad pro kybernetickou a informační bezpečnost schválí a zařadí do jím vedeného seznamu kontrolovaných položek v případě, že je to v souladu se záměry České republiky v oblasti zajišťování ochrany utajovaných informací.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Místní znění neobsahuje výslovný vnitřní odkaz.

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=8ef8a56e030fe226ea5d -->

### § 38 — Výkon kryptografické ochrany

> **§ 38**
>
> *(1) Výkonem kryptografické ochrany se rozumí*
>
> *- a) její bezpečnostní správa,*
>
> *- b) speciální obsluha kryptografického prostředku, nebo*
>
> *- c) výroba nebo servis kryptografického prostředku nebo materiálu k zajištění jeho funkce.*
>
> *(2) Výkon kryptografické ochrany provádí pracovník kryptografické ochrany, který je*
>
> *- a) k výkonu kryptografické ochrany pověřen odpovědnou osobou nebo jí pověřenou osobou,*
>
> *- b) držitelem platného osvědčení fyzické osoby a poučení a*
>
> *- c) držitelem osvědčení o zvláštní odborné způsobilosti pracovníka kryptografické ochrany (dále jen „osvědčení o zvláštní odborné způsobilosti“).*

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

#### F. Kazuistika

**1. Modelová situace.** Orgán státu pověří zaměstnance bezpečnostní správou kryptografických prostředků (distribuce klíčů, audit, monitoring). Zaměstnanec má platné osvědčení fyzické osoby na stupeň Tajné a poučení, avšak nemá osvědčení o zvláštní odborné způsobilosti pracovníka kryptografické ochrany. Přesto začne bezpečnostní správu vykonávat. Účastníci: orgán státu (odpovědná osoba), zaměstnanec (pracovník KO), NÚKIB (vydává osvědčení o ZOZ). Důkazy: pověření odpovědné osoby, osvědčení FO a poučení, osvědčení o zvláštní odborné způsobilosti (chybí).

**2. Právní otázka.** Smí osoba vykonávat výkon kryptografické ochrany (bezpečnostní správu, speciální obsluhu, výrobu/servis), má-li sice pověření a platné osvědčení FO s poučením, ale nemá osvědčení o zvláštní odborné způsobilosti?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 38 — vymezení výkonu kryptografické ochrany (bezpečnostní správa; speciální obsluha; výroba/servis — odst. 1); kumulativní podmínky pro pracovníka kryptografické ochrany: pověření odpovědnou osobou, platné osvědčení FO a poučení, osvědčení o zvláštní odborné způsobilosti (odst. 2).
- *Související ustanovení téhož zákona:* § 39 (zvláštní odborná způsobilost a zkouška), § 40 (provozní obsluha — lehčí režim), § 37 (kryptopracoviště), § 11 (osvědčení FO a poučení), § 9 (poučení), § 42a (nakládání jiným způsobem — obdobné podmínky).
- *Související předpisy:* vyhláška č. 432/2011 Sb. (kryptografická ochrana UI, organizace zkoušky); bezpečnostní standardy NÚKIB.
- *Judikatura:* publikovaná judikatura je sporá; nosné je pravidlo, že tři podmínky odst. 2 jsou kumulativní a absence kterékoli z nich vylučuje oprávněnost výkonu kryptografické ochrany.

**4. Subsumpce.** Bezpečnostní správa kryptoprostředků je výkonem kryptografické ochrany podle odst. 1 písm. a). Pracovník proto musí kumulativně splnit všechny tři podmínky odst. 2: pověření (splněno), osvědčení FO a poučení (splněno) a osvědčení o zvláštní odborné způsobilosti (chybí). Třetí podmínka naplněna není, výkon kryptografické ochrany tedy oprávněný není.

**5. Řešení.** Zaměstnanec musí před výkonem kryptografické ochrany získat osvědčení o zvláštní odborné způsobilosti (zkouška u NÚKIB — § 39); do té doby bezpečnostní správu vykonávat nesmí. Lze jej dočasně přeřadit na pouhou provozní obsluhu (§ 40), jež osvědčení o ZOZ nevyžaduje. Procesní kroky: přihláška ke zkoušce, složení zkoušky, vydání osvědčení o ZOZ, teprve poté pověřený výkon. Riziko/alternativa: výkon kryptografické ochrany bez osvědčení o ZOZ je porušením zákona a bezpečnostním rizikem.

**6. Varianty.** (a) Šlo-li by jen o běžné šifrovací úkony (provozní obsluha), uplatnil by se § 40 — postačí pověření, podmínky přístupu k UI a zaškolení, bez osvědčení o ZOZ. (b) Měla-li by osoba nakládat s kryptomateriálem jiným způsobem (transport, vyřazování), platily by obdobné podmínky podle § 42a (vč. osvědčení o ZOZ).

#### G. Protiargumenty a rizika

- *Protiargument 1: „Platné osvědčení FO opravňuje i k výkonu kryptografické ochrany."* Neutralizace: osvědčení FO je jen jednou ze tří kumulativních podmínek odst. 2; výkon kryptografické ochrany vyžaduje navíc osvědčení o zvláštní odborné způsobilosti.
- *Protiargument 2: „Bezpečnostní správa je jen administrativa, ne výkon kryptografické ochrany."* Neutralizace: odst. 1 písm. a) řadí bezpečnostní správu výslovně mezi výkon kryptografické ochrany; podléhá tedy režimu odst. 2.
- *Slabé místo:* hranice mezi „speciální obsluhou" (§ 38) a „provozní obsluhou" (§ 40) je v praxi neostrá; od zařazení závisí, zda je nutné osvědčení o ZOZ, nebo postačí zaškolení.

#### H. Praktický závěr

§ 38 vymezuje výkon kryptografické ochrany (bezpečnostní správa, speciální obsluha, výroba/servis) a podmiňuje jej kumulativně třemi podmínkami: pověřením, platným osvědčením FO s poučením a osvědčením o zvláštní odborné způsobilosti. Běžnou provozní obsluhu řeší mírnější § 40.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Určit, zda jde o výkon kryptografické ochrany (§ 38) nebo jen provozní obsluhu (§ 40).
- [ ] Ověřit u pracovníka KO všechny tři podmínky odst. 2: pověření, osvědčení FO + poučení, osvědčení o zvláštní odborné způsobilosti.
- [ ] Bez osvědčení o zvláštní odborné způsobilosti nepřipustit výkon kryptografické ochrany.

**Typicky rozhodné důkazy / podklady:** pověření odpovědné osoby, osvědčení FO a doklad o poučení, osvědčení o zvláštní odborné způsobilosti, popis vykonávané činnosti (zařazení dle § 38 vs. § 40).

---


<!-- LEGAL-REVISION:BEGIN id=e521ec6ac354effe79df generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 38 — Výkon kryptografické ochrany

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Výkonem kryptografické ochrany se rozumí
>
> - a) její bezpečnostní správa,
>
> - b) speciální obsluha kryptografického prostředku, nebo
>
> - c) výroba nebo servis kryptografického prostředku nebo materiálu k zajištění jeho funkce.
>
> (2) Výkon kryptografické ochrany provádí pracovník kryptografické ochrany, který je
>
> - a) k výkonu kryptografické ochrany pověřen odpovědnou osobou nebo jí pověřenou osobou,
>
> - b) držitelem platného osvědčení fyzické osoby a poučení a
>
> - c) držitelem osvědčení o zvláštní odborné způsobilosti pracovníka kryptografické ochrany (dále jen „osvědčení o zvláštní odborné způsobilosti“).

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Místní znění neobsahuje výslovný vnitřní odkaz.

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=e521ec6ac354effe79df -->

### § 39 — Zvláštní odborná způsobilost a zkouška

Specializovaný atest vydávaný NÚKIB po zkoušce **před zkušební komisí**. Komisaře jmenuje odp. osoba NÚKIB nebo orgánu státu, jenž zkoušku provádí na základě smlouvy podle § 52. Osvědčení platí **nejdéle 5 let**.

#### Decentralizace zkoušky

NÚKIB může uzavřít smlouvu s orgánem státu o provedení zkoušky (osvědčení vydá tento orgán státu); s PO podle § 60b nebo s podnikatelem může uzavřít smlouvu pouze o **části zkoušky** týkající se speciální obsluhy nebo výroby/servisu.

#### F. Kazuistika

**1. Modelová situace.** Pracovník kryptografické ochrany získal osvědčení o zvláštní odborné způsobilosti před šesti lety; orgán státu jej nadále využívá k bezpečnostní správě kryptoprostředků v domnění, že osvědčení platí trvale. Podnikatel zároveň žádá NÚKIB o uzavření smlouvy, na jejímž základě by sám prováděl celou zkoušku zvláštní odborné způsobilosti svých zaměstnanců. Účastníci: orgán státu/podnikatel (provozovatel), pracovník KO, NÚKIB (organizace zkoušky), zkušební komise. Důkazy: osvědčení o zvláštní odborné způsobilosti s datem vydání, doklad o době platnosti (max. 5 let), smlouva podle § 52.

**2. Právní otázka.** Po jakou dobu platí osvědčení o zvláštní odborné způsobilosti a v jakém rozsahu může NÚKIB svěřit provedení zkoušky podnikateli nebo PO podle § 60b?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 39 — zvláštní odborná způsobilost se ověřuje zkouškou před zkušební komisí (komisaře jmenuje odpovědná osoba NÚKIB nebo orgánu státu provádějícího zkoušku na základě smlouvy podle § 52); osvědčení o zvláštní odborné způsobilosti platí nejdéle 5 let; decentralizace zkoušky — s orgánem státu lze sjednat celou zkoušku, s PO podle § 60b nebo podnikatelem jen část zkoušky (speciální obsluha, výroba/servis).
- *Související ustanovení téhož zákona:* § 38 (výkon kryptografické ochrany — osvědčení o ZOZ jako podmínka), § 40 (provozní obsluha), § 52 (smlouva o zajištění činnosti), § 42a (nakládání jiným způsobem).
- *Související předpisy:* vyhláška č. 432/2011 Sb. (náležitosti přihlášky, organizace a obsah zkoušky); bezpečnostní standardy NÚKIB.
- *Judikatura:* publikovaná judikatura je sporá; nosné je pravidlo, že osvědčení o ZOZ je časově omezené (max. 5 let) a po uplynutí platnosti je k dalšímu výkonu kryptografické ochrany nutná nová zkouška.

**4. Subsumpce.** Osvědčení o ZOZ platí podle § 39 nejdéle 5 let; po šesti letech je tedy prošlé a nezakládá platnou kvalifikaci podle § 38 odst. 2 písm. c). Výkon bezpečnostní správy pracovníkem s prošlým osvědčením je proto neoprávněný. Pokud jde o smlouvu, podnikateli lze podle § 39 svěřit jen část zkoušky (speciální obsluha, výroba/servis), nikoli celou zkoušku.

**5. Řešení.** Orgán státu musí zajistit novou zkoušku a vydání nového osvědčení o ZOZ před dalším výkonem kryptografické ochrany; do té doby pracovníka k výkonu kryptografické ochrany nepřipustí (lze přeřadit na provozní obsluhu — § 40). NÚKIB může s podnikatelem uzavřít smlouvu pouze o části zkoušky (speciální obsluha/výroba/servis); celou zkoušku lze svěřit jen orgánu státu. Procesní kroky: kontrola platnosti osvědčení, přihláška ke zkoušce, složení zkoušky, vydání nového osvědčení. Riziko/alternativa: výkon kryptografické ochrany s prošlým osvědčením je porušením § 38.

**6. Varianty.** (a) Provádí-li zkoušku orgán státu na základě smlouvy podle § 52, vydá osvědčení tento orgán státu (nikoli NÚKIB). (b) Týká-li se činnost jen běžné provozní obsluhy (§ 40), osvědčení o ZOZ se nevyžaduje a jeho prošlost není překážkou.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Osvědčení o zvláštní odborné způsobilosti platí trvale."* Neutralizace: § 39 omezuje platnost na nejdéle 5 let; po uplynutí je nutná nová zkouška.
- *Protiargument 2: „NÚKIB může svěřit celou zkoušku i podnikateli."* Neutralizace: § 39 umožňuje svěřit podnikateli (a PO podle § 60b) jen část zkoušky týkající se speciální obsluhy nebo výroby/servisu; celou zkoušku lze sjednat pouze s orgánem státu.
- *Slabé místo:* časová platnost osvědčení (5 let) bývá v praxi opomíjena; chybí-li sledování expirace, hrozí neoprávněný výkon kryptografické ochrany se zpětnými důsledky pro bezpečnost.

#### H. Praktický závěr

§ 39 upravuje zkoušku zvláštní odborné způsobilosti (před zkušební komisí) a stanoví platnost osvědčení nejdéle na 5 let. Zkoušku lze decentralizovat: celou na orgán státu, pouze část (speciální obsluha/výroba/servis) na PO podle § 60b či podnikatele.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Hlídat dobu platnosti osvědčení o zvláštní odborné způsobilosti (max. 5 let) a včas zajistit přezkoušení.
- [ ] Pověřovat výkonem kryptografické ochrany jen osoby s platným osvědčením o ZOZ (§ 38).
- [ ] Při decentralizaci zkoušky respektovat rozsah: celá zkouška jen orgán státu, část (speciální obsluha/výroba/servis) i PO podle § 60b/podnikatel.

**Typicky rozhodné důkazy / podklady:** osvědčení o zvláštní odborné způsobilosti s datem vydání a platnosti, přihláška ke zkoušce, zápis zkušební komise, smlouva podle § 52 (u decentralizace).

---


<!-- LEGAL-REVISION:BEGIN id=88546b928a2237a65b65 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 39 — Zvláštní odborná způsobilost pracovníka kryptografické ochrany a zkouška zvláštní odborné způsobilosti

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Zvláštní odborná způsobilost pracovníka kryptografické ochrany (dále jen „zvláštní odborná způsobilost“) zahrnuje znalost předpisů z oblasti kryptografické ochrany utajovaných informací, schopnost jejich aplikace a další schopnosti podle § 38 odst. 1. Tyto znalosti a schopnosti ověřuje Národní úřad pro kybernetickou a informační bezpečnost zkouškou zvláštní odborné způsobilosti (dále jen „odborná zkouška“). Odborná zkouška probíhá před zkušební komisí; to není podmínkou pro její část prováděnou podle odstavce 3 písm. b). Členy zkušební komise jmenuje odpovědná osoba nebo jí pověřená osoba Národního úřadu pro kybernetickou a informační bezpečnost nebo orgánu státu podle odstavce 3 písm. a). Tomu, kdo složil odbornou zkoušku, vydá Národní úřad pro kybernetickou a informační bezpečnost nebo orgán státu podle odstavce 3 písm. a) osvědčení o zvláštní odborné způsobilosti a vede o tom evidenci. Osvědčení o zvláštní odborné způsobilosti se vydává nejdéle na 5 let.
>
> (2) Přihlášku k odborné zkoušce podává písemně odpovědná osoba orgánu státu, právnické osoby podle [[#§ 60b|§ 60b]] nebo podnikatele u Národního úřadu pro kybernetickou a informační bezpečnost nebo u jím pověřeného orgánu státu. Odborná zkouška se musí konat do 6 měsíců od podání přihlášky. Národní úřad pro kybernetickou a informační bezpečnost nebo jím pověřený orgán státu písemně oznámí tomu, kdo o odbornou zkoušku požádal, termín a místo konání odborné zkoušky; oznámení musí být odesláno nejpozději 20 dnů přede dnem konání odborné zkoušky. Ten, kdo při odborné zkoušce nevyhověl, ji může vykonat opakovaně. Opakovaná zkouška může být vykonána nejdříve po uplynutí 5 pracovních dnů ode dne neúspěšně vykonané zkoušky.
>
> (3) Národní úřad pro kybernetickou a informační bezpečnost může uzavřít s orgánem státu smlouvu o zajištění činnosti podle [[#§ 52|§ 52]], jejímž předmětem je provedení
>
> - a) odborné zkoušky a vydání osvědčení o zvláštní odborné způsobilosti, nebo
>
> - b) části odborné zkoušky, týkající se § 38 odst. 1 písm. b) nebo c) a příslušné návaznosti na § 38 odst. 1 písm. a).
>
> Smlouvu podle písmene b) může Národní úřad pro kybernetickou a informační bezpečnost uzavřít též s právnickou osobou podle [[#§ 60b|§ 60b]] nebo podnikatelem.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 38, § 60b, § 52

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=88546b928a2237a65b65 -->

### § 40 — Provozní obsluha kryptografického prostředku

Nižší kvalifikační stupeň — **provozní obsluha** zahrnuje běžné uživatelské funkce. Osoba musí:
- a) být pověřena odp. osobou,
- b) splňovat podmínky přístupu k UI (§ 6 odst. 1 nebo § 11 odst. 1 — postačí tedy i Vyhrazené, je-li UI Vyhrazená),
- c) být **zaškolena** (ne plnoprávně atestována).

#### F. Kazuistika

**1. Modelová situace.** Příslušník orgánu státu má v rámci běžné práce obsluhovat šifrátor (zapnout, zadat heslo, odeslat/přijmout zašifrovanou zprávu) pro UI stupně Vyhrazené. Odpovědná osoba zvažuje, zda jej musí vyslat na plnou zkoušku zvláštní odborné způsobilosti (§ 39), nebo zda postačí lehčí režim. Příslušník má osvědčení FO pro Vyhrazené a byl k obsluze přístroje zaškolen. Účastníci: orgán státu (odpovědná osoba), příslušník (provozní obsluha), NÚKIB. Důkazy: pověření odpovědné osoby, doklad o splnění podmínek přístupu k UI (§ 6 odst. 1 / § 11 odst. 1), záznam o zaškolení.

**2. Právní otázka.** Postačí pro běžnou provozní obsluhu kryptografického prostředku pověření, splnění podmínek přístupu k UI a zaškolení, nebo je i zde nutné osvědčení o zvláštní odborné způsobilosti?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 40 — provozní obsluha kryptografického prostředku (běžné uživatelské funkce) vyžaduje, aby osoba byla pověřena odpovědnou osobou, splňovala podmínky přístupu k UI (§ 6 odst. 1 nebo § 11 odst. 1) a byla zaškolena; nevyžaduje se osvědčení o zvláštní odborné způsobilosti.
- *Související ustanovení téhož zákona:* § 38 (výkon kryptografické ochrany — přísnější režim, vč. osvědčení o ZOZ), § 39 (zkouška zvláštní odborné způsobilosti), § 6 odst. 1 a § 11 odst. 1 (podmínky přístupu k UI), § 41 (manipulace s kryptomateriálem).
- *Související předpisy:* vyhláška č. 432/2011 Sb. (kryptografická ochrana UI); bezpečnostní standardy NÚKIB; bezpečnostní provozní směrnice provozovatele.
- *Judikatura:* publikovaná judikatura je sporá; nosné je rozlišení mezi výkonem kryptografické ochrany (§ 38) a pouhou provozní obsluhou (§ 40) podle náročnosti prováděných úkonů.

**4. Subsumpce.** Zapnutí přístroje, zadání hesla a běžné odeslání/přijetí zprávy jsou běžné uživatelské funkce — provozní obsluha podle § 40, nikoli speciální obsluha či bezpečnostní správa (§ 38). Pro provozní obsluhu postačí tři podmínky § 40: pověření (lze doplnit), podmínky přístupu k UI pro stupeň Vyhrazené (§ 6 odst. 1 — splněno) a zaškolení (splněno). Osvědčení o ZOZ se nevyžaduje.

**5. Řešení.** Odpovědná osoba příslušníka pověří provozní obsluhou, ověří splnění podmínek přístupu k UI pro daný stupeň a doloží zaškolení; tím jsou podmínky § 40 splněny a osoba smí přístroj obsluhovat bez zkoušky podle § 39. Procesní kroky: pověření, ověření přístupu k UI, zaškolení a jeho záznam. Riziko/alternativa: má-li osoba vykonávat i bezpečnostní správu, speciální obsluhu nebo výrobu/servis, nepostačí § 40 a uplatní se přísnější § 38 (osvědčení o ZOZ).

**6. Varianty.** (a) Měl-li by příslušník provádět distribuci klíčů, audit či pokročilé funkce, šlo by o výkon kryptografické ochrany (§ 38) s nutností osvědčení o ZOZ. (b) Byla-li by obsluhovaná UI stupně Tajné, vyžadovaly by se podmínky přístupu k UI pro Tajné (osvědčení FO), nikoli jen Vyhrazené.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Každý, kdo se dotkne kryptoprostředku, musí mít osvědčení o zvláštní odborné způsobilosti."* Neutralizace: § 40 pro běžnou provozní obsluhu osvědčení o ZOZ nevyžaduje; postačí pověření, přístup k UI a zaškolení.
- *Protiargument 2: „Zaškolení je totéž co zkouška podle § 39."* Neutralizace: zaškolení je interní příprava provozovatele, kdežto zkouška zvláštní odborné způsobilosti je formalizovaný atest NÚKIB pro náročnější výkon kryptografické ochrany (§ 38, § 39).
- *Slabé místo:* hranice mezi provozní obsluhou (§ 40) a speciální obsluhou (§ 38) je neostrá; zařadí-li provozovatel chybně náročnou činnost pod § 40, jde o neoprávněný výkon kryptografické ochrany bez požadované kvalifikace.

#### H. Praktický závěr

§ 40 zavádí lehčí kvalifikační režim pro provozní (běžnou) obsluhu kryptografického prostředku: postačí pověření, splnění podmínek přístupu k UI a zaškolení; osvědčení o zvláštní odborné způsobilosti se nevyžaduje. Náročnější činnosti spadají pod § 38.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Posoudit, zda jde jen o provozní obsluhu (§ 40), nebo o výkon kryptografické ochrany (§ 38).
- [ ] U provozní obsluhy zajistit pověření, splnění podmínek přístupu k UI (§ 6 odst. 1 / § 11 odst. 1) a zaškolení.
- [ ] Pro náročnější úkony (bezpečnostní správa, speciální obsluha, výroba/servis) vyžadovat osvědčení o ZOZ (§ 38).

**Typicky rozhodné důkazy / podklady:** pověření odpovědné osoby, doklad o splnění podmínek přístupu k UI pro daný stupeň, záznam o zaškolení, popis prováděných úkonů.

---


<!-- LEGAL-REVISION:BEGIN id=ac0adb307cbc627a3313 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 40 — Provozní obsluha kryptografického prostředku

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Provozní obsluhou kryptografického prostředku se rozumí výkon uživatelských funkcí kryptografického prostředku.
>
> (2) Osoba, která provádí provozní obsluhu kryptografického prostředku podle odstavce 1, musí
>
> - a) být k této obsluze pověřena odpovědnou osobou nebo jí pověřenou osobou,
>
> - b) splňovat podmínky přístupu k utajované informaci podle § 6 odst. 1 nebo § 11 odst. 1 a
>
> - c) být k této obsluze zaškolena.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 6, § 11

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=ac0adb307cbc627a3313 -->

### § 41 — Manipulace s kryptomateriálem a CCI

Pravidla pro **přenášení, přepravu, půjčování, ukládání, vyřazování** kryptomateriálu. Klíčové aspekty:

- **odst. 2**: kryptomateriál lze evidovat a manipulovat pouze způsobem a prostředky zajišťujícími jeho ochranu (prováděcí předpis — vyhláška č. 432/2011 Sb.),
- **odst. 3**: přístup ke kryptografickému dokumentu (manuál apod.) lze umožnit FO, jež neprovádí činnosti podle § 38 odst. 1, splňuje-li podmínky § 38 odst. 2 písm. b) (platné osvědčení FO + poučení) a je řádně poučena v oblasti kryptografické ochrany,
- **odst. 4**: kryptoprostředek a keymateriál do stupně Důvěrné lze chránit bez ukládání, je-li trvale pod **dohledem** oprávněného uživatele (typicky služební mobilní šifrátor nošený příslušníkem),
- **odst. 5**: CCI a kontrolovaná položka — podle bezpečnostního standardu.

#### F. Kazuistika

**1. Modelová situace.** Příslušník orgánu státu nosí trvale u sebe služební mobilní šifrátor s nahraným klíčovým materiálem stupně Důvěrné (typicky pro zabezpečené hovory v terénu). Bezpečnostní správce váhá, zda musí být přístroj v době mimo používání vždy uložen v trezoru, nebo zda postačí trvalý dohled uživatele. Současně chce umožnit technikovi nahlížet do kryptografického manuálu (kryptografického dokumentu), aniž by technik vykonával činnosti podle § 38 odst. 1. Účastníci: orgán státu (provozovatel), příslušník (uživatel), technik (přístup k dokumentu), NÚKIB. Důkazy: evidence kryptomateriálu, doklad o trvalém dohledu, osvědčení FO a poučení technika, doklad o poučení v oblasti kryptografické ochrany.

**2. Právní otázka.** Lze kryptografický prostředek a klíčový materiál do stupně Důvěrné chránit bez ukládání pouze trvalým dohledem oprávněného uživatele a za jakých podmínek smí do kryptografického dokumentu nahlížet osoba, jež nevykonává činnosti podle § 38 odst. 1?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 41 — manipulace s kryptomateriálem a CCI; kryptomateriál lze evidovat a manipulovat jen způsobem a prostředky zajišťujícími jeho ochranu (odst. 2); přístup ke kryptografickému dokumentu lze umožnit FO nevykonávající činnosti dle § 38 odst. 1, splňuje-li § 38 odst. 2 písm. b) (platné osvědčení FO a poučení) a je-li řádně poučena v oblasti kryptografické ochrany (odst. 3); kryptoprostředek a key materiál do stupně Důvěrné lze chránit bez ukládání, je-li trvale pod dohledem oprávněného uživatele (odst. 4); CCI a kontrolovaná položka podle bezpečnostního standardu (odst. 5).
- *Související ustanovení téhož zákona:* § 37 (kryptomateriál, evidence — odst. 5), § 38 (výkon kryptografické ochrany), § 42 (přeprava), § 42a (nakládání jiným způsobem), § 43 (kompromitace), § 37a a § 37b (CCI a kontrolovaná položka).
- *Související předpisy:* vyhláška č. 432/2011 Sb. (kryptografická ochrana UI); bezpečnostní standardy NÚKIB.
- *Judikatura:* publikovaná judikatura je sporá; nosné je pravidlo, že režim „bez ukládání pod trvalým dohledem" je omezen stupněm utajení (do Důvěrné) a vázán na trvalý dohled oprávněného uživatele.

**4. Subsumpce.** Mobilní šifrátor a klíčový materiál mají stupeň Důvěrné — spadají do rozsahu odst. 4, který připouští ochranu bez ukládání, je-li materiál trvale pod dohledem oprávněného uživatele. Je-li dohled skutečně trvalý (přístroj nošen u těla, nikdy ponechán bez kontroly), je podmínka splněna. Přístup technika ke kryptografickému dokumentu je podle odst. 3 přípustný, splňuje-li technik § 38 odst. 2 písm. b) (osvědčení FO + poučení) a je-li řádně poučen v oblasti kryptografické ochrany — i bez výkonu činností dle § 38 odst. 1.

**5. Řešení.** Bezpečnostní správce může povolit nošení šifrátoru bez ukládání, zajistí-li trvalý dohled oprávněného uživatele (odst. 4) a vede o materiálu evidenci. Technikovi umožní přístup ke kryptografickému dokumentu, ověří-li jeho osvědčení FO a poučení (§ 38 odst. 2 písm. b)) a provede-li poučení v oblasti kryptografické ochrany (odst. 3). Procesní kroky: zajištění trvalého dohledu, evidence, poučení technika. Riziko/alternativa: u materiálu stupně Tajné a vyššího se režim odst. 4 neuplatní a vyžaduje se ukládání podle standardu; přeruší-li se dohled, materiál musí být uložen.

**6. Varianty.** (a) Měl-li by key materiál stupeň Tajné, režim „bez ukládání" podle odst. 4 by nebyl přípustný a vyžadovalo by se uložení. (b) Vykonával-li by technik činnosti podle § 38 odst. 1 (např. servis), nepostačil by režim odst. 3 a uplatnily by se plné podmínky pracovníka kryptografické ochrany (§ 38 odst. 2 vč. osvědčení o ZOZ).

#### G. Protiargumenty a rizika

- *Protiargument 1: „Kryptomateriál musí být vždy v trezoru."* Neutralizace: odst. 4 výslovně připouští do stupně Důvěrné ochranu bez ukládání, je-li materiál trvale pod dohledem oprávněného uživatele.
- *Protiargument 2: „Do kryptografického manuálu smí jen pracovník kryptografické ochrany s osvědčením o ZOZ."* Neutralizace: odst. 3 umožňuje přístup ke kryptografickému dokumentu i osobě nevykonávající činnosti dle § 38 odst. 1, splní-li osvědčení FO + poučení a poučení v oblasti kryptografické ochrany.
- *Slabé místo:* pojem „trvalý dohled" není v zákoně blíže určen; jeho přerušení (odložení přístroje) okamžitě vyžaduje uložení — riziko nedbalého výkladu „dohledu" v terénu.

#### H. Praktický závěr

§ 41 upravuje manipulaci s kryptomateriálem: vždy jen způsobem zajišťujícím ochranu (odst. 2), do stupně Důvěrné lze chránit bez ukládání při trvalém dohledu uživatele (odst. 4) a do kryptografického dokumentu smí nahlížet i osoba mimo § 38 odst. 1 při splnění osvědčení FO, poučení a poučení v oblasti kryptografické ochrany (odst. 3).

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Manipulovat s kryptomateriálem jen způsobem a prostředky zajišťujícími ochranu (odst. 2) a vést evidenci.
- [ ] Režim „bez ukládání" (odst. 4) použít jen do stupně Důvěrné a jen při skutečně trvalém dohledu oprávněného uživatele.
- [ ] Přístup ke kryptografickému dokumentu (odst. 3) umožnit jen po ověření osvědčení FO, poučení a poučení v oblasti kryptografické ochrany.
- [ ] U CCI/kontrolované položky postupovat podle bezpečnostního standardu NÚKIB (odst. 5).

**Typicky rozhodné důkazy / podklady:** evidence kryptomateriálu, doklad o zajištění trvalého dohledu, osvědčení FO a poučení osoby s přístupem k dokumentu, záznam o poučení v oblasti kryptografické ochrany.

---


<!-- LEGAL-REVISION:BEGIN id=f4a6c1d3c2a307c43e8d generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 41 — Manipulace s kryptografickým materiálem a kontrolovanou kryptografickou položkou

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Manipulací s kryptografickým materiálem se rozumí způsob přenášení, přepravy, zapůjčování, ukládání nebo jiného nakládání s ním, včetně jeho vyřazování.
>
> (2) Kryptografický materiál lze evidovat a manipulovat s ním jen způsobem a prostředky, které zajistí ochranu kryptografického materiálu a splňují požadavky, které stanoví prováděcí právní předpis.
>
> (3) Fyzické osobě, která neprovádí činnosti podle § 38 odst. 1, lze umožnit přístup ke kryptografickému dokumentu, jestliže jej nezbytně potřebuje k výkonu své funkce, pracovní nebo jiné činnosti, splňuje podmínky podle § 38 odst. 2 písm. b) a je prokazatelným způsobem řádně poučena v oblasti kryptografické ochrany.
>
> (4) Ochranu kryptografického prostředku a materiálu k zajištění jeho funkce do stupně utajení Důvěrné, bez nutnosti jejich ukládání, lze zajistit způsobem, při kterém je tento kryptografický prostředek a materiál trvale pod dohledem jejich oprávněného uživatele.
>
> (5) Kontrolovanou kryptografickou položku a kontrolovanou položku lze evidovat, provozovat, ukládat, přepravovat, vyvážet, kontrolovat a distribuovat způsobem, který zajistí její ochranu a splní požadavky bezpečnostního standardu.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 38

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=f4a6c1d3c2a307c43e8d -->

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

#### F. Kazuistika

**1. Modelová situace.** Podnikatel, výrobce certifikovaného kryptografického prostředku, uzavře exportní kontrakt a hodlá prostředek dodat zahraničnímu zákazníkovi. Vývoz zahájí na základě běžné celní deklarace, aniž požádal NÚKIB o povolení vývozu kryptoprostředku. Současně AČR vyveze stejný typ prostředku ke svým jednotkám působícím v zahraniční misi. Účastníci: podnikatel (vývozce), NÚKIB (povoluje vývoz, vede evidenci), orgán státu (AČR). Důkazy: certifikát kryptoprostředku, žádost o povolení vývozu (chybí), povolení NÚKIB, doklad o účelu a místě použití.

**2. Právní otázka.** Lze certifikovaný kryptografický prostředek vyvézt z ČR bez povolení NÚKIB a vztahuje se povolovací režim i na používání prostředku orgánem státu mimo území ČR?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 42 — kurýr kryptomateriálu s trojí kvalifikací (pověření, splnění podmínek přístupu k UI nejméně pro stupeň materiálu, zaškolení — odst. 1); certifikovaný kryptoprostředek lze z ČR vyvážet jen s povolením NÚKIB, žádost je písemná, povolení na konkrétní prostředek a účel vývozu (odst. 2–4); NÚKIB povolení nevydá, byla-li by ohrožena UI ČR nebo UI, k jejíž ochraně se ČR zavázala — na povolení není právní nárok; používání mimo území ČR orgánem státu se nepovažuje za vývoz; NÚKIB vede evidenci povolení.
- *Související ustanovení téhož zákona:* § 37 (kryptoprostředek, certifikace), § 49 (certifikace kryptoprostředku), § 41 (manipulace), § 42a (nakládání jiným způsobem), § 36a (příslušnost NÚKIB).
- *Související předpisy:* vyhláška č. 432/2011 Sb.; zákon č. 594/2004 Sb. a předpisy o kontrole vývozu zboží dvojího užití (komplementárně); mezinárodní závazky ČR (NATO/EU COMSEC).
- *Judikatura:* publikovaná judikatura je sporá; nosné je pravidlo, že na povolení vývozu není právní nárok a rozhodnutí má politicko-bezpečnostní povahu.

**4. Subsumpce.** Dodávka certifikovaného kryptoprostředku do zahraničí je vývozem podle odst. 2; ten je možný jen s předchozím povolením NÚKIB na konkrétní prostředek a účel. Vývoz bez povolení je nezákonný. Naproti tomu používání téhož prostředku orgánem státu (AČR) v zahraniční misi se podle § 42 za vývoz nepovažuje, a povolení vývozu tedy nevyžaduje.

**5. Řešení.** Podnikatel musí před vývozem podat NÚKIB písemnou žádost a vyčkat povolení vázaného na konkrétní prostředek a účel; bez něj vyvážet nesmí. NÚKIB povolení nevydá, byla-li by ohrožena UI ČR nebo UI chráněná na základě závazku ČR — na povolení není nárok. AČR pro použití prostředku v misi povolení vývozu nepotřebuje (výjimka pro orgán státu). Procesní kroky: žádost o povolení, doložení účelu a prostředku, evidence povolení u NÚKIB. Riziko/alternativa: vývoz bez povolení je porušením zákona a může souběžně porušovat režim zboží dvojího užití.

**6. Varianty.** (a) Šlo-li by o přepravu kryptomateriálu v rámci ČR, neaplikoval by se vývozní režim, nýbrž pravidla pro kurýra kryptomateriálu (odst. 1). (b) Hrozila-li by vývozem újma UI, k jejíž ochraně se ČR zavázala (např. NATO COMSEC), NÚKIB povolení nevydá bez ohledu na obchodní zájem žadatele.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Certifikovaný prostředek lze volně vyvážet jako jiné zboží."* Neutralizace: odst. 2 podmiňuje vývoz certifikovaného kryptoprostředku povolením NÚKIB na konkrétní prostředek a účel; běžná celní deklarace nestačí.
- *Protiargument 2: „Použití prostředku v zahraniční misi je vývoz a vyžaduje povolení."* Neutralizace: § 42 výslovně vylučuje z pojmu vývoz používání mimo území ČR orgánem státu; AČR proto povolení vývozu nepotřebuje.
- *Slabé místo:* na povolení vývozu není právní nárok a rozhodnutí má diskreční politicko-bezpečnostní povahu; obchodní jistota vývozce je proto omezená a soudní přezkum úzký.

#### H. Praktický závěr

§ 42 váže vývoz certifikovaného kryptoprostředku z ČR na povolení NÚKIB (na konkrétní prostředek a účel, bez právního nároku); používání orgánem státu mimo území ČR vývozem není. Přepravu kryptomateriálu zajišťuje kvalifikovaný kurýr (odst. 1).

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Před vývozem certifikovaného kryptoprostředku podat NÚKIB písemnou žádost o povolení (konkrétní prostředek a účel).
- [ ] Nezaměňovat vývoz s používáním orgánem státu v zahraničí (to vývozem není).
- [ ] Pro přepravu kryptomateriálu zajistit kurýra s pověřením, přístupem k UI pro daný stupeň a zaškolením (odst. 1).
- [ ] Počítat s tím, že na povolení není právní nárok a NÚKIB je nevydá při ohrožení UI ČR či chráněné UI.

**Typicky rozhodné důkazy / podklady:** certifikát kryptoprostředku, písemná žádost o povolení vývozu, povolení NÚKIB s vymezením prostředku a účelu, doklad o místě a účelu použití (u orgánu státu v zahraničí), kvalifikace kurýra.


<!-- LEGAL-REVISION:BEGIN id=c79541f03a28c848e7ce generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 42 — Přeprava kryptografického materiálu a vývoz kryptografického prostředku

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Přepravu kryptografického materiálu provádí kurýr kryptografického materiálu. Kurýrem kryptografického materiálu je osoba, která
>
> - a) byla k přepravě pověřena odpovědnou osobou nebo jí pověřenou osobou,
>
> - b) splňuje podmínky přístupu k utajované informaci podle § 6 odst. 1 nebo § 11 odst. 1, nejméně pro stupeň utajení přepravovaného kryptografického materiálu a
>
> - c) byla k přepravě zaškolena.
>
> (2) Z území České republiky lze vyvážet certifikovaný kryptografický prostředek [§ 46 odst. 1 písm. c)] pouze na základě povolení Národního úřadu pro kybernetickou a informační bezpečnost. Za vývoz se nepovažuje používání certifikovaného kryptografického prostředku mimo území České republiky orgánem státu.
>
> (3) Povolení podle odstavce 2 lze udělit na základě písemné žádosti. Povolení se vydává na vývoz konkrétního kryptografického prostředku a obsahuje též účel vývozu. Národní úřad pro kybernetickou a informační bezpečnost povolení nevydá, jestliže by vývozem byla ohrožena utajovaná informace České republiky nebo utajovaná informace, k jejíž ochraně se Česká republika zavázala; tuto skutečnost písemně oznámí žadateli o povolení. Na udělení povolení není právní nárok.
>
> (4) Národní úřad pro kybernetickou a informační bezpečnost vede evidenci povolení udělených podle odstavce 2.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 6, § 11, § 46

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=c79541f03a28c848e7ce -->

### § 42a — Nakládání s kryptomateriálem jiným způsobem

Pokud FO nakládá s kryptomateriálem jinak než podle § 38, 40, 41 odst. 3 nebo § 42 (typicky transport mezi pracovišti, vyřazování, přechodné držení), musí být:
- pověřena odp. osobou,
- držitelem osvědčení FO + poučení (§ 38 odst. 2 písm. b)),
- držitelem osvědčení o zvláštní odborné způsobilosti (§ 38 odst. 2 písm. c)).

Tedy obdobné požadavky jako na pracovníka kryptografické ochrany.

#### F. Kazuistika

**1. Modelová situace.** Orgán státu potřebuje fyzicky přemístit vyřazené kryptografické prostředky a klíčový materiál mezi dvěma pracovišti a následně je zlikvidovat. Touto činností pověří administrativního zaměstnance, který má pověření odpovědné osoby a platné osvědčení FO s poučením, avšak nemá osvědčení o zvláštní odborné způsobilosti. Jde o nakládání s kryptomateriálem, jež neodpovídá § 38, 40, 41 odst. 3 ani § 42. Účastníci: orgán státu (odpovědná osoba), zaměstnanec (nakládá jiným způsobem), NÚKIB. Důkazy: pověření, osvědčení FO a poučení, osvědčení o zvláštní odborné způsobilosti (chybí), evidence kryptomateriálu (§ 37 odst. 5).

**2. Právní otázka.** Jaké kvalifikační podmínky musí splnit osoba, která nakládá s kryptomateriálem „jiným způsobem" podle § 42a (transport mezi pracovišti, vyřazování, přechodné držení) mimo režimy § 38, 40, 41 odst. 3 a § 42?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 42a — nakládá-li FO s kryptomateriálem jinak než podle § 38, 40, 41 odst. 3 nebo § 42, musí být pověřena odpovědnou osobou, být držitelem osvědčení FO a poučení (§ 38 odst. 2 písm. b)) a držitelem osvědčení o zvláštní odborné způsobilosti (§ 38 odst. 2 písm. c)) — tedy obdobné podmínky jako u pracovníka kryptografické ochrany.
- *Související ustanovení téhož zákona:* § 38 (výkon kryptografické ochrany a jeho podmínky), § 40 (provozní obsluha), § 41 (manipulace, vč. odst. 3 — přístup k dokumentu), § 42 (přeprava a vývoz), § 37 odst. 5 (evidence osob nakládajících podle § 42a), § 39 (zkouška ZOZ).
- *Související předpisy:* vyhláška č. 432/2011 Sb. (kryptografická ochrana UI); bezpečnostní standardy NÚKIB.
- *Judikatura:* publikovaná judikatura je sporá; nosné je pravidlo, že § 42a je zbytkovou („sběrnou") skutkovou podstatou, na niž se vztahují obdobné kvalifikační požadavky jako na výkon kryptografické ochrany (vč. osvědčení o ZOZ).

**4. Subsumpce.** Transport vyřazených prostředků mezi pracovišti a jejich likvidace nespadá pod § 38 (výkon KO), § 40 (provozní obsluha), § 41 odst. 3 (přístup k dokumentu) ani § 42 (přeprava kurýrem/vývoz) — jde o nakládání „jiným způsobem" podle § 42a. To vyžaduje kumulativně pověření (splněno), osvědčení FO a poučení (splněno) a osvědčení o zvláštní odborné způsobilosti (chybí). Třetí podmínka naplněna není, pověření zaměstnance je tedy nezpůsobilé.

**5. Řešení.** Orgán státu musí pověřit osobu, jež má i osvědčení o zvláštní odborné způsobilosti (§ 38 odst. 2 písm. c)), nebo administrativního zaměstnance nejprve nechat přezkoušet (§ 39); do té doby s kryptomateriálem podle § 42a nakládat nesmí. Osoba musí být zapsána v evidenci podle § 37 odst. 5. Procesní kroky: ověření tří podmínek, případné přezkoušení, pověření, vedení evidence. Riziko/alternativa: nakládání s kryptomateriálem bez osvědčení o ZOZ je porušením zákona a bezpečnostním rizikem (možná kompromitace — § 43).

**6. Varianty.** (a) Šlo-li by jen o přepravu kryptomateriálu kurýrem, uplatnil by se § 42 odst. 1 (kurýr — bez nutnosti osvědčení o ZOZ, postačí zaškolení). (b) Šlo-li by jen o přístup ke kryptografickému dokumentu bez výkonu činností dle § 38 odst. 1, uplatnil by se mírnější § 41 odst. 3 (osvědčení FO + poučení, bez osvědčení o ZOZ).

#### G. Protiargumenty a rizika

- *Protiargument 1: „Na pouhý transport či likvidaci stačí osvědčení FO."* Neutralizace: § 42a vyžaduje navíc osvědčení o zvláštní odborné způsobilosti (§ 38 odst. 2 písm. c)); samotné osvědčení FO nepostačí.
- *Protiargument 2: „Vyřazování kryptomateriálu žádný režim neupravuje."* Neutralizace: § 42a je právě zbytkovou skutkovou podstatou pokrývající nakládání mimo § 38, 40, 41 odst. 3 a § 42 — tedy i transport, vyřazování a přechodné držení.
- *Slabé místo:* odlišení § 42a od § 42 odst. 1 (přeprava kurýrem) a § 41 (manipulace) může být v praxi sporné; nesprávné zařazení vede buď k poddimenzované kvalifikaci (riziko kompromitace), nebo ke zbytečným nárokům.

#### H. Praktický závěr

§ 42a je sběrná skutková podstata: na nakládání s kryptomateriálem jiným způsobem (transport mezi pracovišti, vyřazování, přechodné držení) mimo § 38, 40, 41 odst. 3 a § 42 klade obdobné požadavky jako na pracovníka kryptografické ochrany — pověření, osvědčení FO + poučení a osvědčení o zvláštní odborné způsobilosti.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Ověřit, že nakládání nespadá pod § 38, 40, 41 odst. 3 ani § 42 (jinak platí tamní režim).
- [ ] U osoby podle § 42a zajistit pověření, osvědčení FO + poučení a osvědčení o zvláštní odborné způsobilosti.
- [ ] Zapsat osobu do evidence podle § 37 odst. 5.

**Typicky rozhodné důkazy / podklady:** pověření odpovědné osoby, osvědčení FO a poučení, osvědčení o zvláštní odborné způsobilosti, evidence osob nakládajících podle § 42a (§ 37 odst. 5).

---


<!-- LEGAL-REVISION:BEGIN id=448fd5ed21905862ca5b generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 42a

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> Pokud fyzická osoba nakládá s kryptografickým materiálem jiným způsobem, než je uvedeno v § 38 odst. 1, [[#§ 40|§ 40]], § 41 odst. 3 nebo [[#§ 42|§ 42]], musí být k nakládání pověřena odpovědnou osobou nebo jí pověřenou osobou a splňovat podmínky uvedené v § 38 odst. 2 písm. b) a c).

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 38, § 40, § 41, § 42

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=448fd5ed21905862ca5b -->

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

#### F. Kazuistika

**1. Modelová situace.** Pracovníkovi orgánu státu se ztratí služební šifrátor s nahraným klíčovým materiálem; existuje reálné riziko, že se dostal do nepovolaných rukou. Vedoucí incident nejprve řeší interně a oznámení NÚKIB odkládá o několik dní, než „prošetří okolnosti". Mezitím se kompromitovaný klíčový materiál dále používá ve spojení s ostatními pracovišti i spojeneckou sítí. Účastníci: orgán státu (provozovatel), pracovník (ztráta), NÚKIB (přijímá oznámení a řídí reakci). Důkazy: protokol o ztrátě, časová osa oznámení NÚKIB, evidence klíčového materiálu, doklad o dalším používání materiálu.

**2. Právní otázka.** Vznikla ztrátou šifrátoru s klíčovým materiálem kompromitace ve smyslu § 43 a jakou povinnost má provozovatel, zejména pokud jde o lhůtu k oznámení NÚKIB?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 43 — kompromitací kryptomateriálu je nakládání, které způsobilo nebo by mohlo způsobit porušení ochrany UI (odst. 1); při kompromitaci musí orgán státu/PO podle § 60b/podnikatel neprodleně oznámit NÚKIB (odst. 2).
- *Související ustanovení téhož zákona:* § 37 (kryptomateriál, evidence — odst. 5), § 41 (manipulace a ukládání), § 42 a § 42a (přeprava a jiné nakládání), § 43a (distribuce a evidence — rekey, výměna materiálu), § 36a (příslušnost NÚKIB).
- *Související předpisy:* vyhláška č. 432/2011 Sb. (kryptografická ochrana UI); bezpečnostní standardy NÚKIB; u materiálu NATO režim COMSEC.
- *Judikatura:* publikovaná judikatura je sporá; nosné je pravidlo, že kompromitace je definována i pro situace, jež by mohly způsobit porušení ochrany UI (potenciální ohrožení postačí), a vyžaduje neprodlené oznámení.

**4. Subsumpce.** Ztráta šifrátoru s klíčovým materiálem je nakládáním, které by mohlo způsobit porušení ochrany UI (materiál se mohl dostat do nepovolaných rukou) — naplňuje definici kompromitace podle odst. 1; postačí potenciální ohrožení, prokázaný únik se nevyžaduje. Tím vzniká podle odst. 2 povinnost neprodleně oznámit NÚKIB. Odklad oznámení o několik dní porušuje znak „neprodleně" a dále zvyšuje riziko (pokračující používání kompromitovaného materiálu).

**5. Řešení.** Provozovatel musí neprodleně (bez zbytečného odkladu, nezávisle na vnitřním prošetřování) oznámit kompromitaci NÚKIB; současně zastavit používání kompromitovaného materiálu a vyčkat pokynů NÚKIB (zákaz použití, distribuce nového key materiálu — rekey, vyšetřování zdroje). Procesní kroky: okamžité oznámení NÚKIB, izolace kompromitovaného materiálu, součinnost při rekey. Riziko/alternativa: odklad oznámení a další používání materiálu prohlubuje porušení ochrany UI a může zasáhnout i spojenecké sítě (nutný rozsáhlejší rekey).

**6. Varianty.** (a) Byl-li by kompromitován materiál NATO/pro vojenské účely, oznamovací a distribuční reakci by řídilo Ministerstvo obrany (§ 43a) v režimu COMSEC. (b) Šlo-li by jen o podezření bez reálné možnosti porušení ochrany UI (např. krátká nepřítomnost pod trvalým dohledem), nemuselo by jít o kompromitaci — rozhodující je, zda nakládání mohlo způsobit porušení ochrany UI.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Kompromitace je jen prokázaný únik UI."* Neutralizace: odst. 1 zahrnuje i nakládání, které by mohlo způsobit porušení ochrany UI — postačí potenciální ohrožení, nikoli prokázaný únik.
- *Protiargument 2: „Nejprve interní prošetření, oznámení NÚKIB až po něm."* Neutralizace: odst. 2 vyžaduje neprodlené oznámení; vnitřní šetření nemůže oznámení odkládat, neboť každé prodlení zvyšuje riziko.
- *Slabé místo:* posouzení, zda nakládání „mohlo způsobit" porušení ochrany UI, je v hraničních případech nejisté; podcenění vede k opomenutí oznámení, nadhodnocení ke zbytečně nákladnému rekey.

#### H. Praktický závěr

§ 43 definuje kompromitaci kryptomateriálu šíře — i jako nakládání, jež by mohlo způsobit porušení ochrany UI — a ukládá neprodlené oznámení NÚKIB. Jde o nejzávažnější incident kryptografické ochrany, typicky s nutností rekey.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Vyhodnotit, zda nakládání s kryptomateriálem způsobilo nebo mohlo způsobit porušení ochrany UI (kompromitace).
- [ ] Při kompromitaci neprodleně oznámit NÚKIB (u materiálu NATO/vojenského viz režim § 43a / MO).
- [ ] Okamžitě izolovat kompromitovaný materiál a poskytnout součinnost při rekey a vyšetřování.

**Typicky rozhodné důkazy / podklady:** protokol o incidentu (ztráta/zneoprávněné nakládání), časová osa a doklad o oznámení NÚKIB, evidence kryptomateriálu, dokumentace o zákazu použití a výměně klíčového materiálu.

---


<!-- LEGAL-REVISION:BEGIN id=e34f922ac00ab9245f31 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 43 — Kompromitace kryptografického materiálu

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Kompromitací kryptografického materiálu se rozumí nakládání s kryptografickým materiálem, které způsobilo nebo by mohlo způsobit porušení ochrany utajované informace.
>
> (2) Kompromitaci kryptografického materiálu jsou orgán státu, právnická osoba podle [[#§ 60b|§ 60b]] nebo podnikatel povinni neprodleně oznámit Národnímu úřadu pro kybernetickou a informační bezpečnost.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 60b

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=e34f922ac00ab9245f31 -->

### § 43a — Distribuce a evidence kryptomateriálu (NÚKIB / MO)

Centrální distribuce a evidence kryptomateriálu:
- **NÚKIB**: kryptomateriál ČR, EU a kryptomateriál na základě mezinárodní smlouvy (s výjimkou vojenského),
- **Ministerstvo obrany**: kryptomateriál NATO a kryptomateriál pro vojenské účely.

Toto dvojkolejné dělení reflektuje **specializaci ozbrojených sil** a tradiční vazbu vojenské kryptografie na MO; navíc kryptomateriál NATO podléhá samostatnému režimu COMSEC se sídlem v Bruselu (NATO C3 Board, NICA Mons).

#### F. Kazuistika

**1. Modelová situace.** Orgán státu zapojený do mezinárodní spolupráce potřebuje obstarat klíčový materiál ze tří zdrojů: vnitrostátní kryptomateriál ČR, kryptomateriál NATO a kryptomateriál pro vojenské účely. Zaměstnanec se obrátí jednotně na NÚKIB jako na centrální distribuční a evidenční místo pro veškerý kryptomateriál. Vznikne otázka, zda je NÚKIB příslušný i pro materiál NATO a vojenský materiál, nebo zda je tu příslušné Ministerstvo obrany. Účastníci: orgán státu (odběratel), NÚKIB (distribuce kryptomateriálu ČR/EU a dle mezinárodní smlouvy mimo vojenský), Ministerstvo obrany (distribuce NATO a vojenského materiálu). Důkazy: evidence kryptomateriálu, doklad o původu/typu materiálu, žádosti o přidělení.

**2. Právní otázka.** Který orgán je centrálním distribučním a evidenčním místem pro jednotlivé druhy kryptomateriálu (vnitrostátní/EU/mezinárodní vs. NATO/vojenský)?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 43a — centrální distribuce a evidence kryptomateriálu se dělí mezi NÚKIB (kryptomateriál ČR, EU a kryptomateriál na základě mezinárodní smlouvy s výjimkou vojenského) a Ministerstvo obrany (kryptomateriál NATO a kryptomateriál pro vojenské účely).
- *Související ustanovení téhož zákona:* § 37 (kryptomateriál, evidence — odst. 5), § 43 (kompromitace — rekey z centrálního místa), § 42 (přeprava/vývoz), § 36a (příslušnost NÚKIB v kryptografické ochraně), § 37 odst. 4 (centrální distribuční a evidenční místo jako specializované kryptopracoviště).
- *Související předpisy:* vyhláška č. 432/2011 Sb.; režim NATO COMSEC; mezinárodní smlouvy o ochraně UI; zákon o NÚKIB č. 181/2014 Sb.
- *Judikatura:* publikovaná judikatura chybí; nosné je systematické pravidlo dvojkolejnosti: NÚKIB pro civilní/EU/mezinárodní (nevojenský) materiál, MO pro NATO a vojenský materiál.

**4. Subsumpce.** Vnitrostátní kryptomateriál ČR a materiál na základě mezinárodní smlouvy (nevojenský) spadá podle § 43a pod NÚKIB. Kryptomateriál NATO a kryptomateriál pro vojenské účely naopak spadá pod Ministerstvo obrany. Jednotné obracení se na NÚKIB pro všechny tři druhy je proto chybné u materiálu NATO a vojenského, kde je centrálním místem MO.

**5. Řešení.** Orgán státu rozliší druhy kryptomateriálu a žádosti o přidělení a evidenci materiálu ČR/EU/mezinárodního (nevojenského) směřuje na NÚKIB, kdežto materiálu NATO a vojenského na Ministerstvo obrany. Procesní kroky: klasifikace materiálu podle původu/účelu, směřování žádostí na správné centrální místo, vedení návazné evidence (§ 37 odst. 5). Riziko/alternativa: směřování žádosti o materiál NATO/vojenský na NÚKIB je chybné a vede k prodlení; u materiálu NATO se navíc uplatní režim COMSEC.

**6. Varianty.** (a) Jde-li o kryptomateriál EU, je centrálním místem NÚKIB. (b) Jde-li o kryptomateriál pro vojenské účely byť vnitrostátní povahy, je centrálním místem Ministerstvo obrany, nikoli NÚKIB.

#### G. Protiargumenty a rizika

- *Protiargument 1: „NÚKIB je gestor kryptografické ochrany (§ 36a), tedy distribuuje veškerý kryptomateriál."* Neutralizace: § 43a je speciální vůči obecné příslušnosti a u kryptomateriálu NATO a vojenského svěřuje centrální distribuci a evidenci Ministerstvu obrany.
- *Protiargument 2: „Dělení NÚKIB/MO je jen organizační, lze je obejít."* Neutralizace: § 43a určuje centrální distribuční a evidenční místo závazně podle druhu materiálu; nelze je volit.
- *Slabé místo:* zařazení materiálu (nevojenský mezinárodní vs. vojenský/NATO) může být v hraničních případech sporné; chybné určení centrálního místa ohrožuje evidenci a včasný rekey při kompromitaci.

#### H. Praktický závěr

§ 43a dělí centrální distribuci a evidenci kryptomateriálu mezi NÚKIB (ČR, EU, mezinárodní nevojenský) a Ministerstvo obrany (NATO, vojenský). Druh materiálu určuje, na které centrální místo se obracet.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Klasifikovat kryptomateriál podle původu a účelu (ČR/EU/mezinárodní nevojenský vs. NATO/vojenský).
- [ ] Žádosti o přidělení a evidenci směřovat na NÚKIB (nevojenský) nebo Ministerstvo obrany (NATO/vojenský).
- [ ] U materiálu NATO počítat s navazujícím režimem COMSEC.

**Typicky rozhodné důkazy / podklady:** doklad o původu a účelu kryptomateriálu, evidence kryptomateriálu (§ 37 odst. 5), žádosti o přidělení adresované správnému centrálnímu místu (NÚKIB/MO).

---


<!-- LEGAL-REVISION:BEGIN id=0f39f4dc3d1d4cecf48b generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 43a

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Distribuci a evidenci kryptografického materiálu České republiky, kryptografického materiálu Evropské unie a kryptografického materiálu distribuovaného na základě mezinárodní smlouvy, s výjimkou kryptografického materiálu pro vojenské účely, zajišťuje Národní úřad pro kybernetickou a informační bezpečnost. Distribuci a evidenci kryptografického materiálu Organizace Severoatlantické smlouvy a kryptografického materiálu pro vojenské účely zajišťuje Ministerstvo obrany.
>
> (2) Podmínky evidence, manipulace a kontroly kryptografického materiálu v České republice, zahrnující zejména možnost zřízení účtů pro kryptografický materiál v orgánech státu, u právnické osoby podle [[#§ 60b|§ 60b]] nebo podnikatele, vedení evidencí, kontrolní funkce, povinnosti držitelů kryptografického materiálu vůči Národnímu úřadu pro kybernetickou a informační bezpečnost nebo Ministerstvu obrany a zajištění kurýrní služby pro kryptografický materiál Evropské unie upraví bezpečnostní standard.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 60b

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=0f39f4dc3d1d4cecf48b -->

### § 44 — Zmocňovací ustanovení (kryptografická ochrana)

Zmocňuje k vydání prováděcí vyhlášky (zejm. vyhláška č. 432/2011 Sb., o zajištění kryptografické ochrany utajovaných informací) — náležitosti přihlášky ke zkoušce, organizace zkoušky, požadavky na kryptopracoviště, manipulace s materiálem, evidence atd.

#### F. Kazuistika

**1. Modelová situace.** Podnikatel zpochybní v řízení požadavek NÚKIB na konkrétní technické parametry svého kryptografického pracoviště s tím, že tyto detaily nejsou v zákoně, nýbrž jen ve vyhlášce č. 432/2011 Sb., a vyhláška podle něj překračuje zákonné zmocnění (jde nad rámec § 44). Vznikne spor o zákonnost prováděcí vyhlášky a o to, zda lze povinnost opřít o podzákonný předpis. Účastníci: podnikatel (adresát normy), NÚKIB (aplikuje vyhlášku), případně soud ve správním soudnictví. Důkazy: text § 44 (rozsah zmocnění), napadené ustanovení vyhlášky, odůvodnění uloženého požadavku.

**2. Právní otázka.** V jakém rozsahu § 44 zmocňuje k vydání prováděcí vyhlášky a lze povinnost v oblasti kryptografické ochrany opřít přímo o ustanovení vyhlášky č. 432/2011 Sb.?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 44 — zmocňovací ustanovení k vydání prováděcí vyhlášky upravující náležitosti přihlášky ke zkoušce, organizaci zkoušky, požadavky na kryptopracoviště, manipulaci s kryptomateriálem, evidence apod.
- *Související ustanovení téhož zákona:* § 37–43a (věcná úprava kryptografické ochrany, jež vyhláška provádí), § 39 (zkouška ZOZ), § 36a (příslušnost NÚKIB); čl. 79 odst. 3 Ústavy (mez zmocnění — secundum et intra legem).
- *Související předpisy:* vyhláška č. 432/2011 Sb., o zajištění kryptografické ochrany utajovaných informací; zákon č. 181/2014 Sb. (NÚKIB).
- *Judikatura:* ustálená judikatura Ústavního soudu a NSS k mezím zmocnění — prováděcí předpis se musí pohybovat v mezích zákona (secundum et intra legem) a nesmí ukládat povinnosti nad jeho rámec; nelze jím rozšiřovat zákonné meze.

**4. Subsumpce.** Technické požadavky na kryptopracoviště a organizaci zkoušky jsou právě těmi okruhy, k jejichž úpravě § 44 výslovně zmocňuje. Pohybuje-li se napadené ustanovení vyhlášky v těchto mezích a pouze konkretizuje zákonem předvídané povinnosti, je v souladu se zmocněním (čl. 79 odst. 3 Ústavy). Překračuje-li naopak rozsah § 44 (ukládá zcela novou povinnost bez zákonného základu), bylo by v rozsahu excesu neaplikovatelné.

**5. Řešení.** Orgán i adresát normy posoudí, zda napadené ustanovení vyhlášky zůstává v mezích § 44 (konkretizace) — pak je závazné a povinnost lze o ně opřít. Domnívá-li se podnikatel o exces, může v rámci správního soudnictví namítat nezákonnost podzákonného předpisu; soud k případnému rozporu přihlédne a vyhlášku v rozsahu excesu neaplikuje. Procesní kroky: identifikace zákonného základu povinnosti (§ 37 a násl. + § 44), posouzení souladu vyhlášky se zmocněním, případná soudní obrana. Riziko/alternativa: opření povinnosti o ustanovení vyhlášky, jež nemá oporu v zákoně, je vadou; naopak konkretizující detail v mezích zmocnění je plně závazný.

**6. Varianty.** (a) Týkal-li by se spor okruhu, který § 44 vůbec nepředvídá, šlo by o exekutivní normotvorbu nad rámec zmocnění a vyhláška by v té části nebyla aplikovatelná. (b) Šlo-li by jen o upřesnění technického standardu předvídaného zákonem, byla by úprava v souladu se zmocněním a závazná.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Povinnost není v zákoně, je jen ve vyhlášce, proto je neúčinná."* Neutralizace: § 44 výslovně zmocňuje k úpravě požadavků na kryptopracoviště, manipulaci a evidence vyhláškou; konkretizace v mezích zmocnění je závazná.
- *Protiargument 2: „Vyhláška může upravit cokoli k zajištění bezpečnosti."* Neutralizace: prováděcí předpis se musí držet mezí zákona (secundum et intra legem, čl. 79 odst. 3 Ústavy) a nesmí zakládat povinnosti nad rámec § 44.
- *Slabé místo:* hranice mezi přípustnou konkretizací a nepřípustným rozšířením povinností je v technických detailech neostrá; posouzení excesu vyžaduje srovnání s rozsahem zmocnění a může být sporné.

#### H. Praktický závěr

§ 44 je zmocňovací ustanovení, na jehož základě byla vydána vyhláška č. 432/2011 Sb. Povinnosti v oblasti kryptografické ochrany lze opřít o vyhlášku jen v mezích tohoto zmocnění; podzákonný předpis nesmí jít nad rámec zákona.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] U každé povinnosti dohledat zákonný základ (§ 37 a násl.) a navazující zmocnění v § 44.
- [ ] Ověřit, že ustanovení vyhlášky č. 432/2011 Sb. zůstává v mezích zmocnění (secundum et intra legem).
- [ ] Při podezření na exces zvážit námitku nezákonnosti podzákonného předpisu ve správním soudnictví.

**Typicky rozhodné důkazy / podklady:** text § 44 a navazujících hmotných ustanovení, napadené ustanovení vyhlášky č. 432/2011 Sb., odůvodnění uloženého požadavku.

---


<!-- LEGAL-REVISION:BEGIN id=1ec1c66919f2e4f13669 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 44 — Zmocňovací ustanovení

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> Prováděcí právní předpis stanoví
>
> - a) náležitosti přihlášky k odborné zkoušce,
>
> - b) organizaci, obsah a způsob provádění odborné zkoušky,
>
> - c) náležitosti osvědčení o zvláštní odborné způsobilosti,
>
> - d) minimální požadavky na zajištění bezpečnostní správy kryptografické ochrany,
>
> - e) podrobnosti zajišťování provozu kryptografického prostředku,
>
> - f) způsob zaškolování provozní obsluhy kryptografického prostředku a kurýra kryptografického materiálu a vzor potvrzení o zaškolení provozní obsluhy kryptografického prostředku a kurýra kryptografického materiálu,
>
> - g) podrobnosti způsobu vyznačování náležitostí na utajované informaci z oblasti kryptografické ochrany, zejména podle druhu kryptografického materiálu,
>
> - h) druhy a náležitosti administrativních pomůcek kryptografické ochrany a požadavky na vedení těchto pomůcek,
>
> - i) bližší požadavky na způsob a prostředky manipulace s kryptografickým materiálem,
>
> - j) obsah žádosti pro udělení povolení pro vývoz certifikovaného kryptografického prostředku z území České republiky a náležitosti povolení,
>
> - k) způsob vedení evidencí uvedených v § 37 odst. 5,
>
> - l) kategorie kryptografických pracovišť, typy činností na kryptografickém pracovišti a minimální požadavky na jejich zabezpečení,
>
> - m) podmínky ochrany kryptografického prostředku a materiálu k zajištění jeho funkce podle § 41 odst. 4.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 37, § 41

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=1ec1c66919f2e4f13669 -->

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

#### F. Kazuistika

**1. Modelová situace.** Orgán státu zřizuje jednací oblast pro projednávání UI stupně Tajné a šifrové pracoviště pro stupeň Přísně tajné. Hodlá je vybavit běžnou výpočetní technikou bez ochrany před kompromitujícím vyzařováním (TEMPEST) a pro vysoce citlivé pracoviště plánuje stínicí komoru, kterou si nechá zhotovit, ale nepožádá NÚKIB o její certifikaci. Vznikne otázka, zda je ochrana před kompromitujícím vyzařováním povinná a zda stínicí komora musí být certifikována. Účastníci: orgán státu (provozovatel), NÚKIB (ověřuje způsobilost, certifikuje stínicí komoru), případně zpravodajská služba (vlastní měření). Důkazy: doklad o stupni utajení projednávaných UI, certifikát stínicí komory [§ 46 odst. 1 písm. e)], protokol o ověření způsobilosti.

**2. Právní otázka.** Vyžaduje ochrana UI stupně Důvěrné a vyšší zabezpečení před únikem kompromitujícím vyzařováním a musí být stínicí komora certifikována NÚKIB?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 45 — ochranou UI stupně Přísně tajné, Tajné nebo Důvěrné před únikem kompromitujícím vyzařováním (TEMPEST) je zabezpečení elektrických a elektronických zařízení, zabezpečené/jednací oblasti nebo objektu (odst. 1); stínicí komora musí být certifikována NÚKIB [§ 46 odst. 1 písm. e)] (odst. 2); ověřování způsobilosti provádí NÚKIB při certifikaci IS/kryptoprostředku, schvalování projektu KS nebo na žádost, pro dílčí měření lze uzavřít smlouvu (§ 52); zpravodajské služby provádějí měření pro svá zařízení samy (odst. 3–5).
- *Související ustanovení téhož zákona:* § 4 (stupně utajení), § 24–26 (zabezpečené a jednací oblasti), § 34, § 35 (IS/KS), § 46 odst. 1 písm. e) a § 51 (certifikace stínicí komory), § 52 (smlouva o zajištění činnosti), § 36a (příslušnost NÚKIB).
- *Související předpisy:* prováděcí vyhlášky k fyzické bezpečnosti a kryptografické ochraně; bezpečnostní standardy NÚKIB; mezinárodní standardy TEMPEST (NATO).
- *Judikatura:* publikovaná judikatura je sporá; nosné je pravidlo, že ochrana před kompromitujícím vyzařováním je povinná od stupně Důvěrné a stínicí komora vyžaduje certifikaci NÚKIB.

**4. Subsumpce.** Projednávané UI mají stupně Tajné a Přísně tajné — tedy v rozsahu, pro nějž § 45 odst. 1 vyžaduje zabezpečení před únikem kompromitujícím vyzařováním. Použití běžné techniky bez ochrany TEMPEST je proto u těchto stupňů nedostatečné. Stínicí komora pro vysoce citlivé pracoviště je podle odst. 2 technickým prostředkem, jenž musí být certifikován NÚKIB [§ 46 odst. 1 písm. e)]; bez certifikace ji nelze k ochraně UI použít.

**5. Řešení.** Orgán musí pro UI stupně Důvěrné a vyšší zajistit ochranu před kompromitujícím vyzařováním (zabezpečení zařízení, oblasti či objektu) a stínicí komoru nechat certifikovat NÚKIB před nasazením (odst. 2). Způsobilost ověří NÚKIB (při certifikaci IS/kryptoprostředku, schvalování projektu KS nebo na žádost); pro dílčí měření lze uzavřít smlouvu podle § 52. Procesní kroky: posouzení stupně UI, zajištění TEMPEST opatření, certifikace stínicí komory, ověření způsobilosti. Riziko/alternativa: nasazení necertifikované stínicí komory či absence TEMPEST ochrany u Důvěrné a vyšší UI je porušením zákona a bezpečnostním rizikem (možný únik UI emisemi).

**6. Varianty.** (a) Šlo-li by o UI stupně Vyhrazené, povinnost ochrany před kompromitujícím vyzařováním podle § 45 odst. 1 by se neuplatnila (vztahuje se na Důvěrné a vyšší). (b) Šlo-li by o zařízení/oblast zpravodajské služby, mohla by si měření provést sama bez smlouvy podle § 52 (odst. 3–5, ochrana zpravodajských metod).

#### G. Protiargumenty a rizika

- *Protiargument 1: „Kompromitující vyzařování je teoretické riziko, ochrana není povinná."* Neutralizace: § 45 odst. 1 stanoví zabezpečení před únikem kompromitujícím vyzařováním jako povinnost u UI stupně Důvěrné a vyšší.
- *Protiargument 2: „Stínicí komoru stačí postavit podle technického standardu, certifikace není nutná."* Neutralizace: odst. 2 vyžaduje certifikaci stínicí komory NÚKIB [§ 46 odst. 1 písm. e)]; bez ní nelze komoru k ochraně UI použít.
- *Slabé místo:* posouzení dostatečnosti TEMPEST opatření je vysoce technické a závisí na standardech NÚKIB; bez odborného měření hrozí podcenění emisního rizika, zvláště u Přísně tajné.

#### H. Praktický závěr

§ 45 ukládá u UI stupně Důvěrné a vyšší ochranu před únikem kompromitujícím vyzařováním (TEMPEST) a podmiňuje použití stínicí komory její certifikací NÚKIB. Způsobilost ověřuje NÚKIB; zpravodajské služby měří pro svá zařízení samy.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] U UI stupně Důvěrné a vyšší zajistit zabezpečení před únikem kompromitujícím vyzařováním (zařízení/oblast/objekt).
- [ ] Stínicí komoru nechat certifikovat NÚKIB [§ 46 odst. 1 písm. e), § 51] před nasazením.
- [ ] Zajistit ověření způsobilosti NÚKIB (při certifikaci IS/kryptoprostředku, schvalování KS nebo na žádost); pro dílčí měření uzavřít smlouvu (§ 52).
- [ ] U zpravodajských služeb respektovat oprávnění provést měření vlastními silami (odst. 3–5).

**Typicky rozhodné důkazy / podklady:** doklad o stupni utajení projednávaných UI, certifikát stínicí komory, protokol o ověření způsobilosti / měření, smlouva podle § 52 (u dílčích měření).


<!-- LEGAL-REVISION:BEGIN id=41c15b589e2f7796d2d9 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 45

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Ochranou utajovaných informací stupně utajení Přísně tajné, Tajné nebo Důvěrné před jejich únikem kompromitujícím vyzařováním je zabezpečení elektrických a elektronických zařízení, zabezpečené oblasti, jednací oblasti nebo objektu.
>
> (2) Je-li ochrana utajované informace před únikem kompromitujícím vyzařováním zabezpečena stínicí komorou, musí být tato komora certifikována Národním úřadem pro kybernetickou a informační bezpečnost [§ 46 odst. 1 písm. e)].
>
> (3) Ověřování způsobilosti elektrických a elektronických zařízení, zabezpečené oblasti, jednací oblasti nebo objektu k ochraně před únikem utajované informace kompromitujícím vyzařováním zajišťuje Národní úřad pro kybernetickou a informační bezpečnost při certifikaci informačního systému nebo kryptografického prostředku, při schvalování projektu bezpečnosti komunikačního systému nebo na základě odůvodněné písemné žádosti orgánu státu, právnické osoby podle [[#§ 60b|§ 60b]] nebo podnikatele v souvislosti s ochranou utajovaných informací.
>
> (4) K provádění měření možného úniku utajovaných informací podle odstavce 3 může Národní úřad pro kybernetickou a informační bezpečnost uzavřít s orgánem státu, právnickou osobou podle [[#§ 60b|§ 60b]] nebo podnikatelem smlouvu podle [[#§ 52|§ 52]] o zajištění této činnosti.
>
> (5) K provádění měření zařízení, zabezpečené oblasti, jednací oblasti nebo objektu podle odstavce 3, které jsou provozovány nebo užívány zpravodajskými službami, jsou oprávněny zpravodajské služby. V těchto případech se smlouva podle [[#§ 52|§ 52]] neuzavírá. Zprávy o provedeném měření a protokoly měření podle odstavce 3 se ukládají u zpravodajské služby a předkládají se Národnímu úřadu pro kybernetickou a informační bezpečnost na jeho žádost.
>
> (6) Při provádění měření podle odstavce 5 jsou zpravodajské služby povinny dodržovat ustanovení tohoto zákona, prováděcích právních předpisů a bezpečnostních standardů Národního úřadu pro kybernetickou a informační bezpečnost.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 46, § 60b, § 52

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=41c15b589e2f7796d2d9 -->

### § 45a — Hlava IX — Příslušnost NÚKIB

Obdobně § 33a — pro **certifikaci** (Hlava IX, §§ 46–53) vykonává státní správu zejména NÚKIB, s výjimkami uvedenými níže.

#### F. Kazuistika

**1. Modelová situace.** Výrobce podá žádost o certifikaci dvou prostředků: technického prostředku fyzické bezpečnosti (bezpečnostní zámek — § 30) a informačního systému pro UI. Obě žádosti adresuje jednomu orgánu v domnění, že celá Hlava IX (certifikace) náleží NÚKIB. Vznikne spor, zda je k certifikaci technického prostředku fyzické bezpečnosti příslušný NÚKIB, nebo Úřad. Účastníci: výrobce (žadatel), NÚKIB (certifikace IS a kryptografie), Úřad (certifikace technických prostředků fyzické bezpečnosti). Důkazy: žádosti, doklad o doručení, identifikace druhu prostředku.

**2. Právní otázka.** Vykonává v oblasti certifikace (Hlava IX) státní správu výlučně NÚKIB, nebo existují výjimky ve prospěch Úřadu?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 45a — pro certifikaci (Hlava IX, §§ 46–53) vykonává státní správu zejména NÚKIB, s výjimkami uvedenými níže (obdobně § 33a).
- *Související ustanovení téhož zákona:* § 46 (společná ustanovení o certifikaci a dělba kompetencí), § 47 (certifikace technického prostředku — Úřad), § 48–51 (certifikace IS, kryptoprostředku, kryptopracoviště, stínicí komory — NÚKIB), § 33a, § 35b, § 36a (paralelní kompetenční ustanovení).
- *Související předpisy:* zákon č. 181/2014 Sb. (NÚKIB); kompetenční zákon č. 2/1969 Sb.; prováděcí vyhlášky k certifikaci.
- *Judikatura:* publikovaná judikatura k pravidlu příslušnosti chybí; nosné je, že kompetenční ustanovení svěřuje certifikaci převážně NÚKIB, avšak technický prostředek fyzické bezpečnosti zůstává u Úřadu (§ 47).

**4. Subsumpce.** Certifikace IS spadá podle § 48 pod NÚKIB; certifikace technického prostředku fyzické bezpečnosti (zámku) zůstává podle § 47 u Úřadu jako výjimka, na niž § 45a odkazuje („s výjimkami uvedenými níže"). Jednotné adresování obou žádostí NÚKIB je proto u technického prostředku fyzické bezpečnosti chybné — věcně příslušným je Úřad.

**5. Řešení.** Žadatel směřuje žádost o certifikaci IS na NÚKIB (§ 48) a žádost o certifikaci technického prostředku fyzické bezpečnosti na Úřad (§ 47). Žádost chybně doručenou nepříslušnému orgánu je nutné postoupit (§ 12 spr. ř.). Procesní kroky: rozlišit druh certifikace podle § 46, určit gestora (NÚKIB/Úřad), podat žádosti odděleně. Riziko/alternativa: rozhodnutí nepříslušného orgánu by bylo vadou řízení.

**6. Varianty.** (a) Šlo-li by jen o certifikaci kryptoprostředku, kryptopracoviště nebo stínicí komory (§ 49–51), byl by gestorem NÚKIB. (b) U prostředků/systémů zpravodajských služeb se uplatní zvláštní režim dílčích úloh prováděných samotnými službami (§ 46 odst. 17 a 18).

#### G. Protiargumenty a rizika

- *Protiargument 1: „Celá Hlava IX o certifikaci náleží NÚKIB."* Neutralizace: § 45a sám odkazuje na výjimky; certifikace technického prostředku fyzické bezpečnosti zůstává podle § 47 u Úřadu.
- *Protiargument 2: „Příslušnost si žadatel může zvolit podle vytíženosti orgánů."* Neutralizace: věcná příslušnost je dána zákonem (§ 45a ve spojení s § 46–51) a nelze ji měnit volbou žadatele.
- *Slabé místo:* rozhraní mezi „technickým prostředkem fyzické bezpečnosti" (Úřad) a ostatními předměty certifikace (NÚKIB) může být sporné u prostředků s dvojí povahou; chybné zařazení vede k nepříslušnosti.

#### H. Praktický závěr

§ 45a svěřuje certifikaci (Hlava IX) převážně NÚKIB, avšak s výjimkami — zejména certifikace technického prostředku fyzické bezpečnosti zůstává u Úřadu (§ 47). Druh certifikace (§ 46) určuje příslušný orgán.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Určit druh certifikace podle § 46 (technický prostředek vs. IS/kryptoprostředek/kryptopracoviště/stínicí komora).
- [ ] Žádost o technický prostředek fyzické bezpečnosti podat u Úřadu (§ 47), ostatní u NÚKIB (§ 48–51).
- [ ] Chybně adresované podání nechat postoupit věcně příslušnému orgánu (§ 12 spr. ř.).

**Typicky rozhodné důkazy / podklady:** žádosti s identifikací druhu prostředku, doklad o doručení/postoupení, podklady k certifikaci dle příslušného druhu.

---


<!-- LEGAL-REVISION:BEGIN id=8819b8ec762e098714a9 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 45a

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> Státní správu v oblasti ochrany utajovaných informací podle této hlavy vykonává Národní úřad pro kybernetickou a informační bezpečnost, pokud tento zákon nestanoví jinak.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Místní znění neobsahuje výslovný vnitřní odkaz.

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=8819b8ec762e098714a9 -->

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

#### F. Kazuistika

**1. Modelová situace.** Provozovatel informačního systému pro UI obdrží od NÚKIB rozhodnutí o zrušení platnosti certifikátu IS poté, co IS přestal splňovat bezpečnostní požadavky. Provozovatel chce proti zrušení podat odvolání s odkladným účinkem a domáhat se, aby do rozhodnutí o odvolání mohl IS dále provozovat; současně argumentuje, že certifikát je jen interní dokument bez právní váhy. Účastníci: provozovatel (žadatel/držitel certifikátu), NÚKIB (zrušil certifikát). Důkazy: certifikát IS, rozhodnutí o zrušení platnosti, doklad o odevzdání certifikátu (do 5 dnů).

**2. Právní otázka.** Má odvolání proti zrušení platnosti certifikátu IS odkladný účinek, je vůbec přípustné a jakou právní povahu má certifikát?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 46 — certifikace jako postup, jímž Úřad nebo NÚKIB ověřuje způsobilost technického prostředku, IS, kryptoprostředku, kryptopracoviště nebo stínicí komory (odst. 1); certifikát je veřejnou listinou (odst. 3); zánik platnosti a dělba pravomoci ke zrušení mezi Úřad a NÚKIB, přičemž odvolání proti zrušení nemá odkladný účinek a proti zrušení certifikátu IS nebo kryptoprostředku NÚKIB odvolání není přípustné (odst. 11); odevzdání certifikátu do 5 dnů (odst. 12); jediným účastníkem řízení je žadatel (odst. 19).
- *Související ustanovení téhož zákona:* § 47 (technický prostředek — Úřad), § 48 (certifikace IS — NÚKIB, zánik), § 49–51 (další certifikace), § 34 (provoz IS jen při platné certifikaci), § 45a (příslušnost).
- *Související předpisy:* § 134 OSŘ (veřejná listina a presumpce pravdivosti); správní řád č. 500/2004 Sb. (odvolání, odkladný účinek, postoupení); zákon č. 181/2014 Sb. (NÚKIB).
- *Judikatura:* publikovaná judikatura je sporá; nosné je systematické pravidlo, že zákon u zrušení certifikátu IS/kryptoprostředku vylučuje jak odkladný účinek, tak (u IS/kryptoprostředku) přípustnost odvolání — z důvodu definitivnosti zajištění bezpečnosti.

**4. Subsumpce.** Certifikát IS je podle odst. 3 veřejnou listinou (presumpce pravdivosti dle § 134 OSŘ), nikoli interním dokumentem. Zrušení jeho platnosti spadá pod odst. 11: odvolání nemá odkladný účinek a proti zrušení certifikátu IS NÚKIB navíc odvolání není přípustné. Požadavek provozovatele na odkladný účinek a další provoz IS proto nelze vyhovět; bez platného certifikátu nelze IS provozovat (§ 34). Certifikát je nutné odevzdat do 5 dnů (odst. 12).

**5. Řešení.** Provozovatel musí provoz IS po zrušení certifikátu zastavit (chybí podmínka § 34 odst. 2) a certifikát do 5 dnů odevzdat NÚKIB (odst. 12); odvolání proti zrušení certifikátu IS není přípustné a nemělo by odkladný účinek (odst. 11). Obrana je možná jen v mezích správního soudnictví (žaloba), avšak bez odkladu provozu. Procesní kroky: zastavení provozu, odevzdání certifikátu, případná žaloba, nová žádost o certifikaci. Riziko/alternativa: pokračování v provozu po zrušení certifikátu je porušením zákona; namítat „interní povahu" certifikátu je bezúspěšné (jde o veřejnou listinu).

**6. Varianty.** (a) Šlo-li by o zrušení certifikátu technického prostředku fyzické bezpečnosti, rušil by jej Úřad (§ 47 odst. 4 písm. b)) a režim opravných prostředků by se řídil obecně (odvolání bez odkladného účinku). (b) Šlo-li by o IS/kryptoprostředek zpravodajské služby, uplatnily by se zvláštní postupy podle § 46 odst. 17 a 18.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Proti zrušení certifikátu IS se lze odvolat a provoz zatím pokračuje."* Neutralizace: odst. 11 odkladný účinek vylučuje a u certifikátu IS/kryptoprostředku NÚKIB odvolání vůbec nepřipouští; provoz musí být zastaven.
- *Protiargument 2: „Certifikát je jen technický doklad, ne veřejná listina."* Neutralizace: odst. 3 výslovně přiznává certifikátu povahu veřejné listiny (§ 134 OSŘ) s presumpcí pravdivosti.
- *Slabé místo:* vyloučení odvolání a odkladného účinku zužuje procesní obranu držitele na správní soudnictví; rozhodnutí o zrušení tak nabývá rychlých faktických účinků a jeho zpětná náprava je obtížná.

#### H. Praktický závěr

§ 46 je rámcové ustanovení o certifikaci: rozlišuje pět druhů a gestory (Úřad/NÚKIB), činí z certifikátu veřejnou listinu a u zrušení certifikátu IS/kryptoprostředku NÚKIB vylučuje odkladný účinek i odvolání. Po zániku platnosti se certifikát do 5 dnů odevzdává.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Při zrušení certifikátu IS/kryptoprostředku NÚKIB nepočítat s odvoláním ani odkladným účinkem (odst. 11) a zastavit provoz.
- [ ] Po zániku platnosti certifikát do 5 dnů odevzdat příslušnému gestoru (odst. 12).
- [ ] Respektovat povahu certifikátu jako veřejné listiny (odst. 3) a postavení žadatele jako jediného účastníka řízení (odst. 19).
- [ ] Při potřebě obrany volit správní soudnictví, nikoli odvolání tam, kde je vyloučeno.

**Typicky rozhodné důkazy / podklady:** certifikát (veřejná listina), rozhodnutí o zrušení platnosti, doklad o odevzdání certifikátu do 5 dnů, dokumentace o splnění/nesplnění podmínek způsobilosti.

---


<!-- LEGAL-REVISION:BEGIN id=1f19a35c4edddc090554 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 46 — Společná ustanovení

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Certifikace je postup, jímž Úřad nebo Národní úřad pro kybernetickou a informační bezpečnost
>
> - a) ověřuje způsobilost technického prostředku k ochraně utajovaných informací,
>
> - b) ověřuje způsobilost informačního systému k nakládání s utajovanými informacemi,
>
> - c) ověřuje způsobilost kryptografického prostředku k ochraně utajovaných informací,
>
> - d) ověřuje způsobilost kryptografického pracoviště pro vykonávání činností podle § 37 odst. 4, nebo
>
> - e) ověřuje způsobilost stínicí komory k ochraně utajovaných informací.
>
> (2) Zjistí-li Úřad nebo Národní úřad pro kybernetickou a informační bezpečnost způsobilost podle odstavce 1, certifikát technického prostředku, certifikát informačního systému, certifikát kryptografického prostředku, certifikát kryptografického pracoviště nebo certifikát stínicí komory vydá.
>
> (3) Certifikáty podle odstavce 2 jsou veřejnými listinami.
>
> (4) Certifikát technického prostředku obsahuje
>
> - a) evidenční číslo certifikátu,
>
> - b) název a typové označení technického prostředku,
>
> - c) identifikaci výrobce technického prostředku obchodní firmou (dále jen „firma“) nebo názvem, identifikačním číslem osoby (dále jen „identifikační číslo“) a sídlem, jde-li o právnickou osobu, nebo jménem, příjmením a místem trvalého pobytu, jde-li o osobu fyzickou,
>
> - d) identifikaci držitele certifikátu technického prostředku podle písmene c),
>
> - e) hodnocení technického prostředku,
>
> - f) datum vydání a dobu platnosti certifikátu a
>
> - g) otisk úředního razítka a podpis oprávněného zástupce Úřadu; otisk úředního razítka se nevyžaduje, byl-li certifikát vydán v elektronické podobě.
>
> (5) Certifikát informačního systému, certifikát kryptografického prostředku, certifikát kryptografického pracoviště a certifikát stínicí komory obsahuje
>
> - a) evidenční číslo certifikátu,
>
> - b) identifikaci držitele certifikátu podle odstavce 4 písm. c),
>
> - c) datum vydání a dobu platnosti certifikátu a
>
> - d) otisk úředního razítka Národního úřadu pro kybernetickou a informační bezpečnost a podpis oprávněného zástupce Národního úřadu pro kybernetickou a informační bezpečnost; otisk úředního razítka se nevyžaduje, byl-li certifikát vydán v elektronické podobě.
>
> (6) Certifikát informačního systému vedle náležitostí podle odstavce 5 obsahuje identifikaci informačního systému a stupeň utajení utajovaných informací, pro který byla způsobilost informačního systému ověřena.
>
> (7) Certifikát kryptografického prostředku vedle náležitostí podle odstavce 5 obsahuje
>
> - a) identifikaci kryptografického prostředku,
>
> - b) identifikaci výrobce kryptografického prostředku podle odstavce 4 písm. c) a
>
> - c) stupeň utajení utajovaných informací, pro který byla způsobilost kryptografického prostředku schválena.
>
> (8) Certifikát kryptografického pracoviště vedle náležitostí podle odstavce 5 obsahuje
>
> - a) identifikaci kryptografického pracoviště,
>
> - b) rozsah způsobilosti kryptografického pracoviště a
>
> - c) kategorii kryptografického pracoviště.
>
> (9) Certifikát stínicí komory vedle náležitostí podle odstavce 5 obsahuje
>
> - a) identifikaci stínicí komory, pro kterou je vydáván,
>
> - b) identifikaci výrobce stínicí komory podle odstavce 4 písm. c) a
>
> - c) stupeň utajení utajovaných informací, pro který byla způsobilost stínicí komory schválena.
>
> (10) Není-li Úřadem nebo Národním úřadem pro kybernetickou a informační bezpečnost zjištěna způsobilost podle odstavce 1, rozhodne o nevydání certifikátu. Proti rozhodnutí o nevydání certifikátu podle odstavce 1 písm. b) a c) není odvolání přípustné.
>
> (11) Úřad rozhoduje o zániku platnosti certifikátu v případech uvedených v § 47 odst. 4 písm. b). Národní úřad pro kybernetickou a informační bezpečnost rozhoduje o zániku platnosti certifikátu v případech uvedených v § 48 odst. 4 písm. d), § 49 odst. 5 písm. b), § 50 odst. 4 písm. d) a § 51 odst. 4 písm. d). Odvolání podané proti rozhodnutí Úřadu nebo Národního úřadu pro kybernetickou a informační bezpečnost o zániku platnosti certifikátu nemá odkladný účinek. Proti rozhodnutí Národního úřadu pro kybernetickou a informační bezpečnost o zániku platnosti certifikátu informačního systému a certifikátu kryptografického prostředku není odvolání přípustné.
>
> (12) Jestliže platnost certifikátu, který nebyl vydán v elektronické podobě, zanikla podle § 48 odst. 4 písm. b) a d), § 49 odst. 5 písm. b), § 50 odst. 4 písm. b) a d) nebo § 51 odst. 4 písm. b) a d), je držitel certifikátu povinen do 5 dnů ode dne doručení oznámení Národního úřadu pro kybernetickou a informační bezpečnost odevzdat certifikát Národnímu úřadu pro kybernetickou a informační bezpečnost. Jestliže platnost certifikátu, který nebyl vydán v elektronické podobě, zanikla podle § 47 odst. 4 písm. b), je držitel certifikátu povinen do 5 dnů ode dne doručení oznámení Úřadu odevzdat certifikát Úřadu.
>
> (13) Přílohou certifikátu informačního systému, kryptografického prostředku, kryptografického pracoviště nebo stínicí komory je certifikační zpráva, která obsahuje zásady a podmínky jejich provozování. V příloze certifikátu technického prostředku mohou být stanoveny podmínky jeho používání.
>
> (14) Úřad ověřuje způsobilost technického prostředku podle odstavce 1 písm. a) na základě posudku vlastností technického prostředku (dále jen „posudek“). K vydávání posudku podle věty první může Úřad uzavřít s orgánem státu, právnickou osobou podle [[#§ 60b|§ 60b]] nebo podnikatelem smlouvu podle [[#§ 52|§ 52]] o zajištění činnosti.
>
> (15) K provádění dílčích úloh při ověřování způsobilosti podle odstavce 1 písm. b) až e) může Národní úřad pro kybernetickou a informační bezpečnost uzavřít s orgánem státu, právnickou osobou podle [[#§ 60b|§ 60b]] nebo podnikatelem smlouvu podle [[#§ 52|§ 52]] o zajištění těchto činností; to neplatí, jde-li o ověřování způsobilosti informačního systému, kryptografického prostředku nebo pracoviště anebo stínící komory, které mají být provozovány zpravodajskými službami.
>
> (16) Seznam orgánů státu, právnických osob podle [[#§ 60b|§ 60b]] a podnikatelů, s nimiž je uzavřena smlouva podle [[#§ 52|§ 52]], s výjimkou zpravodajských služeb, zveřejňuje Úřad a Národní úřad pro kybernetickou a informační bezpečnost v příslušném věstníku nebo na svých internetových stránkách.
>
> (17) K provádění dílčích úloh při ověřování způsobilosti podle odstavce 1 písm. b) až e), které z důvodu utajení nelze provést Národním úřadem pro kybernetickou a informační bezpečnost, jde-li o informační systém, kryptografický prostředek, kryptografické pracoviště nebo stínicí komoru, které mají být provozovány zpravodajskými službami, jsou oprávněny tyto zpravodajské služby. V těchto případech zpravodajské služby předloží Národnímu úřadu pro kybernetickou a informační bezpečnost výsledky provedení dílčích úloh a na žádost Národního úřadu pro kybernetickou a informační bezpečnost k nahlédnutí též protokoly o provedení dílčích úloh.
>
> (18) Při provádění dílčích úloh podle odstavce 17 jsou zpravodajské služby povinny dodržovat ustanovení tohoto zákona, prováděcích právních předpisů a bezpečnostních standardů Národního úřadu pro kybernetickou a informační bezpečnost.
>
> (19) Účastníkem řízení o certifikaci nebo o zrušení platnosti certifikátu je žadatel podle § 47 odst. 1, § 48 odst. 1, § 49 odst. 1, § 50 odst. 1 a § 51 odst. 1.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 37, § 47, § 48, § 49, § 50, § 51, § 60b, § 52

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=1f19a35c4edddc090554 -->

### § 47 — Certifikace technického prostředku (Úřad)

- O certifikaci písemně žádá u **Úřadu** výrobce/dovozce/distributor/uživatel.
- Doba platnosti: **nejdéle 5 let**.
- Seznam certifikovaných prostředků je **veřejný** (na webu Úřadu) — kromě těch certifikovaných na žádost uživatele.
- Zánik: uplynutím doby, nebo rozhodnutím Úřadu (prostředek neodpovídá zákonu/posudku).
- Po uplynutí doby platnosti lze **stále používat** — odst. 6 (zákon nevyžaduje vyřazení, jen brání novému nasazení).
- Úřad může přihlédnout k zahraničnímu certifikátu (mezinárodní uznávání).

#### F. Kazuistika

**1. Modelová situace.** Orgán státu má v zabezpečené oblasti instalovaný bezpečnostní trezor (technický prostředek fyzické bezpečnosti — § 30), jehož certifikát vydaný Úřadem před více než pěti lety pozbyl platnosti. Orgán váhá, zda musí trezor okamžitě vyřadit, a současně chce do jiné oblasti nasadit nový trezor, k němuž má jen zahraniční certifikát. Žádost o certifikaci adresuje NÚKIB. Účastníci: orgán státu (uživatel), Úřad (certifikuje technické prostředky fyzické bezpečnosti), výrobce/dovozce. Důkazy: certifikát trezoru s datem platnosti, zahraniční certifikát, žádost o certifikaci.

**2. Právní otázka.** Musí být technický prostředek fyzické bezpečnosti po uplynutí platnosti certifikátu vyřazen, který orgán je k jeho certifikaci příslušný a lze využít zahraniční certifikát?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 47 — o certifikaci technického prostředku žádá u Úřadu výrobce/dovozce/distributor/uživatel; doba platnosti nejdéle 5 let; seznam certifikovaných prostředků je veřejný (kromě certifikovaných na žádost uživatele); zánik uplynutím doby nebo rozhodnutím Úřadu; po uplynutí doby platnosti lze prostředek stále používat (odst. 6 — zákon nevyžaduje vyřazení, brání jen novému nasazení); Úřad může přihlédnout k zahraničnímu certifikátu.
- *Související ustanovení téhož zákona:* § 46 (společná ustanovení o certifikaci, veřejná listina, zánik), § 45a (příslušnost — výjimka ve prospěch Úřadu), § 30 (technické prostředky fyzické bezpečnosti), § 48–51 (certifikace v gesci NÚKIB), § 27–29 (opatření fyzické bezpečnosti).
- *Související předpisy:* vyhláška o fyzické bezpečnosti a technických prostředcích; mezinárodní normy a certifikace (uznávání); správní řád č. 500/2004 Sb.
- *Judikatura:* publikovaná judikatura je sporá; nosné je výkladové pravidlo odst. 6, že uplynutí platnosti certifikátu technického prostředku nezakládá povinnost jeho vyřazení, pouze brání novému nasazení.

**4. Subsumpce.** Trezor je technickým prostředkem fyzické bezpečnosti, k jehož certifikaci je podle § 47 příslušný Úřad (nikoli NÚKIB — žádost je tedy adresována nepříslušnému orgánu). Uplynutí platnosti certifikátu podle odst. 6 neznamená povinnost vyřazení; již nasazený trezor lze dále používat, brání to jen novému nasazení. Pro nový trezor lze podle § 47 přihlédnout k zahraničnímu certifikátu, o čemž však rozhoduje Úřad.

**5. Řešení.** Orgán nemusí stávající trezor po uplynutí platnosti certifikátu vyřadit (odst. 6) — může jej dále používat; pro nové nasazení však potřebuje platnou certifikaci. Žádost o certifikaci nového trezoru podá u Úřadu (§ 47), který může zohlednit zahraniční certifikát. Žádost chybně adresovanou NÚKIB je nutné postoupit Úřadu (§ 12 spr. ř.). Procesní kroky: ověření gestora (Úřad), případné využití zahraničního certifikátu, podání žádosti u Úřadu. Riziko/alternativa: nové nasazení necertifikovaného prostředku není přípustné, byť stávající prostředek po expiraci certifikátu používat lze.

**6. Varianty.** (a) Šlo-li by o certifikaci IS (nikoli technického prostředku), byl by příslušný NÚKIB (§ 48) a platnost certifikátu by byla 3 roky (PT/T/D), resp. 5 let (Vyhrazené). (b) Byl-li by trezor certifikován na žádost uživatele, nebyl by uveden ve veřejném seznamu certifikovaných prostředků.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Po expiraci certifikátu se technický prostředek musí ihned vyřadit."* Neutralizace: odst. 6 vyřazení nevyžaduje — prostředek lze dále používat; uplynutí platnosti brání jen novému nasazení.
- *Protiargument 2: „Technické prostředky certifikuje NÚKIB jako vše ostatní."* Neutralizace: § 47 (a § 45a) ponechává certifikaci technického prostředku fyzické bezpečnosti Úřadu; NÚKIB zde příslušný není.
- *Slabé místo:* pravidlo „stávající používat lze, nové nasadit ne" může v praxi vést k provozu zastaralých prostředků; bezpečnostně je vhodné nasazení obnovit, byť zákon vyřazení nevyžaduje.

#### H. Praktický závěr

§ 47 svěřuje certifikaci technického prostředku fyzické bezpečnosti Úřadu (platnost max. 5 let). Po uplynutí platnosti lze prostředek dále používat (odst. 6); certifikace je nutná jen pro nové nasazení. Úřad může přihlédnout k zahraničnímu certifikátu.

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Žádost o certifikaci technického prostředku fyzické bezpečnosti podávat u Úřadu (§ 47), nikoli u NÚKIB.
- [ ] Po expiraci certifikátu rozlišit: stávající prostředek lze dále používat (odst. 6), nové nasazení vyžaduje platnou certifikaci.
- [ ] U nového prostředku zvážit využití zahraničního certifikátu (rozhoduje Úřad).
- [ ] Ověřit, zda je prostředek ve veřejném seznamu (neplatí u certifikace na žádost uživatele).

**Typicky rozhodné důkazy / podklady:** certifikát technického prostředku s dobou platnosti, případný zahraniční certifikát, žádost o certifikaci adresovaná Úřadu, doklad o nasazení prostředku.


<!-- LEGAL-REVISION:BEGIN id=8d4f818c0ec23e417834 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 47 — Žádost o certifikaci technického prostředku a platnost certifikátu technického prostředku

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) O certifikaci technického prostředku písemně žádá u Úřadu výrobce, dovozce, distributor nebo uživatel technického prostředku. K žádosti se přiloží posudek podle § 46 odst. 14 a dokumentace nezbytná pro provedení certifikace technického prostředku.
>
> (2) Dobu platnosti certifikátu technického prostředku stanoví Úřad nejdéle na dobu 5 let.
>
> (3) Seznam certifikovaných technických prostředků, kromě technických prostředků certifikovaných na žádost uživatele technického prostředku, je zveřejňován na internetových stránkách Úřadu.
>
> (4) Platnost certifikátu technického prostředku zaniká
>
> - a) uplynutím doby jeho platnosti, nebo
>
> - b) rozhodnutím Úřadu o zániku platnosti certifikátu v případě, že vyráběný technický prostředek nesplňuje požadavky tohoto zákona a prováděcích právních předpisů nebo není ve shodě s posuzovaným technickým prostředkem.
>
> (5) Zanikla-li platnost certifikátu technického prostředku podle odstavce 4, Úřad tento technický prostředek vyřadí ze seznamu zveřejňovaného podle odstavce 3.
>
> (6) Technický prostředek používaný k ochraně utajovaných informací lze nadále používat i po uplynutí doby platnosti jeho certifikátu.
>
> (7) Úřad může při certifikaci technického prostředku přihlédnout k certifikátu nebo obdobnému dokumentu technického prostředku vydanému oprávněným pracovištěm cizí moci.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 46

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=8d4f818c0ec23e417834 -->

### § 48 — Certifikace IS (NÚKIB)

- O certifikaci IS žádá u **NÚKIB** orgán státu / PO podle § 60b / podnikatel, jenž bude IS provozovat.
- Doba platnosti:
  - **PT, T, D**: nejdéle **3 roky**,
  - **Vyhrazené**: nejdéle **5 let**.
- Zánik: uplynutím doby; **u IS pro D a vyšší — zánikem osvědčení podnikatele**; zrušením orgánu státu / zánikem PO podle § 60b; rozhodnutím NÚKIB; oznámením držitele o zrušení IS.
- **Opakovaná žádost**: musí být doručena **nejméně 6 měsíců** před uplynutím doby platnosti.
- Lhůty: NÚKIB rozhodne **do 1 roku**, ve zvlášť složitých případech **do 2 let**, s prodloužením ředitele NÚKIB nejvýše o 6 měsíců.

#### F. Kazuistika

**1. Modelová situace.** Podnikatel s osvědčením podnikatele provozuje certifikovaný informační systém pro UI stupně Tajné, jehož certifikát (platný 3 roky) se blíží konci platnosti. Podnikatel podá opakovanou žádost o certifikaci teprve dva měsíce před uplynutím platnosti. Souběžně podnikateli zanikne platnost osvědčení podnikatele. Účastníci: podnikatel (provozovatel IS), NÚKIB (certifikační orgán). Důkazy: certifikát IS s dobou platnosti, opakovaná žádost s datem doručení, doklad o platnosti osvědčení podnikatele.

**2. Právní otázka.** V jaké lhůtě musí být podána opakovaná žádost o certifikaci IS, jaká je doba platnosti certifikátu podle stupně utajení a jaký vliv má zánik osvědčení podnikatele na platnost certifikátu IS?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 48 — o certifikaci IS žádá u NÚKIB orgán státu/PO podle § 60b/podnikatel; doba platnosti nejdéle 3 roky (PT, T, D) a 5 let (Vyhrazené); zánik uplynutím doby, u IS pro stupeň Důvěrné a vyšší též zánikem osvědčení podnikatele, dále zrušením/zánikem žadatele, rozhodnutím NÚKIB či oznámením o zrušení IS; opakovaná žádost musí být doručena nejméně 6 měsíců před uplynutím platnosti; lhůty pro rozhodnutí (1 rok, složité 2 roky, prodloužení nejvýše o 6 měsíců).
- *Související ustanovení téhož zákona:* § 34 (provoz IS jen při platné certifikaci a schválení), § 46 (společná ustanovení, zánik, veřejná listina), § 16 a § 15a (osvědčení a prohlášení podnikatele), § 4 (stupně utajení), § 45a (příslušnost).
- *Související předpisy:* vyhláška o bezpečnosti IS pro UI; správní řád č. 500/2004 Sb. (lhůty, řízení); zákon č. 181/2014 Sb. (NÚKIB).
- *Judikatura:* publikovaná judikatura je sporá; nosné je pravidlo, že opožděná opakovaná žádost (po lhůtě 6 měsíců) nezachová kontinuitu platnosti a že u IS pro Důvěrné a vyšší je platnost certifikátu navázána na trvání osvědčení podnikatele.

**4. Subsumpce.** IS zpracovává UI stupně Tajné — doba platnosti certifikátu je proto nejdéle 3 roky (§ 48). Opakovaná žádost musí být doručena nejméně 6 měsíců před uplynutím platnosti; podání dva měsíce předem této lhůtě nevyhovuje, takže kontinuita certifikace není zajištěna. Zánik osvědčení podnikatele navíc u IS pro Důvěrné a vyšší (Tajné spadá do této kategorie) způsobuje zánik platnosti certifikátu IS.

**5. Řešení.** Podnikatel měl opakovanou žádost podat nejméně 6 měsíců před koncem platnosti; při opožděném podání hrozí, že po uplynutí platnosti nebude IS certifikován a podle § 34 v něm nelze nakládat s UI. Zaniklo-li osvědčení podnikatele, zaniká i platnost certifikátu IS (pro Tajné) a provoz je nutné zastavit do obnovení osvědčení a certifikace. Procesní kroky: hlídání doby platnosti, včasná opakovaná žádost (6 měsíců předem), sledování platnosti osvědčení podnikatele. Riziko/alternativa: provoz IS po zániku certifikátu či osvědčení podnikatele je porušením zákona.

**6. Varianty.** (a) Zpracovával-li by IS jen UI stupně Vyhrazené, byla by platnost certifikátu až 5 let a zánik osvědčení podnikatele by se na certifikát nevztahoval (zánik podle osvědčení se týká D a vyšší). (b) Šlo-li by o zvlášť složitý případ, mohl by NÚKIB rozhodovat až 2 roky (s prodloužením ředitele nejvýše o 6 měsíců) — důvod pro včasné podání žádosti.

#### G. Protiargumenty a rizika

- *Protiargument 1: „Opakovanou žádost lze podat kdykoli před koncem platnosti."* Neutralizace: § 48 vyžaduje doručení nejméně 6 měsíců předem; pozdější podání nezaručí kontinuitu certifikace a hrozí přerušení provozu IS.
- *Protiargument 2: „Zánik osvědčení podnikatele se certifikátu IS netýká."* Neutralizace: u IS pro stupeň Důvěrné a vyšší zákon váže zánik platnosti certifikátu právě na zánik osvědčení podnikatele.
- *Slabé místo:* dlouhé lhůty pro rozhodnutí (až 2 roky + prodloužení) znamenají, že opožděná žádost reálně vede k mezeře v certifikaci; bez včasného podání nelze zákonný provoz IS udržet.

#### H. Praktický závěr

§ 48 upravuje certifikaci IS NÚKIB: platnost 3 roky (PT/T/D), 5 let (Vyhrazené); opakovaná žádost nejméně 6 měsíců před koncem platnosti; u IS pro Důvěrné a vyšší zaniká certifikát se zánikem osvědčení podnikatele. Bez platné certifikace nelze IS provozovat (§ 34).

**Checklist (advokát / soud / správní orgán / adresát normy):**
- [ ] Evidovat dobu platnosti certifikátu IS podle stupně utajení (3 roky PT/T/D, 5 let Vyhrazené).
- [ ] Opakovanou žádost o certifikaci doručit NÚKIB nejméně 6 měsíců před uplynutím platnosti.
- [ ] U IS pro stupeň Důvěrné a vyšší hlídat platnost osvědčení podnikatele (jeho zánik ruší certifikát IS).
- [ ] Při zániku certifikátu zastavit nakládání s UI v IS (§ 34).

**Typicky rozhodné důkazy / podklady:** certifikát IS s dobou platnosti, opakovaná žádost s datem doručení, doklad o platnosti osvědčení podnikatele, doklad o stupni utajení zpracovávaných UI.


<!-- LEGAL-REVISION:BEGIN id=ef37732d8ec619e4d431 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 48 — Žádost o certifikaci informačního systému a platnost certifikátu informačního systému

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) O certifikaci informačního systému písemně žádá u Národního úřadu pro kybernetickou a informační bezpečnost orgán státu, právnická osoba podle [[#§ 60b|§ 60b]] nebo podnikatel, který bude informační systém provozovat.
>
> (2) Ten, kdo o certifikaci informačního systému podle odstavce 1 požádal, předkládá v průběhu certifikace na žádost Národního úřadu pro kybernetickou a informační bezpečnost dokumentaci nezbytnou pro provedení certifikace.
>
> (3) Dobu platnosti certifikátu informačního systému stanoví Národní úřad pro kybernetickou a informační bezpečnost. Platnost certifikátu informačního systému je pro stupeň utajení
>
> - a) Přísně tajné, Tajné a Důvěrné nejdéle 3 roky a
>
> - b) Vyhrazené nejdéle 5 let.
>
> (4) Platnost certifikátu informačního systému zaniká
>
> - a) uplynutím doby jeho platnosti,
>
> - b) v případě informačního systému pro nakládání s utajovanými informacemi stupně utajení Důvěrné nebo vyššího zánikem platnosti osvědčení podnikatele,
>
> - c) zrušením orgánu státu nebo zánikem právnické osoby podle [[#§ 60b|§ 60b]],
>
> - d) rozhodnutím Národního úřadu pro kybernetickou a informační bezpečnost o zániku platnosti certifikátu, přestal-li být informační systém způsobilý k nakládání s utajovanými informacemi, nebo
>
> - e) oznámením orgánu státu, právnické osoby podle [[#§ 60b|§ 60b]] nebo podnikatele, který je držitelem certifikátu, o zrušení informačního systému.
>
> (5) Má-li být informační systém používán i bezprostředně po uplynutí doby platnosti jeho certifikátu, je žadatel podle odstavce 1 povinen požádat Národní úřad pro kybernetickou a informační bezpečnost o certifikaci informačního systému. Opakovaná žádost musí být Národnímu úřadu pro kybernetickou a informační bezpečnost doručena nejméně 6 měsíců před uplynutím doby platnosti původního certifikátu informačního systému.
>
> (6) Národní úřad pro kybernetickou a informační bezpečnost je povinen rozhodnout o certifikaci informačního systému do 1 roku od zahájení řízení o certifikaci, ve zvlášť složitých případech do 2 let; nelze-li vzhledem k povaze věci rozhodnout v této lhůtě, může ji přiměřeně prodloužit ředitel Národního úřadu pro kybernetickou a informační bezpečnost, nejvýše však o 6 měsíců.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 60b

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=ef37732d8ec619e4d431 -->

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

#### F. Kazuistika

**1. Modelová situace.** Český výrobce šifrátorů „KryptoTech, s. r. o.“ (držitel osvědčení podnikatele pro formu § 20 odst. 1 písm. a) na stupeň Tajné) vyvinul nový hardwarový kryptografický prostředek a podá NÚKIB žádost o certifikaci pro stupeň Tajné se způsobilostí i k ochraně taktické informace (§ 35a). Součástí prostředku je zahraniční šifrovací modul od německého subdodavatele. NÚKIB v průběhu řízení zjistí, že prostředek obsahuje komponentu pocházející ze státu, vůči němuž ČR uplatňuje exportní/bezpečnostní restrikce. Důkazy: žádost s technickou dokumentací prostředku, výsledky kryptanalytického a TEMPEST testování v laboratoři NÚKIB, doklad o původu komponent, případně zahraniční certifikát modulu.

**2. Právní otázka.** Může NÚKIB žádost o certifikaci kryptoprostředku odmítnout pro rozpor se záměry ČR i tehdy, je-li prostředek technicky způsobilý, a je takové odmítnutí soudně přezkoumatelné?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 49 — certifikace kryptoprostředku NÚKIB; možnost odmítnout žádost nesouladnou se záměry ČR; vyloučení odvolání a soudního přezkumu; platnost max. 5 let; způsobilost k ochraně taktické informace (§ 35a).
- *Související ustanovení téhož zákona:* § 35a (taktická informace), § 37 a násl. (kryptografická ochrana), § 42 odst. 2 (vývoz kryptoprostředku), § 48 odst. 6 (lhůty), § 53 (zmocnění k prováděcí vyhlášce).
- *Související předpisy:* vyhláška č. 432/2011 Sb. (kryptografická ochrana); zákon č. 594/2004 Sb. / pravidla kontroly vývozu zboží dvojího užití; mezinárodní závazky NATO/EU ke kryptografickým prostředkům.
- *Judikatura:* na povahu rozhodnutí navázaných na bezpečnostní zájmy státu dopadá konstantní linie ÚS a NSS (srov. Pl. ÚS 11/2000, NSS k bezpečnostním řízením), podle níž lze přezkum omezit, je-li zájem na utajení proporcionální; samotné vyloučení přezkumu však musí mít zákonný podklad a nesmí být svévolné.

**4. Subsumpce.** Žadatel (podnikatel s osvědčením) i předmět (kryptoprostředek) odpovídají hypotéze § 49. Technická způsobilost je sice nutnou, nikoli postačující podmínkou — zákon výslovně dává NÚKIB diskreci žádost odmítnout pro nesoulad se „záměry ČR“, což je politicko-bezpečnostní kritérium stojící mimo ryze technické posouzení. Zjištěný původ komponenty z rizikového státu naplňuje důvod nesouladu se záměry ČR. Sporné je, zda je vyloučení soudního přezkumu ústavně konformní.

**5. Řešení.** NÚKIB je oprávněn žádost odmítnout; rozhodnutí se neodůvodňuje technickou nezpůsobilostí, ale nesouladem se záměry ČR. Proti odmítnutí podle § 49 není odvolání ani žaloba ve správním soudnictví (výslovné vyloučení). Žadatel může pouze podat novou žádost (např. po výměně rizikové komponenty) nebo se domáhat ochrany ústavní cestou, namítá-li svévoli; soud by však zkoumal jen mezní excesy, nikoli věcnou správnost bezpečnostního úsudku. Praktický krok: žadatel reformuluje výrobní řetězec, doloží český/spojenecký původ kritických komponent a podá žádost znovu.

**6. Varianty.** (a) Kdyby NÚKIB chtěl žádost zamítnout pro samotnou technickou nezpůsobilost (neúspěšná kryptanalýza), nešlo by o odmítnutí podle věty o nesouladu se záměry ČR, ale o standardní zamítnutí — zde je namístě zvážit, zda zákon poskytuje opravný prostředek; vyloučení přezkumu se vztahuje na bezpečnostně-politické odmítnutí. (b) Pokud by existoval platný zahraniční certifikát prostředku z členského státu NATO, NÚKIB k němu může přihlédnout (§ 49) a řízení zkrátit, byť není vázán jej převzít.

#### G. Protiargumenty a rizika

- *Protiargument „úplné vyloučení přezkumu je protiústavní“.* Lze namítat rozpor s čl. 36 odst. 2 Listiny. Neutralizace: jde o rozhodnutí ve věci, kde převažuje zájem na ochraně bezpečnostních zájmů státu a originator control; ÚS opakovaně připustil omezení přezkumu v bezpečnostní oblasti, je-li proporcionální a týká se diskrečního politicko-bezpečnostního aktu, nikoli zásahu do subjektivních práv srovnatelného s prověrkou FO.
- *Protiargument „odmítnutí zastírá diskriminaci konkurenta“.* Riziko, že nesoulad se záměry ČR poslouží jako záminka. Neutralizace: NÚKIB musí mít konkrétní bezpečnostní podklad (analýza dodavatelského řetězce, zpravodajský poznatek); absence jakéhokoli podkladu by zakládala svévoli přezkoumatelnou alespoň v mezích excesu.
- *Slabé místo:* hranice mezi „odmítnutím pro nesoulad se záměry ČR“ (bez přezkumu) a „zamítnutím pro nezpůsobilost“ není v textu ostře vymezena — v praxi se opírá o prováděcí vyhlášku a interní metodiku NÚKIB.

#### H. Praktický závěr

Certifikace kryptoprostředku je dvojí filtr: technická způsobilost (testování NÚKIB) a bezpečnostně-politická vůle státu. Druhý filtr dává NÚKIB silnou diskreci odmítnout i technicky funkční prostředek a takové odmítnutí je vyloučeno z přezkumu.

**Checklist (žadatel / NÚKIB):**
- [ ] Je žadatel oprávněn (výrobce/dovozce/distributor/uživatel; podnikatel jen s osvědčením pro formu § 20 odst. 1 písm. a))?
- [ ] Je doložen původ všech kritických komponent a posouzen dodavatelský řetězec?
- [ ] Požaduje žadatel způsobilost k ochraně taktické informace (§ 35a)?
- [ ] Existuje zahraniční certifikát, k němuž lze přihlédnout?
- [ ] Je opakovaná žádost podána nejméně 6 měsíců před uplynutím platnosti?

**Typicky rozhodné důkazy / podklady:** žádost s technickou dokumentací, výsledky kryptanalytického a TEMPEST testování, doklad o původu komponent, analýza dodavatelského řetězce, případný zahraniční certifikát.


<!-- LEGAL-REVISION:BEGIN id=38395da7e49df5562589 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 49 — Žádost o certifikaci kryptografického prostředku a platnost certifikátu kryptografického prostředku

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) O certifikaci kryptografického prostředku písemně žádá u Národního úřadu pro kybernetickou a informační bezpečnost výrobce, dovozce, distributor nebo uživatel kryptografického prostředku. Žádá-li o certifikaci kryptografického prostředku podnikatel, musí být držitelem platného osvědčení podnikatele pro přístup k utajované informaci podle § 20 odst. 1 písm. a).
>
> (2) Národní úřad pro kybernetickou a informační bezpečnost žádost podle odstavce 1 rozhodnutím odmítne, není-li v souladu se záměry České republiky v oblasti zajišťování ochrany utajovaných informací kryptografickou ochranou. Proti rozhodnutí podle věty první není odvolání přípustné a nelze jej ani přezkoumat soudem.
>
> (3) Ten, kdo o certifikaci kryptografického prostředku podle odstavce 1 požádal, předkládá v průběhu certifikace na žádost Národního úřadu pro kybernetickou a informační bezpečnost kryptografický prostředek v potřebném počtu a dokumentaci nezbytnou pro provedení certifikace.
>
> (4) Dobu platnosti certifikátu kryptografického prostředku stanoví Národní úřad pro kybernetickou a informační bezpečnost na dobu nejdéle 5 let.
>
> (5) Platnost certifikátu kryptografického prostředku zaniká
>
> - a) uplynutím doby jeho platnosti, nebo
>
> - b) rozhodnutím Národního úřadu pro kybernetickou a informační bezpečnost o zániku platnosti certifikátu, přestal-li být kryptografický prostředek způsobilý k ochraně utajovaných informací.
>
> (6) Má-li být kryptografický prostředek používán i bezprostředně po uplynutí doby platnosti jeho certifikátu, je žadatel podle odstavce 1 povinen požádat Národní úřad pro kybernetickou a informační bezpečnost o certifikaci kryptografického prostředku. Opakovaná žádost musí být Národnímu úřadu pro kybernetickou a informační bezpečnost doručena nejméně 6 měsíců před uplynutím doby platnosti původního certifikátu kryptografického prostředku.
>
> (7) Národní úřad pro kybernetickou a informační bezpečnost může při certifikaci kryptografického prostředku přihlédnout k certifikátu nebo obdobnému dokumentu kryptografického prostředku vydanému oprávněným pracovištěm cizí moci.
>
> (8) Řízení o certifikaci kryptografického prostředku lze též přerušit současně s odesláním žádosti adresované zahraničnímu subjektu o informaci nezbytnou pro spolehlivé zjištění stavu věci.
>
> (9) Národní úřad pro kybernetickou a informační bezpečnost může stanovit při certifikaci kryptografického prostředku jeho způsobilost k ochraně taktické informace.
>
> (10) Pro lhůty pro vydání rozhodnutí platí § 48 odst. 6.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 20, § 48

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=38395da7e49df5562589 -->

### § 50 — Certifikace kryptopracoviště (NÚKIB)

- Žadatel: orgán státu / PO podle § 60b / podnikatel s osvědčením podnikatele.
- Doba platnosti: nejdéle **3 roky**.
- Zánik: uplynutím doby, zánikem osvědčení podnikatele, zrušením/zánikem žadatele, rozhodnutím NÚKIB, oznámením o zrušení pracoviště.
- Opakovaná žádost: nejméně **6 měsíců** před uplynutím.
- Lhůty: **6 měsíců**, složité případy **1 rok**, prodloužení **až o 3 měsíce**.

#### F. Kazuistika

**1. Modelová situace.** Orgán státu (ministerstvo) zřídí specializované kryptografické pracoviště pro provoz národních šifrátorů a požádá NÚKIB o jeho certifikaci na stupeň Tajné. Tři roky po certifikaci, ještě před uplynutím platnosti, ministerstvo přesune pracoviště do nové budovy a změní jeho personální obsazení. Současně provozuje vedle něj druhé kryptopracoviště, jehož faktickou obsluhu zajišťuje podnikatel na základě smlouvy o zajištění činnosti (§ 52); osvědčení tohoto podnikatele má zaniknout. Důkazy: certifikát kryptopracoviště, dokumentace prostor a personálu, oznámení o přesunu/zrušení pracoviště, osvědčení podnikatele a smlouva podle § 52.

**2. Právní otázka.** Trvá platnost certifikátu kryptopracoviště po přestěhování a změně personálu, a jaký vliv má na certifikaci pracoviště zánik osvědčení podnikatele, který činnost zajišťuje?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 50 — certifikace kryptopracoviště NÚKIB; platnost max. 3 roky; zánik mj. zánikem osvědčení podnikatele, zrušením/zánikem žadatele, oznámením o zrušení pracoviště; opakovaná žádost ≥ 6 měsíců předem; lhůty 6 měsíců / 1 rok / +3 měsíce.
- *Související ustanovení téhož zákona:* § 37 (kryptografický materiál a pracoviště), § 38–41 (výkon kryptoochrany, obsluha), § 49 (certifikace kryptoprostředku), § 52 (smlouva o zajištění činnosti), § 56 (zánik osvědčení podnikatele).
- *Související předpisy:* vyhláška č. 432/2011 Sb. (kryptografická ochrana); vyhláška č. 528/2005 Sb. (fyzická bezpečnost) na zabezpečenou oblast pracoviště.
- *Judikatura:* obecná zásada vázanosti platnosti odvozeného aktu na trvání jeho podmínek (rozhodovací praxe k zániku veřejnoprávních oprávnění při odpadnutí předpokladu).

**4. Subsumpce.** Certifikace kryptopracoviště je vázána na konkrétní prostory, technické a personální zajištění. Změna stěžejních parametrů (přesun do jiných prostor) zpravidla znamená, že certifikovaný stav již neexistuje — pracoviště v nové budově je fakticky jiným pracovištěm. Zánik osvědčení podnikatele, který činnost zajišťuje, je výslovným důvodem zániku certifikace (§ 50).

**5. Řešení.** Přestěhováním pracoviště pozbývá certifikát materiálního podkladu; ministerstvo by mělo oznámit zrušení původního pracoviště a požádat o certifikaci nového. Pouhá personální obměna sama o sobě certifikát neruší, jsou-li noví pracovníci odborně způsobilí a oprávnění, ale musí být promítnuta do dokumentace. U druhého pracoviště: zanikne-li osvědčení podnikatele zajišťujícího jeho činnost, zaniká i certifikace kryptopracoviště (§ 50) — ministerstvo musí zajistit činnost jinak (jiný podnikatel, vlastní zaměstnanci) a požádat o novou certifikaci. Opakovanou žádost je třeba podat nejméně 6 měsíců předem, jinak hrozí přerušení provozu.

**6. Varianty.** (a) Kdyby se pouze vyměnila část kryptografického vybavení uvnitř stejné zabezpečené oblasti, certifikát by mohl trvat při doplnění dokumentace, případně by postačila změna. (b) Kdyby žadatelem nebyl orgán státu, ale PO podle § 60b, platí stejný režim; zrušením této PO certifikace zaniká.

#### G. Protiargumenty a rizika

- *Protiargument „certifikát se váže k subjektu, ne k místu, přesun proto nevadí“.* Neutralizace: certifikace kryptopracoviště hodnotí konkrétní fyzické zabezpečení prostor (zabezpečená oblast, TEMPEST, ostraha); jiné prostory mají jiné vlastnosti, takže certifikovaný stav reálně zaniká, i kdyby formálně subjekt zůstal týž.
- *Protiargument „zánik osvědčení podnikatele je vada na straně podnikatele, nemá dopadat na žadatele-stát“.* Neutralizace: zákon přesto výslovně váže zánik certifikace na zánik osvědčení podnikatele zajišťujícího činnost — riziko nese provozovatel pracoviště, který musí kontinuitu zajistit předem.
- *Slabé místo:* hranice mezi „změnou vyžadující jen aktualizaci“ a „faktickým novým pracovištěm vyžadujícím novou certifikaci“ je posuzována NÚKIB; metodika není veřejně podrobně dostupná.

#### H. Praktický závěr

Certifikace kryptopracoviště je nejkratší z certifikací (3 roky) a je nejcitlivější na změny — provozovatel musí každou podstatnou změnu prostor, personálu nebo zajišťujícího podnikatele neprodleně řešit a žádost o novou certifikaci podávat s dostatečným předstihem.

**Checklist (provozovatel pracoviště / NÚKIB):**
- [ ] Je žadatel oprávněný subjekt (orgán státu / PO podle § 60b / podnikatel s osvědčením)?
- [ ] Odpovídá certifikovaný stav stále skutečným prostorám, technice a personálu?
- [ ] Nezaniklo osvědčení podnikatele zajišťujícího činnost (§ 56)?
- [ ] Byla opakovaná žádost podána nejméně 6 měsíců před uplynutím platnosti?
- [ ] Je při přesunu oznámeno zrušení původního pracoviště?

**Typicky rozhodné důkazy / podklady:** certifikát kryptopracoviště, dokumentace prostor a personálu, projekt fyzické bezpečnosti zabezpečené oblasti, osvědčení podnikatele a smlouva podle § 52, oznámení o zrušení/přesunu pracoviště.


<!-- LEGAL-REVISION:BEGIN id=279f725707462d1cc551 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 50 — Žádost o certifikaci kryptografického pracoviště a platnost certifikátu kryptografického pracoviště

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) O certifikaci kryptografického pracoviště písemně žádá u Národního úřadu pro kybernetickou a informační bezpečnost orgán státu, právnická osoba podle § 60b nebo podnikatel, u kterého má být kryptografické pracoviště provozováno. Žádá-li o certifikaci kryptografického pracoviště podnikatel, musí být držitelem platného osvědčení podnikatele.
>
> (2) Ten, kdo o certifikaci kryptografického pracoviště podle odstavce 1 požádal, předkládá v průběhu certifikace na žádost Národního úřadu pro kybernetickou a informační bezpečnost dokumentaci nezbytnou pro provedení certifikace.
>
> (3) Dobu platnosti certifikátu kryptografického pracoviště stanoví Národní úřad pro kybernetickou a informační bezpečnost na dobu nejdéle 3 let.
>
> (4) Platnost certifikátu kryptografického pracoviště zaniká
>
> - a) uplynutím doby jeho platnosti,
>
> - b) zánikem platnosti osvědčení podnikatele,
>
> - c) zrušením orgánu státu nebo zánikem právnické osoby podle [[#§ 60b|§ 60b]],
>
> - d) rozhodnutím Národního úřadu pro kybernetickou a informační bezpečnost o zániku platnosti certifikátu, přestalo-li být kryptografické pracoviště způsobilé pro vykonávání určených činností, nebo
>
> - e) oznámením orgánu státu, právnické osoby podle [[#§ 60b|§ 60b]] nebo podnikatele, který je držitelem certifikátu, o zrušení kryptografického pracoviště.
>
> (5) Má-li být kryptografické pracoviště využíváno i bezprostředně po uplynutí doby platnosti jeho certifikátu, je žadatel podle odstavce 1 povinen požádat Národní úřad pro kybernetickou a informační bezpečnost o certifikaci kryptografického pracoviště. Opakovaná žádost musí být Národnímu úřadu pro kybernetickou a informační bezpečnost doručena nejméně 6 měsíců před uplynutím doby platnosti původního certifikátu kryptografického pracoviště.
>
> (6) Národní úřad pro kybernetickou a informační bezpečnost je povinen rozhodnout o certifikaci kryptografického pracoviště do 6 měsíců od zahájení řízení o certifikaci, ve zvlášť složitých případech do 1 roku; nelze-li vzhledem k povaze věci rozhodnout v této lhůtě, může ji přiměřeně prodloužit ředitel Národního úřadu pro kybernetickou a informační bezpečnost, nejvýše však o 3 měsíce.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 60b

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=279f725707462d1cc551 -->

### § 51 — Certifikace stínicí komory (NÚKIB)

- Žadatel: orgán státu / PO podle § 60b / podnikatel.
- Doba platnosti: nejdéle **5 let**.
- Zánik: stejné kategorie jako u § 50.
- Opakovaná žádost: nejméně **12 měsíců** před uplynutím (delší než u jiných — fyzické zařízení vyžaduje delší přípravu rekertifikace).
- Lhůty podle § 50 odst. 6.

#### F. Kazuistika

**1. Modelová situace.** Podnikatel zřídil stínicí komoru (Faradayovu klec) pro provoz koncových zařízení zpracovávajících UI stupně Tajné tak, aby splnil požadavky TEMPEST (§ 45). NÚKIB komoru certifikoval na stupeň Tajné s dobou platnosti 5 let. Po čtyřech letech provozu se v sousedství komory provádí stavební úprava (vrtání do nosné stěny pro nové rozvody), která naruší stínicí plášť komory. Podnikatel chce komoru používat dál až do uplynutí pětileté platnosti. Důkazy: certifikát stínicí komory, protokoly o měření útlumu/útěkového vyzařování, stavební dokumentace zásahu, nové měření TEMPEST po zásahu.

**2. Právní otázka.** Trvá platnost certifikátu stínicí komory i po stavebním zásahu, který může narušit její stínicí vlastnosti, a kdy nejpozději je třeba podat opakovanou žádost?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 51 — certifikace stínicí komory NÚKIB; platnost max. 5 let; zánik shodně jako u § 50; opakovaná žádost ≥ 12 měsíců předem (delší lhůta odráží náročnost rekertifikace fyzického zařízení); lhůty podle § 50 odst. 6.
- *Související ustanovení téhož zákona:* § 45 (kompromitující vyzařování / TEMPEST), § 36 (zařízení mimo IS/KS), § 50 (certifikace kryptopracoviště — společné kategorie zániku a lhůty), § 52 (smlouva o zajištění měření).
- *Související předpisy:* vyhláška k TEMPEST/měření kompromitujícího vyzařování; standardy NATO SDIP-27 pro stínění.
- *Judikatura:* obecná zásada, že odvozené oprávnění trvá jen po dobu trvání jeho hmotných předpokladů; rozhodovací praxe ke kontrolním měřením jako podmínce platnosti.

**4. Subsumpce.** Certifikace stínicí komory osvědčuje měřením prokázané stínicí vlastnosti. Stavební zásah do pláště komory je způsobilý tyto vlastnosti narušit; certifikovaný stav pak již nemusí existovat. Formálně doba platnosti běží dál, materiálně však může předpoklad certifikace odpadnout, což odpovídá důvodu zániku „přestal být způsobilý“ (kategorie § 50 aplikované na § 51).

**5. Řešení.** Podnikatel nesmí v komoře zpracovávat UI, dokud novým měřením neprokáže zachování stínicích parametrů; jinak hrozí kompromitace. Správně: před zásahem nebo bezprostředně po něm zajistit kontrolní měření TEMPEST; při poklesu útlumu komoru z provozu vyřadit a buď ji opravit a nechat přeměřit, nebo požádat o novou certifikaci. Pro plánovanou rekertifikaci platí lhůta 12 měsíců předem — delší než u jiných certifikací právě proto, že úprava a přeměření fyzického zařízení trvá. Pokud lhůtu zmešká, riskuje provozní výpadek.

**6. Varianty.** (a) Kdyby měření po zásahu prokázalo nezměněný útlum, certifikát by trval bez nutnosti nové žádosti (jen by se doplnil protokol). (b) Kdyby žadatelem byl orgán státu a komoru fyzicky měřil podnikatel na základě smlouvy podle § 52, zánik této smlouvy/osvědčení podnikatele by se na platnosti certifikátu komory neprojevil přímo, ale ovlivnil by schopnost provádět budoucí měření.

#### G. Protiargumenty a rizika

- *Protiargument „certifikát platí 5 let bez ohledu na zásahy, dokud NÚKIB nerozhodne o zrušení“.* Neutralizace: formální doba platnosti nezhojí faktickou ztrátu stínicích vlastností; zpracování UI v komoře, která reálně neodstiňuje, je porušením povinnosti chránit UI bez ohledu na běžící lhůtu certifikátu a zakládá odpovědnost.
- *Protiargument „12měsíční lhůta na opakovanou žádost je nepřiměřeně dlouhá“.* Neutralizace: lhůta odráží technickou realitu — projekt, stavební úpravu komory a opětovné měření nelze stihnout v řádu týdnů; delší předstih chrání kontinuitu provozu.
- *Slabé místo:* zákon výslovně neupravuje povinnost přeměření po stavebním zásahu — opírá se o obecnou povinnost ochrany UI a o prováděcí předpisy; v praxi záleží na bezpečnostní dokumentaci pracoviště.

#### H. Praktický závěr

Stínicí komora je fyzické zařízení, jehož certifikace stojí na měřitelných parametrech; jakýkoli zásah do pláště je třeba posoudit jako možný důvod ztráty způsobilosti. Delší lhůta pro opakovanou žádost (12 měsíců) nutí provozovatele plánovat rekertifikaci s velkým předstihem.

**Checklist (provozovatel / NÚKIB):**
- [ ] Je žadatel oprávněný subjekt (orgán státu / PO podle § 60b / podnikatel)?
- [ ] Existuje aktuální protokol o měření stínicích vlastností odpovídající certifikovanému stavu?
- [ ] Nedošlo ke stavebnímu či technickému zásahu, jenž mohl narušit plášť komory?
- [ ] Byla opakovaná žádost podána nejméně 12 měsíců před uplynutím platnosti?
- [ ] Je provoz pozastaven, dokud nové měření nepotvrdí způsobilost?

**Typicky rozhodné důkazy / podklady:** certifikát stínicí komory, protokoly o měření útlumu / kompromitujícího vyzařování (TEMPEST), stavební dokumentace zásahů, projekt fyzické bezpečnosti, smlouva podle § 52 o zajištění měření.

---


<!-- LEGAL-REVISION:BEGIN id=a69313b87741dc6ca31e generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 51 — Žádost o certifikaci stínicí komory a platnost certifikátu stínicí komory

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) O certifikaci stínicí komory písemně žádá u Národního úřadu pro kybernetickou a informační bezpečnost orgán státu, právnická osoba podle § 60b nebo podnikatel, u kterého je stínicí komora používána.
>
> (2) Ten, kdo o certifikaci stínicí komory podle odstavce 1 požádal, předkládá v průběhu certifikace na žádost Národního úřadu pro kybernetickou a informační bezpečnost dokumentaci nezbytnou pro provedení certifikace.
>
> (3) Dobu platnosti certifikátu stínicí komory stanoví Národní úřad pro kybernetickou a informační bezpečnost na dobu nejdéle 5 let.
>
> (4) Platnost certifikátu stínicí komory zaniká
>
> - a) uplynutím doby jeho platnosti,
>
> - b) zánikem platnosti osvědčení podnikatele,
>
> - c) zrušením orgánu státu nebo zánikem právnické osoby podle [[#§ 60b|§ 60b]], nebo
>
> - d) rozhodnutím Národního úřadu pro kybernetickou a informační bezpečnost o zániku platnosti certifikátu, přestala-li být stínicí komora způsobilá k ochraně utajovaných informací.
>
> (5) Má-li být stínicí komora používána i bezprostředně po uplynutí doby platnosti jejího certifikátu, je žadatel podle odstavce 1 povinen požádat Národní úřad pro kybernetickou a informační bezpečnost o certifikaci stínicí komory. Opakovaná žádost musí být Národnímu úřadu pro kybernetickou a informační bezpečnost doručena nejméně 12 měsíců před uplynutím doby platnosti původního certifikátu stínicí komory.
>
> (6) Pro lhůty pro vydání rozhodnutí platí § 50 odst. 6.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 60b, § 50

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=a69313b87741dc6ca31e -->

### § 52 — Smlouva o zajištění činnosti

> **§ 52**
>
> *(1) Smlouva o zajištění činnosti (dále jen „smlouva“) uvedená v § 39 odst. 3, § 45 odst. 4 a § 46 odst. 14 a 15 se uzavírá na dobu určitou nebo neurčitou. Smlouva musí mít písemnou formu. Projev vůle účastníků smlouvy musí být na téže listině.*
>
> *(2) Smlouvu lze uzavřít s orgánem státu, právnickou osobou podle § 60b nebo podnikatelem na základě jejich písemné žádosti, a to pouze tehdy, budou-li činnosti, jež jsou předmětem smlouvy,*
>
> *- a) prováděny odborně způsobilými zaměstnanci státu, právnické osoby podle § 60b nebo podnikatele,*
>
> *- b) zajištěny u orgánu státu, právnické osoby podle § 60b nebo podnikatele organizačně, technicky a materiálně.*
>
> *(3) Smlouvu s podnikatelem lze dále uzavřít pouze tehdy, je-li*
>
> *- a) jeho sídlo na území České republiky,*
>
> *- b) držitelem platného osvědčení podnikatele příslušného stupně utajení; tato podmínka neplatí, má-li být uzavřena smlouva k vydávání posudku uvedená v § 46 odst. 14 a 15.*
>
> *(4) Smlouva musí obsahovat*
>
> *- a) označení účastníků smlouvy,*
>
> *- b) vymezení předmětu smlouvy a jeho rozsahu,*
>
> *- c) práva a povinnosti účastníků smlouvy,*
>
> *- d) způsob kontroly prováděné Úřadem nebo Národním úřadem pro kybernetickou a informační bezpečnost podle odstavce 6,*
>
> *- e) způsob a podmínky odstoupení účastníků od smlouvy,*
>
> *- f) souhlas se zveřejněním technického prostředku na internetových stránkách Úřadu, jde-li o smlouvu k vydávání posudku uvedenou v § 46 odst. 14.*
>
> *(5) V podmínkách podle odstavce 4 písm. e) musí být též stanoveno, že Úřad nebo Národní úřad pro kybernetickou a informační bezpečnost odstoupí od smlouvy v případě, že druhý účastník smlouvy poruší povinnost stanovenou tímto zákonem, prováděcími právními předpisy nebo uzavřenou smlouvou.*
>
> *(6) Úřad nebo Národní úřad pro kybernetickou a informační bezpečnost kontroluje, zda druhý účastník smlouvy dodržuje ustanovení tohoto zákona, prováděcích právních předpisů a uzavřené smlouvy.*
>
> *(7) Změnit obsah smlouvy lze pouze písemnou dohodou účastníků smlouvy.*
>
> *(8) Smlouvu lze vypovědět pouze písemnou formou.*
>
> *(9) Nestanoví-li tento zákon jinak, použijí se v ostatním přiměřeně ustanovení občanského zákoníku.*

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

#### F. Kazuistika

**1. Modelová situace.** Úřad uzavřel s akreditovanou laboratoří (podnikatel se sídlem v ČR, držitel platného osvědčení podnikatele) smlouvu o zajištění činnosti podle § 52 na vydávání posudků k technickým prostředkům (§ 46 odst. 14). Smlouva obsahuje souhlas se zveřejněním posuzovaných prostředků na webu Úřadu. Po roce laboratoř opakovaně poruší metodiku posuzování (vydá posudek bez předepsaných testů) a navíc jí během doby trvání smlouvy zanikne platnost osvědčení podnikatele. Druhý účastník tvrdí, že smlouvu na dobu neurčitou nelze ukončit dříve než výpovědí s výpovědní dobou. Důkazy: písemná smlouva na jedné listině, žádost podnikatele o uzavření smlouvy, doklady o odborné způsobilosti zaměstnanců, kontrolní protokoly Úřadu, doklad o zániku osvědčení podnikatele.

**2. Právní otázka.** Je Úřad oprávněn (a povinen) od smlouvy podle § 52 odstoupit pro porušení povinností druhým účastníkem, a jak se projeví zánik osvědčení podnikatele coby podmínky uzavření smlouvy?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 52 — smlouva o zajištění činnosti; písemná forma na téže listině (odst. 1); podmínky uzavření (odborná způsobilost, organizační/technické/materiální zajištění, u podnikatele sídlo v ČR a platné osvědčení — odst. 2, 3); obligatorní náležitosti vč. způsobu odstoupení (odst. 4); povinnost Úřadu/NÚKIB odstoupit při porušení (odst. 5); kontrola (odst. 6); subsidiárně občanský zákoník (odst. 9).
- *Související ustanovení téhož zákona:* § 39 odst. 3 (zkoušky), § 45 odst. 4 (měření vyzařování), § 46 odst. 14 a 15 (posudky, dílčí certifikace), § 16 a násl. (osvědčení podnikatele), § 53 (zmocnění).
- *Související předpisy:* zákon č. 89/2012 Sb., občanský zákoník (subsidiárně — § 1968 a násl. o prodlení, § 2001 a násl. o odstoupení); předpisy o akreditaci zkušebních laboratoří.
- *Judikatura:* obecná civilistická judikatura k odstoupení od smlouvy pro podstatné porušení a k mezím autonomie vůle u smíšených veřejnoprávně-soukromoprávních kontraktů.

**4. Subsumpce.** Smlouva splňuje formální podmínky (písemná, na jedné listině). Opakované porušení metodiky je porušením povinnosti stanovené zákonem/prováděcím předpisem/smlouvou ve smyslu odst. 5 — Úřad tedy nejen může, ale musí odstoupit. Zánik osvědčení podnikatele odstraňuje jednu z podmínek, za nichž smlouvu vůbec lze uzavřít (odst. 3 písm. b)); výjimka pro posudky podle § 46 odst. 14 se na povinnost mít osvědčení nevztahuje, ale ostatní podmínky trvají.

**5. Řešení.** Úřad od smlouvy odstoupí podle odst. 5 ve spojení se sjednanými podmínkami odstoupení (odst. 4 písm. e)). Odstoupení má přednost před tvrzenou nutností výpovědi — povinnost odstoupit při porušení je kogentní a smluvní ujednání ji musí reflektovat. Subsidiárně se použije občanský zákoník pro účinky odstoupení (vypořádání). Po odstoupení nesmí bývalý partner v činnosti pokračovat; již vydané posudky Úřad přehodnotí. Změna obsahu smlouvy by byla možná jen písemnou dohodou (odst. 7), výpověď jen písemně (odst. 8) — zde je však namístě odstoupení, nikoli výpověď.

**6. Varianty.** (a) Kdyby šlo o smlouvu k vydávání posudku podle § 46 odst. 14 a podnikateli zaniklo jen osvědčení (jinak plní), nemusí to být důvod odstoupení, protože pro tento typ posudku zákon platné osvědčení nevyžaduje. (b) Kdyby porušení bylo na straně Úřadu, druhý účastník může od smlouvy odstoupit podle sjednaných podmínek a subsidiárně podle občanského zákoníku, neboť jde o dvoustranný vztah.

#### G. Protiargumenty a rizika

- *Protiargument „smlouvu na dobu neurčitou lze ukončit jen výpovědí“.* Neutralizace: odst. 5 ukládá Úřadu povinnost odstoupit při porušení povinnosti; jde o zvláštní kogentní úpravu, která má přednost před obecným režimem výpovědi a před odlišným smluvním ujednáním.
- *Protiargument „subsidiarita občanského zákoníku znamená plnou smluvní volnost“.* Neutralizace: subsidiarita platí jen tam, kde ZOÚI nestanoví jinak; kogentní prvky (forma na jedné listině, povinné náležitosti, povinnost odstoupit, kontrola) volnost stran omezují.
- *Slabé místo:* hybridní povaha smlouvy (veřejnoprávní účel, soukromoprávní forma) vyvolává spory o pravomoc soudu a o použitelný procesní režim při sporu o vypořádání po odstoupení.

#### H. Praktický závěr

§ 52 umožňuje státu smluvně delegovat specializované úkoly (posudky, zkoušky, měření) na způsobilé externí subjekty, ale za přísně formalizovaných podmínek a s povinností Úřadu/NÚKIB od smlouvy odstoupit při jakémkoli porušení povinnosti druhou stranou.

**Checklist (Úřad / NÚKIB / druhý účastník):**
- [ ] Je smlouva písemná a projevy vůle na téže listině?
- [ ] Splňuje druhý účastník podmínky odst. 2 a 3 (způsobilost, zajištění, sídlo v ČR, osvědčení — kromě posudku dle § 46 odst. 14)?
- [ ] Obsahuje smlouva všechny náležitosti odst. 4 vč. způsobu kontroly a podmínek odstoupení?
- [ ] Je sjednána povinnost Úřadu/NÚKIB odstoupit při porušení (odst. 5)?
- [ ] Probíhá pravidelná kontrola plnění (odst. 6)?

**Typicky rozhodné důkazy / podklady:** písemná smlouva na jedné listině, žádost o uzavření, doklady o odborné způsobilosti a materiálním zajištění, osvědčení podnikatele, kontrolní protokoly Úřadu/NÚKIB, dokumentace porušení a úkon odstoupení.

---


<!-- LEGAL-REVISION:BEGIN id=b41f93e4d669f9f19f70 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 52 — Smlouva o zajištění činnosti

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Smlouva o zajištění činnosti (dále jen „smlouva“) uvedená v § 39 odst. 3, § 45 odst. 4 a § 46 odst. 14 a [[#§ 15|15]] se uzavírá na dobu určitou nebo neurčitou. Smlouva musí mít písemnou formu. Projev vůle účastníků smlouvy musí být na téže listině.
>
> (2) Smlouvu lze uzavřít s orgánem státu, právnickou osobou podle [[#§ 60b|§ 60b]] nebo podnikatelem na základě jejich písemné žádosti, a to pouze tehdy, budou-li činnosti, jež jsou předmětem smlouvy,
>
> - a) prováděny odborně způsobilými zaměstnanci státu, právnické osoby podle [[#§ 60b|§ 60b]] nebo podnikatele,
>
> - b) zajištěny u orgánu státu, právnické osoby podle [[#§ 60b|§ 60b]] nebo podnikatele organizačně, technicky a materiálně.
>
> (3) Smlouvu s podnikatelem lze dále uzavřít pouze tehdy, je-li
>
> - a) jeho sídlo na území České republiky,
>
> - b) držitelem platného osvědčení podnikatele příslušného stupně utajení; tato podmínka neplatí, má-li být uzavřena smlouva k vydávání posudku uvedená v § 46 odst. 14 a [[#§ 15|15]].
>
> (4) Smlouva musí obsahovat
>
> - a) označení účastníků smlouvy,
>
> - b) vymezení předmětu smlouvy a jeho rozsahu,
>
> - c) práva a povinnosti účastníků smlouvy,
>
> - d) způsob kontroly prováděné Úřadem nebo Národním úřadem pro kybernetickou a informační bezpečnost podle odstavce 6,
>
> - e) způsob a podmínky odstoupení účastníků od smlouvy,
>
> - f) souhlas se zveřejněním technického prostředku na internetových stránkách Úřadu, jde-li o smlouvu k vydávání posudku uvedenou v § 46 odst. 14.
>
> (5) V podmínkách podle odstavce 4 písm. e) musí být též stanoveno, že Úřad nebo Národní úřad pro kybernetickou a informační bezpečnost odstoupí od smlouvy v případě, že druhý účastník smlouvy poruší povinnost stanovenou tímto zákonem, prováděcími právními předpisy nebo uzavřenou smlouvou.
>
> (6) Úřad nebo Národní úřad pro kybernetickou a informační bezpečnost kontroluje, zda druhý účastník smlouvy dodržuje ustanovení tohoto zákona, prováděcích právních předpisů a uzavřené smlouvy.
>
> (7) Změnit obsah smlouvy lze pouze písemnou dohodou účastníků smlouvy.
>
> (8) Smlouvu lze vypovědět pouze písemnou formou.
>
> (9) Nestanoví-li tento zákon jinak, použijí se v ostatním přiměřeně ustanovení občanského zákoníku.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 39, § 45, § 46, § 15, § 60b

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=b41f93e4d669f9f19f70 -->

### § 53 — Zmocňovací ustanovení (certifikace)

Zmocnění k prováděcí vyhlášce: detaily žádostí, dokumentace, postup certifikace, vzory certifikátů. Zejména vyhláška č. 525/2005 Sb. (technické prostředky), č. 523/2005 Sb. (IS), č. 524/2005 Sb. (administrativní bezpečnost — částečně se vztahuje), č. 432/2011 Sb. (kryptografie).

#### F. Kazuistika

**1. Modelová situace.** Žadatel o certifikaci technického prostředku napadne zamítavé rozhodnutí Úřadu mimo jiné námitkou, že požadavky na obsah žádosti a na předkládanou dokumentaci, jež Úřad uplatnil, nemají oporu v zákoně, nýbrž jen v prováděcí vyhlášce, a že jde proto o nezákonné rozšiřování zákonných povinností podzákonným předpisem. Důkazy: žádost o certifikaci, výzva Úřadu k doplnění podle vyhlášky, znění příslušné prováděcí vyhlášky, zmocňovací ustanovení § 53.

**2. Právní otázka.** Může prováděcí vyhláška vydaná na základě § 53 stanovit konkrétní náležitosti žádosti, dokumentace a postupu certifikace, a kde leží ústavní mez tohoto zmocnění (čl. 79 odst. 3 Ústavy — sekundární, nikoli originární normotvorba)?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 53 — zmocnění k vydání prováděcí vyhlášky upravující detaily žádostí, dokumentace, postup certifikace a vzory certifikátů.
- *Související ustanovení téhož zákona:* § 46–52 (certifikace technických prostředků, IS, KS, kryptoprostředků, kryptopracovišť, stínicích komor, smlouva), na něž zmocnění navazuje.
- *Související předpisy:* vyhlášky č. 525/2005 Sb., č. 523/2005 Sb., č. 524/2005 Sb., č. 432/2011 Sb.; čl. 79 odst. 3 Ústavy (mez podzákonné normotvorby).
- *Judikatura:* konstantní linie ÚS k zákazu nálezu povinností nad rámec zákona prováděcím předpisem (např. Pl. ÚS 3/2000, Pl. ÚS 23/02) — vyhláška se musí pohybovat „secundum et intra legem“.

**4. Subsumpce.** § 53 je výslovné a obsahově ohraničené zmocnění (předmět: žádosti, dokumentace, postup, vzory). Pokud vyhláška jen konkretizuje formu a obsah toho, co zákon předpokládá (úplnost žádosti, podklady pro posouzení způsobilosti), pohybuje se intra legem. Pokud by však zaváděla zcela nové hmotné povinnosti nebo nové důvody zamítnutí bez opory v zákoně, překročila by zmocnění.

**5. Řešení.** Námitka žadatele neobstojí, drží-li se vyhláška mezí § 53 — požadavky na obsah žádosti a dokumentaci jsou typickým a přípustným předmětem prováděcí úpravy. Soud (NSS) by vyhlášku posoudil jako podklad rozhodnutí a případně by ji v rámci konkrétní kontroly ústavnosti neaplikoval jen tehdy, kdyby zjistil exces ze zmocnění. Praktický krok pro žadatele: doplnit žádost podle vyhlášky a teprve v případě zamítnutí napadat konkrétní požadavek jako excesivní.

**6. Varianty.** (a) Kdyby vyhláška stanovila např. nový samostatný důvod pro odmítnutí certifikace, který zákon nezná, byla by v této části protizákonná a soud by ji neaplikoval. (b) Kdyby zmocnění v zákoně chybělo úplně, nemohl by Úřad vyžadovat podklady jen na základě interní metodiky bez podzákonného předpisu.

#### G. Protiargumenty a rizika

- *Protiargument „vyhláška ukládá povinnosti nad rámec zákona“.* Neutralizace: rozlišuje se mezi konkretizací zákonné povinnosti (přípustné) a zaváděním nové povinnosti (nepřípustné); požadavky na formu a obsah žádosti jsou konkretizací, nikoli novou hmotnou povinností.
- *Protiargument „odkaz na více vyhlášek je nepřehledný a porušuje právní jistotu“.* Neutralizace: roztříštěnost prováděcích předpisů sama o sobě nezpůsobuje neústavnost; každá vyhláška má vlastní zmocnění a předmět.
- *Slabé místo:* u zmocňovacích ustanovení nelze argumentovat samotným § 53 — jeho aplikace vždy závisí na konkrétním znění a mezích prováděcí vyhlášky, kterou je nutné posoudit samostatně.

#### H. Praktický závěr

§ 53 sám o sobě neukládá povinnosti — je „mostem“ k prováděcím vyhláškám, které teprve stanoví detaily certifikačního procesu. Při sporu je třeba pracovat s konkrétní vyhláškou a testovat ji proti mezím zmocnění a čl. 79 odst. 3 Ústavy.

**Checklist (žadatel / Úřad / NÚKIB):**
- [ ] Které prováděcí vyhlášky se na daný typ certifikace vztahují (525/2005, 523/2005, 524/2005, 432/2011)?
- [ ] Pohybuje se uplatněný požadavek v mezích zmocnění § 53 (forma/obsah žádosti, dokumentace, postup, vzory)?
- [ ] Nezavádí vyhláška novou hmotnou povinnost či důvod zamítnutí bez opory v zákoně?
- [ ] Je žádost a dokumentace v souladu s aktuálním zněním vyhlášky?

**Typicky rozhodné důkazy / podklady:** žádost o certifikaci, výzva k doplnění, znění příslušné prováděcí vyhlášky a zmocňovacího § 53, srovnání požadavku s textem zákona.

---


<!-- LEGAL-REVISION:BEGIN id=19c5c17b9c134ff36e1b generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 53 — Zmocňovací ustanovení

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> Prováděcí právní předpis stanoví
>
> - a) náležitosti žádosti o certifikaci technického prostředku, dokumentaci nezbytnou k provedení certifikace technického prostředku, pravidla pro stanovení doby platnosti certifikátu technického prostředku, pravidla a způsob používání technického prostředku po uplynutí doby platnosti jeho certifikátu a vzor certifikátu technického prostředku,
>
> - b) náležitosti žádosti a opakované žádosti o certifikaci informačního systému, certifikaci kryptografického prostředku, certifikaci kryptografického pracoviště a certifikaci stínící komory, a dokumentaci nezbytnou k provedení certifikace informačního systému, certifikace kryptografického prostředku, certifikace kryptografického pracoviště a certifikace stínící komory,
>
> - c) způsob a podmínky provádění certifikace nebo akreditace informačního systému, certifikace kryptografického prostředku, certifikace kryptografického pracoviště a certifikace stínící komory a jejich opakování a obsah certifikační zprávy podle § 46 odst. 13,
>
> - d) vzory certifikátu informačního systému, certifikátu kryptografického prostředku, certifikátu kryptografického pracoviště a certifikátu stínící komory,
>
> - e) náležitosti žádosti o ověření způsobilosti elektrických a elektronických zařízení, zabezpečené oblasti nebo objektu k ochraně před únikem utajované informace kompromitujícím vyzařováním a způsob hodnocení jejich způsobilosti a
>
> - f) náležitosti žádosti orgánu státu, právnické osoby podle [[#§ 60b|§ 60b]] nebo podnikatele o uzavření smlouvy podle [[#§ 52|§ 52]].

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 46, § 60b, § 52

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=19c5c17b9c134ff36e1b -->

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

#### F. Kazuistika

**1. Modelová situace.** Fyzická osoba je držitelem osvědčení FO na stupeň Tajné. Po svatbě si změní příjmení. V mezidobí mezi změnou příjmení a doručením nového osvědčení s aktualizovaným jménem má vstoupit do zabezpečené oblasti a převzít dokument stupně Tajné; ostraha jí přístup odepře s tím, že její doklad totožnosti (nové příjmení) neodpovídá jménu na osvědčení (staré příjmení). V jiném sporu protistrana v soudním řízení zpochybní pravdivost údaje o stupni utajení uvedeném v osvědčení podnikatele. Důkazy: původní osvědčení FO, oddací list / doklad o změně příjmení, žádost o nové osvědčení, doklad totožnosti, samotné osvědčení podnikatele jako listina.

**2. Právní otázka.** Jaké jsou důsledky toho, že osvědčení je veřejnou listinou, pro jeho důkazní sílu a pro přístup k UI v období mezi změnou údaje a doručením nového osvědčení?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 54 — osvědčení FO a osvědčení podnikatele jsou veřejnými listinami (odst. 1); obligatorní náležitosti (odst. 2, 3) vč. nejvyššího stupně utajení a u podnikatele formy přístupu; při změně údaje Úřad bezodkladně vydá nové osvědčení a přístup k UI není dotčen do doručení nového (odst. 4).
- *Související ustanovení téhož zákona:* § 11 (osvědčení FO), § 16 (osvědčení podnikatele), § 20 (formy přístupu), § 55 (doba platnosti), § 56 (zánik, vč. doručení nového osvědčení jako důvodu zániku starého).
- *Související předpisy:* § 134 o. s. ř. (presumpce pravdivosti veřejné listiny); § 53 odst. 3 správního řádu (důkaz veřejnou listinou).
- *Judikatura:* obecná judikatura k vyvratitelné domněnce pravdivosti veřejných listin a k rozložení důkazního břemene při jejím zpochybnění.

**4. Subsumpce.** Osvědčení je veřejnou listinou (odst. 1) — zakládá vyvratitelnou domněnku pravdivosti svého obsahu (stupeň utajení, forma přístupu, doba platnosti). Změna příjmení je změnou údaje podle odst. 4; do doručení nového osvědčení zůstává přístup k UI zachován ze zákona, byť jméno na dokladu a na osvědčení dočasně nesouhlasí. Zpochybnění údaje o stupni utajení v řízení je možné, ale tíží toho, kdo proti listině brojí.

**5. Řešení.** Ostraha nesmí přístup odepřít jen pro nesoulad příjmení — odst. 4 výslovně chrání kontinuitu přístupu do doručení nového osvědčení; soulad lze doložit oddacím listem prokazujícím totožnost osoby. Po vydání nového osvědčení zaniká staré (§ 56 odst. 1 písm. k)), s 15denní ochranou přístupu při včasném poučení (§ 56 odst. 5). V soudním sporu platí, že údaj v osvědčení se má za pravdivý, dokud protistrana neprokáže opak — pouhé tvrzení nestačí.

**6. Varianty.** (a) Kdyby šlo o osvědčení podnikatele a změnila se forma přístupu (§ 20), nepostačí jen aktualizace jména — forma je obligatorní náležitostí a její změna se promítne do nového osvědčení. (b) Kdyby osoba získala nové osvědčení, ale nebyla do 15 dnů poučena, ochrana přístupu podle § 56 odst. 5 by skončila a přístup by bylo nutné obnovit poučením.

#### G. Protiargumenty a rizika

- *Protiargument „nesoulad jména na dokladu a osvědčení znamená neplatnost osvědčení“.* Neutralizace: odst. 4 výslovně zachovává přístup do doručení nového osvědčení; změna údaje nezpůsobuje neplatnost, jen povinnost Úřadu vydat aktualizovanou listinu.
- *Protiargument „veřejná listina je nevyvratitelným důkazem stupně utajení“.* Neutralizace: jde o vyvratitelnou domněnku (§ 134 o. s. ř.) — lze prokázat opak, byť důkazní břemeno nese ten, kdo listinu zpochybňuje.
- *Slabé místo:* odst. 4 chrání přístup „do doby doručení nového“, ale nestanoví výslovnou lhůtu, do kdy musí osoba o nové osvědčení požádat při běžné změně údaje — v praxi se opírá o povinnost bezodkladnosti a o návaznost na § 56.

#### H. Praktický závěr

Osvědčení FO i podnikatele jsou veřejné listiny s presumpcí pravdivosti; při změně údaje je přístup k UI chráněn až do doručení nového osvědčení, takže administrativní změna (např. příjmení) nesmí vést k bezdůvodnému odepření přístupu.

**Checklist (odpovědná osoba / ostraha / účastník řízení):**
- [ ] Obsahuje osvědčení FO všechny náležitosti odst. 2 (vč. nejvyššího stupně a doby platnosti)?
- [ ] Obsahuje osvědčení podnikatele i formu přístupu podle § 20 (odst. 3)?
- [ ] Jde o pouhou změnu údaje (odst. 4) — je přístup zachován do doručení nového osvědčení?
- [ ] Byla po vydání nového osvědčení dodržena návaznost podle § 56 (poučení do 15 dnů)?
- [ ] Při zpochybnění údaje v řízení — kdo nese důkazní břemeno vyvrácení veřejné listiny?

**Typicky rozhodné důkazy / podklady:** samotné osvědčení FO/podnikatele, doklad o změně údaje (např. oddací list), žádost o nové osvědčení, doklad totožnosti, doklad o poučení.

---


<!-- LEGAL-REVISION:BEGIN id=a89ae173f943e419b648 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 54

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Osvědčení fyzické osoby a osvědčení podnikatele jsou veřejnými listinami.
>
> (2) Osvědčení fyzické osoby obsahuje
>
> - a) jméno, příjmení, rodné příjmení,
>
> - b) den, měsíc, rok a místo narození,
>
> - c) státní občanství,
>
> - d) uvedení nejvyššího stupně utajení utajované informace, pro přístup k níž osvědčení fyzické osoby opravňuje,
>
> - e) datum vydání a dobu platnosti a
>
> - f) otisk úředního razítka a podpis oprávněného zástupce Úřadu.
>
> (3) Osvědčení podnikatele obsahuje
>
> - a) identifikaci podnikatele firmou nebo názvem a identifikačním číslem, jde-li o právnickou osobu, a jménem a příjmením nebo firmou a identifikačním číslem, jde-li o fyzickou osobu,
>
> - b) uvedení nejvyššího stupně utajení utajované informace, pro přístup k níž osvědčení podnikatele opravňuje,
>
> - c) formu přístupu podle [[#§ 20|§ 20]],
>
> - d) datum vydání a dobu platnosti a
>
> - e) otisk úředního razítka a podpis oprávněného zástupce Úřadu.
>
> (4) V případě změny některého údaje obsaženého v osvědčení fyzické osoby nebo v osvědčení podnikatele vydá Úřad bezodkladně nové osvědčení fyzické osoby nebo nové osvědčení podnikatele. Přístup k utajované informaci není do doby doručení nového osvědčení dotčen.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 20

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=a89ae173f943e419b648 -->

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

#### F. Kazuistika

**1. Modelová situace.** Zaměstnanec získá 1. 3. 2018 osvědčení FO na stupeň Přísně tajné. V roce 2022 je převeden na pozici, kde nově potřebuje přístup jen ke stupni Tajné, a odpovědná osoba se domnívá, že tím se „prodlužuje“ platnost jeho osvědčení na 10 let. Zaměstnanec v dobré víře přistupuje k UI stupně Přísně tajné i po 1. 3. 2023. Důkazy: osvědčení FO se stupněm PT a datem vydání, doklad o převedení na novou pozici, evidence přístupů k UI.

**2. Právní otázka.** Po jakou dobu platí osvědčení FO na stupeň Přísně tajné a lze tuto dobu odvozovat od stupně, který osoba aktuálně fakticky potřebuje?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 55 — platnost osvědčení FO a podnikatele činí pro Přísně tajné 5 let a pro Tajné a Důvěrné 10 let.
- *Související ustanovení téhož zákona:* § 54 (náležitosti — doba platnosti je vyznačena v osvědčení), § 56 (zánik platnosti uplynutím doby), § 9 odst. 2 (5letá periodicita u oznámení/Vyhrazené), § 22 odst. 5 (prověření trvání důvodů utajení).
- *Související předpisy:* žádné přímo; navazuje na bezpečnostní řízení podle části čtvrté zákona.
- *Judikatura:* obecná zásada, že lhůty platnosti veřejnoprávních oprávnění jsou stanoveny kogentně a nelze je dovozovat účelově.

**4. Subsumpce.** Osvědčení bylo vydáno pro stupeň Přísně tajné, k němuž se podle § 55 písm. a) váže platnost 5 let. Doba platnosti je určena nejvyšším stupněm, pro nějž bylo osvědčení vydáno, a je vyznačena přímo v osvědčení (§ 54 odst. 2 písm. e)). Pozdější faktická potřeba nižšího stupně nemění dobu platnosti zapsanou v osvědčení.

**5. Řešení.** Osvědčení na PT pozbylo platnosti uplynutím 5 let (k 1. 3. 2023), nikoli za 10 let — § 56 odst. 1 písm. a). Přístup zaměstnance k UI stupně PT po tomto datu byl bez platného osvědčení; odpovědná osoba měla včas iniciovat novou žádost. Praktický krok: pokud osoba reálně potřebuje již jen Tajné, je namístě vydat osvědčení pro stupeň Tajné (platnost 10 let) na základě nové žádosti — to však nelze zaměňovat za prodloužení původního. Po uplynutí doby je nutné zajistit, aby osoba k UI příslušného stupně neměla přístup, dokud nemá nové osvědčení.

**6. Varianty.** (a) Kdyby osvědčení bylo od počátku vydáno na stupeň Tajné, platilo by 10 let (do 2028) a problém by nevznikl. (b) Kdyby šlo o oznámení pro Vyhrazené, platí jiná, 5letá periodicita reverifikace podle § 9 odst. 2, nikoli režim § 55.

#### G. Protiargumenty a rizika

- *Protiargument „faktická potřeba nižšího stupně automaticky mění dobu platnosti na 10 let“.* Neutralizace: § 55 váže dobu na stupeň, pro který bylo osvědčení vydáno a vyznačen v listině; změna potřeby nemění zápis ani dobu — bylo by nutné nové osvědčení.
- *Protiargument „uplynutí doby je formalismus, prověrka stále platí věcně“.* Neutralizace: uplynutí doby je samostatným kogentním důvodem zániku (§ 56 odst. 1 písm. a)); věcné trvání bezpečnostní spolehlivosti je třeba znovu osvědčit v řízení, nikoli presumovat.
- *Slabé místo:* § 55 neřeší přechodné situace mezi stupni — ty je nutné dovodit ze systematiky (§ 54, § 56) a z praxe bezpečnostního řízení.

#### H. Praktický závěr

Doba platnosti osvědčení je dána stupněm, pro který bylo vydáno: 5 let pro Přísně tajné, 10 let pro Tajné a Důvěrné. Sledování data uplynutí a včasné podání nové žádosti je klíčové — uplynutím doby přístup ze zákona končí.

**Checklist (odpovědná osoba / držitel):**
- [ ] Jaký nejvyšší stupeň utajení je v osvědčení vyznačen a jaká doba platnosti z toho plyne (§ 55)?
- [ ] Je v evidenci sledováno datum uplynutí platnosti?
- [ ] Je nová žádost podána s dostatečným předstihem před uplynutím doby?
- [ ] Při změně potřebného stupně — řeší se to novou žádostí, nikoli „prodloužením“?
- [ ] Je po uplynutí doby zamezen přístup k UI příslušného stupně do vydání nového osvědčení?

**Typicky rozhodné důkazy / podklady:** osvědčení FO/podnikatele s vyznačeným stupněm a dobou platnosti, evidence platnosti, doklady k nové žádosti, evidence přístupů k UI.

---


<!-- LEGAL-REVISION:BEGIN id=1d98dfd17b8a3bf47115 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 55

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> Platnost osvědčení fyzické osoby a osvědčení podnikatele je pro stupeň utajení
>
> - a) Přísně tajné 5 let a
>
> - b) Tajné a Důvěrné 10 let.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Místní znění neobsahuje výslovný vnitřní odkaz.

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=1d98dfd17b8a3bf47115 -->

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

#### F. Kazuistika

**1. Modelová situace.** Vedoucí pracovník podnikatele (držitele osvědčení podnikatele na stupeň Tajné) má v aktovce dokumenty stupně Tajné. Aktovku mu odcizí ze zaparkovaného auta i s osvědčením FO. Pracovník krádež ohlásí téhož dne. Bezpečnostní ředitel podnikatele řeší, zda pracovník smí druhý den pokračovat v práci s UI, a do kdy je třeba požádat o nové osvědčení. Souběžně Úřad pravomocně rozhodne o zrušení platnosti osvědčení podnikatele pro ztrátu způsobilosti; podnikatel přitom drží UI poskytnutou objednatelem i UI, kterou sám vytvořil. Důkazy: oznámení o odcizení osvědčení, evidence vydaných UI, rozhodnutí Úřadu o zrušení osvědčení podnikatele a doklad o jeho vykonatelnosti, předávací protokoly o odevzdání UI.

**2. Právní otázka.** Kterým okamžikem a z jakého důvodu zaniká platnost osvědčení v případě (a) ohlášení odcizení osvědčení FO a (b) zrušení osvědčení podnikatele Úřadem, a jaké navazující povinnosti (záchranná lhůta, odevzdání UI) z toho plynou?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 56 — dvanáct důvodů zániku platnosti (odst. 1); důsledky zániku osvědčení podnikatele a FO — odevzdání UI a zamezení přístupu (odst. 2, 3); záchranná lhůta 15 dnů na novou žádost při odcizení/ztrátě/poškození a vydání nového do 5 dnů (odst. 4); ochrana přístupu při doručení nového osvědčení, je-li FO poučena do 15 dnů (odst. 5).
- *Související ustanovení téhož zákona:* § 11a (trvající mlčenlivost), § 54 (vydání nového osvědčení při změně údaje), § 56a (návaznost osvědčení vydaných různými orgány), § 123 odst. 3 a § 126 odst. 4 (zrušení osvědčení).
- *Související předpisy:* vyhláška o administrativní bezpečnosti (manipulace a odevzdání UI); trestní zákoník k případné odpovědnosti za ohrožení utajované informace.
- *Judikatura:* obecná praxe k okamžiku nabytí vykonatelnosti rozhodnutí a k povinnosti vrátit listiny po zániku oprávnění.

**4. Subsumpce.** Ohlášení odcizení osvědčení FO je důvodem zániku podle odst. 1 písm. e); zánik nastává ohlášením, nikoli teprve uplynutím lhůty. Současně se aktivuje záchranná lhůta odst. 4 — držitel může do 15 dnů požádat o nové osvědčení a přístup k UI není dotčen; Úřad vydá nové do 5 dnů. Zrušení osvědčení podnikatele Úřadem je důvodem podle písm. b) s účinky ke dni vykonatelnosti rozhodnutí; podle odst. 2 musí podnikatel odevzdat UI (poskytnutou tomu, kdo ji poskytl; vlastní produkci orgánu státu, jinak Úřadu).

**5. Řešení.** (a) Pracovník smí druhý den pokračovat v práci s UI, požádá-li včas o nové osvědčení v 15denní lhůtě (odst. 4) — přístup zůstává zachován a Úřad vydá nové do 5 dnů. (b) Po vykonatelnosti rozhodnutí o zrušení osvědčení podnikatele nesmí podnikatel s UI dále nakládat; musí ji bez prodlení odevzdat podle odst. 2. Bezpečnostní ředitel zajistí předávací protokoly a evidenci. Trvá povinnost mlčenlivosti (§ 11a) bez ohledu na zánik osvědčení.

**6. Varianty.** (a) Kdyby pracovník o nové osvědčení v 15denní lhůtě nepožádal, přístup by skončil a UI by bylo nutné mu odepřít. (b) Kdyby šlo o zánik osvědčení FO doručením nového (písm. k)), přístup by nebyl dotčen jen za podmínky poučení do 15 dnů (odst. 5) — jiný mechanismus než u odcizení.

#### G. Protiargumenty a rizika

- *Protiargument „při odcizení osvědčení přístup okamžitě končí“.* Neutralizace: odst. 4 výslovně zachovává přístup, požádá-li držitel o nové osvědčení do 15 dnů; smyslem je nepřerušit plnění úkolů kvůli ztrátě listiny.
- *Protiargument „po zrušení osvědčení podnikatele může podnikatel dokončit rozpracované zakázky s UI“.* Neutralizace: účinky nastávají vykonatelností rozhodnutí (písm. b)) a podnikatel musí UI odevzdat (odst. 2); pokračování v práci s UI by bylo nakládání bez oprávnění.
- *Slabé místo:* odst. 4 a 5 mají odlišné podmínky (žádost do 15 dnů vs. poučení do 15 dnů) — záměna lhůt a jejich účelu je v praxi častým zdrojem chyb.

#### H. Praktický závěr

§ 56 vyjmenovává taxativně důvody zániku platnosti osvědčení a k nim připíná dvě záchranné lhůty: 15 dnů na novou žádost při odcizení/ztrátě/poškození (s vydáním nového do 5 dnů) a zachování přístupu při doručení nového osvědčení, je-li FO poučena do 15 dnů. Po zániku je třeba bez prodlení odevzdat UI a zamezit přístupu; mlčenlivost trvá dále.

**Checklist (odpovědná osoba / podnikatel / Úřad):**
- [ ] Který z důvodů odst. 1 nastal a kterým okamžikem (ohlášení / vykonatelnost / doručení nového)?
- [ ] Při odcizení/ztrátě/poškození — byla podána žádost o nové osvědčení do 15 dnů (odst. 4)?
- [ ] Při doručení nového osvědčení FO — byla osoba poučena do 15 dnů (odst. 5)?
- [ ] Byla po zániku odevzdána UI správnému subjektu a zamezen přístup (odst. 2, 3)?
- [ ] Je zajištěno trvání mlčenlivosti podle § 11a?

**Typicky rozhodné důkazy / podklady:** oznámení o odcizení/ztrátě/poškození, rozhodnutí Úřadu o zrušení osvědčení a doklad o vykonatelnosti, žádost o nové osvědčení, evidence a předávací protokoly o odevzdání UI, doklad o poučení.

---


<!-- LEGAL-REVISION:BEGIN id=e39d5a837e24db16191f generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 56

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Platnost osvědčení fyzické osoby nebo osvědčení podnikatele zaniká
>
> - a) uplynutím doby jeho platnosti,
>
> - b) dnem vykonatelnosti rozhodnutí Úřadu (§ 123 odst. 3, § 126 odst. 4) o zrušení jeho platnosti,
>
> - c) úmrtím fyzické osoby, nebo byla-li prohlášena za mrtvou,
>
> - d) zrušením nebo zánikem podnikatele,
>
> - e) ohlášením jeho odcizení nebo ztráty,
>
> - f) ohlášením takového poškození, že zápisy v něm uvedené jsou nečitelné nebo je porušena jeho celistvost,
>
> - g) jde-li o osvědčení fyzické osoby vydané Úřadem
>
> - 1. vznikem služebního poměru příslušníka zpravodajské služby,
>
> - 2. převedením příslušníka bezpečnostního sboru na služební místo v Bezpečnostní informační službě nebo Úřadu pro zahraniční styky a informace,
>
> - 3. služebním zařazením vojáka na služební místo ve Vojenském zpravodajství,
>
> - 4. vznikem pracovního poměru zaměstnance zařazeného do zpravodajské služby, nebo
>
> - 5. dnem, kdy začne být fyzická osoba osobou uvedenou v § 141 odst. 1,
>
> - h) jde-li o osvědčení fyzické osoby vydané příslušnou zpravodajskou službou
>
> - 1. skončením služebního poměru příslušníka zpravodajské služby,
>
> - 2. převedením příslušníka Bezpečnostní informační služby nebo Úřadu pro zahraniční styky a informace na služební místo v jiném bezpečnostním sboru,
>
> - 3. služebním zařazením příslušníka Vojenského zpravodajství na služební místo mimo tuto zpravodajskou službu, nebo
>
> - 4. skončením základního pracovněprávního vztahu zaměstnance zařazeného do zpravodajské služby,
>
> - i) jde-li o osvědčení fyzické osoby vydané Ministerstvem vnitra, dnem, kdy přestane být fyzická osoba osobou uvedenou v § 141 odst. 1,
>
> - j) vrácením jeho držitelem tomu, kdo jej vydal,
>
> - k) dnem doručení nového osvědčení fyzické osoby, nebo
>
> - l) dnem doručení nového osvědčení podnikatele pro stejnou formu přístupu podnikatele k utajované informaci.
>
> (2) Při zániku platnosti osvědčení podnikatele podle odstavce 1 písm. a), b), d) nebo j) je podnikatel povinen utajovanou informaci, která mu byla poskytnuta, odevzdat tomu, kdo mu ji poskytl nebo do jehož oblasti věcné působnosti náleží; nelze-li tak učinit, je povinen odevzdat ji Úřadu. Utajované informace, které u podnikatele vznikly, je povinen předat orgánu státu, do jehož působnosti utajované informace náleží, není-li jej, Úřadu. Odevzdání a předání utajované informace podle tohoto odstavce je podnikatel povinen provést neprodleně po zániku platnosti osvědčení podnikatele.
>
> (3) Při zániku platnosti osvědčení fyzické osoby podle odstavce 1 písm. a), b) nebo j) je odpovědná osoba nebo ten, kdo provedl poučení, povinen zajistit, aby tato fyzická osoba neměla přístup k utajované informaci. V případě zániku platnosti osvědčení fyzické osoby podle odstavce 1 písm. j) Úřad písemně vyrozumí její odpovědnou osobu o zániku platnosti osvědčení fyzické osoby; Úřad postupuje stejně i v případě zániku platnosti osvědčení fyzické osoby podle odstavce 1 písm. k), pokud jde o osvědčení fyzické osoby vydané pro nižší stupeň utajení.
>
> (4) Pokud držitel osvědčení fyzické osoby nebo podnikatele do 15 dnů ode dne zániku jeho platnosti podle odstavce 1 písm. e) nebo f) požádá písemně Úřad o vydání osvědčení nového, přístup fyzické osoby nebo podnikatele k utajované informaci není zánikem platnosti původního osvědčení dotčen; Úřad vydá do 5 dnů od doručení žádosti osvědčení nové, které nahrazuje původní. Pokud nebude podána žádost podle věty první, postupuje Úřad podle odstavce 3 věty druhé.
>
> (5) V případě zániku platnosti osvědčení fyzické osoby podle odstavce 1 písm. k) není přístup k utajované informaci dotčen, pokud bude fyzická osoba poučena do 15 dnů ode dne tohoto zániku.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 123, § 126, § 141

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=e39d5a837e24db16191f -->

### § 56a — Návaznost osvědčení vydaných různými orgány

§ 56a řeší specifickou situaci, kdy FO **přechází** mezi orgány s různými vydavatelskými kompetencemi:
- vstoupí do zpravodajské služby nebo MV → původní osvědčení Úřadu zaniká (§ 56 odst. 1 písm. g)), nové vydá příslušná zpravodajská služba nebo MV (odst. 1),
- vystoupí ze zpravodajské služby nebo MV → původní osvědčení zaniká (písm. h), i)), nové vydá:
  - **zpravodajská služba**, vstoupí-li do jiné zpravodajské služby,
  - **MV**, stane-li se osobou podle § 141 odst. 1,
  - **Úřad** v ostatních případech (do 5 dnů od žádosti, žádost lze podat do **30 dnů** od zániku).

#### Předávání bezpečnostního svazku (odst. 4)

Orgán, jenž vydá nové osvědčení, si **písemně vyžádá bezpečnostní svazek** od předchozího vydavatele — předání do 5 dnů. Tím se zachová **kontinuita prověřování** a sníží duplicitní bezpečnostní řízení.

#### F. Kazuistika

**1. Modelová situace.** Příslušník, který byl dosud zaměstnancem civilního ministerstva s osvědčením FO vydaným Úřadem (stupeň Tajné), nastoupí do služebního poměru u zpravodajské služby. Jeho původní osvědčení Úřadu zaniká; zpravodajská služba mu má vydat nové. Po dvou letech ze zpravodajské služby odejde a vrátí se do civilní sféry mimo zpravodajské služby i mimo působnost § 141 odst. 1. O nové osvědčení požádá Úřad až 40. den po zániku osvědčení vydaného zpravodajskou službou. Důkazy: doklad o vzniku a skončení služebního poměru u zpravodajské služby, původní i navazující osvědčení, žádost o nové osvědčení s datem podání, bezpečnostní svazek.

**2. Právní otázka.** Který orgán vydává nové osvědčení při přechodu osoby mezi sférami s různou vydavatelskou kompetencí, v jaké lhůtě a s jakými důsledky pro kontinuitu přístupu, požádá-li osoba o nové osvědčení až po 30 dnech od zániku?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 56a — návaznost osvědčení vydaných různými orgány; při vstupu do zpravodajské služby/MV vydá nové osvědčení příslušný orgán (odst. 1); při výstupu vydá nové zpravodajská služba (vstup do jiné), MV (osoba podle § 141 odst. 1) nebo Úřad v ostatních případech (do 5 dnů od žádosti; žádost lze podat do 30 dnů od zániku); předání bezpečnostního svazku do 5 dnů (odst. 4).
- *Související ustanovení téhož zákona:* § 56 odst. 1 písm. g), h), i) (zánik osvědčení při změně sféry), § 11 (osvědčení FO), § 141 odst. 1 (osoby v působnosti MV).
- *Související předpisy:* zákony o zpravodajských službách (č. 153/1994 Sb., č. 154/1994 Sb., č. 289/2005 Sb.); zákon č. 361/2003 Sb. o služebním poměru příslušníků bezpečnostních sborů.
- *Judikatura:* obecná praxe k zániku a obnově veřejnoprávních oprávnění při přechodu mezi orgány a k zachování kontinuity prověřování.

**4. Subsumpce.** Vstupem do zpravodajské služby zaniká osvědčení Úřadu (§ 56 odst. 1 písm. g)) a nové vydá zpravodajská služba (§ 56a odst. 1). Výstupem zaniká osvědčení vydané zpravodajskou službou (§ 56 odst. 1 písm. h)); protože osoba nevstupuje do jiné zpravodajské služby ani se nestává osobou podle § 141 odst. 1, je k vydání nového osvědčení příslušný Úřad. Žádost je však třeba podat do 30 dnů od zániku — osoba ji podala až 40. den, tedy po lhůtě.

**5. Řešení.** Příslušný k vydání nového osvědčení je Úřad (zbytková kompetence). Úřad si písemně vyžádá bezpečnostní svazek od zpravodajské služby (předání do 5 dnů), aby navázal na dosavadní prověření a vydal nové osvědčení do 5 dnů od žádosti. Zmeškání 30denní lhůty znamená ztrátu zvláštního navazujícího režimu — osoba již nemá nárok na hladkou návaznost a o osvědčení musí být vedeno řízení standardním postupem; v mezidobí nemá přístup k UI. Praktické doporučení: žádat ihned po zániku, ideálně předem koordinovat s novým zaměstnavatelem.

**6. Varianty.** (a) Kdyby osoba ze zpravodajské služby přešla rovnou do jiné zpravodajské služby, vydala by nové osvědčení tato jiná zpravodajská služba, nikoli Úřad. (b) Kdyby se stala osobou podle § 141 odst. 1 (MV), vydalo by nové osvědčení Ministerstvo vnitra.

#### G. Protiargumenty a rizika

- *Protiargument „přechodem mezi orgány přístup k UI bez přerušení trvá automaticky“.* Neutralizace: původní osvědčení zaniká (§ 56 odst. 1 písm. g)–i)) a přístup je vázán na vydání nového osvědčení příslušným orgánem; kontinuitu zajišťuje včasná žádost a předání svazku, nikoli automatismus.
- *Protiargument „30denní lhůta je pořádková, její zmeškání nemá následek“.* Neutralizace: lhůta vymezuje zvláštní navazující režim; po jejím marném uplynutí odpadá nárok na zjednodušenou návaznost a uplatní se standardní řízení, což reálně přeruší přístup.
- *Slabé místo:* § 56a předpokládá hladké předání bezpečnostního svazku mezi orgány; spory o rozsah a aktuálnost svazku mohou návaznost fakticky zdržet.

#### H. Praktický závěr

§ 56a zajišťuje plynulé předání „prověřovací štafety“ mezi Úřadem, zpravodajskými službami a MV při přechodu osoby mezi sférami. Klíčové je podat žádost o nové osvědčení do 30 dnů od zániku a zajistit předání bezpečnostního svazku; jinak hrozí přerušení přístupu k UI.

**Checklist (osoba / nový vydavatel / předchozí vydavatel):**
- [ ] Do které sféry osoba vstupuje/vystupuje a který orgán je proto příslušný vydat nové osvědčení (odst. 1–3)?
- [ ] Byla žádost o nové osvědčení podána do 30 dnů od zániku?
- [ ] Vyžádal si nový vydavatel písemně bezpečnostní svazek (předání do 5 dnů)?
- [ ] Bylo nové osvědčení vydáno do 5 dnů od žádosti?
- [ ] Je v mezidobí ošetřen přístup k UI (nebo zamezen, není-li osvědčení)?

**Typicky rozhodné důkazy / podklady:** doklady o vzniku/skončení služebního/pracovního poměru, původní a navazující osvědčení, žádost o nové osvědčení s datem, bezpečnostní svazek a doklad o jeho předání.

---


<!-- LEGAL-REVISION:BEGIN id=8a6d9b289c44ec0f45f5 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 56a

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) V případě zániku platnosti osvědčení fyzické osoby podle § 56 odst. 1 písm. g) vydá příslušná zpravodajská služba nebo Ministerstvo vnitra této fyzické osobě nové osvědčení, které nahrazuje osvědčení původní, a to ke dni vzniku jejího služebního nebo pracovního poměru nebo ke dni, kdy se tato fyzická osoba stala osobou uvedenou v § 141 odst. 1.
>
> (2) V případě zániku platnosti osvědčení fyzické osoby podle § 56 odst. 1 písm. h) a i) vydá této fyzické osobě nové osvědčení, jež nahrazuje osvědčení původní,
>
> - a) příslušná zpravodajská služba, a to ke dni, kdy této fyzické osobě vznikl služební poměr příslušníka zpravodajské služby nebo základní pracovněprávní vztah zaměstnance zařazeného do zpravodajské služby,
>
> - b) Ministerstvo vnitra, a to ke dni, kdy se tato fyzická osoba stala osobou uvedenou v § 141 odst. 1, nebo
>
> - c) Úřad v ostatních případech, a to ke dni následujícímu po dni zániku platnosti původního osvědčení. Nové osvědčení fyzické osoby Úřad vydá na základě písemné žádosti této fyzické osoby, a to do 5 dnů ode dne doručení žádosti. Žádost o vydání nového osvědčení fyzické osoby lze podat do 30 dnů ode dne zániku platnosti původního osvědčení; přílohou žádosti musí být potvrzení příslušné zpravodajské služby nebo Ministerstva vnitra podle odstavce 3.
>
> (3) Příslušná zpravodajská služba nebo Ministerstvo vnitra potvrdí v případě postupu podle odstavce 2 písm. c) zánik platnosti osvědčení fyzické osoby na základě žádosti této fyzické osoby, a to do 5 dnů ode dne doručení žádosti. V potvrzení se uvede označení orgánu státu, který původní osvědčení fyzické osoby vydal, údaje uvedené v § 54 odst. 2 písm. a) až e) a den zániku platnosti tohoto osvědčení.
>
> (4) Orgán státu, který vydal nové osvědčení fyzické osoby, si písemně vyžádá bezpečnostní svazek této osoby od orgánu státu, který vydal původní osvědčení; bezpečnostní svazek se předá do 5 dnů ode dne doručení této žádosti.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 56, § 141, § 54

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=8a6d9b289c44ec0f45f5 -->

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

#### F. Kazuistika

**1. Modelová situace.** Český podnikatel (držitel platného osvědčení podnikatele na stupeň Tajné) má plnit subdodávku pro program NATO, v jehož rámci bude přistupovat k utajovaným informacím NATO (UI cizí moci). Mezinárodní bezpečnostní úřad NATO vyžaduje, aby podnikatel doložil osvědčení pro cizí moc (FSC for Foreign Country). Podnikatel požádá Úřad o jeho vydání současně se žádostí o vydání osvědčení podnikatele. V průběhu plnění je na celém území ČR vyhlášen nouzový stav a doba platnosti osvědčení podnikatele uplyne. Důkazy: žádost o osvědčení pro cizí moc s odůvodněním, platné osvědčení podnikatele, požadavek zahraničního partnera, doklad o vyhlášení krizového stavu, mezinárodní smlouva/závazek upravující sdílení UI s NATO.

**2. Právní otázka.** Za jakých podmínek Úřad vydá osvědčení pro cizí moc, jaký je vztah jeho platnosti k osvědčení podnikatele a jak působí krizový stav na zánik osvědčení pro cizí moc?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 57 — osvědčení pro cizí moc (PSC/FSC FCO); vydání na odůvodněnou žádost držitele platného osvědčení, je-li to v souladu s bezpečnostními a ekonomickými zájmy ČR a se závazky z mezinárodní smlouvy a neprobíhá-li řízení o zrušení; souběh s žádostí o vydání osvědčení (odst. 3); platnost nejdéle na dobu platnosti osvědčení FO/podnikatele (odst. 7); krizové prodloužení až o 12 měsíců (odst. 9); potvrzení o rozsahu ochrany u PO podle § 60b (odst. 12).
- *Související ustanovení téhož zákona:* § 11 a § 15 písm. b) (podmínky přístupu), §§ 94, 96 (žádosti o vydání osvědčení), § 56 odst. 1 písm. a) (zánik uplynutím doby), § 60b (PO).
- *Související předpisy:* mezinárodní smlouvy o vzájemné ochraně UI s NATO/EU; ústavní zákon č. 110/1998 Sb. o bezpečnosti ČR (krizové stavy); krizový zákon č. 240/2000 Sb.
- *Judikatura:* Pl. ÚS 7/09 (citováno v komentáři u § 58) — legitimním cílem je ochrana UI cizí moci a dodržení mezinárodněprávních závazků.

**4. Subsumpce.** Podnikatel je držitelem platného osvědčení a doložil odůvodněnou žádost i požadavek cizí moci — podmínky vydání osvědčení pro cizí moc jsou naplněny, je-li to v souladu se zájmy ČR a mezinárodními závazky a neběží řízení o zrušení. Souběžné podání obou žádostí spadá pod odst. 3 (Úřad postupuje neprodleně po vydání osvědčení podnikatele). Uplynutí doby osvědčení podnikatele za krizového stavu spadá pod odst. 9 — neplatnost podle § 56 odst. 1 písm. a) automaticky neznamená zánik osvědčení pro cizí moc.

**5. Řešení.** Úřad vydá osvědčení pro cizí moc, je-li splněn soulad se zájmy ČR a závazky; platnost stanoví nejdéle na dobu platnosti osvědčení podnikatele (odst. 7). Nastane-li za nouzového stavu uplynutí doby osvědčení podnikatele, osvědčení pro cizí moc nezaniká, ale platí dále až do rozhodnutí o nové žádosti, nejdéle 12 měsíců (odst. 9) — tím je zajištěna operační kontinuita účasti v programu NATO. Podnikatel by měl přesto co nejdříve podat novou žádost o osvědčení podnikatele.

**6. Varianty.** (a) Kdyby u podnikatele probíhalo řízení o zrušení osvědčení, Úřad by osvědčení pro cizí moc nevydal. (b) Kdyby šlo o PO podle § 60b, namísto osvědčení pro cizí moc by Úřad vydal časově omezené potvrzení o rozsahu ochrany UI zajištěné u této PO (odst. 12).

#### G. Protiargumenty a rizika

- *Protiargument „české osvědčení podnikatele samo o sobě stačí pro přístup k UI NATO“.* Neutralizace: požaduje-li to cizí moc, je nutné osvědčení pro cizí moc podle § 57; národní osvědčení neprokazuje vůči zahraničnímu partnerovi splnění jeho požadavků (originator control).
- *Protiargument „uplynutím platnosti osvědčení podnikatele zaniká i osvědčení pro cizí moc“.* Neutralizace: za krizového stavu platí výjimka odst. 9 — osvědčení pro cizí moc trvá až 12 měsíců do rozhodnutí o nové žádosti, aby nebyla přerušena mezinárodní spolupráce.
- *Slabé místo:* vydání závisí na neurčitých pojmech „soulad s bezpečnostními a ekonomickými zájmy ČR“ a na obsahu konkrétní mezinárodní smlouvy — posouzení je do značné míry diskreční.

#### H. Praktický závěr

Osvědčení pro cizí moc je nadstavbou národního osvědčení pro mezinárodní spolupráci; vydává se na odůvodněnou žádost držitele platného osvědčení, jeho platnost je navázána na národní osvědčení a za krizového stavu může přetrvat až o 12 měsíců déle (odst. 9).

**Checklist (podnikatel / FO / Úřad):**
- [ ] Požaduje cizí moc osvědčení pro cizí moc (PSC/FSC FCO)?
- [ ] Je žadatel držitelem platného osvědčení FO/podnikatele a neběží řízení o jeho zrušení?
- [ ] Je vydání v souladu s bezpečnostními a ekonomickými zájmy ČR a se závazky z mezinárodní smlouvy?
- [ ] Je doba platnosti omezena nejdéle na platnost národního osvědčení (odst. 7)?
- [ ] Trvá za krizového stavu osvědčení pro cizí moc i přes uplynutí národního osvědčení (odst. 9)?

**Typicky rozhodné důkazy / podklady:** odůvodněná žádost o osvědčení pro cizí moc, platné národní osvědčení, požadavek zahraničního partnera, mezinárodní smlouva o ochraně UI, doklad o vyhlášení krizového stavu.

---


<!-- LEGAL-REVISION:BEGIN id=3688f88c77bca8d413ca generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 57 — Osvědčení fyzické osoby pro cizí moc a osvědčení podnikatele pro cizí moc

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Má-li mít fyzická osoba nebo podnikatel přístup k utajované informaci cizí moci, musí splňovat podmínky podle [[#§ 11|§ 11]] nebo § 15 písm. b), a požaduje-li tak cizí moc, být též držitelem osvědčení pro cizí moc.
>
> (2) Je-li to v souladu s bezpečnostními a ekonomickými zájmy České republiky a se závazky vyplývajícími pro Českou republiku z mezinárodní smlouvy a neprobíhá-li s danou osobou řízení o zrušení platnosti osvědčení fyzické osoby nebo osvědčení podnikatele, Úřad na základě písemné odůvodněné žádosti držitele platného osvědčení fyzické osoby nebo platného osvědčení podnikatele vydává
>
> - a) osvědčení fyzické osoby pro cizí moc, nebo
>
> - b) osvědčení podnikatele pro cizí moc.
>
> (3) Pokud je žádost podle odstavce 2 podána současně s žádostí podle [[#§ 94|§ 94]] nebo [[#§ 96|96]] nebo v průběhu řízení podle části čtvrté o této žádosti, Úřad postupuje podle odstavce 2 neprodleně po vydání osvědčení fyzické osoby nebo osvědčení podnikatele.
>
> (4) Osvědčení podle odstavce 2 je veřejnou listinou.
>
> (5) Osvědčení podle odstavce 2 obsahuje náležitosti uvedené v [[#§ 54|§ 54]] s tím, že označení nejvyššího stupně utajení utajované informace, pro přístup k níž toto osvědčení opravňuje, se uvádí včetně zkratky ve smyslu § 21 odst. 2.
>
> (6) Osvědčení podle odstavce 2 potvrzuje, že u jeho držitele bylo provedeno bezpečnostní řízení podle části čtvrté a je držitelem platného osvědčení fyzické osoby nebo osvědčení podnikatele daného stupně utajení; v případě osvědčení podnikatele potvrzuje též formy přístupu podnikatele k utajované informaci podle [[#§ 20|§ 20]].
>
> (7) Osvědčení podle odstavce 2 se vydává na dobu nezbytně nutnou, nejdéle však na dobu, na kterou je vydáno osvědčení fyzické osoby nebo osvědčení podnikatele.
>
> (8) Platnost osvědčení uvedeného v odstavci 2 zaniká
>
> - a) zánikem platnosti osvědčení fyzické osoby nebo osvědčení podnikatele, nejde-li o zánik podle § 56 odst. 1 písm. e) nebo f) a fyzická osoba nebo podnikatel ve lhůtě 15 dnů požádal o vydání osvědčení nového (§ 56 odst. 4), nebo
>
> - b) z důvodů stanovených v § 56 odst. 1 písm. a), e), f) nebo j).
>
> (9) Platnost osvědčení podle odstavce 2 nezaniká z důvodu uvedeného v § 56 odst. 1 písm. a) do doby rozhodnutí o žádosti podle § 94 odst. 3 nebo § 96 odst. 3, nejdéle však po dobu 12 měsíců od uplynutí doby platnosti osvědčení, pokud byla žádost podána v době, kdy byl vyhlášen válečný stav nebo pro celé území České republiky nouzový stav nebo stav ohrožení státu (dále jen „krizový stav“), nebo byl-li krizový stav vyhlášen v průběhu řízení o této žádosti.
>
> (10) V případě změny některého údaje obsaženého v osvědčení podle odstavce 2 vydá Úřad bezodkladně nové osvědčení podle odstavce 2. Úřad do 5 dnů vydá též osvědčení podle odstavce 2, pokud držitel tohoto osvědčení do 15 dnů ode dne zániku jeho platnosti podle § 56 odst. 1 písm. e) nebo f) požádá o vydání osvědčení nového. Přístup k utajované informaci cizí moci není do doby doručení nového osvědčení podle odstavce 2 dotčen.
>
> (11) Držitel osvědčení podle odstavce 2 je povinen odevzdat je do 15 dnů Úřadu, zanikla-li
>
> - a) platnost osvědčení fyzické osoby nebo osvědčení podnikatele podle § 56 odst. 1 písm. b) nebo g) až l),
>
> - b) platnost osvědčení fyzické osoby nebo osvědčení podnikatele podle § 56 odst. 1 písm. e) a f) a v důsledku toho zanikl přístup k utajované informaci,
>
> - c) jeho platnost z důvodů stanovených v § 56 odst. 1 písm. f), nebo
>
> - d) jeho platnost doručením nového osvědčení podle odstavce 2 v souvislosti s postupem podle odstavce 8.
>
> (12) Na základě odůvodněné písemné žádosti právnické osoby podle [[#§ 60b|§ 60b]] Úřad vydá, je-li to požadavek jejího zahraničního partnera nebo cizí moci, časově omezené potvrzení o rozsahu ochrany utajovaných informací, zajištěné podle [[#§ 5|§ 5]] u právnické osoby podle [[#§ 60b|§ 60b]]. Před vydáním potvrzení Úřad v nezbytné míře ověří splnění podmínek tohoto zákona.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 11, § 15, § 94, § 96, § 54, § 21, § 20, § 56, § 60b, § 5

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=3688f88c77bca8d413ca -->

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

**Judikatura (z místních zdrojů):**

- *ÚS* [Pl.ÚS 7/09](https://nalus.usoud.cz/Search/GetText.aspx?sz=Pl-7-09_1) — nález, 4. 5. 2010
  > „smyslem přijetí napadeného ustanovení bylo omezit přístup k utajovaným informacím cizí moci osobám bez platného osvědčení. To vede k závěru, že účelem napadeného ustanovení je právně zajistit utajované informace cizí moci, a tím i dodržet závazky vyplývající z mezinárodního práva, a nikoliv krátit právo na obhajobu. … napadené ustanovení sleduje legitimní cíl, jímž je ochrana utajovaných informací cizí moci, tedy ochrana zájmů státu a mezinárodních zájmů v bezpečnostní oblasti"

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

#### F. Kazuistika

**1. Modelová situace.** V trestním řízení pro trestný čin vyzvědačství je obviněný zastoupen obhájcem. Klíčový důkaz tvoří dokumenty stupně Tajné a zčásti i utajovaná informace cizí moci (NATO). Předseda senátu zvažuje, zda a v jakém rozsahu umožní obhájci, znalci a tlumočníkovi přístup k těmto podkladům; obhájce žádá plný přístup s odkazem na právo na obhajobu, státní zástupce navrhuje přístup omezit. U UI cizí moci navíc chybí souhlas NATO s jejím zpřístupněním obhájci. Důkazy: spis s UI, poučení účastníků podle § 58 odst. 5, případný souhlas cizí moci, protokol o poučení provedeném předsedou senátu.

**2. Právní otázka.** Mají obhájce, znalec a tlumočník v trestním řízení přístup k UI bez osvědčení FO, v jakém rozsahu a za jakých podmínek, a jak se liší režim u UI cizí moci?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 58 — osoby s přístupem k UI všech stupňů bez osvědčení a poučení ex constitutione (odst. 1); rozsah po dobu výkonu funkce a v rozsahu nezbytném (odst. 2); operativní výjimky (odst. 3); procesní výjimky pro účastníky řízení podle zvláštního předpisu, v rozsahu nezbytném pro uplatnění práv a na základě poučení (odst. 4, 5); UI cizí moci jen pro vyjmenované ústavní činitele a soudce, ostatní jen po předchozím souhlasu cizí moci (odst. 6).
- *Související ustanovení téhož zákona:* § 11 (osvědčení FO), § 58a–58c (další zvláštní přístupy), § 60 (zvláštní oprávnění).
- *Související předpisy:* § 8a–8d trestního řádu (utajované skutečnosti v trestním řízení); čl. 36, 38 a 40 Listiny a čl. 6 EÚLP (spravedlivý proces, právo na obhajobu).
- *Judikatura:* Pl. ÚS 7/09 (citováno v komentáři — legitimní cíl ochrany UI cizí moci a mezinárodních závazků); dále linie ÚS k zákazu „slepých“ procesů, kde strana nezná podklad (Pl. ÚS 41/02, II. ÚS 28/03).

**4. Subsumpce.** Obhájce, znalec a tlumočník nespadají do ústavní výjimky odst. 1, ale do procesní výjimky odst. 4 — přístup k UI bez osvědčení jim umožňuje zvláštní předpis (trestní řád) v rozsahu nezbytném pro uplatnění práv a po poučení (odst. 5). U UI cizí moci však platí odst. 6: přístup mají bez dalšího jen prezident, poslanci/senátoři, členové vlády a soudci; obhájce a znalec jen po předchozím souhlasu cizí moci.

**5. Řešení.** Předseda senátu umožní obhájci, znalci a tlumočníkovi přístup k UI stupně Tajné v rozsahu nezbytném pro uplatnění práv obviněného, a to po poučení podle odst. 5 (v řízení před soudem poučuje předseda senátu). Přístup nelze plošně odepřít — vedlo by to k ústavně nepřípustnému „slepému“ procesu. U UI cizí moci (NATO) však bez předchozího souhlasu cizí moci obhájci přístup umožnit nelze (odst. 6); soud musí buď souhlas vyžádat, nebo procesně řešit, aby obhajoba nebyla zkrácena (např. nepoužitelnost takové UI jako důkazu v neprospěch obviněného). Tím se vyvažuje ochrana UI s právem na spravedlivý proces.

**6. Varianty.** (a) Kdyby šlo výhradně o národní UI bez prvku cizí moci, postačí poučení podle odst. 5 a přístup obhájce je přípustný bez dalšího souhlasu. (b) Kdyby přístup žádal sám obviněný coby účastník, posuzuje se rovněž podle odst. 4–5, ale rozsah „nezbytný pro uplatnění práv“ se vykládá s ohledem na jeho procesní postavení.

#### G. Protiargumenty a rizika

- *Protiargument „obhájce má vždy nárok na plný přístup ke všem podkladům“.* Neutralizace: přístup je dán jen v rozsahu nezbytném pro uplatnění práv (odst. 4) a u UI cizí moci je podmíněn souhlasem cizí moci (odst. 6); právo na obhajobu se poměřuje s ochranou bezpečnostních a mezinárodních zájmů (Pl. ÚS 7/09).
- *Protiargument „bez souhlasu cizí moci nelze obviněného odsoudit na základě utajeného důkazu“.* Neutralizace: tento argument je do značné míry správný — UI cizí moci, k níž obhajoba nemá přístup ani zprostředkovaně, nesmí být použita způsobem zakládajícím „slepý“ proces; soud proto buď zajistí souhlas, nebo důkaz v neprospěch obviněného nepoužije.
- *Slabé místo:* § 58 odkazuje na „zvláštní právní předpis“ (trestní řád) — rozsah přístupu se neurčuje jen ZOÚI, ale procesním kodexem; aplikace vyžaduje souběžnou znalost trestního řádu a ústavní judikatury.

#### H. Praktický závěr

§ 58 odlišuje ústavní výjimku (odst. 1 — činitelé bez prověrky) od procesní výjimky (odst. 4–5 — účastníci řízení po poučení v rozsahu nezbytném pro uplatnění práv). U UI cizí moci je okruh osob s přístupem užší a u ostatních je podmíněn souhlasem cizí moci (odst. 6). Cílem je vyvážit ochranu UI s právem na obhajobu a spravedlivý proces.

**Checklist (předseda senátu / státní zástupce / obhájce):**
- [ ] Spadá osoba do ústavní výjimky (odst. 1), nebo jde o procesní přístup účastníka (odst. 4)?
- [ ] Je přístup omezen na rozsah nezbytný pro uplatnění práv a předcházelo mu poučení (odst. 5)?
- [ ] Jde o UI cizí moci? Pokud ano, má osoba přístup podle odst. 6, nebo je nutný souhlas cizí moci?
- [ ] Kdo provádí poučení (přípravné řízení — policejní orgán/státní zástupce; před soudem — předseda senátu)?
- [ ] Nehrozí použitím utajeného důkazu „slepý“ proces v rozporu s čl. 36 a 40 Listiny?

**Typicky rozhodné důkazy / podklady:** spis obsahující UI, protokol o poučení podle odst. 5, případný souhlas cizí moci se zpřístupněním, doklad o procesním postavení osoby, příslušná ustanovení trestního řádu.

---


<!-- LEGAL-REVISION:BEGIN id=d9603079531605a48128 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 58

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Osobami, které mají přístup k utajované informaci všech stupňů utajení bez platného osvědčení fyzické osoby a poučení, jsou
>
> - a) prezident republiky,
>
> - b) poslanci a senátoři Parlamentu,
>
> - c) členové vlády,
>
> - d) veřejný ochránce práv, ochránce práv dětí a jejich zástupce,
>
> - e) soudci a
>
> - f) prezident, viceprezident a členové Nejvyššího kontrolního úřadu.
>
> (2) Osoby uvedené v odstavci 1 mají přístup k utajované informaci ode dne zvolení nebo jmenování do funkce po dobu jejího výkonu a v rozsahu nezbytném pro její výkon.
>
> (3) Přístup k utajovaným informacím bez platného osvědčení fyzické osoby lze umožnit fyzické osobě jednající ve prospěch zpravodajské služby24), informátorovi25) nebo fyzické osobě, které je poskytována zvláštní nebo krátkodobá ochrana podle zvláštního právního předpisu26), nebo příslušníku zpravodajské služby, který je zařazen v záloze zvláštní27) nebo určen do zvláštní dispozice58). Poučení této osoby provede ten, kdo jí přístup k utajované informaci umožní. Této osobě lze umožnit přístup k utajované informaci cizí moci pouze v souladu s požadavky této cizí moci.
>
> (4) Zvláštní právní předpis28) stanoví, které fyzické osoby a za jakých podmínek mají přístup k utajované informaci bez platného osvědčení fyzické osoby v trestním řízení, v občanském soudním řízení, ve správním řízení a v soudním řízení správním, a to v rozsahu nezbytném pro uplatnění jejich práv a plnění povinností v těchto řízeních. Přístup k utajovaným informacím lze v těchto případech umožnit pouze na základě poučení podle odstavce 5.
>
> (5) Poučení podle § 2 písm. i) u osob uvedených v odstavci 4 provede ten, o němž to stanoví zvláštní právní předpis28). Poučení se provede přiměřeně způsobem uvedeným v § 9 odst. 1; poučení musí dále obsahovat spisové označení věci, která je předmětem řízení, a poučení o tom, že údaje o osobách, které mají přístup k utajované informaci podle odstavce 4, jsou Úřadem evidovány a mohou být využity způsobem stanoveným tímto zákonem.
>
> (6) Osoby uvedené v odstavcích 1 a [[#§ 4|4]] nemají přístup k utajované informaci cizí moci, nejde-li o prezidenta republiky, poslance a senátora Parlamentu, člena vlády a soudce rozhodujícího ve věcech, kde se nakládá s utajovanou informací cizí moci, kteří musí být před prvním přístupem k utajované informaci cizí moci informováni o právech a povinnostech v oblasti ochrany utajovaných informací cizí moci. V trestním řízení mají přístup k utajované informaci cizí moci po předchozím souhlasu cizí moci též přísedící rozhodující ve věcech, kde se nakládá s utajovanou informací cizí moci, obviněný, zúčastněná osoba, poškozený, jejich zákonný zástupce, opatrovník, zmocněnec, důvěrník, obhájce, znalec a tlumočník, a to v rozsahu nezbytném pro uplatnění jejich práv a plnění povinností v takovém řízení. Před prvním přístupem k utajované informaci cizí moci v řízení musí být osoby podle věty druhé poučeny postupem podle odstavce 5 o právech a povinnostech v oblasti ochrany utajovaných informací cizí moci. Poučení provede v přípravném řízení policejní orgán nebo státní zástupce a v řízení před soudem předseda senátu. Poučení podepisuje fyzická osoba a ten, kdo poučení provedl; ten, kdo poučení provedl, jeden výtisk poučení předá fyzické osobě, jeden výtisk založí do spisu a kopii zašle Úřadu; kopii poučení lze Úřadu zaslat i elektronicky.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 2, § 9, § 4

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=d9603079531605a48128 -->

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

#### F. Kazuistika

**1. Modelová situace.** Státní zaměstnanec zařazený na místě, které je v přehledu podle § 69 odst. 1 písm. b) (místa s nezbytným přístupem k UI Vyhrazené), pracuje bez oznámení podle § 6 — má jen poučení. Po roce je přeřazen k jinému služebnímu úřadu, kde s UI nepracuje. Bezpečnostní ředitel původního úřadu řeší, zda dosavadní přístup k Vyhrazenému trvá a jak naložit s tím, že zaměstnanec měl přístup k UI. Souběžně jiný zaměstnanec, jenž oznámení nemá, je dočasně pověřen úkolem na místě, které v přehledu podle § 69 odst. 1 písm. b) uvedeno není, ale fakticky vyžaduje nahlédnout do UI Vyhrazené. Důkazy: služební zařazení a přehled míst podle § 69 odst. 1 písm. b), doklad o poučení, doklad o přeřazení, potvrzení mlčenlivosti podle § 11a.

**2. Právní otázka.** Za jakých podmínek mají „silové“ kategorie funkcionářů přístup k Vyhrazenému bez oznámení podle § 58a a co se stane s tímto přístupem při skončení vztahu nebo změně služebního úřadu?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 58a — přístup k UI stupně Vyhrazené bez platného oznámení po dobu trvání služebního/pracovního poměru a v rozsahu nezbytném pro jeho výkon pro příslušníky bezpečnostních sborů, státní zaměstnance, vojáky v činné službě a státní zástupce, jsou-li poučeni a zařazeni na místě/funkci uvedené v přehledu podle § 69 odst. 1 písm. b) (odst. 1); zánik při skončení vztahu/změně úřadu — má se za to, že FO není poučena, a postupuje se podle § 11a (odst. 3).
- *Související ustanovení téhož zákona:* § 6 (oznámení pro Vyhrazené), § 9 odst. 1 a 7 (poučení a jeho zánik), § 11a (potvrzení mlčenlivosti), § 69 odst. 1 písm. b) (přehled míst).
- *Související předpisy:* zákon č. 234/2014 Sb. o státní službě; zákon č. 361/2003 Sb. o služebním poměru; zákon č. 221/1999 Sb. o vojácích z povolání; zákon č. 283/1993 Sb. / 283/2021 Sb. o státním zastupitelství.
- *Judikatura:* obecná praxe k vázanosti zjednodušeného přístupu na trvání služebního poměru a na zařazení podle interního katalogu míst.

**4. Subsumpce.** Zaměstnanec spadá do kategorie „státní zaměstnanci“ (odst. 1) a byl zařazen na místě uvedeném v přehledu podle § 69 odst. 1 písm. b) a poučen — přístup k Vyhrazenému bez oznámení byl tedy oprávněný. Přeřazením k jinému služebnímu úřadu nastává situace odst. 3: má se za to, že FO není poučena; přístup končí. Druhý zaměstnanec není zařazen na místě uvedeném v přehledu — podmínka odst. 1 (zařazení na místě v přehledu) není splněna, zjednodušený přístup mu proto nesvědčí.

**5. Řešení.** U přeřazeného zaměstnance přístup k Vyhrazenému zaniká změnou služebního úřadu; protože měl přístup k UI, postupuje se podle § 11a — zajistí se potvrzení trvající mlčenlivosti. U druhého zaměstnance nelze přístup opřít o § 58a, neboť jeho místo není v přehledu podle § 69 odst. 1 písm. b); pokud má reálně přistupovat k Vyhrazenému, je nutné buď doplnit jeho místo do přehledu, nebo zajistit oznámení podle § 6 (případně zvláštní přístup). Bez toho mu přístup umožnit nelze.

**6. Varianty.** (a) Kdyby zaměstnanec přešel na jiné místo téhož úřadu, které je rovněž uvedeno v přehledu, přístup by mohl pokračovat při zachování poučení. (b) Kdyby šlo o přístup k vyššímu stupni než Vyhrazené, § 58a se neuplatní vůbec — pro Důvěrné a výše je nutné osvědčení FO (§ 11).

#### G. Protiargumenty a rizika

- *Protiargument „služební poměr sám o sobě zakládá přístup k Vyhrazenému“.* Neutralizace: kromě příslušnosti k jedné ze čtyř kategorií je nutné poučení a zařazení na místě/funkci uvedené v přehledu podle § 69 odst. 1 písm. b); samotný poměr nestačí.
- *Protiargument „přeřazením k jinému úřadu přístup automaticky pokračuje“.* Neutralizace: odst. 3 stanoví, že se má za to, že FO není poučena; přístup zaniká a aplikuje se § 11a — pokračování by vyžadovalo nové splnění podmínek u nového zařazení.
- *Slabé místo:* funkčnost § 58a stojí na aktuálnosti přehledu míst podle § 69 odst. 1 písm. b); je-li přehled neúplný nebo neaktuální, přístup buď chybí tam, kde je potřeba, nebo přetrvává neoprávněně.

#### H. Praktický závěr

§ 58a je administrativní úlevou pro příslušníky bezpečnostních sborů, státní zaměstnance, vojáky a státní zástupce: k Vyhrazenému přistupují bez oznámení, jsou-li poučeni a zařazeni na místě uvedeném v přehledu podle § 69 odst. 1 písm. b). Přístup je vázán na trvání poměru a konkrétní zařazení; skončení nebo změna úřadu jej ukončuje (§ 11a).

**Checklist (bezpečnostní ředitel / služební úřad):**
- [ ] Spadá osoba do některé ze čtyř kategorií odst. 1?
- [ ] Je osoba poučena a zařazena na místě/funkci uvedené v přehledu podle § 69 odst. 1 písm. b)?
- [ ] Je přístup omezen jen na stupeň Vyhrazené a na rozsah nezbytný pro výkon poměru?
- [ ] Při skončení vztahu/změně úřadu — je uplatněn § 11a (potvrzení mlčenlivosti)?
- [ ] Je přehled míst podle § 69 odst. 1 písm. b) aktuální?

**Typicky rozhodné důkazy / podklady:** služební/pracovní zařazení, přehled míst podle § 69 odst. 1 písm. b), doklad o poučení, doklad o skončení/změně poměru, potvrzení mlčenlivosti podle § 11a.

---


<!-- LEGAL-REVISION:BEGIN id=3143f0039c64e45e1e68 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 58a

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Osobami, které mají přístup k utajované informaci stupně utajení Vyhrazené bez platného oznámení po dobu trvání služebního nebo pracovního poměru a v rozsahu nezbytném pro jeho výkon, jsou
>
> - a) příslušníci bezpečnostních sborů,
>
> - b) státní zaměstnanci,
>
> - c) vojáci v činné službě a
>
> - d) státní zástupci,
>
> pokud jsou poučené a zařazené na místě nebo vykonávají funkci, na kterých je nezbytné mít přístup k utajovaným informacím, a které jsou uvedené v přehledu podle § 69 odst. 1 písm. b).
>
> (2) Pro poučení osob uvedených v odstavci 1 se použije § 9 odst. 1 obdobně.
>
> (3) V případě skončení služebního nebo pracovního poměru nebo při změně služebního úřadu fyzických osob uvedených v odstavci 1 se má za to, že fyzická osoba poučena není, a v případě, že měla přístup k utajované informaci, se dále postupuje podle [[#§ 11a|§ 11a]].

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 69, § 9, § 11a

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=3143f0039c64e45e1e68 -->

### § 58b — Zvláštní oprávnění zpravodajských služeb

Zpravodajská služba může umožnit přístup k UI FO/podnikateli **bez osvědčení/oznámení**, je-li to **nezbytné**:
- a) pro plnění zákonné povinnosti FO/podnikatele,
- b) v rámci **zpravodajských operací**.

Operativní oprávnění reflektující charakter zpravodajské práce (agenturní operace, oslovování zdrojů, krycí aktivity). Postup podle § 60 odst. 2–6 se použije **obdobně** (poučení, evidence, dohled).

#### F. Kazuistika

**1. Modelová situace.** Zpravodajská služba potřebuje v rámci probíhající zpravodajské operace zapojit externí osobu (zdroj/spolupracovníka) bez osvědčení i bez oznámení a umožnit jí dílčí přístup k UI nezbytný k provedení operace. Současně jiná osoba má ze zákona povinnost (např. provozovatel kritické infrastruktury) poskytnout zpravodajské službě součinnost, k níž potřebuje seznámit se s UI. Vedoucí útvaru řeší, zda lze přístup umožnit bez standardní prověrky a jaké formality (poučení, evidence) je třeba dodržet. Důkazy: interní akt o zpravodajské operaci, doklad o zákonné povinnosti součinnosti, záznam o poučení a evidence přístupu podle § 60.

**2. Právní otázka.** Může zpravodajská služba umožnit přístup k UI bez osvědčení a oznámení, v jakých případech a za jakých procesních podmínek (poučení, evidence, dohled)?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 58b — zpravodajská služba může umožnit přístup k UI FO/podnikateli bez osvědčení/oznámení, je-li to nezbytné pro plnění zákonné povinnosti FO/podnikatele (písm. a)) nebo v rámci zpravodajských operací (písm. b)); postup podle § 60 odst. 2–6 obdobně.
- *Související ustanovení téhož zákona:* § 58 odst. 3 (operativní výjimky — agenti, informátoři), § 60 odst. 2–6 (poučení, evidence, dohled), § 11a (mlčenlivost).
- *Související předpisy:* zákon č. 153/1994 Sb. o zpravodajských službách ČR; zákony o BIS (č. 154/1994 Sb.) a ÚZSI / Vojenském zpravodajství (č. 289/2005 Sb.).
- *Judikatura:* obecná praxe k operativním výjimkám v bezpečnostní oblasti a k nezbytnosti (proporcionalitě) zásahu.

**4. Subsumpce.** Zapojení externího zdroje do zpravodajské operace odpovídá důvodu podle písm. b) (zpravodajská operace); umožnění přístupu osobě plnící zákonnou povinnost součinnosti odpovídá písm. a). V obou případech je podmínkou nezbytnost přístupu. Procesně se použije § 60 odst. 2–6 obdobně — tedy poučení, vedení evidence a výkon dohledu, byť bez plné prověrky.

**5. Řešení.** Zpravodajská služba může v obou případech přístup k UI umožnit bez osvědčení/oznámení, je-li nezbytný; provede poučení, založí evidenci přístupu a zajistí dohled (§ 60 odst. 2–6 obdobně). Rozsah přístupu musí být omezen na nezbytné minimum (need-to-know). Po skončení operace/součinnosti se uplatní mlčenlivost (§ 11a). Praktické kroky: vymezit konkrétní UI, ke které je přístup nezbytný; doložit důvod (operace/zákonná povinnost); pořídit záznam o poučení a evidenci.

**6. Varianty.** (a) Kdyby přístup nebyl pro operaci ani pro zákonnou povinnost skutečně nezbytný, oprávnění podle § 58b nelze využít — chybí podmínka nezbytnosti. (b) Šlo-li by o agenta či informátora, bylo by možné rovněž využít § 58 odst. 3; § 58b a § 58 odst. 3 se v operativní praxi doplňují.

#### G. Protiargumenty a rizika

- *Protiargument „zpravodajská výjimka obchází bezpečnostní prověrku a otevírá UI nekontrolovaně“.* Neutralizace: přístup je vázán na nezbytnost a na konkrétní důvod (operace/zákonná povinnost) a procesně podléhá § 60 odst. 2–6 (poučení, evidence, dohled); nejde o bezbřehé oprávnění.
- *Protiargument „bez osvědčení nelze nikdy umožnit přístup k UI“.* Neutralizace: § 58b je výslovnou zákonnou výjimkou reflektující povahu zpravodajské práce, kde standardní prověrka zdroje není možná ani účelná.
- *Slabé místo:* posouzení „nezbytnosti“ je interní a obtížně přezkoumatelné; kontrolu zajišťují především mechanismy dohledu nad zpravodajskými službami, nikoli běžný správní přezkum.

#### H. Praktický závěr

§ 58b dává zpravodajským službám operativní oprávnění umožnit přístup k UI bez osvědčení/oznámení tam, kde je to nezbytné pro plnění zákonné povinnosti dotčené osoby nebo pro zpravodajskou operaci, vždy však za dodržení poučení, evidence a dohledu podle § 60 odst. 2–6.

**Checklist (zpravodajská služba):**
- [ ] Je dán zákonný důvod — plnění zákonné povinnosti FO/podnikatele (písm. a)) nebo zpravodajská operace (písm. b))?
- [ ] Je přístup k UI skutečně nezbytný a omezený na nezbytné minimum (need-to-know)?
- [ ] Bylo provedeno poučení a založena evidence přístupu (§ 60 odst. 2–6 obdobně)?
- [ ] Je zajištěn dohled nad přístupem?
- [ ] Je po skončení důvodu ošetřena mlčenlivost (§ 11a)?

**Typicky rozhodné důkazy / podklady:** interní akt o zpravodajské operaci nebo doklad o zákonné povinnosti součinnosti, vymezení konkrétní UI, záznam o poučení, evidence přístupu, doklady o dohledu.

---


<!-- LEGAL-REVISION:BEGIN id=9cd6a6355d826a424d70 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 58b

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Zpravodajská služba může umožnit přístup k utajované informaci fyzické osobě, která není držitelem osvědčení fyzické osoby nebo nemá přístup k utajovaným informacím stupně utajení Vyhrazené, nebo podnikateli, který není držitelem osvědčení podnikatele nebo nemá přístup k utajovaným informacím stupně utajení Vyhrazené, je-li to nezbytné
>
> - a) pro plnění povinnosti uložené této fyzické osobě nebo podnikateli jiným právním předpisem, nebo
>
> - b) v rámci zpravodajských operací.
>
> (2) V případě přístupu k utajované informaci podle odstavce 1 se postup podle § 60 odst. 2 až 6 použije obdobně.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 60

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=9cd6a6355d826a424d70 -->

### § 58c — Zvláštní oprávnění Policie ČR

Policie může umožnit přístup k UI FO bez osvědčení/oznámení, **je-li to nezbytné** pro plnění zákonných úkolů v oblasti:
- zvláštní ochrany a pomoci (zákon č. 137/2001 Sb.),
- krátkodobé ochrany (chráněné osoby),
- zajišťování bezpečnosti chráněných objektů a prostorů (vč. určených osob),
- sledování osob a věcí (§ 158d TŘ).

**Vyloučen** je přístup k UI cizí moci a UI stupně **Přísně tajné**. Postup podle § 60 odst. 2–5 obdobně, ale poučení a záznam se Úřadu **nezasílají** — ukládají se u policie.

#### F. Kazuistika

**1. Modelová situace.** Policie ČR realizuje program zvláštní ochrany ohroženého svědka (zákon č. 137/2001 Sb.). K zajištění jeho bezpečnosti je nutné seznámit s utajovanými informacemi (operativní plán, stupeň Tajné) i externí osobu — pronajímatele konspiračního objektu, který bude prostor poskytovat. Velitel útvaru chce této osobě umožnit přístup k UI bez osvědčení/oznámení a zvažuje rozsah. Současně se objeví potřeba seznámit tutéž osobu i s informací stupně Přísně tajné a s utajovanou informací zahraničního partnera. Důkazy: doklad o zařazení do programu ochrany podle zákona č. 137/2001 Sb., vymezení UI nezbytné k zajištění ochrany, záznam o poučení a evidence vedená u policie.

**2. Právní otázka.** Může Policie ČR umožnit přístup k UI bez osvědčení/oznámení při plnění úkolů ochrany osob a objektů, na které stupně se toto oprávnění vztahuje a jak se procesně liší od režimu zpravodajských služeb?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 58c — Policie může umožnit přístup k UI bez osvědčení/oznámení, je-li to nezbytné pro plnění zákonných úkolů (zvláštní ochrana a pomoc dle zákona č. 137/2001 Sb., krátkodobá ochrana, bezpečnost chráněných objektů a prostorů vč. určených osob, sledování osob a věcí dle § 158d TŘ); vyloučen přístup k UI cizí moci a stupně Přísně tajné; postup podle § 60 odst. 2–5 obdobně, ale poučení a záznam se Úřadu nezasílají, ukládají se u policie.
- *Související ustanovení téhož zákona:* § 58 odst. 3 (zvláštní/krátkodobá ochrana — svědci, oběti), § 58b (obdobné oprávnění zpravodajských služeb), § 60 odst. 2–5 (poučení, evidence), § 11a (mlčenlivost).
- *Související předpisy:* zákon č. 137/2001 Sb. o zvláštní ochraně svědka; § 158d trestního řádu (sledování osob a věcí); zákon č. 273/2008 Sb. o Policii ČR.
- *Judikatura:* obecná praxe k operativním výjimkám a k zákazu rozšiřování přístupu nad zákonem stanovené stupně.

**4. Subsumpce.** Zajištění bezpečnosti chráněného svědka spadá pod úkoly zvláštní ochrany a pomoci (zákon č. 137/2001 Sb.) a pod bezpečnost chráněných objektů/prostorů — tedy do okruhu § 58c. Přístup pronajímatele k operativnímu plánu stupně Tajné je proto v zásadě přípustný, je-li nezbytný. Přístup k UI stupně Přísně tajné a k UI cizí moci je však § 58c výslovně vyloučen — pro tyto kategorie oprávnění nelze použít.

**5. Řešení.** Policie může pronajímateli umožnit přístup k UI stupně Tajné bez osvědčení/oznámení, je-li nezbytný pro zajištění ochrany; provede poučení a vede evidenci (§ 60 odst. 2–5 obdobně), avšak poučení a záznam Úřadu nezasílá, nýbrž ukládá u sebe. Naproti tomu k UI stupně Přísně tajné a k UI cizí moci přístup umožnit nelze — pro ně by bylo nutné standardní osvědčení, případně by se taková informace v rámci ochrany této osobě vůbec nezpřístupnila. Rozsah přístupu musí být omezen na nezbytné minimum; po skončení důvodu se uplatní mlčenlivost (§ 11a).

**6. Varianty.** (a) Kdyby šlo o sledování osob a věcí podle § 158d TŘ, oprávnění § 58c se rovněž uplatní, opět s vyloučením Přísně tajné a UI cizí moci. (b) Kdyby přístup zajišťovala zpravodajská služba, použil by se § 58b, kde uvedené stupňové vyloučení (PT, cizí moc) v této podobě není — režimy se liší.

#### G. Protiargumenty a rizika

- *Protiargument „policejní úkol ochrany ospravedlňuje přístup ke kterékoli UI“.* Neutralizace: § 58c výslovně vylučuje přístup k UI stupně Přísně tajné a k UI cizí moci; oprávnění je stupňově omezené bez ohledu na naléhavost úkolu.
- *Protiargument „poučení a evidence se musí zasílat Úřadu jako u jiných přístupů“.* Neutralizace: u § 58c se poučení a záznam Úřadu nezasílají, nýbrž ukládají u policie — to je vědomá odchylka chránící utajení samotného opatření (krycí činnost).
- *Slabé místo:* okruh úkolů odkazuje na zvláštní předpisy (zákon č. 137/2001 Sb., § 158d TŘ); přípustnost přístupu se vždy odvíjí od toho, zda konkrétní činnost pod tyto úkoly skutečně spadá.

#### H. Praktický závěr

§ 58c umožňuje Policii ČR poskytnout přístup k UI bez osvědčení/oznámení při ochraně osob a objektů a při sledování podle § 158d TŘ, avšak s pevným stropem: nikdy k UI stupně Přísně tajné ani k UI cizí moci. Poučení a evidence se vedou u policie, nikoli u Úřadu.

**Checklist (Policie ČR):**
- [ ] Spadá činnost pod některý ze zákonných úkolů uvedených v § 58c (ochrana dle zákona č. 137/2001 Sb., krátkodobá ochrana, bezpečnost objektů, sledování dle § 158d TŘ)?
- [ ] Je přístup k UI skutečně nezbytný a omezený na nezbytné minimum?
- [ ] Nejde o UI stupně Přísně tajné nebo o UI cizí moci (přístup vyloučen)?
- [ ] Bylo provedeno poučení a vedena evidence podle § 60 odst. 2–5 obdobně?
- [ ] Jsou poučení a záznam uloženy u policie (nikoli zaslány Úřadu) a je zajištěna mlčenlivost (§ 11a)?

**Typicky rozhodné důkazy / podklady:** doklad o zařazení do programu ochrany / o úkonu sledování, vymezení nezbytné UI a jejího stupně, záznam o poučení a evidence vedená u policie.

---


<!-- LEGAL-REVISION:BEGIN id=4e60b83a3f42be39b032 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 58c

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Policie může umožnit přístup k utajované informaci fyzické osobě, která není držitelem osvědčení fyzické osoby nebo nemá přístup k utajovaným informacím stupně utajení Vyhrazené, je-li to nezbytné pro plnění povinnosti uložené této fyzické osobě jiným právním předpisem v souvislosti s plněním úkolů policie v oblasti poskytování zvláštní ochrany a pomoci59), krátkodobé ochrany, zajišťování bezpečnosti chráněných objektů a prostorů a určených osob60) a provádění sledování osob a věcí61). Postup podle věty první se nepoužije v případě přístupu k utajované informaci cizí moci a utajované informaci stupně utajení Přísně tajné.
>
> (2) V případě přístupu k utajované informaci podle odstavce 1 se postup podle § 60 odst. 2 až 5 použije obdobně s tím, že písemný záznam ani poučení se Úřadu nezasílají, ale ukládají se u policie.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 60

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=4e60b83a3f42be39b032 -->

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

#### F. Kazuistika

**1. Modelová situace.** Pracovník ministerstva je držitelem osvědčení FO na stupeň Důvěrné. Je urgentně přizván do mezirezortní krizové pracovní skupiny, kde se má jednorázově seznámit s analýzou stupně Tajné (o jeden stupeň výše). Odpovědná osoba podá Úřadu písemnou žádost o souhlas s jednorázovým přístupem. Po čtyřech měsících vznikne potřeba, aby tentýž pracovník měl znovu jednorázový přístup k jiné informaci stupně Tajné v rámci pokračujícího krizového řízení. Důkazy: osvědčení FO na stupeň Důvěrné, písemná žádost odpovědné osoby, souhlas Úřadu, doklad o poučení provedeném před přístupem.

**2. Právní otázka.** Za jakých podmínek může Úřad vydat souhlas s jednorázovým přístupem k UI o jeden stupeň vyššímu a lze takový souhlas téže osobě udělit opakovaně?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 59 — na písemnou žádost odpovědné osoby může Úřad ve výjimečných a odůvodněných případech vydat souhlas s jednorázovým přístupem k UI o jeden stupeň vyššímu, na dobu nezbytně nutnou, nejdéle 6 měsíců; u podnikatele jen pro formu § 20 odst. 1 písm. b); nelze udělit dvakrát téže osobě (odst. 6); vydání neprodleně, nejpozději do 5 dnů (odst. 5), poté poučení před přístupem; u UI cizí moci jen v souladu s požadavky cizí moci (odst. 7).
- *Související ustanovení téhož zákona:* § 4 (stupně utajení), § 11 (osvědčení FO), § 20 odst. 1 písm. b) (forma přístupu podnikatele), § 59a (zvýšení o dva stupně pro orgány TŘ), § 141 odst. 1.
- *Související předpisy:* krizový zákon č. 240/2000 Sb.; ústavní zákon č. 110/1998 Sb. o bezpečnosti ČR.
- *Judikatura:* obecná zásada restriktivního výkladu výjimek z pravidla, že přístup k UI vyžaduje osvědčení odpovídajícího stupně.

**4. Subsumpce.** Pracovník má osvědčení na Důvěrné a má se seznámit s UI stupně Tajné — tedy o jeden stupeň výše, což § 59 dovoluje. Naléhavost (krizová skupina) naplňuje výjimečnost a odůvodněnost. První souhlas je proto přípustný. Druhá potřeba téhož pracovníka však naráží na odst. 6 — jednorázový přístup nelze téže osobě udělit dvakrát.

**5. Řešení.** Úřad na písemnou žádost odpovědné osoby vydá souhlas s prvním jednorázovým přístupem (neprodleně, nejpozději do 5 dnů); odpovědná osoba pak pracovníka před přístupem poučí. Pro druhou potřebu však Úřad další jednorázový souhlas téže osobě vydat nemůže (odst. 6) — opakovaná potřeba přístupu k vyššímu stupni signalizuje, že namístě je standardní cesta: podání žádosti o osvědčení FO na stupeň Tajné. Praktické doporučení: pokud je zřejmé, že přístup k Tajnému bude opakovaný, neřešit to jednorázovým souhlasem, ale rovnou iniciovat řízení o vydání osvědčení vyššího stupně.

**6. Varianty.** (a) Kdyby pracovník potřeboval přístup rovnou o dva stupně výše (z Důvěrného na Přísně tajné), § 59 to neumožňuje — povolen je jen jeden stupeň; výjimkou je § 59a pro vyjmenované orgány činné v trestním řízení. (b) Kdyby šlo o UI cizí moci, jednorázový přístup je možný jen v souladu s požadavky cizí moci (odst. 7).

#### G. Protiargumenty a rizika

- *Protiargument „jednorázový souhlas lze obnovovat, dokud trvá potřeba“.* Neutralizace: odst. 6 výslovně zakazuje udělit jednorázový přístup téže osobě dvakrát; opakovaná potřeba se řeší osvědčením, nikoli řetězením jednorázových souhlasů.
- *Protiargument „v krizi lze povolit přístup i o více stupňů“.* Neutralizace: § 59 dovoluje pouze jeden stupeň; zvýšení o dva stupně je vyhrazeno § 59a a jen pro vyjmenované orgány činné v trestním řízení za přísnějších podmínek.
- *Slabé místo:* pojmy „výjimečné a odůvodněné případy“ a „doba nezbytně nutná“ jsou neurčité; jejich naplnění posuzuje Úřad diskrečně, což ztěžuje předvídatelnost.

#### H. Praktický závěr

§ 59 je úzká operativní výjimka: na písemnou žádost odpovědné osoby Úřad ve výjimečných případech povolí jednorázový přístup o jeden stupeň výše, nejdéle na 6 měsíců a jen jednou téže osobě. Opakovaná či trvalá potřeba vyžaduje řádné osvědčení; u UI cizí moci platí originator control.

**Checklist (odpovědná osoba / Úřad):**
- [ ] Jde o přístup pouze o jeden stupeň vyšší, než na který má osoba osvědčení?
- [ ] Je dán výjimečný a odůvodněný případ a podána písemná žádost odpovědné osoby?
- [ ] Nebyl téže osobě jednorázový přístup již jednou udělen (odst. 6)?
- [ ] Je doba omezena na nezbytně nutnou, nejdéle 6 měsíců, a bylo provedeno poučení před přístupem?
- [ ] Jde-li o UI cizí moci — je přístup v souladu s požadavky cizí moci (odst. 7)?

**Typicky rozhodné důkazy / podklady:** osvědčení FO/podnikatele s vyznačeným stupněm, písemná žádost odpovědné osoby, souhlas Úřadu, doklad o poučení, případně požadavky cizí moci.

---


<!-- LEGAL-REVISION:BEGIN id=66e2b1ff587bb9d11957 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 59 — Jednorázový přístup k utajované informaci

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Na základě písemné žádosti odpovědné osoby může Úřad ve výjimečných a odůvodněných případech vydat souhlas s jednorázovým přístupem k utajované informaci se stupněm utajení o jeden vyšším, než na který je vydáno platné osvědčení fyzické osoby nebo osvědčení podnikatele, a to na dobu nezbytně nutnou, nejdéle však na dobu 6 měsíců.
>
> (2) Souhlas podle odstavce 1 lze podnikateli vydat pouze pro přístup k utajované informaci podle § 20 odst. 1 písm. b).
>
> (3) Souhlas s jednorázovým přístupem podle odstavce 1 může u příslušníků zpravodajských služeb vydat ředitel příslušné zpravodajské služby a v případech příslušníků policie podle § 141 odst. 1 ministr vnitra, a to na základě písemné žádosti příslušného služebního funkcionáře.
>
> (4) Žádost podle odstavce 1 obsahuje
>
> - a) zdůvodnění jednorázového přístupu,
>
> - b) označení oblasti utajovaných informací, ke kterým má být jednorázový přístup umožněn,
>
> - c) kopii osvědčení fyzické osoby nebo osvědčení podnikatele,
>
> - d) požadovanou dobu jednorázového přístupu a
>
> - e) v případě podnikatele písemný souhlas poskytovatele utajované informace s vydáním souhlasu podle odstavce 1.
>
> (5) Úřad vydá souhlas podle odstavce 1 neprodleně, nejpozději do 5 dnů ode dne doručení žádosti. Odpovědná osoba nebo jí pověřená osoba, která po vydání souhlasu Úřadu umožní přístup fyzické osoby k utajované informaci podle odstavce 1 nebo [[#§ 3|3]], provede její poučení.
>
> (6) Na udělení souhlasu k jednorázovému přístupu k utajované informaci není právní nárok a lze jej téže osobě udělit jen jednou.
>
> (7) K utajované informaci cizí moci lze jednorázový přístup umožnit pouze v souladu s požadavky této cizí moci.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 20, § 141, § 3

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=66e2b1ff587bb9d11957 -->

### § 59a — Operativní zvýšení o dva stupně pro orgány TŘ

Speciální výjimka pro:
- osoby služebně činné v policejním orgánu,
- státní zástupce jako orgány činné v trestním řízení,
- státní zástupce plnící úkoly podle jiného předpisu.

Úřad může vydat souhlas s přístupem k UI **až o dva stupně vyšší**, než pro nějž má FO osvědčení.

Pro osobu **služebně činnou v policejním orgánu** musí být žádost doplněna **souhlasným stanoviskem dozorujícího státního zástupce**; u UI **Přísně tajné** též stanoviskem **vedoucího státního zástupce nejblíže vyššího státního zastupitelství**. Tato kaskádová kontrola reflektuje princip **soudního dozoru nad orgány policie v trestním řízení**.

#### F. Kazuistika

**1. Modelová situace.** V přípravném řízení o závažné organizované trestné činnosti potřebuje vyšetřovatel — osoba služebně činná v policejním orgánu, držitel osvědčení FO na stupeň Důvěrné — nahlédnout do utajovaných podkladů jiného orgánu, jež jsou klasifikovány stupněm Přísně tajné (tedy o dva stupně výše). O souhlas s přístupem požádá Úřad. K žádosti připojí stanovisko dozorujícího státního zástupce, ale opomene stanovisko vedoucího státního zástupce nejblíže vyššího státního zastupitelství. Důkazy: osvědčení FO vyšetřovatele na stupeň Důvěrné, žádost o souhlas, stanovisko dozorujícího státního zástupce, podklady stupně Přísně tajné, doklad o pověření v trestním řízení.

**2. Právní otázka.** Může Úřad povolit orgánu činnému v trestním řízení přístup k UI až o dva stupně vyšší, a jaké souhlasy musí žádost obsahovat, jde-li o osobu služebně činnou v policejním orgánu a o UI stupně Přísně tajné?

**3. Použitelné právo.**
- *Komentované ustanovení:* § 59a — Úřad může vydat souhlas s přístupem k UI až o dva stupně vyšší pro osoby služebně činné v policejním orgánu, státní zástupce jako orgány činné v trestním řízení a státní zástupce plnící úkoly podle jiného předpisu; pro osobu služebně činnou v policejním orgánu je nutné souhlasné stanovisko dozorujícího státního zástupce a u UI Přísně tajné též stanovisko vedoucího státního zástupce nejblíže vyššího státního zastupitelství.
- *Související ustanovení téhož zákona:* § 4 (stupně utajení), § 11 (osvědčení FO), § 59 (jednorázový přístup o jeden stupeň — obecný režim).
- *Související předpisy:* trestní řád (postavení policejního orgánu a dozor státního zástupce — § 174 TŘ); zákon č. 283/1993 Sb. / 283/2021 Sb. o státním zastupitelství (soustava a vztahy nadřízenosti).
- *Judikatura:* obecná praxe k dozoru státního zástupce nad přípravným řízením a k restriktivnímu výkladu výjimek umožňujících přístup k vyšším stupňům UI.

**4. Subsumpce.** Vyšetřovatel je osobou služebně činnou v policejním orgánu a jde o trestní řízení — spadá do okruhu § 59a. Požadovaný přístup je o dva stupně vyšší (z Důvěrného na Přísně tajné), což § 59a umožňuje (na rozdíl od § 59, který povoluje jen jeden stupeň). U osoby služebně činné v policejním orgánu je však nutné stanovisko dozorujícího státního zástupce a u stupně Přísně tajné navíc stanovisko vedoucího státního zástupce nejblíže vyššího státního zastupitelství — druhé z nich v žádosti chybí.

**5. Řešení.** Žádost není v dané podobě úplná: u UI stupně Přísně tajné musí být doplněna jak stanovisko dozorujícího státního zástupce, tak stanovisko vedoucího státního zástupce nejblíže vyššího státního zastupitelství. Úřad bez druhého stanoviska souhlas vydat nemůže; vyšetřovatel (resp. policejní orgán) musí stanovisko doplnit. Po doplnění a vydání souhlasu následuje poučení před přístupem. Tato kaskáda souhlasů zajišťuje, že rozšířený přístup policejního orgánu k nejcitlivějším informacím podléhá dozoru státního zastupitelství.

**6. Varianty.** (a) Kdyby žadatelem byl sám státní zástupce jako orgán činný v trestním řízení (nikoli osoba služebně činná v policejním orgánu), požadavek na stanoviska dozorujícího/nadřízeného státního zástupce by se neuplatnil v téže podobě — kaskádová kontrola míří na policejní orgán. (b) Kdyby šlo o UI stupně Tajné (nikoli Přísně tajné), postačilo by stanovisko dozorujícího státního zástupce, bez stanoviska vedoucího státního zástupce vyššího státního zastupitelství.

#### G. Protiargumenty a rizika

- *Protiargument „§ 59a je jen zvláštním případem § 59, platí proto i strop jednoho stupně“.* Neutralizace: § 59a je samostatná výjimka výslovně dovolující přístup až o dva stupně; jde o lex specialis vůči § 59, nikoli o jeho pouhou aplikaci.
- *Protiargument „stanovisko dozorujícího státního zástupce postačí i u Přísně tajné“.* Neutralizace: u stupně Přísně tajné zákon vyžaduje i stanovisko vedoucího státního zástupce nejblíže vyššího státního zastupitelství; jeho absence brání vydání souhlasu.
- *Slabé místo:* § 59a rozlišuje mezi „osobou služebně činnou v policejním orgánu“ a „státním zástupcem“ s odlišnými procesními požadavky — záměna těchto kategorií vede k vadné žádosti.

#### H. Praktický závěr

§ 59a je nejširší výjimkou ze stupňového omezení přístupu — dovoluje orgánům činným v trestním řízení přístup až o dva stupně výše. U osob služebně činných v policejním orgánu je však podmíněna kaskádou souhlasů státního zastupitelství: vždy stanovisko dozorujícího státního zástupce a u stupně Přísně tajné navíc stanovisko vedoucího státního zástupce nejblíže vyššího státního zastupitelství.

**Checklist (policejní orgán / státní zástupce / Úřad):**
- [ ] Spadá žadatel do okruhu § 59a (osoba služebně činná v policejním orgánu / státní zástupce v trestním řízení / státní zástupce dle jiného předpisu)?
- [ ] Jde skutečně o přístup nejvýše o dva stupně vyšší, než na který má osoba osvědčení?
- [ ] U osoby služebně činné v policejním orgánu — je připojeno stanovisko dozorujícího státního zástupce?
- [ ] Jde-li o UI stupně Přísně tajné — je připojeno i stanovisko vedoucího státního zástupce nejblíže vyššího státního zastupitelství?
- [ ] Bylo po vydání souhlasu provedeno poučení před přístupem?

**Typicky rozhodné důkazy / podklady:** osvědčení FO žadatele, žádost o souhlas, stanovisko dozorujícího státního zástupce (a u Přísně tajné stanovisko vedoucího státního zástupce vyššího státního zastupitelství), doklad o pověření v trestním řízení, doklad o poučení.

---


<!-- LEGAL-REVISION:BEGIN id=65a7dd5bd3b7ae4a83c5 generator=2026-07-17.4 source_sha256=a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36 -->
#### Revizní doplnění k § 59a

> Revize: 17. 7. 2026 | Znění předpisu k: verze místního zdroje účinná od 1. 7. 2025 (ověřeno pouze v místním souboru; online aktuálnost ⚠️ [NEOVĚŘENO]) | Stav: koncept
>
> Místní zdroj: `../Documents/Obsidian Vaults/Production 2026-05-12/Czech Law/e-Sbirka/2005/412-2005 Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti.md`; identifikátor verze: `SB-2005-00412_2025-07-01`; SHA-256: `a4e25c252066a006c80900f96c5bdeee17bffa915b5e00ee4a058823e31b9b36`.

##### Znění ustanovení

> (1) Na základě písemné žádosti odpovědné osoby může Úřad ve výjimečných a odůvodněných případech vydat souhlas s přístupem k utajované informaci se stupněm utajení až o dva vyšším, než na který je vydáno platné osvědčení fyzické osoby, a to osobě služebně činné v policejním orgánu, státnímu zástupci jako orgánu činnému v trestním řízení nebo státnímu zástupci plnícímu v trestním řízení úkoly podle jiného právního předpisu62), neprobíhá-li s danou osobou řízení o zrušení platnosti osvědčení fyzické osoby.
>
> (2) Žádost podle odstavce 1 pro osobu služebně činnou v policejním orgánu musí být doplněna souhlasným stanoviskem státního zástupce, který vykonává dozor nad zachováváním zákonnosti v přípravném řízení, a v případě utajované informace stupně utajení Přísně tajné musí být doplněna též souhlasným stanoviskem vedoucího státního zástupce nejblíže vyššího státního zastupitelství.
>
> (3) Žádost podle odstavce 1 pro státního zástupce v případě utajované informace stupně utajení Přísně tajné musí být doplněna souhlasným stanoviskem vedoucího státního zástupce nejblíže vyššího státního zastupitelství, s výjimkou státního zástupce činného u Nejvyššího státního zastupitelství.
>
> (4) Žádost podle odstavce 1 obsahuje
>
> - a) zdůvodnění přístupu,
>
> - b) označení utajované informace, ke které má být souhlas s přístupem vydán,
>
> - c) spisové označení věci, která je předmětem trestního řízení, a
>
> - d) kopii osvědčení fyzické osoby, které má být souhlas podle odstavce 1 vydán.
>
> (5) Úřad vydá souhlas podle odstavce 1 neprodleně, nejpozději do 5 dnů ode dne doručení žádosti, a jen na dobu nezbytnou pro účast fyzické osoby v trestním řízení.
>
> (6) Odpovědná osoba nebo jí pověřená osoba provede poučení fyzické osoby a zajistí založení písemného záznamu o jejím poučení do trestního spisu a zaslání kopie poučení do 30 dnů ode dne poučení Úřadu; kopii poučení lze Úřadu zaslat i elektronicky.
>
> (7) Souhlas podle odstavce 1 zaniká dnem následujícím po dni, kdy skončila účast fyzické osoby v trestním řízení, nejpozději však dnem zániku platnosti osvědčení fyzické osoby podle § 56 odst. 1.
>
> (8) K utajované informaci cizí moci lze souhlas podle odstavce 1 vydat pouze v souladu s požadavky této cizí moci.

##### Přehled výkladu

- [1] Provenience a meze automatického doplnění
- [2] Nutná ruční právní revize
- [3] Stav citací původního komentáře

##### Souvisící ustanovení

- Výslovné vnitřní odkazy v místním znění: § 56

##### Souvisící předpisy

- Místní znění neobsahuje výslovnou citaci jiného předpisu.

##### Z důvodové zprávy

⚠️ [NEOVĚŘENO] Místní soubor [DUVODOVA-ZPRAVA.md](DUVODOVA-ZPRAVA.md) existuje, ale konkrétní pasáž nebyla automaticky přiřazena k tomuto ustanovení.

##### Literatura

⚠️ [NEOVĚŘENO] Automatické doplnění literatury nebylo provedeno; v místním korpusu nebyl pro tuto jednotku ověřen bibliografický pramen.

##### Výklad

[1] Tento automatický blok dokládá pouze identitu místního pramene a mechanicky převzaté znění. Neobsahuje samostatný závěr o výkladu ustanovení.
[2] Jazykový, systematický, historický a teleologický výklad, procesní dopady, důkazní břemeno, lhůty a sporné otázky musí být doplněny a dvakrát oponovány nad konkrétními místními prameny; do té doby je stav výslovně jen koncept.
[3] Citace judikatury a literatury v původním komentáři nebyly tímto mechanickým doplněním jednotlivě ověřeny. Pro účely této revize jsou proto ⚠️ [NEOVĚŘENO], ledaže jejich ověření výslovně dokládá samostatný kurátorovaný blok nebo revizní zpráva.

##### Judikatura

⚠️ [NEOVĚŘENO] Judikatura nebyla automaticky doplněna; shoda klíčového slova není ověřením právní věty ani použitelnosti rozhodnutí.

<!-- LEGAL-REVISION:END id=65a7dd5bd3b7ae4a83c5 -->

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

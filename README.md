
# Drón jogosítvány jegyzet

- [Bevezető](#bevezető)
- [Weboldalak](#weboldalak)
- [Tananyag](#tananyag)

## Bevezető

Ezt a jegyzetet saját magamnak készítettem a A1/A3 drón jogosítvány megszerzéséhez.

>Ez a jegyzet nem egy hivatalos tananyag, nem garantálja az vizsga teljesítését.

A jogosítványt az ausztriai légiforgalmi szolgálatnál (Astro Control) tettem le online, angol nyelven. Ezt ajánlom neked is, ha nincs kedved fizetni a vizsgáért.

## Weboldalak

Az [Astro Control Drone Space](https://dronespace.at) weboldala tök jól leír mindent.

- [Astro Control tananyag](https://online-kurs.dronespace.at/online-kurs/lehrmaterial/): ez csak németül elérhető, de egy böngésző neked lefordítja bármire
- [Astro Control gyakorló feladatok](https://online-kurs.dronespace.at/online-kurs/uebungsaufgaben/): a teszt megoldásához kiválasztható az angol nyelv

# Tananyag

A tananyag 5 részből áll

- [Bevező](#bevezető-1)
- [Légi jog és biztonság](#légi-jog-és-biztonság)
- [Emberi tényezők és korlátaik](#emberi-tényezők-és-korlátaik)
- [Üzemeltetési eljárások](#üzemeltetési-eljárások)
- [Műszaki alapok](#műszaki-alapok)

![Alt text](./Kepek/struktura.svg)

# Bevezető

Miért kell a drón jogosítvány? Mert exponenciálisan nő a drónok száma, nem csak speciális (katonai) esetekben. Erre kellett választ találnia az EASA-nak (európai repülésbiztonsági szervezet) és a nemzeti légiforgalmi irányítoknak.

Emellett nyilván nem elhanyagolhatóak egyéb tényezők, mint például a drónok keltette zaj, akár vizuális zaj (fel alá repkednek), vagy a magánszéfra (privacy) megsértése, például berepül a telkedre.

-> Ezekre a megoldás a szabályzás: képzés majd vizsga

Fontos: onanntól kezdve hogy felszálltál egy drónnal a légi közlekedés résztvevője vagy, így rád is vonatkoznak az aktuális szabályok.

## Definíciók

### Automata üzemmód

Olyan üzemmódok, amely során a drón egy automata műveletet hajt végre, de lehetőség van a manuális beavatkozásra. 

Például "return to home", automatic landing, stabilizálás.

### Autonóm üzemmód
Autonóm üzemmód során a drón teljesen önállóan cselekszik, nem feltétlen van lehetőség a beavatkozásra.

Az OPEN kategóriába ilyen drónok nem esnek.

### Érintett személy

Azok az emberek akik segítik a drón üzemelését. A felelősségi körök kiterjedhetnek 
- a légtér figyelésre (airspace observation)
- kommunikációra (communication)
- a fel és leszállási terület biztosítása (securing the take-off and landing site)

Fontos, hogy az érintett személyeket részletese utasításokkal lássuk el, illetve tisztázzuk velük a felelősségi köröket (ki mire figyel, mit csinál) egy kisebb megbeszélés során a felszállás előtt.

### BVLOS

BVLOS (“Beyond Visual Line Of Sight”) a vízuális látóhatáron túl (nem látod).

OPEN kategóriában nem engedélyezett

### Repülési magasságok

Több magasság is létezik.

#### AGL ("Above Ground Level")

Föld feletti magasság. Adott pontban értelmezhető. Egy hegyes terepen ez hamar elég bizarr tud lenni, pl. ha elszáll az ember egy szakadék mellett hirtelen felugrik a AGL magasság.

#### MSL ("Mean Sea Level")

Tengerszint feletti magasság. Ez egy általánosabb magasság adat (egyébként egy nyomásértéket szokott jelenteni). 

### FPV 

"First Person View": belső nézet. Repülés esetén azt jelenti, hogy a drónon egy kamera van elhelyeztve és a kezelő egy VR szeműveg segítségével látja, hogy mi történik a drónnal, merre halad. 

Az FPV VLOS-nak számít, lévén a drón egy direkt vizuális összeköttetésben áll az üzemelővel.

### Földrajzi zónák

A légtér felvan osztva több zónára, attól függően hogy a légiirányítási szolgálat engedélyezi, korlátozza, vagy megtiltja a drón használatot.

Csak ott lehet drónnal repkedni ahol nincs ideiglenesen korlátozva, vagy teljesen megtiltva. 

Pilótaként a te felelősséged, hogy a megfelelő zónában repülj, így naprakésznek kell lenni a zónákkal kapcsolatban. Ezek az információk közzé vannak téva a légiirányítási szolgálat által.

### Súly

Repüléstechnikában több tömeg is meg van határozva, viszont a legfontosabb a "maximális felszállási tömeg" (MTOM - Maximum Take-off Mass), ami magában foglalja az üzemanyagot, illetve a hasznos terhet (payload). Ezt a gyártó megadja minden drón esetén és a rendszer soha nem lépheti át ezt a tömeget.

### Tömeg (mint emberek)

Azok az emberek, akik annyira sűrűn állnak, hogy nem tudnak könnyedén és gyorsan arrébb mozdulni (egy kis utcában 20 ember is tömegnek számít, míg egy nagy mezőn akár 100 ember se).

Ennek az állapotnak a megítélése nehéz lehet nagyobb távolságból (vagy amúgy is, ki mennyire mozgékony), ezért legyünk mindig elővigyázatosak.

### Hasznos teher

Minden olyan dolog, ami nem szükséges ahhoz hogy műkődjön a drón. Motorok, akksi, propeller, váz, szükséges kommunikáció / vezérlő nem számít hasznos tehernek. Egyéb dolgok, mint pl. kamera, vagy egyébb opcionális dolgok viszont annak számítanak, attól függetlenül, hogy könnyen eltávolítható-e a drónról vagy nem.

### UAS ("Unmanned aerial system") / Drón

Az UAS kifejezés letakaraja magát a drónt, viszont mivel rendszer, ezért bele tartozik például az irányítás is.

### Nem tájékoztatott emberek/nem bevont emberek (Uninvolved persons)

Azok az emberek, akik nem használnak drónt, és/vagy nem tudnak a drónhasználat lépéseiről és szabályairól (egységsugarú ember). Az nem lényeges, hogy ki vannak-e téve közvetlen vagy közvetve a drón repülés hatásainak vagy nem. 

Nem bevont emberek esetén sokkal szigurúbb szabályok vonatkoznak, amelyekre mindig figyelemmel kell lenni pilótaként.


### VLOS ("Visual Line Of Sight”)

Vizuális látóhatár: látod közvetlenül a drónt. OPEN kategória esetén csak ilyen repülés engedélyezett.

A VLOS nem egy elméleti látóhatárt jelent, hanem gyakorlati látóhatárt, például ködben ez csak pár méter.

# Légi jog és biztonság

- [UAS kategóriák](#uas-kategóriák)
- [Repülés adminisztráció és alap szabályok](#repülés-adminisztráció-és-alap-szabályok)
- [Légterek és korlátozások](#légterek-és-korlátozások)
- [Biztonságos repülés és felelősségek](#biztonságos-repülés-és-felelősségek)
- [Biztonság, magánszféra, biztosítás (Securtiy, Privacy, Insurance)](#biztonság-magánszféra-biztosítás-securtiy-privacy-insurance)

## UAS kategóriák

Pilóta nélküli repülőgépnek (unmanned aerial vehicle - UAV) számít minden olyan repülőgép, amelyet nem egy a fedélzeten tartozkodó pilóta irányít. Ez jelentheti azt, hogy a drón önvezető (autónom), vagy egy távoli pilató vezérli a megfelelő távirányítással.

Lehetséges az az eset, hogy a pilóta nélküli repülőgépnek vannak utasai, ezeket pilóta nélküli rendszereknek (Unmanned Aircraft System - UAS) nevezzük.

### UAS osztályok

Az EASA szabályozása alá eső drónok három kategóriába vannak sorolva

- Nyitott (**OPEN**)
- Speciális (**SPECIFIC**)
- Regisztráció köteles (**CERTIFIED**)

Az EASA szabályozás alá nem eső drónok

- A beltéren üzemeltetett drónok (mini drón a nappaliban)
- Rendőrség, tűzoltóság, egyéb hivatalos szervek által használt drónok

#### Besorolás

Az **OPEN** kategóriába esik az a drón, ami

- Könnyebb mint 25 kg
- Nem repül tömeg felett
- Nem repül magasabban mint 120 méter (AGL - Above Ground Level - Föld feletti magasság)
- VLOS repülés
- Se veszélyes anyagokat, se embereket nem szállít

A **SPECIFIC** kategóriába esik az a drón, amire igaz bármelyik az alábbiak közül:

- Nehezebb mint 25 kg
- 120 méter AGL feletti agasságban vagy speciális légtérben történő repülés
- BVLOS repülés

A **CERTIFIED** ategóriába esik az a drón, amire igaz bármelyik az alábbiak közül:

- Tömeg feletti repülés
- Veszélyes anyagokat szállít
- Embereket szállít

### Open kategória

Ez a kategória a legkevésbé szabályozott, de a név ellenére léteznek itt is szabályok. 

Egy OPEN kategóriájú drón reptetése **általában** nem igényel előzetes bejelentést és jóváhagyást se. A drónnal lehet repülni, ha 
- a drón megfelel a műszaki feltételeknek
- a pilóta megfelelel az előírásoknak
- a pilóta a megfelelő képesítéssel rendelkezik
- egyéb segítők be vannak jelentve (ha vannak)

Az OPEN kategórián belül a repülések különböző repülési kategóriákba vannak sorolva aszerint, hogy milyen terep felett szeretnénk repülni. Ezek a kategóriák az A1, A2 és A3.

A drón a műszaki paraméterei szerint is alkategóriákba van sorolva, ezek a C0, C1, C2, C3 és C3.

A repülés okozta kockázatok több tényezőn alapulnak, a fő tényező nyilván a drón tömege, illetve, hogy merre és mire használnánk (kert felett az alma fa felett vagy tömeg felett). Egy kis drón kisebb sérülést és kárt okoz, így emberekhez közelebb is használható, amíg egy nagyobb, nehezebb drón akár meg is ölhet valakit ha véletlen lezúhan, ezért a repülési szabályok a repülési kategória és a drón alkategória függők, egy mátrixot alkotva.

Ha adott milyen drónnal repülnél --> meg van szabva, hogy milyen fajta repülést végezhetsz.
Ha adott, hogy milyen repülést végeznél --> meg van szabva, milyen drónokkal teheted

![Alt text](./Kepek/open_matrix.svg)

Adott repülés típus esetén csak adott képesítésű személy repülhet adott típusú drónkkal. A típusokról a következőkben lesz szó.

![Alt text](./Kepek/besorolas.svg)

### Műszaki kategóriák

Ahhoz hogy egy terméket el lehessen adni az EU-ban egy "CE" jelöléssel kell rendelkezni, amely azt mutatja meg, hogy a termék megfelel az európai szabványoknak. A CE mellett a drónoknak rendelkeznie kell egy osztály jelölő jellel, amely megmutatja, hogy a C0 - C4 kategóriák közül melyikbe tartozik. Ezek nélkül nem repülhet egy drón.

![Alt text](./Kepek/CE.jpg)

Az hogy milyen drónt vegyünk nagyban függ a felhasználási feltételtől (használati mátrix), például hogy közel akarunk-e repülni emberekhez vagy nem.

- C0 kategória: nem kizárható, hogy nem tájékoztatott emberek (Uninvolved person) felett is elrepülnénk.
- C1 kategória: biztos, hogy nem fogunk nem tájékoztatott emberek (uninvolved person) felett repülni. 
- C2 kategória: nem tájékoztatott emberektől (uninvolved person) horizontálisan 30 méterre (lassú repülés módban 5 méterre) történő repülés. A távolságnak mindig megfigyelhetőnek (observable) kell lennie.
- C3 és C4 esetén nem lehet a közelben nem tájékoztatott ember, emellett 150 méterre kell repülni ipari létesítményektől, épületektől és infrastruktúrűtól.

Az EASA meghatároz még C5 és C6 kategóriákat is, de ezek nem számítanak az OPEN kategóriában.

#### Sebesség korlátok

C0 és C1 kategória esetén maximális sebesség van meghatározva, ami 19 m/s. Ezt a sebességkorlátot azért számolták ki, hogy ezen kategóriájú drónok egy véletlen ütközés esetén ne okozzanak súlyos sérüléseket még.

C2, C3 és C4 kategóriájú drónok esetén nincs sebességkorlátozás, mert ezen drónok annyival nehezebbek, hogy akármilyen ütközés súlyos sérülést tudna okozni.

Ezen okokból kifolyólag csak C0 és C1 kategóriájú drónok reptethetőek emberek között.

#### Magasság

A C0 kategóriájú drónokba be van építve egy funkció ami megakadályozza, hogy 120 méternél magasabbra szálljanak fel. Ez nem zárja ki teljesen a légtér sértés kockázatát, viszot segít megakadályozni a magasságkorlát megszegését.

A C1, C2 és C3 drónokban állítható ez a beállítás, például egy model-repülőgép légtérben vagy ha erre speciális engedélyt kap a pilóta.

Viszont a beépített maximális korlát miatt a C1, C2 és C3 típusú drónokat el kell látni egy magasságmérővel, amelyet a pilóta folyamatosan figyelhet. Meg kell említeni, hogy a magasságmérőnek van egy pontatlansága, illetve a felszín egyenetlensége miatt megeshet, hogy a magasságmérő egy 120 méter alatti értéket mutat, amíg a drón már 120 méter felett repül

#### Azonosítás

A C1, C2 és C3 drónoknak egy távoli azonosítást lehetővé tevő funkcióval, ami lehetővé teszi, hogy a földről meg lehessen határozni, hogy milyen drón repül a légtérben, hol található a pilóta, illetve ki a pilóta. 

Az alábbi adatokat köldi el:
- pilóta datai
- azonosító szám
- drón pozíció
- pilóta pozíció
- sebesség
- magasság

Ezért tartsd észben, hogy nem névtelenül repülsz, amikor megnézel vagy lefilemzel egy területet kamerával.

#### Helymeghatározás

Ha a drón fel van szerelve helymeghatározással, akkor automatikusan összeveti a helyzetét a különböző hivatali szervek által megadott légterekkel. Ha a légtér tiltott terület, akkor erről értesítést küld a felhasználónak.

A virtuális kerítés (geo-fencing) funkció annyival szigorúbb, hogy nem csak értesítést küld a tiltott légtérről, hanem megakadályozza, hogy egy ilyen területre berepüljön a drón

C1, C2 és C3 drónok számára kötelező a helymeghatározás, viszont a virtuális kerítés nem kötelező (viszont be lehet építeni, így ne lepődjünk meg).

Összefoglalva az alábbi táblázatban látható

![Alt text](./Kepek/dronok.svg)

Láthatjuk, hogy C4 esetén megengedőbbek a szabályok. Ez azért van, mert a C4 egy gyújtő kategória a régebbi drónok esetére, például ha van egy 3 kg nehéz drónod, ami a súlya alapján C2 kategória lenne, így jogósult lenne az emberek közeli repülésre (A2), de nincsen helymeghatározója, így C4 kategóriába kerül, amivel csak A3 repülésre lehet használni.

### Repülés kategóriák

#### A1 - emberek felett

Ennek a kategóriának van a legkevesebb szabálya. Lehetőség van akár sűrű embertömeg felett is repülni (de nem tömeg felett! Igen, ez egy kicsit megtévesztő, gondolj arra hogy tüntetés vs egy focimeccs). 

C0 és C1 kategóriájú drón végezhet ilyen repülést. 

C1 drón esetén a pilótának meg kell vizsgálni a területet ahol a repülni fog és meg kell győzödnie, hogy nem bevont / tájékoztatott ember (uninvolved person) felett nem fog repülni.

Ezen vizsgálat során az alábbiakat kell figyelemmbe venni és értékelni
- A szituáció a földön (útak, járdák, bicikli út, merre vannak emberek, etc.)
- Lehetőségek a terület biztosítására
- a napszak

Ha véletlen egy járókelő felett repülönk, törekedjünk, hogy minél kevesebb időt repüljünk felette. 

Minden esetben a pilóta látómezején belül kell lennie a drónnak, és nem repülhet magasabbra mint 120 méter.

C0 kategóriájú drónnal, illetve házi építésű, 250 grammnál könnyebb drón esetén megengedett az emberek feletti repülés extrém óvatossággal. Ennek ellenére kerüljük ezt, ha tudjuk.

C2, C3, C4 típusó drónokkal tilos ilyen módon repülni.

![Alt text](./Kepek/A1.png)

#### A2 - emberekhez közel

##### C2

Ez a kategória van a leginkább szabályozva, lévén ilyen repülés folyamán van a legnagyobb kockázat. Relatív nehéz ( < 4 kg) drónok repülhetnek emberekhez közel.

Ebben a kategóriában ha C2 típusú drónnal akarunk repülni, akkor egy szigorúbb képzést is el kell végezni.

Mivel a sérülés esélye nő a drón sebességével, ezért **a biztonsági távolság sebességfüggő**. 

- lassú repülésben 5 méter
- egyébként 30 m

Lassú repülésnek az számit, ha a drón sebessége 3 m/s (10 km/h) sebességnél kisebb, vagy a drón egy ballonnak vagy léghajónak lett tervezve.

Ennél nagyobb biztonsági távolság kötelező, ha nem ideálisak a környezeti feltételek (szél, alacsony akksi töltöttség), vagy ha különböző akadályok (fák) ezt indokolják.

A maximális magasság ebben az esetben is 120 méter és a drónnak a pilóta látómezejében kell hogy legyen (VLOS)

A2 vizsga az alábbi mód tehető:
- online képzés és vizsga
- gyakorlati képzés
- gyakorlati vizsga

##### C0 és C1 

Ugyan úgy reptethető, mint A1


##### C3 és C4

Ezek a kategóriájú drónok nem repülhetnek emberekhez közel se

![Alt text](./Kepek/A2.png)

#### A3 - emberektől távol

Ebben a kategóriában reptethetőek a legnehezebb drónok ( < 25 kg). Annak ellenére, hogy a pilótának nem kell szigorúbb feltételeknek megfelelnie, mégis itt vannak a legnagyobb biztonsági távolságok alkalmazva bármitől, aminek a drón nekiütközhet (épületek, infrastruktúra).

A minimum távolság lakó és ipari épületektől, pihenő övezetektől és infrastruktúrától minimum **150 méter**.

Kötelező biztosítani, hogy nem tájékoztatott / bevont ember (uninvolved person) nem lehet jelen a repülés során a területen.

Ha nem lehetséges a biztonságos távolság tartása ezen járókelőktől, azonnal le kell szállni.

A biztonsági távolságra az alábbi szabályok vonatkoznak
- több mint 30 méter
-  1:1 szabály, azaz 1 m távolság esetén max 1 méter magasság, 20 méter távolság esetén max 20 méter, 120 méter távolság esetán 120 méter magasság
- minimum 2 másodpercnyi utazási távolság, amely körülbelül a reakció időnek felel meg

Ezek mellé a 120 méteres magassági korlátozás is vonatkozik a drónra, amely a pilóta látómezójében kell hogy történjen (VLOS)

![Alt text](./Kepek/A3.png)


## Adminisztráció és alap szabályok

Ebben a fejezetben a repülési szabályzó szervek felépülésével és egymás alá és fölé rendeltségével, illetve a repülséhez szükséges képesítésekkel foglalkozunk.


## Légterek és korlátozások

## Biztonságos repülés és felelősségek

## Biztonság, magánszféra, biztosítás (Securtiy, Privacy, Insurance)

# Emberi tényezők és korlátaik

# Üzemeltetési eljárások

# Műszaki alapok
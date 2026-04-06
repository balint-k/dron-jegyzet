
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

### Nem tájékoztatott emberek/nem bevont emberek (Univoldved persons)

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
- 120 méter AGL feletti agasságban vagy speciális légtérben történő reülés
- BVLOS repülés

A **CERTIFIED** ategóriába esik az a drón, amire igaz bármelyik az alábbiak közül:

- Tömeg feletti repülés
- Veszélyes anyagokat szállít
- Embereket szállít

### Open kategória

Ez a kategória a legkevésbé szabályozott, de a név ellenére léteznek így is szabályok.

## Repülés adminisztráció és alap szabályok

## Légterek és korlátozások

## Biztonságos repülés és felelősségek

## Biztonság, magánszféra, biztosítás (Securtiy, Privacy, Insurance)

# Emberi tényezők és korlátaik

# Üzemeltetési eljárások

# Műszaki alapok
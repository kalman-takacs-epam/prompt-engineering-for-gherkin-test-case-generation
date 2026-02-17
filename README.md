# Mi az a CREATE keretrendszer?

A jól megfogalmazott prompt elsődleges célja, hogy egy adott problémára fókuszáljon, és minőségi adatokat kapjunk eredményül.  
A **CREATE keretrendszer** hasznos útmutatót nyújt a promptok megírásához vagy finomításához.  
A CREATE egy mozaikszó, amelynek minden betűje egy-egy elemet jelöl, amelyek növelik a „jó” válasz esélyét, és csökkentik a „hallucinációk” (téves, pontatlan válaszok) arányát.

> **Fontos:**  
> A CREATE betűszó nem határozza meg, milyen sorrendben kell az egyes elemeket a promptba beépíteni. Ezeket akár több promptban is eloszthatod, hogy javítsd az olvashatóságot és elkerüld a félreértéseket.

Az alábbi vázlat alapján vizsgálhatod meg, hogyan lehet hatékony promptokat készíteni a CREATE keretrendszer segítségével:

---

## CREATE elemei

### Character (Szerep)
Határozd meg, milyen szerepet töltsön be az AI eszköz, és mi a motivációja.  
Ez irányt ad az AI-nak, hogy milyen adatokat használjon fel.  
**Példa:**  
„Szeretném, ha szoftvertesztelő mérnökként működnél.”

---

### Request (Kérés)
Mondd el az AI-nak, milyen műveleteket vársz tőle.  
Legyél minél leíróbb, adj releváns kontextust és konkrét információkat.  
**Példa:**  
„Írj teszteseteket funkcionális teszteléshez a megadott user story alapján.”

---

### Examples (Példák – opcionális)
Ha szeretnéd pontosabban irányítani az AI-t, adhatsz további példákat, mint előfeltételek, lépések, elvárt eredmények vagy a válasz hangvétele.  
**Példa:**  
„Használd az alábbi tesztpéldákat konkrét forgatókönyvek alapján.”

---

### Adjustment (Finomítás)
Itt javíthatod a promptot, hogy minden fontos szempont benne legyen, vagy éppen kizárj bizonyos elemeket a legjobb eredmény érdekében.  
**Példa:**  
„Vegyél figyelembe szélsőséges eseteket és felhasználói interakciók variációit, hogy átfogó teszteseteket kapjunk.”

---

### Type of Output (Kimenet típusa)
Mondd el az AI-nak, pontosan milyen formátumban szeretnéd a választ.  
Ez lehet cikk, táblázat, jegyzet, konkrét szerkezet, szkript vagy bármilyen írásos forma.  
**Példa:**  
„Adj részletes leírást minden tesztesetről szöveges formában, beleértve a feltételeket, lépéseket és elvárt eredményeket.”

---

### Extras (Kiegészítők)
Az LLM-ek (nagy nyelvi modellek) chat-alapúak, így emberi interakcióra vannak optimalizálva.  
Ezt kihasználva javíthatod a kommunikációt: dicsérheted a jó választ, visszajelzést adhatsz, kérheted, hogy ignorálja az előző üzeneteket, vagy igazolja a válaszát.  
Egy-egy szó vagy mondat jelentősen befolyásolhatja az AI válaszát.  
**Példák:**  
„Nagyon jó!”  
„Ez nem egészen az, amit vártam.”  
„Magyarázd el lépésről lépésre!”  
„Mutass példákat a válaszodban!”

---

> **Fontos:**  
> Nem minden prompt igényli a CREATE minden elemét. Válaszd ki és használd azokat, amelyek az adott feladathoz szükségesek!

---

# Feladat: Prompt tervezése Gherkin tesztesetek generálásához

## Háttér

A minőségbiztosítási (QA) szakemberek egyre gyakrabban használnak mesterséges intelligenciát (AI) tesztesetek automatikus generálására user story-kból.  
A Gherkin egy népszerű formátum, amely segít világos, strukturált teszteseteket írni webes alkalmazásokhoz.  
A CREATE elvek segítenek abban, hogy a promptok minőségi eredményt adjanak.

---

## Feladat

Készíts egy promptot, amely egy user story alapján Gherkin formátumú teszteseteket generál az AI segítségével!  
A promptnak követnie kell a CREATE elveket, és tartalmaznia kell a követelményt is.

---

## Követelmény

Képzelj el egy webes alkalmazást, ahol a felhasználók testre szabhatják a profiljukat.  
A user story:

> **"Felhasználóként szeretném frissíteni a profilomat, beleértve a profilképet, a megjelenítendő nevet és a bemutatkozást, hogy a fiókom tükrözze a valóságot."**

**További részletek:**
- A profilkép csak érvényes képformátum lehet (JPG, PNG vagy GIF), maximum méret: 1mb.
- A megjelenítendő név 3 és 30 karakter közötti lehet.
- A bemutatkozás maximum 150 karakter lehet.
- A rendszernek kezelnie kell az érvénytelen fájlformátumokat, túl nagy képeket és üres mezőket is.

---

## A teendőid

1. Írj egy promptot, amely az AI-t arra utasítja, hogy a fenti user story alapján generáljon Gherkin teszteseteket a megadott szerkezetben!
2. Alkalmazd a CREATE elveket a promptodban.

---

## Elvárt eredmény

- A promptod, világosan megfogalmazva, a CREATE elvek szerint.
- A prompt utasítsa az AI-t, hogy a megadott user story alapján, a megadott szerkezetben, minden mezőre és esetre kiterjedően generáljon Gherkin teszteseteket.
- Opcionálisan utasíthatod az AI-t, hogy vegye figyelembe a szélsőséges eseteket is (pl. érvénytelen fájlformátum, üres mezők, karakterkorlátok).

---

## Cél

- A promptot szöveges fájlban add le.
- Ügyelj arra, hogy a promptod jól strukturált és könnyen követhető legyen.

---

## Értékelési szempontok

- Világosság és a CREATE elvek betartása.
- Relevancia a user story-hoz és a Gherkin formátumhoz.
- Tipikus és szélsőséges esetek lefedettsége.
- A megadott teszteset-struktúra helyes használata.
- A prompt hatékonysága az AI irányításában.

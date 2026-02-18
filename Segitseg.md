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

## Használható eszközök

ChatGPT
https://chatgpt.com/
 
Gemini
https://gemini.google.com/app
 
Perplexity
https://www.perplexity.ai/
 
MS Copilot
https://copilot.microsoft.com/
 
Claude
https://claude.ai/

---

> **Fontos:**  
> Nem minden prompt igényli a CREATE minden elemét. Válaszd ki és használd azokat, amelyek az adott feladathoz szükségesek!

---

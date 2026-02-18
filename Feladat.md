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

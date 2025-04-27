# Revoke-Fixing-Guide

For English version click this link: COMING SOON


---

### Mi az a Revoke?

A Revoke egy gyakori hiba az iOS sideloadolt alkalmazások között, amikor hivatalos App Store helyett más forrásból telepítenél appokat. Ha elakadtál vagy hibaüzenetet kapsz, ez a lépésről-lépésre útmutató segít megoldani ezeket.

## Tartalom

- [1. módszer: Alacsony sikerességi arány, nem szükséges számítógép.](#1-módszer-alacsony-sikerességi-arány-nem-szükséges-számítógép)
- [2. módszer: Közepes-magas sikerességi arány, számítógép szükséges.](#2-módszer-közepes-magas-sikerességi-arány-számítógép-szükséges)
- [3. módszer: Magas sikerességi arány, számítógép szükséges.](#3-módszer-magas-sikerességi-arány-számítógép-szükséges)
- [4. módszer: Működni fog, számítógép szükséges, de törli az adataidat.](#4-módszer-működni-fog-számítógép-szükséges-de-törli-az-adataidat)
- [GYIK](#gyik)
- [Kapcsolat](#kapcsolat)

---

## Előfeltételek

- **iOS**:  12 vagy újabb. 
- **macOS**: 10.15 vagy újabb (Windows esetén iTunes 12.10+ VAGY Apple Devices legújabb verziója (Apple Devices mostantól már ajánlott az Apple oldaláról, az iTunes nem.). (Nem szükséges ha On-Device útmutatót követsz.)
- **Internet**: stabil, akár gyors (8 gigás fájlra van szükség újratelepítéskor Apple Devices vagy iTunes segítségével.) kapcsolat. (Nem szükséges ha On-Device útmutatót követsz.)
- **Eszköz**: Lightning kábel, Mac/Windows. (Nem szükséges ha On-Device útmutatót követsz.)

## Tippek és trükkök (Géphez)

- Indítsd újra a készüléket és a számítógépet, mielőtt nekiállsz.
- Jelentkezz ki és be az Apple ID-dal a Beállításokban.
- Töröld a böngésző és a Finder/iTunes cache-t.
- Ha bármi gubanc van, próbáld meg másik kábellel vagy porttal.
- Nézd át a hivatalos GitHub-issue-ket, hátha ott van már megoldás.

## 1. módszer: Alacsony sikerességi arány, nem szükséges számítógép. 

- Távolítsd el a konfigurációs profilt, és törölj minden sideloadolt alkalmazást.
- Készíts biztonsági mentést az iCloud segítségével.
- Állítsd vissza a készüléket: Beállítások > Általános > iPhone átvitele vagy visszaállítása > Összes tartalom és beállítás törlése.
- Állítsd vissza az iCloud biztonsági mentésedet.
- Kövesd újra az útmutatót.

## 2. módszer: Közepes-magas sikerességi arány, számítógép szükséges. 

- Távolítsd el a konfigurációs profilt, és törölj minden sideloadolt alkalmazást.
- Készíts biztonsági mentést, majd állítsd a készüléket helyreállítási módba.
- Nyisd meg a Findert vagy az iTunes-t, majd kattints a "Frissítés" gombra.
- Kövesd újra az útmutatót.

## 3. módszer: Magas sikerességi arány, számítógép szükséges. 

- Távolítsd el a konfigurációs profilt, és törölj minden sideloadolt alkalmazást.
- Készíts biztonsági mentést iTunes vagy Finder segítségével.
- Állítsd vissza a készüléket DFU módban.
- Csatlakoztasd a telefont a számítógéphez, majd a Finderben vagy iTunesban válaszd a biztonsági mentés visszaállítását.
- Kövesd újra az útmutatót.

## 4. módszer: Működni fog, számítógép szükséges, de törli az adataidat. 

- Állítsd vissza a készüléket DFU módban az iTunes vagy Finder segítségével.
- **Figyelem:** Ez a módszer törli az összes adatot a készülékről, ezért előtte mindenképp készíts teljes mentést!
- Kövesd újra az útmutatót.

---

## GYIK

**K: Melyik módszer a legbiztonságosabb?**  
A 3. módszer a legjobb kompromisszum a magas sikerességi arány és az adatbiztonság között.

**K: Mit tegyek, ha továbbra sem működik?**  
Ellenőrizd, hogy macOS, iTunes és Finder is naprakész, majd próbáld meg egy másik módszerrel.

**K: Hogyan ellenőrizhetem a konfigurációs profil állapotát?**  
Beállítások > Általános > VPN & Eszközkezelés alatt találod.

---

## Kapcsolat

Van ötleted vagy kérdésed? Discord: thatappleuser

---

*Pro tipp:* Győződj meg róla, hogy biztonsági mentésed készen áll, mielőtt bármit törölnél! 😉

*Peace* ✌️

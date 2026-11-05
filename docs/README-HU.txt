Villanyműhely / ElectroWorkshop Basic 1.0.1 – Windows

INDÍTÁS
1. Csomagold ki a teljes ZIP-et egy saját mappába.
2. Indítsd el az ElectroWorkshop.exe fájlt.
3. A műhely az alapértelmezett böngészőben nyílik meg.
4. A fejléc Magyar / English választójával válthatsz nyelvet.
5. A használat végén a kis indítóablak Leállítás gombjával zárd be.
   A böngészőlap bezárása önmagában nem állítja le a helyi kiszolgálót.

BEÁLLÍTÁSOK – ElectroWorkshop.ini
Az EXE mellett található fájlt szövegszerkesztővel módosíthatod.
Előbb zárd be az indítót, majd a módosítás után indítsd újra.
Nem kell új EXE-t készíteni vagy újracsomagolni.
- default_language=en: első indításkor angol; hu esetén magyar.
- remember_language=true: a korábban kiválasztott nyelv elsőbbséget kap.
  false esetén minden új megnyitás a default_language nyelvével indul.
- open_browser=true: indításkor automatikusan megnyílik a böngésző.
  false esetén az indító Megnyitás gombjával nyitható meg.
A hiányzó fájl alapértékei: en / true / true. Hibás értéknél az indító
hibaüzenetet mutat. A beállítás nem változtatja meg a mentett kapcsolásokat.
Ha korábban magyart választottál, és ezután mindig angol kezdést szeretnél,
állítsd default_language=en és remember_language=false értékre.

Rendszer: Windows 10/11, korszerű Edge, Chrome vagy Firefox böngésző.
Az indító a Windows .NET Framework 4.5 vagy újabb rendszerösszetevőjét
használja; Windows 10/11 rendszeren ez szokásosan már rendelkezésre áll.
Külön Python, Docker, rendszergazdai telepítés vagy internet nem szükséges.
A saját, helyi cím: http://127.0.0.1:18743/ . A program nem figyel a LAN-on.
Ha a port foglalt, zárd be a másik ElectroWorkshop Basic példányt.

TARTALOM
Hagyományos világítási és motorvezérlési feladatok, készülékek elhelyezése,
vezetékezés, szerelési és sematikus nézet, szimuláció, mérőeszközök,
kapcsolatkövetés, feladatellenőrzés és helyi JSON-mentés/betöltés.
Nincs MQTT, Home Assistant, okoseszköz, 3D alaprajz vagy iskolai fiókrendszer.
A hagyományos oktatási kapcsolási feladatok megmaradtak.
A külön fényképes referenciaanyagok nincsenek ebben a kiadásban.

MENTÉSEK
A munka a választott böngésző saját helyi tárában, feladatonként tárolódik.
A két nyelv ugyanazokat a helyi mentéseket használja. Saját eszközneveid nem
fordulnak át automatikusan. Másik böngésző külön tárat használ.
Fontos munkát a Mentés gombbal JSON-fájlba is ments: a böngészőadatok
törlése eltávolíthatja az automatikus mentéseket. E program külön helyi
címet használ, így a teljes/NAS-os műhely böngészőtárát nem írja felül.
Az okoseszközös vagy alaprajzos mentést elutasítja, nem alakítja át.

A készülékek rajzai és a kapcsolási modell oktatási célúak. A program nem
valós villamos felülvizsgálat, feszültségmentességi igazolás vagy méretezés.
A mérési és védelmi modell korlátai a felületi súgóban olvashatók.

HASZNÁLAT ÉS TERJESZTÉS
Magáncélra és nem üzleti oktatásra ingyenes, a mellékelt használati
feltételekkel. Üzleti használatra ez a kiadás nem ad engedélyt.
A fejlesztési forráscsomag nem része a kiadásnak. A böngészőben futó
JavaScript műszakilag megvizsgálható; az EXE-be csomagolás nem titkosítás.
Az EXE nincs digitálisan aláírva. A csomaghoz SHA256 ellenőrzőösszeg jár.

Nem került bele személyes mentés, jelszó, adatbázis vagy HA/MQTT-beállítás.

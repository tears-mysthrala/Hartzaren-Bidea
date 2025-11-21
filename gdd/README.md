# 📄 HARTZAREN-BIDEA: GAME DESIGN DOCUMENT (GDD)

## I. 🎮 Proiektuaren Irizpidea (Game Vision)

| Kategoria | Zehaztapena |
| :--- | :--- |
| **Jokoaren Izena** | Hartzaren-Bidea (Bear's Path) |
| **Generoa** | 2D Incremental Idle / Wuxia RPG |
| **Plataforma** | Web (HTML5/JavaScript) |
| **Helburu-Publikoa** | Idle/Incremental zaleak, Wuxia/Martzial Arteak eta Euskal Mitologia gustuko dituztenak. |
| **Giroa** | Euskal Herri mitologikoa, giro mistiko eta lainotsuarekin, non arte martzialak eta antzinako kondairak nahasten diren. |
| **Tonua** | Serioa, erreflexiboa, eta aurrerapen etengabean zentratua. |

## II. 🖼️ Giroa eta Arte-Estiloa (Setting and Art Style)

* **Kokapena:** Euskal Herri fantastikoa. Jokalariak zonalde mitologiko desberdinetan egingo du aurrera (Basajaunen Basoa, Mariren Haitzuloa, Itsasgizona Kostaldean).
* **Estilo Artistikoa:** **Pixel Art 2D** atmosferikoa. Kolore-paleta nagusia berdea, grisa eta urdina izango da, gorri eta urre ukituekin, Wuxia-ren indarra eta energia adierazteko.
* **Pertsonaien Diseinua:** Wuxia estiloko jantziak (mantelak, gerrikoak) eta euskal ukituak (txapelak, artilezko ehunak).

## III. 💻 Zehaztapen Teknikoak

| Kategoria | Zehaztasuna |
| :--- | :--- |
| **Motorra/Framework** | **JavaScript (Vanilla JS) / [Hemen sartu: React edo Vue bezalako aukerak]** |
| **Programazio Hizkuntza** | **JavaScript (ES6+)** |
| **Datu Biltegiratzea** | Local Storage (Jokoaren datuak) |

## IV. ⚔️ Mekanika Nagusiak

### A. Oinarrizko Baliabideak (Core Resources)

| Baliabidea | Ikonoa | Nola Sortzen da | Funtzioa |
| :--- | :--- | :--- | :--- |
| **Ausardia (Bravery)** | 🩸 | Denbora pasatzearekin (Idle) eta *Ki* mailaren arabera. | Arte Martzialak entrenatzeko eta Borroka puntuak hasteko gastatzen da. |
| **Indarra (Ki/Chi)** | ✨ | *Ausardia* modu eraginkorrean gastatzean (birziklatzea). | *Ki* gaitasun iraunkorrak desblokeatzeko eta *Prestige* (Ospea) egiteko. |
| **Ospea (Prestige)** | 🏆 | *Bidea* berrabiaraztean (Rebirth). | Hobekuntza global iraunkorrak erosteko moneta. |

### B. Entrenamendu-Sistema (Bideak)

Jokalariak *Ausardia* erabiliko du Arte Martzialen Bideak entrenatzeko. Trebetasun bat entrenatzeak automatikoki **Indarra (Ki)** sortzen du.

| Bidea | Estilo Nagusia | Deskribapen Laburra | Indar-Fokua |
| :--- | :--- | :--- | :--- |
| **1. Aketegi Hartza** | Defentsa/Tanka | Erresistentzian eta Kolpe gogorretan oinarritua. | **Defentsa Iraunkorra** eta Ausardiaren produkzio motela. |
| **2. Akelarreko Dantzaria** | Abiadura/Saihestea | Mugimendu azkarrak eta saiheste-probabilitateak. | **Abiadura (Speed)** eta Ausardiaren gastatze efizientzia. |
| **3. Basajaunaren Makila** | Trebetasun Kudeaketa | *Ki*-a birziklatzea eta baliabideekin eraginkortasuna. | **Ki Birziklapen Azkarra** eta Trebetasun Indarra. |

### C. Aurrerapen Zikloa (Loop / Rebirth)

1.  **ITXARON:** *Ausardia* pilatu.
2.  **ENTRENATU:** Entrenatu Bideak *Ausardia* gastatuz.
3.  **PILATU:** Irabazi *Indarra (Ki)* entrenamenduaren bidez.
4.  **BIDEAREN BERRABIAZTERAZTEA (Prestige):** *Indarra* kopuru jakin bat lortutakoan, jokalariak Bidea Berrabiarazi dezake.
    * **Galdu:** *Ausardia* eta Bideetako Trebetasunak maila 0-ra itzultzen dira.
    * **Irabazi:** **Ospea** (Prestige Currency) irabazten da, hobekuntza global iraunkorrak erosteko.

## V. 🗿 Mitologia eta Hobekuntza Arbolak

**Ospea** gastatuz, jokalariak Euskal Mitologiako izaki nagusien baimena lortzen du, jokoa modu iraunkorrean hobetuz (Prestige hobekuntzak):

| Mitologia Gaia | Efektu Nagusia | Hobekuntza Adibideak (Ospea erabiliz) |
| :--- | :--- | :--- |
| **Mari, Amalurren Gogoa** | Baliabideen sorrera tasa globala handitu. | Indarraren (Ki) produkzio bikoiztua, denboraren eraginkortasuna. |
| **Basajaun, Basoko Jauna** | Defentsa eta Erresistentzia hobetu, borroka ziklo luzeetarako. | *Ausardia*ren mugak handitu, defentsa hobekuntza pasiboak. |
| **Sugaar, Zeruko Dragoia** | Abiadura eta Efizientzia handitu. | Ausardiaren biderkatzaile txikiak segundoko, berritze denborak murriztu. |
| **Olentzero** | Baliabide (loot) bereziak edo eguneroko hobariak. | Eguneko konektatzeko hobariak hobetu, baliabideen bilketa automatikoa. |

## VI. 📜 Lizentzia eta Copyright-a

Dirua irabazteko asmoa eta garapen komunitarioa uztartzeko, Lizentzia Bikoitzeko Eredu bat ezartzen da:

* **Kodea (Codebase):** Proiektuaren programazio-kodea **MIT Lizentziaren** pean argitaratzen da.
* **Aktiboak (Assets):** Arte Bisualak (Pixel Art, UI Elementuak), Musika, Soinuak, eta Istorioko Testu Guztia **All Rights Reserved (Copyright Osoa)** pean daude. (Ezin da jokoaren itxura kopiatu).

# Interaktivní tréninková hokejová deska

## Autor
**Tadeáš Zíkl**  
SPŠE Ječná  
E-mail: tadeas.zikl@gmail.com

## Popis projektu
Tento projekt se zabývá návrhem a realizací interaktivního hokejového trenažeru pro zlepšení rychlosti, přesnosti a koordinace hráče. Zařízení využívá Hallovy senzory umístěné v hrací desce a magnet zabudovaný v puku pro přesnou detekci jeho pohybu.

Systém je řízen mikrokontrolérem ESP32. Součástí zařízení je LED pásek pro vizuální signalizaci, OLED displej pro zobrazování informací a ovládací tlačítka pro výběr herních režimů.

Výsledkem je funkční prototyp vhodný pro domácí trénink, výuku elektroniky a další rozšíření.

---

# Uživatelský manuál
## Interaktivní hokejový trenažer

---

## 1. Úvod

Tento trenažer je interaktivní zařízení určené pro trénink práce s hokejovým pukem. Slouží ke zlepšení rychlosti reakce, koordinace pohybu a přesnosti ovládání puku.

Hrací deska obsahuje matici tréninkových bodů, které jsou tvořeny kombinací LED diod a Hallových senzorů. V puku je umístěn magnet, díky kterému zařízení dokáže přesně detekovat jeho polohu.

Zařízení je řízeno mikrokontrolérem ESP32 a obsahuje LED pásek WS2812B, OLED displej a ovládací tlačítka.

---

## 2. Popis zařízení

**Hrací deska**  
Obsahuje tréninkové body s LED diodami a Hallovými senzory.

**LED indikace**  
Zobrazuje aktuální cíle, na které má hráč reagovat.

**Hallovy senzory**  
Detekují magnet v puku a zaznamenávají zásah cíle.

**Puk s magnetem**  
Obsahuje magnet pro detekci pohybu na desce.

**OLED displej**
- aktuální režim  
- skóre  
- čas  
- menu  

**Ovládací tlačítka**
- levé tlačítko – předchozí položka  
- pravé tlačítko – další položka  
- střední tlačítko – potvrzení / spuštění hry  

---

## 3. Zapnutí zařízení

Po zapnutí se zobrazí úvodní obrazovka a následně hlavní menu, kde si hráč vybere herní režim pomocí tlačítek.

---

## 4. Ovládání menu

- levé tlačítko – pohyb v menu  
- pravé tlačítko – pohyb v menu  
- střední tlačítko – potvrzení vybrané hry  

Aktuálně vybraný režim je označen na displeji. Po potvrzení se hra spustí.

---

## 5. Princip hry

Po spuštění se rozsvítí cílový bod nebo více bodů.

Úkolem hráče je:
- sledovat aktivní cíl  
- co nejrychleji přejet pukem dané místo  
- systém zaznamená zásah pomocí Hallova senzoru  
- zobrazí se další cíl  

Za každý správný zásah hráč získává bod.

Na displeji se zobrazuje:
- skóre  
- čas hry  

---

## 6. Herní režimy

- Náhodné cíle  
- Driblink  
- Zhasni všechny cíle  

---

## 7. Průběh hry

- LED diody zobrazují aktuální cíle  
- Hallovy senzory detekují zásah  
- systém počítá skóre  
- displej zobrazuje průběh hry  

Po skončení hry se zobrazí výsledek a zařízení se vrátí do menu.

---

## 8. Bezpečnost

- používat na stabilním povrchu  
- nepoužívat nadměrnou sílu  
- nepřibližovat silné magnety k elektronice  
- chránit zařízení před vlhkostí  

---

## 9. Rozšíření

- nové herní režimy  
- statistiky hráče  
- mobilní aplikace  
- bezdrátový přenos dat  

---

## 10. Závěr

Trenažer umožňuje efektivní trénink práce s pukem a reakční rychlosti hráče. Díky kombinaci Hallových senzorů, LED indikace a mikrokontroléru ESP32 vzniklo zařízení, které propojuje sportovní trénink s moderní elektronikou.

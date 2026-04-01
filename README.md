# Interaktivní tréninková hokejová deska

## Autor
**Tadeáš Zíkl**  
SPŠE Ječná  
E-mail: tadeas.zikl@gmail.com

## Popis projektu
Tento projekt se zabývá návrhem a realizací interaktivního hokejového trenažeru pro zlepšení rychlosti, přesnosti a koordinace hráče. Zařízení využívá Hallovy senzory umístěné v hrací desce a magnet zabudovaný v puku pro přesnou detekci jeho pohybu.

Systém je řízen mikrokontrolérem ESP32. Součástí zařízení je LED pásek pro vizuální signalizaci, OLED displej pro zobrazování informací a ovládací tlačítka pro výběr herních režimů.

Výsledkem je funkční prototyp vhodný pro domácí trénink, výuku elektroniky a další rozšíření.

## Hlavní cíle projektu
- zlepšení rychlosti reakce hráče
- zlepšení koordinace pohybu
- zlepšení přesnosti ovládání puku
- propojení sportovního tréninku s elektronikou a programováním

## Jak zařízení funguje
- puk obsahuje magnet
- Hallovy senzory v hrací desce detekují jeho polohu
- ESP32 vyhodnocuje data ze senzorů
- LED pásek označuje aktivní cíle
- OLED displej zobrazuje informace o hře
- hráč reaguje pohybem puku na rozsvícené body

## Použité komponenty
- ESP32-WROOM
- Hallův senzor 44E
- LED pásek WS2812B
- I²C expandér MCP23017
- OLED displej
- magnetický puk

## Herní režimy

### 1. Náhodné cíle
LED diody se rozsvěcují na náhodných pozicích. Hráč musí rychle reagovat a přejet správné místo pukem.

### 2. Driblink
Cíle se střídají mezi více body. Hráč musí rychle přesouvat puk mezi jednotlivými pozicemi.

### 3. Zhasni všechny cíle
Na začátku hry se rozsvítí více bodů. Úkolem hráče je všechny postupně přejet a zhasnout v co nejkratším čase.

## Obsah repozitáře

```text
.
├── README.md
├── src/
│   └── main.ino
├── docs/
│   ├── Uzivatelsky_manual.md
│   ├── Soucastky.docx
│   └── obrazky/
```

## Spuštění projektu
1. Otevřít zdrojový kód v Arduino IDE nebo jiném vhodném prostředí.
2. Zkontrolovat použité knihovny a připojený ESP32.
3. Nahrát program do mikrokontroléru.
4. Zapnout zařízení.
5. Pomocí tlačítek vybrat herní režim.
6. Spustit trénink.

## Uživatelský manuál
Uživatelský manuál je uložen v repozitáři ve složce `docs/`.

## Možnosti rozšíření
- nové herní režimy
- více tréninkových bodů
- ukládání statistik hráče
- propojení s mobilní aplikací
- bezdrátový přenos dat

## Výsledek projektu
Byl vytvořen funkční prototyp interaktivního hokejového trenažeru, který propojuje elektroniku, programování a sportovní trénink. Projekt je možné dále rozšiřovat a upravovat.

## Licence
Tento projekt byl vytvořen jako školní projekt.

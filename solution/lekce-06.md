# Samostatné cvičení - lekce 6
## Cvičení - JSON
---

## 1 - Závod

Pracuj dál se souborem [zavod.json](./assets/zavod.json). Cílem cvičení je zjistit čas závodníka, který získal stříbrnou medaili - seznam závodníků je seřazený, tedy výherce je zapsán jako první v našem souboru. Budeš tedy muset projít data pomocí cyklu a vytvořit seznam všech závodníků, kteří závod dokončili, tj. jejich oficiální čas není 'DNF'.

Můžeš postupovat následujícím způsobem:

Vytvoř si prázdný seznam finishers, kam budeš vkládat jména závodníků, kteří závod doběhli.
Pomocí cyklu projdi seznam závodníků.
Do cyklu vlož podmínku, která ověří, zda oficiální čas závodníka je odlišná od řetězce DNF.
Dovnitř podmínky vlož kód, který vloží jméno a oficiální čas závodníka do seznamu finishers. (obě hodnoty můžeš dát do nového seznamu, výsledný seznam finishers bude tedy obsahovat seznamy jako jeho položky). Pro přidání prvku do seznamu použij metodu append(), tedy finishers.append(seznam_s_jmenem_a_casem_zavodnika)
Na konec programu (mimo cyklus) vlož příkaz na vypsání obsahu seznamu finishers.
Zvol index výsledného seznamu finishers tak aby print vypisoval pouze stříbrného medailistu.
U každého bodu si klidně ověř že tvůj aktuální kus kódu dělá to co má - například dočasným pomocným printem.

<details>
<summary><b>Řešení</b></summary>

```python
Tady zatím řešení není :)
```

</details>

## 2 - Kurz

```python
{
    "nazev": "Úvod do programování",
    "lektor": "Michal Kučera",
    "konani": [
        {
            "misto": "T-Mobile",
            "koucove": [
                "Dan Vrátil",
                "Filip Kopecký",
                "Martina Nemčoková"
            ],
            "ucastnic": 30
        },
        {
            "misto": "MSD IT",
            "koucove": [
                "Dan Vrátil",
                "Zuzana Tučková",
                "Martina Nemčoková"
            ],
            "ucastnic": 25
        },
        {
            "misto": "Škoda DigiLab",
            "koucove": [
                "Dan Vrátil",
                "Filip Kopecký",
                "Kateřina Kalášková"
            ],
            "ucastnic": 41
        }
    ]
}
```
Stáhněte si soubor [kurz.json](./assets/kurz.json) s výše uvedeným obsahem a načtěte jej v Pythonu do proměnné kurz. Odpovězte na následující otázky:

- Vypište na výstup počet účastnic na posledním konání kurzu.
- Vypište na výstup jméno posledního kouče na prvním konání kurzu.
- Vypište na výstup celkový počet konání kurzu.
- Vypište na výstup všechna místa, na kterých se kurz konal.
- Vypište na výstup součet všech účastnic.
- Vypište na výstup množinu všech koučů, kteří se kdy kurzu účastnili.

<details>
<summary><b>Řešení</b></summary>

```python
Tady zatím řešení není :)
```

</details>

## 3 - Transformace dat

Stáhněte si soubor [words.txt](./assets/words.txt) a zpracujte z něj výstupní soubor ve formátu JSON obsahující slovník. Klíče budou písmena a hodnoty seznamy slov, které začínají písmenem v klíči. Pokud na nějaké písmeno žádná slova nezačínají, tak ve výstupu toto písmeno nebude. Seřaďte tyto seznamy podle abecedy. Zajistěte, aby i klíče ve výstupním JSON souboru byly seřazeny a data byla odsazena čtyřmi mezerami pro lepší čitelnost člověkem.

Vzorový výstup: [output.json](./assets/output.json).

<details>
<summary><b>Nápověda</b></summary>

- Vytvořím si prázdný slovník, do kterého budu vytvářet požadovaný výstup
- Otevřu si vstupní soubor a budu ho načítat v cyklu po řádcích
- Zbavím se znaku pro nový řádek v každém slově
- Zjistím si první písmeno slova
- Pokud písmeno není klíčem slovníku, tak tento záznam vytvořím a jako hodnotu vložím seznam s tímto slovem
- Jinak slovo připojím na konec existujícího seznamu slov
- Po zpracování celého vstupu seřadím seznamy slov na všech klíčích
- Výstupní slovník zapíšu do souboru ve formátu JSON
- V dokumentaci musím najít, jak zajistím, aby byl výstup hezky odsazovaný o 4 mezery a klíče slovníku byly seřazené

</details>

<details>
<summary><b>Řešení</b></summary>

```python
Tady zatím řešení není :)
```

</details>
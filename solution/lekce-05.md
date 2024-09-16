# Samostatné cvičení - lekce 5
## Cvičení - Slovníky a cykly
---

## 1 - Vysvědčení

Uvažujme vysvědčení, které máme zapsané jako slovník.

Napiš program, který spočte průměrnou známku ze všech předmětů.
Uprav program, aby vypsal všechny předměty, ve kterých získal student známku 1.

```python
school_report = {
    "Český jazyk": 1,
    "Anglický jazyk": 1,
    "Matematika": 1,
    "Přírodopis": 2,
    "Dějepis": 1,
    "Fyzika": 2,
    "Hudební výchova": 4,
    "Výtvarná výchova": 2,
    "Tělesná výchova": 3,
    "Chemie": 4,
}
```

<details>
<summary><b>Řešení</b></summary>

```python
Tady zatím nic není :)
```

</details>

## 2 - Čtenářský deník

Gustav je vášnivým čtenářem detektivek z našeho nakladatelství a navíc si zapisuje knihy, které přečetl. Níže ve slovníku vidíme, jaké informace si eviduje - název knihy, počet stran a hodnocení od 0 do 10.

- Napiš program, který spočte celkový počet stran, které Gustav přečetl.
- Připiš do programu výpočet počtu knih, kterým dal Gustav hodnocení alespoň 8.

```python
books = [
    {"title": "Vražda s příliš mnoha notami", "pages": 450, "rating": 5},
    {"title": "Vražda podle knihy", "pages": 524, "rating": 9},
    {"title": "Past", "pages": 390, "rating": 4},
    {"title": "Popel popelu", "pages": 411, "rating": 10},
    {"title": "Noc, která mě zabila", "pages": 159, "rating": 7},
    {"title": "Vražda, kouř a stíny", "pages": 258, "rating": 6},
    {"title": "Zločinný steh", "pages": 542, "rating": 8},
    {"title": "Zkus mě chytit", "pages": 247, "rating": 7},
    {"title": "Vrah zavolá v deset", "pages": 396, "rating": 6},
]
```

<details>
<summary><b>Řešení</b></summary>

```python
Tady zatím nic není :)
```

</details>

## 3 - Poznávací značky

V následujícím slovníků je evidence automobilů. Klíčem jsou státní poznávací značky (SPZ) a hodnotou je jméno majitele vozu. Napiš program, který vypíše všechny majitele, jejichž vozidlo je registrováno v Plzeňském kraji, tj. na druhém místě (index 1!) řetězce v klíči je písmeno P.

```python
plates = {"4A2 3000": "František Novák",
    "6P5 4747": "Jana Pilná",
    "3B7 3652": "Jaroslav Sečkár",
    "1P5 5269": "Marta Nováková",
    "37E 1252": "Martina Matušková",
    "2A5 2241": "Jan Král"}
```

<details>
<summary><b>Řešení</b></summary>

```python
Tady zatím nic není :)
```

</details>

## 4 - recepty

Pohlédněte na následující reprezentaci receptu:

```python
{
    'nazev': 'Batáty se šalvějí a pancettou',
    'narocnost': 'stredni',
    'doba': 30,
    'ingredience': [
        ['batát', '1', '15 kč'],
        ['olivový olej', '2 lžíce', '2 kč'],
        ['pancetta', '4-6 plátků', '21 kč'],
        ['přepuštěné máslo', '2 lžíce', '5 kč'],
        ['mletý černý pepř', '1/2 lžičky', '0.5 kč'],
        ['sůl', '1/2 lžičky', '0.1 kč'],
        ['muškátový oříšek', 'špetka', '1 kč'],
        ['česnek', '2 stroužky', '1 kč'],
        ['šalvějové lístky', '20-25', '12 kč']
    ]
}
```

Uložte si tuto strukturu do proměnné recept na začátek nového programu. Vypište pomocí funkce print kolik bude celé jídlo stát korun zaokrouhlené na celé koruny nahoru.

<details>
<summary><b>Řešení</b></summary>

```python
Tady zatím nic není :)
```

</details>

## Cvičení - Soubory
---

## 1 - Vyplata

Zatím jsme výplatu počítali za předpokladu, že každý měsíc odpracujeme stejný počet hodin, což není příliš realistické. Stáhněte si textový soubor [vykaz.txt](./assets/vykaz.txt), který obsahuje 12 řádků a na každém řádku počet odpracovaných hodin za každý měsíc za poslední rok.

Otevřete tento soubor ve svém programu a načtěte hodnoty na řádcích do seznamu vykaz. Vytiskněte tento seznam do terminálu funkcí print() abyste si ověřili, že jste soubor načetli správně.
Nechte uživatele zadat na příkazovém řádku hodinovou mzdu. Spočítejte a na výstup vytiskněte celkovou výplatu za celý rok a průměrnou výplatu na jeden měsíc.

<details>
<summary><b>Řešení</b></summary>

```python
Tady zatím nic není :)
```

## 2 - Počet slov

Stáhněte si odevzdanou [slohovou práci](./assets/prace.txt). Zadání bylo sepsat text o nejméně 150ti slovech pojednávající o našem hlavním městě. Napište program, který spočítá počet slov v tomto textu, abychom věděli, zda bylo zadání formálně splněno. Nechte se vést následujícím návodem.

Nechte váš program otevřít soubor a načíst jednotlivé řádky do seznamu
Každý řádek převeďte na seznam slov. Slovem se rozumí vše, co je odděleno mezerou nebo novým řádkem
Vypište na výstup počty slov na každém řádku
Vypište na výstup celkový počet všech slov v souboru

<details>
<summary><b>Řešení</b></summary>

```python
Tady zatím nic není :)
```

## 3 - Půjčovna

Půjčovna aut má v každém kraji ČR jedno auto s danou SPZ. Ke konci roku chce zjistit, kolik všechna auta najezdila dohromady kilometrů. V souboru [auta.txt](./assets/auta.txt) je pro každou SPZ zaznamenáno kolik dané auto ujelo kilometrů za daný rok. Hodnoty jsou v tisících kilometrů. Bohužel se v jednotlivých krajích blbě zkoordinovali a někdo používal desetinnou čárku, někdo zase tečku.

Pozor! V souboru s daty je ještě jeden problém, který není na první pohled vidět!

Napište program, který na výstup vypíše součet všech ujetých kilometrů. Jistě se vám bude hodit metoda řetězců jménem replace().

<details>
<summary><b>Řešení</b></summary>

```python
Tady zatím nic není :)
```
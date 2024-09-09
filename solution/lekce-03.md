# Samostatné cvičení - lekce 3 
## Cvičení - cykly 
---

## 1 - Seznam hodnocení

Mějme seznam hodnocení divadelní hry Plyšáci na útěku , který vypadá takto: 

```python
hodnoceni = [7, 9, 6, 7, 9, 8]
```

- Vytvořte program, který projde tento seznam a vypíše každé hodnocení na nový řádek.
- Upravte program tak, aby vypisoval výstup v tomto formátu

```python
7/10
9/10
6/10
7/10
9/10
8/10
```

<details>
<summary><b>Řešení</b></summary>

Tady zatím nic není :)

</details>

## 2 - Procházení seznamu
Založte si program **hesla.py** a na jeho začátek vložte následující kód obsahující seznam hesel pro přihlášení do nějakého systému

```python
hesla = [
    "xyz101",
    "punťa",
    "razor-blade",
    "1234",
    "12011986",
    "martin111",
    "trhnisi",
    "hokuspokus",
    "jeník15",
    "kristus-te-spasi",
    "beruška",
    "strčprstskrzkrk",
]
```

- Pomocí cyklu vypište všechny hesla na obrazovku, každé na jeden řádek.
- Upravte váš program tak, aby vypisoval jen bezpečná hesla, tedy taková, jež jsou delší než 8 znaků.

<details>
<summary><b>Řešení</b></summary>

Tady zatím nic není :)

</details>

## 3 - Složitější seznam
Založte si program **cykly02.py** a použijte v něm následující seznam měsíců v roce, Všimněte si, že je to seznam seznamů.

```python
mesice = [
    ["leden", 31],
    ["únor", 28],
    ["březen", 31],
    ["duben", 30],
    ["květen", 31],
    ["červen", 30],
    ["červenec", 31],
    ["srpen", 31],
    ["září", 30],
    ["říjen", 31],
    ["listopad", 30],
    ["prosinec", 31],
]
```

- Pomocí cyklu projděte tento seznam a vypište na výstup názvy jednotlivých měsíců.
- Pomocí dalšího cyklu vypište na výstup počty dní v jednotlivých měsících.

<details>
<summary><b>Řešení</b></summary>

Tady zatím nic není :)

</details>

## 4 - Průměr
Napište cyklus, který projde zadaný seznam desetinných čísel a spočítá jejich průměr. Seznam čísel si vytvořte na začátku programu.

<details>
<summary><b>Řešení</b></summary>

Tady zatím nic není :)

</details>

## 5 - Hry
Následující seznam obsahuje seznam všech divadelních her, které se hrají v divadle Pěst na oko. Každá hra má svůj název a trvání v minutách.

```python
hry = [
    ["Ňadro na ňadru na nádru", 180],
    ["Útok plyšových krokodýlů", 95],
    ["Cesta do říše zelí", 128],
    ["Romance na zdymadle", 144],
    ["Zátiší s mimozemšťanem", 135],
    ["Čtyři facky a dortík", 100],
    ["Motorová okurka", 165],
    ["Johnny Noir", 140],
    ["Pražská kavárna vrací úder", 130],
    ["Pět sester ve vratech", 111],
    ["Stařec a krajta", 187],
    ["Růžová nemoc", 210],
    ["Smrt v přímém přenosu", 265],
]
```

- Pomocí cyklu projděte tento seznam a vypište na výstup názvy všech her.
- Vypište na výstup názvy všech her, které trvají více než 120 minut.
- Vypište na výstup názvy všech her spolu s jejich trváním v hodinách a minutách.

<details>
<summary><b>Řešení</b></summary>

Tady zatím nic není :)

</details>

## Cvičení - funkce 
---

## 1 - Násobení
Napiš funkci mult, která bude mít dva číselné parametry. Funkce oba parametry vynásobí a vrátí výsledek.

<details>
<summary><b>Řešení</b></summary>

Tady zatím nic není :)

</details>

## 2 - Hotel
Napiš funkci total_price, která vypočte cenu noci v hotelu. Funkce bude mít dva parametry - persons a breakfast. Cena za noc za osobu je 850 Kč a cena za snídani za osobu je 125 Kč. Funkce vrátí výslednou cenu. Parametr breakfast je nepovinný a výchozí hodnota je False.

Funkci vyzkoušej se zadáním dvou i jedné hodnoty, např. total_price(3), total_price(2, True).

<details>
<summary><b>Řešení</b></summary>

Tady zatím nic není :)

</details>

## 3 - Faktoriál
Vytvoř program, který obsahuje funkci pro výpočet libovolného faktoriál. (https://cs.wikipedia.org/wiki/Faktori%C3%A1l) 

Využij funkci z matematického modulu.

<details>
<summary><b>Řešení</b></summary>

Tady zatím nic není :)

</details>

## 4 - Rámeček
Napiš funkci, která jako parametr převezme řetězec a vytiskne jej obalen hvězdičkami.

```
Zadej slovo: ahoj
********
* ahoj *
********
```

Nápověda: 8 * '*' == '********'

Bonus: Znak, kterým se má text obalit, bude zadán také jako parametr.

<details>
<summary><b>Řešení</b></summary>

Tady zatím nic není :)

</details>
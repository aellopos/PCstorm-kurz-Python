# Samostatné cvičení - lekce 4
## Cvičení - slicing 
---

## 1 - Pohyby na účtu

Mějme seznam pohybů na nějakém bankovním účtu:

```python
pohyby = [1200, -250, -800, 540, 721, -613, -222]
```

1. Vypište v pořadí třetí pohyb z uvedeného seznamu.
2. Vypište všechny pohyby kromě prvních dvou.
3. Vypište kolik je všech pohybů dohromady.
4. Pomocí volání vhodných funkcí vypište nejvyšší a nejnižší pohyb.
5. Spočítejte celkový přírůstek na účtu za dané období. Pozor, že přírůstek může vyjít i záporný.


<details>
<summary><b>Řešení</b></summary>

```python
Tady zatím řešení není :)
```

</details>


## 2 - Průměr

Mějme proměnnou s, ve které předpokládáme uložený nějaký seznam. Sestavte v výraz (vzoreček), který spočítá průměrnou hodnotu v takovém seznamu. Otestujte jej na seznamech různých délek.


<details>
<summary><b>Řešení</b></summary>

```python
Tady zatím řešení není :)
```

</details>

## 3 - Rozpětí

Postupujte obdobně jako v úložce Průměr, ale tentokrát sestavte výraz pro výpočet rozpětí, tedy rozdílu mezi minimální a maximální hodnotou.


<details>
<summary><b>Řešení</b></summary>

```python
Tady zatím řešení není :)
```

</details>

## 4 - Střed seznamu

Sestavte výraz, který vrátí číslo nacházející se přesně uprostřed v zadaném seznamu s. U seznamů liché délky je střed jasně definovaný, ovšem u seznamů sudé délky nám padne mezi dvě čísla. V takovém případě vyberte jako střed číslo blíže ke konci seznamu.


<details>
<summary><b>Řešení</b></summary>

```python
Tady zatím řešení není :)
```

</details>

## 5 - Střed seznamu podruhé

Sestavte vzoreček, který vrátí číslo nacházející se přesně uprostřed v zadaném seznamu s. Tentokrát však u seznamů sudé délky vyberte jako střed číslo blíž k začátku seznamu.


<details>
<summary><b>Řešení</b></summary>

```python
Tady zatím řešení není :)
```

</details>

## Cvičení - metody na textových řetězcích 
---

## 1 - Převod písmen

Uložte si do proměnné jmeno svoje jméno. Pomocí volání vhodných metod jej převeďte nejdříve na malá písmena a poté na velká písmena.

<details>
<summary><b>Řešení</b></summary>

```python
Tady zatím řešení není :)
```

</details>

## 2 - Zasedačka

Níže máš seznam akcí, které se konaly v zasedačce jedné firmy.

```python
akce = [
    "školení - řízení firemních vozidel",
    "jazykový kurz - angličtina",
    "pohovor - Jan Dvořák",
    "pohovor - Antonín Sova",
    "jazykový kurz - němčina",
    "pohovor - Iveta Hájková",
    "pohovor - Ivan Brož",
    "pohovor - Katarína Martináková",
    "setkání se zákazníkem - Metrostav",
    "jazykový kurz - angličtina",
    "školení - vykazování práce",
    "pohovor - Klaudie Moudrusová",
]
```

Napiš program, který zjistí následující:

1. Kolik se uskutečnilo pohovorů?
2. V jakých jazycích se mohou zaměstnanci firmy vzdělávat?
3. Při řešení můžeš využít operátor in a slicing, případně metodu split()


<details>
<summary><b>Řešení</b></summary>

```python

```

</details>

## 3 - Čísla jako text

Mějme seznam celých čísel zadaných jako text

```python
hodnoty = ['12', '1', '7', '-11']
```

Potřebujeme k třetímu číslu v seznamu přičíst 4, aby výsledek vypadal takto:

```python
hodnoty = ['12', '1', '11', '-11']
```

<details>
<summary><b>Řešení</b></summary>

```python

```

</details>

## 4 - Čísla v textu

Máme obdobné zadání jako v předchozím cvičení, avšak tentokrát máme čísla zadána nikoliv v seznamu, ale v řetězci oddělená mezerou:

```python
hodnoty = '12.1 1.68 7.45 -11.51'
```

K poslednímu číslu v seznamu chceme přičíst 0.25 tak, aby výsledek vypadal takto

```python
hodnoty = '12.1 1.68 7.45 -11.26'
```

Určitě se vám budou hodit metody split a join.

<details>
<summary><b>Řešení</b></summary>

```python

```

</details>

## Cvičení - slovníky
---

## 1 - Vysvědčení

Vytvoř slovník, který reprezentuje vysvědčení. Klíč slovníku bude název předmětu a hodnota známka z daného předmětu. Pro zjednodušení vlož do slovníku pouze tři předměty (například český jazyk, matematiku a dějepis). Vypiš obsah slovníku pomocí funkce print().

<details>
<summary><b>Řešení</b></summary>

```python
Tady zatím řešení není :)
```

</details>

## 2 - Detektivky

Vydavatel detektivek si eviduje prodané kusy u jednotlivých knih. V následujícím slovníku najdeš tři knihy a u každé z nich je počet prodaných kusů.

```python
sales = {
    "Zkus mě chytit": 4165,
    "Vrah zavolá v deset": 5681,
    "Zločinný steh": 2565,
}
```

Zkopíruj si slovník do svého programu.
Přidej do slovníku nově vydanou detektivku "Noc, která mě zabila", která zatím nebyla uvedena na trh, je tedy prodáno 0 kusů.
U knihy "Vrah zavolá v deset" zvyš počet prodaných kusů o 100.

<details>
<summary><b>Řešení</b></summary>

```python
Tady zatím řešení není :)
```

</details>

## 3 - Tombola

V následujícím slovníku jsou uložena čísla lístků tomboly a příslušné výhry.

```python
tombola = {
    7: "Láhev kvalitního vína Château Headache",
    15: "Pytel brambor z místního družstva",
    23: "Čokoládový dort",
    47: "Kniha o historii města",
    55: "Šiška salámu",
    67: "Vyhlídkový let balónem",
    79: "Moderní televizor",
    91: "Roční předplatné městského zpravodaje",
    93: "Společenská hra Sázky a dostihy",
}
```

Napiš program, který se nejprve zeptá uživatele na číslo jeho lístku. Vstup uživatele si převeď na int!
Zkontroluj, zda je číslo lístku ve slovníku. Pokud ne, vypiš text "Bohužel nevyhráváš nic." Pokud číslo ve slovníku je, vypiš uživateli, co vyhrál.

<details>
<summary><b>Řešení</b></summary>

```python
Tady zatím řešení není :)
```

</details>

## 4 - Paranoidní večírek

Pořadatel našeho večírku se stává stále více paranoidním a nyní rozhodl, že každý z hostů bude mít speciální heslo, které je platné jen pro něj. Seznam hostů a jejich hesel je níže. Napiš program, který nejprve zkontroluje, zda je host na seznamu, a pokud tam je, zeptá se ho na heslo a zkontroluje jeho správnost. Hostu na seznamu, který zadá správné heslo, vypíše program text: "Smíš vstoupit."

```python
passwords = {"Jiří": "tajne-heslo", "Natálie": "jeste-tajnejsi-heslo", "Klára": "nejtajnejsi-heslo"}
```

<details>
<summary><b>Řešení</b></summary>

```python
Tady zatím řešení není :)
```

</details>
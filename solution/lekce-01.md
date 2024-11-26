# Samostatné cvičení - lekce 1

## 1 - Jednoduchý výstup
Náš vůbec první program nebude dělat nic víc, než vypisovat text na obrazovku.

Založte si program **vstup-vystup.py**. V tomto programu pomocí funkce print() vypište na obrazovku Divadlo Pěst na oko. Program spusťte na konzoli a vyzkoušejte, že dělá co má.

Upravte tento program tak, že do proměnné nazev uložíte název nějakého divadelního představení a do proměnné cas uložte čas konání tohoto představení. Nyní pomocí funkce print() nechte program vypsat na obrazovku na jeden řádek název představení a čas konání, např. Zkrocení zlé ženy - 19:30.

Upravte dále program tak, že do proměnné hodina uložíte hodinu konání představení (jako celé číslo) a do proměnné minuta minutu konání, také jako celé číslo. Zařiďte, aby výstup programu vypadal takto: Zkrocení zlé ženy - 19:30.

<details>
<summary><b>Řešení</b></summary>

```Python
print("Divadlo Pěst na oko")

nazev = "Zkrocení zlé ženy"
cas = "19:30"
print(f"{nazev} - {cas}")

hodina = 19
minuta = 30
print(f"{nazev} - {hodina}:{minuta:02d}")
```

</details>

## 2 - Házení kostkami
Napište program **kostky.py**, který bude simulovat hod dvěma klasickými šestistěnnými kostkami. Jeho výstupu bude součet bodů na těchto dvou kostkách.

Nápověda:

- Generování náhodných čísel dělá funkce random.randint().
- Pokud chcete ve vašem programu použít modul random, musíte na jeho úplném začátku napsat příkaz import random

<details>
<summary><b>Řešení</b></summary>

```Python
import random
kostka1 = random.randint(1, 6)
kostka2 = random.randint(1, 6)
soucet = kostka1 + kostka2
print(f"Součet hodů kostkami: {soucet}")

```

</details>

## 3 - Generátor čísel
Napište program **generator.py**, kde zadáte dolní mez a horní mez do proměnné - a vypíše na výstup náhodné číslo v zadaných mezích.

<details>
<summary><b>Řešení</b></summary>

```Python
dolni_mez = 1
horni_mez = 100
nahodne_cislo = random.randint(dolni_mez, horni_mez)
print(f"Náhodné číslo mezi {dolni_mez} a {horni_mez} je {nahodne_cislo}")

```

</details>

## 4 - Jednoduchý vstup
Teď už budeme chtít, aby náš program dokázal získat vstup od uživatele.

Napište program **jmeno.py**, který získá jméno a příjmení od uživatele voláním funkce input(). Vypište je na obrazovku podobně jako v předchozím cvičení.
Nechte uživatele zadat také věk. Pozor na to, že funkce input() vždy vrací řetězec, ale my chceme v proměnné vek mít číslo. Použijte tedy funkci int(), abyste převedli uživatelem zadaný řetězec na číslo. Opět vypište na obrazovku jméno, příjmení a věk tak jako v předchozí verzi.

<details>
<summary><b>Řešení</b></summary>


```Python
jmeno = "Jan"
prijmeni = "Novák"
vek = int(input("zadej vek: "))  
print(f"{jmeno} {prijmeni}, {vek} let")
```



</details>
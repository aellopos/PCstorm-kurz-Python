# Samostatné cvičení - lekce 2 
## Cvičení - podmínky 
---

## 1 - Jednoduché podmínky
Založte si program **prihlaseni.py**. V tomto nechte uživatele zadat svoje uživatelské jméno a poté heslo. Pokud se heslo neshoduje s heslem simsalabim, vypište na výstup **Vstup nepovolen** a zavolejte funkci exit(), aby uživatel neznalý hesla nemohl s programem dál pracovat.

Na konec programu vlož příkaz, který se uživatele zeptá na věk. Pokud je uživatel starší 18 let, vypište na výstup **Smíš vstoupit** Pokud je mladší, vypiš **Vstup povolen od 18 let**

<details>
<summary><b>Řešení</b></summary>

```Python
uzivatelske_jmeno = input("Zadejte uživatelské jméno: ")
heslo = input("Zadejte heslo: ")

if heslo != "simsalabim":
    print("Vstup nepovolen")
    exit()
```

</details>

## 2 - Cena vstupenky

Vytvořte program **vstupenky01.py**, vytvořte si proměnnou plnaCena, do které uložte hodnotu 12.
Vytvořte podmínku, která do proměnné cena uloží cenu spočítanou podle věku uživatele dle následujících pravidel
- 0 euro pro návštěvníky mladší 6 let,
- 65% ze základní ceny pro návštěvníky 6 až 26 let (žák, student),
- 100% ze základní ceny pro návštěvníky 27 až 64 let (dospělý),
- 50% ze základní ceny pro ostatní (senior).
Nezapomeňte na zaokrouhlování, ať nám cena vyjde v celých centech. (využijte funkci round())

Nakonec spočtenou cenu vypište s nějakou hezkou zprávou na výstup.

<details>
<summary><b>Řešení</b></summary>

```Python
plnaCena = 12

vek = int(input("Zadejte svůj věk: "))

if vek < 6:
    cena = 0
elif vek <= 26:
    cena = round(0.65 * plnaCena, 2)
elif ek <= 64:
    cena = plnaCena
else:
    cena = round(0.5 * plnaCena, 2)

print(f"Cena vaší vstupenky je {cena} euro. Děkujeme za nákup!")
```

</details>

## 3 - Registrace

Založte si program **registrace.py**. Program nechá uživatele, aby si zvolil uživatelské jméno a heslo. Heslo jej nechejte zadat dvakrát a ověřte, že jej uživatel zadal dvakrát stejně. V opačném případě vypište varování, že hesla nejsou stejná. Při prvním zadávání ověřte, že heslo je bezpečné, což v tomto případě znamená, že je delší než 8 znaků (využijte funkci len()).

<details>
<summary><b>Řešení</b></summary>

```Python
uzivatelske_jmeno = input("Zadejte uživatelské jméno: ")
heslo1 = input("Zadejte heslo: ")

if len(heslo1) > 8:
    heslo2 = input("Zadejte heslo znovu pro potvrzení: ")
    if heslo1 == heslo2:
        print("Registrace úspěšná. Vítejte, " + uzivatelske_jmeno + "!")
    else:
        print("Hesla nejsou stejná. Zkuste to znovu.")
else:
    print("Heslo musí být delší než 8 znaků.")
```

</details>

## Cvičení - sekvenční hodnoty
---

## 1 - Řetězce jako sekvence
Vytvořte nový program **jmeno.py**. Do proměnné jmeno uložte svoje celé jméno a nechte vypsat jeho třetí, pátý a sedmý znak. Vyzkoušejte, co se stane, když budete chtít znak na pozici, která překračuje délku řetězce.

<details>
<summary><b>Řešení</b></summary>

```Python
jmeno = "František Novák"

print(f"Třetí znak: {jmeno[2]}")  # 'a'
print(f"Pátý znak: {jmeno[4]}")  # 't'
print(f"Sedmý znak: {jmeno[6]}")  # 'š'

```


</details>

## 2 - Seznamy
Vytvořte nový program **seznam.py**. V tomto programu vytvořte následující:
- Vytvořte nějaký seznam celých čísel, například počty diváků na několika po sobě jdoucích představeních.
- Vytvořte nějaký seznam desetinných čísel, například zaplněnost divadla v několika po sobě jdoucích představeních.
- Vytvořte nějaký seznam řetězců, například seznam názvů několika divadelních představení, která divadlo hraje. Uložte tento   seznam do proměnné hry. Uložte do nějaké proměnné druhou položku tohoto seznamu.
- Do proměnné hodnoceni uložte seznam hodnocení, které obdržela divadelní hra "Plyšáci na útěku" v různých recenzních časopisech. Hodnocení je vždy dvouprvkový seznam obsahující název recenzního časopisu jako řetězec a samotné hodnocení jako číslo mezi 1 až 10

<details>
<summary><b>Řešení</b></summary>

```Python
divaci = [120, 150, 130, 145, 160]
zaplnenost = [0.9, 0.85, 0.95, 0.80, 0.75]
hry = ["Hamlet", "Romeo a Julie", "Válka s mloky", "Faust", "Othello"]
druha_hra = hry[1]  # "Romeo a Julie"

hodnoceni = [
    ["Divadelní noviny", 8],
    ["Scéna", 7],
    ["Kultura21", 9],
    ["Theatrolog", 6]
]

```

</details>

## 3 - Ověřování hesla
Založte si program **heslo.py**. Ověřování hesla se někdy dělá tak, že se vás systém ptá pouze na některé jeho znaky. Napište program, který má uloženo heslo, které musí uživatel zadat. Pak se jej postupně zeptejte například na druhý, pátý a sedmý znak hesla. Propusťte uživatele pouze tehdy, zadá-li všechny tyto znaky správně.

<details>
<summary><b>Řešení</b></summary>

```Python
heslo = "bezpecneHeslo123"

druhy_znak = input("Zadejte druhý znak vašeho hesla: ")
paty_znak = input("Zadejte pátý znak vašeho hesla: ")
sedmy_znak = input("Zadejte sedmý znak vašeho hesla: ")

if (druhy_znak == heslo[1] and paty_znak == heslo[4] and sedmy_znak == heslo[6]):
    print("Heslo ověřeno, vstup povolen.")
else:
    print("Nesprávné znaky, vstup nepovolen.")

```

</details>
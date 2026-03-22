# 350-Python-strings

1. Srtings - Łańcuchy znaków

```python

a = 'tekst \n druga linia'

b = 'text' + 'tekst'

c = 'text ' * 3

d = """
tekst
wieloliniowy
"""

```

2. Fragmenty

```
 +---+---+---+---+---+---+
 | P | y | t | h | o | n |
 +---+---+---+---+---+---+
 0   1   2   3   4   5   6
-6  -5  -4  -3  -2  -1

---

for x in "Python":
  print(x)

---
word.find('...')

len(word)

```


```python

letter = word[0]  # word[-1]

fragment = word[1:3] # word[:4]

```


```python

sentence.split(' ')
sentence.splitlines()

```
3. Transformacje

```python
a.upper()  # title()
a.lower()  # swapcase()

---

txt.center(20)

---

word.strip()

---

sentence.replace('A','B')

---

txt.count("apple")

---

txt.find("welcome")

---

",".join(myTuple)
```

### Zadania
#### ZAD35001.

Przypisz do zmiennej akapit skopiowany z dowolnej strony internetowej (np lipsum.com) i wykonaj następujące polecenia:
- wypisz na ekranie fragment od 10 do 30 znaku
- zamień i wypisz pierwsze 10 znaków wersalikami
- zamień wszystkie litery na kapitaliki i wypisz pierwsze 100 znaków zmienionego tekstu

#### ZAD35002.

- Sprawdź i wypisz ile znaków zawiera tekst.
- Sprawdź i wypisz ile słów zawiera tekst.
- Wyswietl komunikat "Przekroczono limit znaków/słów" jeśli zostanie przekroczony limit 20 znaków/słów.

#### ZAD35003.

Wypisz ile razy słowo "yes" pojawia się w podanym tekście. Uwzględnij dowolną wielkość znaków w tekście.

#### ZAD35004.

Wypisz podany tekst w taki sposób, aby po kazdym wierszu z tekstu wstawić pusty wiersz

Na końcu i na początku dodaj linię zawierającą znaki "---***---"

Wszystkie wiersze (linie) wyśrodkuj dla lini o długości 40 znaków

- dodatkowo: podziel tekst na zwrotki zawierające 4 lini z odstępami 1 linii (oddzielone znakami "---<|>---")

#### ZAD35005.

Wypisz fragment dowolnego tekstu od pierwszego wystąpienia słowa "yes" do końca tekstu. Poniżej przykład wyniku:

```python
tekst = "No we can't or yes we can"

wynik = "yes we can"
```

### Info
- https://docs.python.org/pl/3.14/tutorial/introduction.html#text
- https://www.w3schools.com/python/python_strings.asp
- https://www.w3schools.com/python/python_strings_methods.asp

### Linki
- https://www.lipsum.com/

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
```


```python

letter = word[0]  # word[-1]

fragment = word[1:3] # word[:4]

```


```python

sentence.split(' ')

```
3. Transformacje

```python
a.upper()  # title()
a.lower()  # swapcase()

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
- zamień wsztstkie litery na kapitaliki i wypisz pierwsze 100 znaków

### Info
- https://docs.python.org/pl/3.14/tutorial/introduction.html#text
- https://www.w3schools.com/python/python_strings.asp
- https://www.w3schools.com/python/python_strings_methods.asp

### Linki
- https://www.lipsum.com/

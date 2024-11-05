# Markdown fájlok használata a GitHub-on
Ez egy md azaz Markdown fájl, ahova lehet írni egy rövid eligazítást, hogy pl. mit hol talál a felhasználó!
Minden markdown fájlnak sajátos szintaxisa van, ami kicsit eltérő a megszokott pl. html fájlokhoz képest.

A .md fájl kiterjesztés a Markdown jelölőnyelvet használó fájlokat jelöli. A Markdown egy egyszerű, könnyen olvasható és írható szöveges formátum, amelyet gyakran használnak dokumentációk és README fájlok írására, például a GitHubon. A Markdown segítségével egyszerű szöveges formában formázhatunk címeket, listákat, linkeket, képeket, kódrészleteket és táblázatokat. Ezáltal gyorsan áttekinthető és struktúrált dokumentációt hozhatunk létre, amelyet a legtöbb kódkezelő platform automatikusan formáz és jelenít meg.

 Íme néhány alapvető Markdown szintaxis, amellyel könnyedén rendszerezhetik és formázhatják a projektjeiket:

# Címek létrehozása

# Nagy cím (H1)
## Kisebb cím (H2)
### Alcím (H3) stb.
```Markdown
# Nagy cím (H1)
## Kisebb cím (H2)
### Alcím (H3) stb.
```
A címek # jelekkel kezdődnek, és minél több # jel, annál kisebb a cím szintje.

# Felsorolások

## Számozott lista:
1. Első pont
2. Második pont
## Pontozott lista:
- Első elem
- Második elem
# Kiemelések

Dőlt: *dőlt szöveg* vagy _dőlt szöveg_
Félkövér: **félkövér szöveg** vagy __félkövér szöveg__
Félkövér és dőlt: ***félkövér és dőlt szöveg***
# Kódrészletek

## Egysoros kód:
`kódrészlet`
## Többsoros kódblokk:
```javascript
console.log("Hello, world!");
```
## Linkek beszúrása:
[Link szövege](https://sulla.hu)
## Képek hozzáadása
![Kép leírása](https://sulla.hu/Polgar.jpg)
# Táblázatok
| Fejléc 1 | Fejléc 2 |
| -------- | -------- |
| Tartalom | Tartalom |
# Hivatkozások jegyzéke
Forrásokat is beszúrhatnak, például [1] és [2] jelölésekkel és a dokumentum végén definiálhatják őket

[1]: https://sulla.hu
[2]: https://www.kkszki.hu

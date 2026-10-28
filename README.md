# Statika Időgép

Nyolcszintes, böngészőben futó fizikajáték a **statika** témakör tanulásához. A játékos az őskortól a modern korig halad, és minden korszakban egy-egy statikai elvet alkalmaz egy interaktív feladatban.

| # | Korszak | Feladat | Elv |
|---|---|---|---|
| 1 | Őskor | Forgáspont a szikla elgördítéséhez | Emelőtörvény |
| 2 | Ókori Egyiptom, Kr. e. 2560 k. | Rámpa szöge, nedves vagy száraz homok | Lejtő és súrlódás |
| 3 | Szirakúza, Kr. e. 3. sz. | Súlyok Archimédész mérlegén | Nyomatéki egyensúly |
| 4 | Róma, Kr. e. 1. sz. | Kötélágak száma a darun | Csigasor |
| 5 | Pisa, 1178 | Legnagyobb dőlés borulás nélkül | Állékonyság |
| 6 | Kora újkor, 1586 | Kötélhossz a templomi csillárhoz | Erők felbontása |
| 7 | Ipari forradalom, 1847 | Húzott és nyomott rudak a hídban | Csomóponti módszer |
| 8 | Modern kor, 1949 | Ellensúly a toronydaruhoz | Billenés és ellensúly |

## Használat

Egyetlen statikus `index.html`, build lépés nélkül. Helyben is megnyitható, vagy bármilyen statikus tárhelyen (pl. Vercel, GitHub Pages) kiszolgálható.

- A haladást (csillagokat, megnyitott szinteket) a böngésző `localStorage`-a tárolja.
- A lábléc **Tanári mód** gombja minden szintet megnyit, így órán bármelyik korszakra rá lehet ugrani.

## Modell

Egyszerűsített modellek: g ≈ 10 m/s², merev testek, súlytalan rudak és kötelek. A rajzok szemléltetők, nem mindenhol méretarányosak.

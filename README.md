# Srpska prezimena
Biblioteka srpskih prezimena

Prezime kao nasledni deo informacije o poreklu svakog pojedinca jeste neophodan za stvaranje šire slike o poreklu čitavog naroda. Do sada je sastavljeno više obimnih zbirki sa srpskim prezimenima i postoji dosta objava na internetu na ovu temu ali izneti podaci do sada još uvek nisu formatirani u obliku pogodnom za mašinsku upotrebu. Pred vama je prva zbirka ovog tipa sačuvana na ćiriličnom i na latiničnom pismu u tri različita formata:

- u vidu liste sa prezimenima razdvojenim novim redom sačuvanih pod `.txt` ekstenzijom
- u `csv` formatu (Comma-separated values)
- u `json` formatu

# Hijerarhijski pregled projekta
Faljovi su grupisani prema formatu i sačuvani pod nazivom jednakim početnom slovu prezimena koje sadrže. U osnovnom direktorijumu i u pod-direktorijumu [/prezimena-latinica](/prezimena-latinica) nalazi se fajl `srpska-prezimena` sačuvan u gore navedena tri formata koji sadrži sva prezimena poređana po azbučnom redu u osnovnom direktorijumu projekta i po abecednom redu u pod-direktorijumu [/prezimena-latinica](/prezimena-latinica)

Stablo projekta prikazano je na dijagramu ispod:
```
csv
├─ А.csv
├─ Б.csv
└─ В.csv
json
├─ А.json
├─ Б.json
└─ В.json
lista
├─ А.txt
├─ Б.txt
└─ В.txt
prezimena-latinica
├─ csv
│   ├─ A.csv
│   ├─ B.csv
│   └─ C.csv
├─ json
│   ├─ A.json
│   ├─ B.json
│   └─ C.json
├─ lista
│   ├─ A.txt
│   ├─ B.txt
│   └─ C.txt
├─ srpska-prezimena-lat.csv
├─ srpska-prezimena-lat.json
└─ srpska-prezimena-lat.txt
srpska-prezimena.csv
srpska-prezimena.json
srpska-prezimena.txt
README.md
LICENSE
```
Ukoliko imate potrebu za nekim drugim formatom podataka možete nas kontaktirati direktno putem naše email adrese `fondacija@glasnik.org.rs`

# Podaci o projektu
**Licenca:** MIT

**Datum kreiranja projekta:** 25.08.2019.

> Ukoliko imate predolg za dodavanje prezimena možete poslati PR.
> Ukoliko smatrate da neko prezime treba da bude uklonjeno sa liste ili ste primetili slovnu grešku, otvorite novu grešku.

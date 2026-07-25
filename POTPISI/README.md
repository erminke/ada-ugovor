# POTPISI — Registar potpisnika Ugovora o viziji

Original ugovora je **jedini fajl grane `main`** ovog repozitorija, zaključan
i nepromjenjiv: commit `2ebb8d8bfd846ef1e73e0400395ce3dd71b8d386`.
Original se ne dira nikad. Potpisi i budući amandmani žive ovdje, pored njega.

## Pravilo distroa (values-copyleft)

Svako ko napravi distro — fork, whitelabel, ili izvedeni sistem zasnovan na
ADA-i — obavezuje se da:

1. **Nosi original**: `UGOVOR.md` ide u distro netaknut, s referencom na
   commit `2ebb8d8`.
2. **Potpisuje javno**: vlasnik distroa dodaje svoj potpis u ovaj registar
   (pull request na granu `potpisi`), svojim imenom i datumom.
3. **Prenosi obavezu**: svaki dalji distro njegovog distroa preuzima iste
   tri obaveze. Vrijednosti se nasljeđuju kao i kod — bez izuzetka.
4. **Prihvata pushback**: potpis uključuje i tri uslova iz ugovora (ko
   definiše dobro — otvoreno; pravo izlaska; ADA odgovara korisniku, ne
   mreži) i ustavno pravilo o vanjskim sistemima.

Potpis ne sprječava korupciju — čini je javnom i dokazivom. Git historija je
notar: svaki potpis nosi hash, datum i ime, zauvijek.

## Format potpisa

Fajl `POTPISI/NNNN-ime.md`:

```
# Potpis: <ime>, <uloga/distro>
Datum: <YYYY-MM-DD>
Original: 2ebb8d8bfd846ef1e73e0400395ce3dd71b8d386

<izjava svojim riječima — zašto potpisuješ>
```

## Registar

| # | Ime | Distro / uloga | Datum |
|---|-----|----------------|-------|
| 0001 | Ermin | ADA Core (upstream) — osnivač | 2026-07-26 |

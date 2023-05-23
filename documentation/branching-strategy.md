
## Veje
V repozitoriju imamo `main` in `development` veji. 

- Glavna veja `main` naj vsebuje najnovejšo, stabilno in produkcijsko pripravljeno verzijo kode.
- Razvojna veja `development` pa se uporablja za kontinuirano delo na novih funkcijah in odpravljanje napak. To je ločena veja od glavne veje in ponuja prostor za razvijalce, da izvajajo spremembe, jih testirajo in združujejo v glavno vejo, ko so pripravljene za objavo.
 

## Konvencije imenovanja vej
- tvoje_ime/feat/ime_naloge/ime_veje
- tvoje_ime/fix/ime_naloge/ime_veje
- tvoje_ime/chore/ime_naloge/ime_veje

#### Primeri
- Uporabi to, če dodajaš novo funkcijo v aplikacijo

`janez/feat/prijava`

- Uporabi to, če popravljaš težavo v aplikaciji

`janez/fix/prijava`

- Uporabi to, če prenavljaš aplikacijo

`janez/chore/refaktoriranje-razreda`

## Konvencije imenovanja commitov

Uporabi enega od teh treh tipov kot predpono za vsak commit:

- `feat`
- `fix`
- `chore`

#### Primeri

- Dodajanje prijavne strani

`feat: dodaj prijavno stran`

- Popravljanje prijavne strani

`fix: prijavna stran`

- Prenavljanje prijavne strani

`chore: prenovi prijavno stran`

## Potek dela
- pridobi naj novejše stanje iz `develoment`
- ustvari novo vejo iz `development`
- potrdi svoje spremembe
- Združi nove spremembe iz razvoja v svojo vejo (po želji)
- Pošji svoje spremembe na Github
- Pojdi na GitHub in odpri zahtevek za `Pull Request` (tvoja veja naj se združi v `development`)

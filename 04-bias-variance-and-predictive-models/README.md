# Pristranskost, varianca in napovedni modeli

## Ocenjevanje točnosti modelov
- merjenje kakovosti prilagajanja
- kompromis med pristranskostjo in varianco

### Merjenje kakovosti prilagajanja
- pogosto uporabljeno merilo: **kvadratna napaka (MSE)**
- $$MSE = \frac{1}{n} \sum_{i=1}^n (y_i - \hat{y}_i)^2$$
- izberemo takšno linearno funkcijo, da je MSE minimizirana
- v splošnem velja, da imajo bolj fleksibilne metode nižji MSE na učnih podatkih

## Pristranskost
- napaka, ki nastane zaradi modeliranja zapletenega problema s preprostim modelom
- linearna regresija npr. predpostavlja, da obstaja premo sorazmerje med atributi in razredom, kar pa je v resničnosti zelo malo verjetno
- **bolj**, kot je metoda kompleksna oz. fleksibilna, **manjša** je njena pristranskost

## Varianca
- za koliko se spremeni ocena $f$, če bi imeli drugačno učno množico
- **bolj**, kot je metoda fleksibilna, **večja** je njena varianca

## Bayes error rate
# Predictive modeling - predvidevanje

## Učenje
- pridobivanje in izboljšava znanja, veščin, obnašanja, ...
- iščemo funkcijo, ki se najbolj prilega podatkom

## Statistika in strojno učenje
- strojno učenje gradi model na podlagi primerov vhodnih podatkov (vzorcev)
- $$Y = f(X) + \epsilon$$
- $$Y_i = f(\mathbf{X}_i) + \epsilon_i$$

## Cilji učenja
1. napovedovanje
2. sklepanje

### Napovedovanje
- če dobimo nov (še ne viden) vektor atributov $\mathbf{X}$ in imamo dobro oceno funkcije $f$, lahko dobimo dobro oceno razreda $Y$.

### Sklepanje
- iz $Y$ sklepamo, kakšen je bil $\mathbf{X}$
- tudi ugotavljanje, kateri atributi vplivajo na rezultat

## Ocenjevanje funkcije $f$
- s pomočjo učnih podatkov in statističnih metod
  - parametrične metode
  - neparametrične metode

### Parametrične metode
 - oceno funkcije $f$ dobimo iz ocene njenih parametrov
    1. na podlagi poznavanja vhodnih podatkov se odločimo za model (npr. linearni, kvadratni, ...).   
       - Primer lin. modela:
$$f(\mathbf{X}_i) = \beta_0 + \beta_1 \mathbf{X}_{\textit{i}1} + \beta_2 \mathbf{X}_{\textit{i}2} + \ldots + \beta_n \mathbf{X}_{\textit{i}n}$$
    1. z uporabo učnih podatkov prilagodimo parametre modela
        - npr. za linearni model: metoda najmanjših kvadratov 

### Neparametrične metode
- ne sklepajo o obliki funkcije $f$
- lahko se prilagodijo raznolikim $f$, vendar za točno oceno potrebujemo veliko število vhodnih podatkov

## Regresija in kvalifikacija
 - **Regresija:** Y je zvezen oz. številčen
 - **Klasifikacija:** Y je kategoričen

## Kriteriji uspeha strojnega učenja
- Kako izbrati najboljši model?
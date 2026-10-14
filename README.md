#  Metrocount
Desenvolupament d'una aplicacio per saber la quantitat que tan ple va el metro de Barcelona
 
![Text de prova](projecte-imatge.jpg)

## Links

[Documentació de la API de TMB "Incluyent autobusos"](https://developer.tmb.cat/api-docs/v1 )

[Més dades per consultar de la API de TMB"](https://developer.tmb.cat/data)


## Context

La nostra idea es fer-hi en Python una demostració de com es podria fer un comptador de persones en els vagons del metro de Barcelona perquè aixì a traves d'una aplicació es pogues consultar que tan ocupat va el metro i llavors els passatgers poguesin decidir si es convenient entrar o no al vago

## Com es fara?

Resumidament el que teniem pensat nosaltres es implementar uns sensors just a la porta dels vagons del metro perquè així compti les persones que hi pasen, la nostra forma que habiem pensat d'implementar els sensors es tractaria de dos sensors, un que s'encarregui de comptar els que entren i l'altre dels que surten, si es possible fer els sensors s'actualitzin de manera rapida i frequent (cada 0,5 segons per exemple), i que els infrarojos sapigan diferenciar quan pasen persones i quan no. 
(D'Aquest tema s'ha en parlare en un altre secció sobre els que s'ens queda fora de l'abast i quins problemes podrien surgir)

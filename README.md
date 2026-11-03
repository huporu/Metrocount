#  Metrocount
 
![Text de prova](/img/projecte-imatge.jpg)
![Imatge esquema resumit](/img/metrocount.jpg)

## Links

[Documentació de la API de TMB "Incluyent autobusos"](https://developer.tmb.cat/api-docs/v1 )

[Més dades per consultar de la API de TMB"](https://developer.tmb.cat/data)


## Context

El nostre projecte de Metrocount s'enmarca com si fossim uns treballadors de TMB (Transports Metropilitans de Barcelona) i volem implementar un sistema informatic capaç de comptar persones en els vagons del metro de Barcelona

## Descripció

El nostre sistema el que aportaria seria que les persones poguessin veure quantes persones hi han en els vagons, això resoldria el problema que tenen dubtes sobre que tan ple van els vagons i si es millor agafar el metro o esperar-se a que hi passí un que hi te menys persones per la seva comoditat.

Per el nostre sistema habiem pensat en implementar una serie de tecnologies com seria uns sensors infrarojos en les portes del vagó perquè així hi poguin comptar quantes persones entren, un codi que es comuniqui amb els infrarojos i que sigui capaç de communicar-se perqué així poguin comptar les persones que hi entren i emmagatzemar-les perque es mostrin en una interficie i un servidor que mostri l'informació.

Aquest sistema estaria enfocat per aquelles persones que utilitzen el metro d'una manera regular i activa i es volen estalviar estar en vagons on hi esta ple de gent


 

## Problemes i fora d'abast

Els problemes d'abast en els quals ens podríem arribar a trobar és la precisió d'aquestes dades, un dels principals reptes d'aquest projecte és que les dades no podran ser 100% precises, ja que podrien sorgir problemes com que hi ha una avalancha de persones que entrin juntes al vagó i que el sensor compta com si hagués entrat una persona, però en realitat hi ha entrat dues o tres persones o inclús més. <br>

També en la part de recollida de dades els repetidors de wifi que hi ha que serveixen per enviar les dades cap al servidor sobre les persones podria fallar per culpa de l'alta demanda de persones que estiguessin utilitzant la xarxa<br>

Per això la nostra visió és fer que les dades siguin aproximades, encara que sempre hi busquem que sigui el més precís possible resulta ser que es una tasca bastant complicada saber amb exactitud la quantitat real dels passatgers, per això la nostra idea és fer una barra amb colors (per exemple de verd a vermell) en la qual hi hagi una fletxa que indiqui que tan ocupat està el tren segons les dades recollides dels sensors.

# Vaja5-buttons-LED-STM32F0

Glede na vašo razvojno ploščico in razširitveno vezje s tipkami, izberite ustrezne digitalne vhode za tipke in izhode za modro in zeleno LED. Izbrani pini: 
T1: __PB10__, T2:__PB11__, T3:__PB12__ T4:__PB13__, T5:__PB14__, T6:__PB15__, zelena LED: __PC9__, modra LED: __PC8__.

KOMENTAR NA DELOVANJE
Če pritisnemo tipko 1, zelena LED utripa s frekvenco 2 Hz, in sicer 5x.
Če pritisnemo tipko 1, modra LED utripa s frekvenco 2 Hz, in sicer 5x.
Če pritisnemo tipko 1, modra in zelena LED utripata izmenično s frekvenco 1 Hz, vsaka LED 5x.
Če pritisnemo tipko 1, prikazuje SOS (Morsejeva abeceda) z zeleno LED, modra pa za eno sekundo naznani konec in začetek SOS.
Če pritisnemo tipko 1, utripanje zelene LED: začetna frekvenca je 1 Hz, vsak naslednji cikel je frekvenca  mnogokratnik števila 2, vse do frekvence 1000 Hz. 
Če pritisnemo tipko 1, modra in zelena LED utripata izmenično z začetno frekvenco 1000 Hz, vsak naslednji cikel je frekvenca deljena z 2, vse do frekvence 1 Hz. 

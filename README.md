# AoC_22_Baltie

AoC 2022 solving in Baltie language

Ján Plachý - Jajopi

More info about Baltie: https://sgpsys.com/

## Čo je to ten inputter.bpr?

Baltík dokáže čítať textové súbory po jednotlivých záznamoch, čo efektívne znamená,
že číta textové súbory v kvadratickom čase. To trvá dlho pre 1000 a neúnosne dlho pre viac, než 2000 riadkov,
preto sa to nedá použiť, ak si človek nie je na 100% istý, čo robí. To tu nefunguje :D.
Takže inputter.bpr rozseká .txt súbor na menšie (dĺžky 100 záznamov) a potom ich jednotlivé programy čítajú postupne,
a to ich beh skoro vôbec nezdržuje.

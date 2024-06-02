# Granular Synthesizer

Un patcher de sintetizare granulara - extragerea unor mici portiuni dintr-un fisier incarcat si manipularea pozitiei, vitezei de redare si lungimii acestora, rezultatul fiind redat in loop.

## (Instalare)

Este suficienta deschiderea patcherului *granular.maxpat* in MaxMSP.

## (Utilizare)

In prima faza se incarca un fisier audio din stocarea locala si se seteaza avelopa dorita:
![[assets/max_1.gif]]

Apoi se pot configura parametrii granulei de sunet:
![[assets/max_2.gif]]

## (Istoric)

(07.05) Patch inceput, functionalitati de baza implementate

(12.05) Patch functional in cea mai mare parte, dar cu probleme precum clicuri si pocnituri, si posibilitatea setarii pozitia de inceput a granulei prea tarziu in sample cat sa mai poata fi redata

(01.06) Patch finalizat, clicks & pops corectate iar granula nu mai poate depasi lungimea fisierului incarcat
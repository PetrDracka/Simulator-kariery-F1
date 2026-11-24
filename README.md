# Simulátor kariéry F1

## Cíle práce
Cílem práce je vytvořit funkční simulátor kariéry jezdce Formule 1. Hráč si vytvoří vlastního závodníka, bude postupovat napříč sezónami, podepisovat smlouvy s týmy, vylepšovat monopost a bojovat o titul mistra světa.

## Rozsah aplikace
* **Co bude aplikace umět:** Tvorba jezdce, kalendář závodů, simulace výsledků závodů a kvalifikací na základě statistik jezdce a vozu, správa financí a smluv, průběžný žebříček šampionátu, ukládání a načítání rozehrané kariéry.
* **Co aplikace obsahovat nebude:** 3D grafiku ani přímé ovládání formule v reálném čase (jde o manažerskou/textovou simulaci).

## Uživatelské role
* **Hráč (Jezdec):** Hlavní role. Zakládá novou kariéru, rozhoduje mezi závody (trénink, smlouvy, vývoj), spouští simulaci závodů a ukládá svůj postup.

## Zvolená technologie
* **Jazyky / Technologie:** PHP, HTML5, CSS3
* **Zdůvodnění výběru:** 
  * Kombinace PHP, HTML a CSS umožňuje vytvořit přehlednou webovou aplikaci, kterou lze snadno spustit přímo v prohlížeči.
  * PHP je ideální pro zpracování herní logiky na straně serveru, výpočty výsledků závodů, správu statistik a ukládání postupu v kariéře.
  * HTML a CSS zajistí strukturu a moderní vizuální vzhled uživatelského rozhraní (tabulky šampionátu, profil jezdce, správa monopostu).

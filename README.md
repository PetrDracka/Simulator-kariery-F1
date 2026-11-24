Simulator-kariery-F1

#Cíl práce
Cílem práce je vytvořit simulátor kariéry jezdce Formule 1. Hráč si vytvoří vlastního závodníka, bude postupovat napříč sezónami, podepisovat smlouvy s týmy, vylepšovat monopost a bojovat o titul mistra světa.

# Rozsah aplikace
* **Co bude aplikace umět:** Tvorba jezdce, kalendář závodů, simulace výsledků závodů a kvalifikací na základě statistik jezdce a vozu, správa financí a smluv, průběžný žebříček šampionátu, ukládání a načítání rozehrané kariéry.
* **Co aplikace obsahovat nebude:** 3D grafiku ani přímé ovládání formule v reálném čase (jde o manažerskou/textovou simulaci).

# Uživatelské role
* **Hráč (Jezdec):** Hlavní role. Zakládá novou kariéru, rozhoduje mezi závody (trénink, smlouvy, vývoj), spouští simulaci závodů a ukládá svůj postup.

# Zvolená technologie
* **Jazyk:** Python 3
* **Zdůvodnění výběru:** 
  * Python je ideální jazyk pro vývoj logiky, textových simulací a správu dat (ukládání stavu kariéry do souborů, výpočty statistik závodů).
  * Nabízí přehlednou a srozumitelnou syntaxi, což mi umožní soustředit se na herní mechaniky a pravidla Formule 1 namísto složitého nastavování prostředí.
  * Díky široké komunitě existuje spousta návodů a knihoven, které lze v případě potřeby využít pro rozšíření aplikace.

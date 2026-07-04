# Analýza rizikových faktorů a závažnosti dopravních nehod na federálních dálnicích v Brazílii

Tento repozitář obsahuje semestrální projekt, který předkládá komplexní analýzu 2,01 milionu dopravních nehod zaznamenaných na brazilských federálních dálnicích v časovém rozmezí let 2007–2023. Primárním výzkumným cílem práce je identifikace determinant ovlivňujících závažnost nehod (klasifikovaných jako nehody s úmrtím nebo těžkým zraněním) a statistická verifikace hypotéz týkajících se vlivu bezpečnostní infrastruktury a environmentálních podmínek.

## Metodologický rámec a cíle
* Výzkum je strukturován v souladu se standardizovanou metodikou CRISP-DM (Cross-Industry Standard Process for Data Mining).
* Součástí analytického procesu je sestavení a optimalizace klasifikačních algoritmů (Logistická regrese, Random Forest) za účelem predikce závažnosti dopravních kolizí.

## Hlavní závěry výzkumu
* **Vliv stacionárních radarů:** Byla prokázána statisticky signifikantní korelace mezi přítomností stacionárního měřiče rychlosti a nižší pravděpodobností vážných následků dopravních nehod. Přítomnost tohoto prvku koreluje s relativním snížením rizika vzniku vážné nehody o 24,1 %.
* **Meteorologický paradox:** Byla verifikována existence tzv. bezpečnostního paradoxu, kdy zhoršené povětrnostní podmínky (např. déšť) aktivují adaptivní chování řidičů a vedou k významnému poklesu letality kolizí. Naopak ideální podmínky (jasno) indukují falešný pocit bezpečí, což ústí v nehody s disproporčně vyšší závažností.
* **Temporální rizikové faktory:** Analýza identifikovala kritické časové okno v období víkendových nocí, kdy pravděpodobnost vážné nehody stoupá z výchozích 13,99 % na 26,02 %. Tento rozdíl představuje relativní nárůst rizika o 86,0 %.
* **Výsledky prediktivního modelování:** Výstupy modelu Random Forest potvrdily, že klíčovými determinantami ovlivňujícími závažnost nehody jsou primárně prostorové charakteristiky (rozlišení intravilánu a extravilánu, typ vozovky) a temporální kontext (hodina vzniku nehody).

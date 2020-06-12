    Copyright (C) 2020 Per Tunedal, Stockholm, Sweden
    Author: Per Tunedal <info@tunedal.nu>

    This file is part of Dicelist. Word lists for making secure 
    passwords with the help of 4-5 dices.

    Dicelist is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    Dicelist is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with Dicelist.  If not, see <https://www.gnu.org/licenses/>.

Råd
===
Listan för 5 tärningar innehåller 7776 ord på 2-6 bokstäver, medan listan 
för 4 tärningar innehåller 1296 ord på 2-4 bokstäver.

Använd i första hand listan för 5 tärningar. Då behöver du bara komma ihåg 
6 ord. Om det är viktigt för dig att orden är korta och inte så ovanliga, 
välj istället den korta listan för 4 tärningar. Då behöver du istället komma 
ihåg 8 ord, men de är mer vardagliga.

Om du får några ord du inte känner igen, eller vet vad de betyder: slå upp dem 
i en ordbok eller sök på internet för att ta reda på vad de står för. Då blir 
de lättare att komma ihåg för dig.

4 dice list
===========
Användning
----------
Använd 4 tärningar för att slumpa fram en sifferkombination mellan 1111 och 
6666, som motsvarar ett ord i listan. Kombinationen 1234 motsvarar t.ex. ordet 
"avog", medan kombinationen 5316 motsvarar ordet "roa". Du behöver slumpa fram 
minst 8 ord för att få ett säkert lösenord. Skilj orden åt på något sätt, t.ex. 
med mellanslag, med någon siffra, med något tecken eller genom att skriva första 
eller sista bokstaven med versaler.

Säkerhet
--------
En lösenmening bestående av 8 slumpade ord from denna lista har något högre 
säkerhet än ett lösenord som består av 12 slumpade tecken valda från en 
uppsättning bestående av versala och gemena bokstäver (a-z), samt siffror 
(0-9) och specialtecken.

Motivering
----------
En lösenmening med 8 slumpade ord är väldigt mycket lättare att komma ihåg, 
än ett lösenord med 12 slumpade tecken.

4 dice list
===========

Användning
----------
Använd 4 tärningar för att slumpa fram en sifferkombination mellan 1111 och 
6666, som motsvarar ett ord i listan. Kombinationen 1234 motsvarar t.ex. ordet 
"avog", medan kombinationen 5316 motsvarar ordet "roa". Du behöver slumpa fram 
minst 8 ord för att få ett säkert lösenord. Skilj orden åt på något sätt, t.ex. 
med mellanslag, med någon siffra, med något tecken eller genom att skriva första 
eller sista bokstaven med versaler.

Säkerhet
--------
En lösenmening bestående av 8 slumpade ord from denna lista har något högre 
säkerhet än ett lösenord som består av 12 slumpade tecken valda från en 
uppsättning bestående av versala och gemena bokstäver (a-z), samt siffror 
(0-9) och specialtecken.

Motivering
----------
En lösenmening med 6 slumpade ord är väldigt mycket lättare att komma ihåg, 
än ett lösenord med 12 slumpade tecken.

5 dice list
===========
Användning
----------
Använd 5 tärningar för att slumpa fram en sifferkombination mellan 11111 och 
66666, som motsvarar ett ord i listan. Kombinationen 12345 motsvarar t.ex. ordet 
"avig", medan kombinationen 53164 motsvarar ordet "samsas". Du behöver slumpa fram 
minst 6 ord för att få ett säkert lösenord. Skilj orden åt på något sätt, t.ex. 
med mellanslag, med någon siffra, med något tecken eller genom att skriva första 
eller sista bokstaven med versaler.


Beskrivning
===========
För många år sedan tänkte jag göra en svensk version av DiceWare-ordlistan*, 
utan de konstiga siffer- och bokstavskombinationerna. Det var emellertid 
besvärligt att hitta ord, så jag lade det åt sidan. Nu insåg jag att det 
skulle vara möjligt att skapa en ny ordlista genom att utgå från Apertiums 
nya svenska ordlista apertium-swe.swe.dix (För mer information om Apertium 
se www.apertium.org) Apertium måste distribueras under GPL version 2, eller 
senare.

Jag blev sedan inspirerad av de alternativa ordlistor som sammanställts av 
The Electronic Frontier Foundation (EFF) år 2016. De har försökt undvika 
sällsynta, svårstavade och "fula" ord. De har även utöver listan för 5 
tärningar, gjort en kortare lista med korta och lätta ord för 4 tärningar.
Den kortare listan kräver att man skapar ett lösenord på minst 8 ord, medan 
det räcker med minst 6 ord om man använder den längre listan.

Jag började därför med att göra denna korta lista med ord på högst 4 bokstäver, 
som inte innehåller å, ä eller ö. Först filtrerade jag orden från Apertium 
efter min egen lista på rättstavade ord, där de flesta av orden är 
högfrekventa. Därefter har jag manuellt rensat bort svåra ord, delvis med 
hjälp av en frekvensordlista. Jag har även rensat bort homofoner och fula 
ord.

Jag har däremot inte uteslutit ord som samtidigt kan råka utgöra början eller 
slut på andra ord. Därför bör orden skrivas med en avgränsing, t.ex. mellanslag, 
emellan dem. Annars minskar antalet möjliga kombinationer en aning och därmed 
också säkerheten.

Senare gjorde jag klart den långa listan för 5 tärningar, med ord som är högst 
6 bokstäver långa. Den listan är inte lika noga kontrollerad som den kortare 
listan för 4 tärningar. Orden är kontrollerade mot stopplistor med t.ex. 
potentiellt anstötliga ord och homofoner. Dessutom är stavningen kontrollerad 
med Hunspell. 

Föreslå förbättringar
=====================
Om du hittar ord som du inte tycker om, gör gärna en pull request med ditt 
förslag till ändring. Alla substantiv och verb jag fått från Apertium, utom de 
bortfiltrerade, är redan använda i den långa listan. Några adjektiv är också 
använda. Du kan hitta nya ord att välja bland i filen adjectives_not_used.txt

Bidra med en ordlista
=====================
Bidrag är välkomna! Gör en ordlista på ditt eget språk. Det är ganska enkelt 
om ditt språk används i Apertium. Se www.apertium.org
Annars kan du samla ihop en massa text till en stor corpus och sedan göra en 
frekvensordlista. Stryk de långa och de ovanliga orden. Substantiv och verb 
väljs i första hand.

Per Tunedal

* Diceware är ett varumärke som tillhör A G Reinhold. 
http://world.std.com/~reinhold/diceware.html

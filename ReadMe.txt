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

4 dice list
===========

Usage
-----
Use 4 dices to randomly get a combination of digits between 1111 and 6666, that 
corresponds to a word in the list. The combination 1234 corresponds e.g. to the 
word "avog" and the combination 5316 corresponds to the word "roa". You need to 
get at least 8 words to form a secure password. Separate the words in some way, 
e.g. with space, some number, some symbol or by writing the first or last 
letter in upper case.

Security
--------
A passphrase consisting of 8 random words from this list has slightly stronger 
security than a password consisting of 12 random characters chosen from a set 
consisting of upper and lower case characters (a-z), numbers and symbols.

Rational
--------
A passphrase of 8 random words is far more easy to remember, than a password 
of 12 random characters. 

5 dice list
===========

Usage
-----
Use 5 dices to randomly get a combination of digits between 11111 and 66666, that 
corresponds to a word in the list. The combination 12345 corresponds e.g. to the 
word "avig" and the combination 53164 corresponds to the word "samsas". You need to 
get at least 6 words to form a secure password. Separate the words in some way, 
e.g. with space, some number, some symbol or by writing the first or last 
letter in upper case.

Security
--------
A passphrase consisting of 6 random words from this list has approximately 
the same security as a password consisting of 12 random characters chosen 
from a set consisting of upper and lower case characters (a-z), numbers and symbols.

Rational
--------
A passphrase of 6 random words is far more easy to remember, than a password 
of 12 random characters. 

Description
===========
Many years ago I intended to make a Swedish version of the DiceWare* word
list, without the strange numbers and combinations of characters. However,
it turned out to be difficult to find words, thus I put the projekt aside.
Now, I realized the possibility to create a new word list based on 
Apertiums new Swedish word list apertium-swe.swe.dix (For more information 
on Apertium, please see www.apertium.org) Apertium has to be distributed 
under the license GPL version 2, or later. 

Now, I was inspired by the alternative word lists compiled by The 
Electronic Frontier Foundation (EFF) in the year 2016. They have tried to 
avoid the inclusion of rare words, words that are hard to spell and vulgar 
words. Further more, they have made a shorter list of short and easy words for 
4 dices, as a complement to the word list for 5 dices. The short list requires 
at least 8 words in a password, opposed to only 6 words if you use the longer 
list.

Thus, I started with the short list with words of at most 4 characters, not 
containing the letters å, ä or ö. I began with filtering the words from 
Apertium, with the help of my own list of correctly spelled words, most of 
them with high frequency. Then I manually removed rare words, partly by the 
help of a word frequenzy list. Additionnally, I have removed homophones and 
vulgar words.

On the contrary, I haven't excluded words that might be the begining or the 
end of other words. Hence, you should write the words with a separator, e.g. 
space, between them. Otherwise, the number of possible combinations will 
decrease slightly, and thus the security as well.

Later, I finished the longer list for 5 dices with words of at most 6 characters.
This list is not as thoroughly checked as the shorter list for 4 dices. The 
words are checked against checklists with e.g. potentially offensive words and 
spell checked with Hunspell. If you find words you don't like, feel free to make a 
pull request. All nouns and verbs I got from Apertium, exept those filtered out, 
are already used. Some adjectives are used as well. You can find new words to 
choose among in the file adjectives_not_used.txt 

Contribute a word list
======================
Contributions are welcome! Make a wordlist in your own language. It's fairly 
easy if your language is used in Apertium. See www.apertium.org
Otherwise, you can gather a lot of text to make a large corpus and create a 
frequenzy list. Remove long and infrequent words. Nouns and verbs are a first 
hand choice.

Per Tunedal

* Diceware is a trademark of A G Reinhold. 
http://world.std.com/~reinhold/diceware.html

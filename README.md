# Mallan-Gendo
Unambigous artificial auxiliary pronunciation for hexadecimal numerals

## Introduction
Mallan-Gendo is a system to make someone able to pronounce hexadecimal values, just like we can pronounce decimals values. Hexadecimal values are widely used in computer science and software engineering to give a more convenient representation to humans of binary values that are native to computers. Hexadecimal values can be converted in a lossless way from and to binary and decimal values.

There are 16 different distinct words, like mallan and gendo, each for one of the 16 hexidecimal values, which range from 0-F (0-15 in decimal). The lowest value is mallan (0), the highest value in gendo (F, or 15 as decimal value). They can be compounded as in mallan-gendo, and the compounded words can be combined in pairs such as maillan-gendo mallan-gendo. A compounded word is equivalent to a byte (more precisely an octet). Combined pairs are equivalent to multiple bytes/octets.

The name mallan-gendo itself therefore is the decimal value 15 (hexadecimal value 0F), and contains in itself all the possible phonetic distinctions that are employed in constructing the sounds of the hexadecimal values. The sounds at each of 4 positions in the word are paired, where each pair has a 'zero' and a 'value' sound, corresponding to 0 or a value of 1, 2, 4 or 8:

|Low sound|High sound|Low value|High value|
|:-:|:-:|:-:|:-:|
|m---|g---|0|8|
|-a--|-e--|0|4|
|--ll-|--nd-|0|2|
|---an|---o|0|1|

The total value of a word is therefore calculated by replacing each sound in all 4 positions in the word with its actual value, and then summing all the resulting values, e.g.:

|Word|Sounds|Values per sound|Total value|
|:-:|:-:|:-:|:-:|
|mallan|m+a+ll+an|0+0+0+0|0|
|gendo|g+e+nd+0|8+4+2+1|15|

## Pronunciation
|Letter|English|Remarks|IPA|
|:-:|:-----:|:-----:|:-:|
|m|as in mum||/m/|
|a|as in father|short vowel as American English, not long as in British English|/&#x0251;/|
|l|as in let|always thin, never thick as in dull|/l/|
|n|as in not||/n/|
|g|as in get|always hard, never soft as in gem|/g/|
|e|as in yes||/&#x025B;/|
|d|as in dad||/d/|
|o|as in no|rounded vowel as American English, not unrounded as in British English|/o/|

### Syllables, stress, compound words and combined pairs 
Each single word always contains two syllables (separated with a '.'), with the stress always on the first syllable (indicated by a preceding '&#0712;'), e.g.:

|Word|IPA|
|:-:|:-:|
|mallan|/&#0712;m&#x0251;.l&#x0251;n/|
|gendo|/&#0712;g&#x025B;n.do/|

Compound words are joined with a '-', and in such cases the second word have the primary stress and the first word the secondary stress (indicated by a preceding '&#0716;'), e.g.:

|Word|IPA|
|:-:|:-:|
|mallan-gendo|/&#0716;m&#x0251;.l&#x0251;n &#0712;g&#x025B;n.do/|

Compound words can be combined in pairs (separated with a space), e.g.:

|Word|IPA|
|:-:|:-:|
|mallan-gendo mallan-gendo|/&#0716;m&#x0251;.l&#x0251;n &#0712;g&#x025B;n.do &#0716;m&#x0251;.l&#x0251;n &#0712;g&#x025B;n.do/|

## Full chart
|Word|IPA|Hexadecimal value|Decimal value|
|:-:|:-:|:-:|:-:|
|mallan|/&#0712;m&#x0251;.l&#x0251;n/|0|0|
|mallo|/&#0712;m&#x0251;.lo/|1|1|
|mandan|/&#0712;m&#x0251;n.d&#x0251;n/|2|2|
|mando|/&#0712;m&#x0251;n.do/|3|3|
|mellan|/&#0712;m&#x025B;.l&#x0251;n/|4|4|
|mello|/&#0712;m&#x025B;.lo/|5|5|
|mendan|/&#0712;m&#x025B;n.d&#x0251;n/|6|6|
|mendo|/&#0712;m&#x025B;n.do/|7|7|
|gallan|/&#0712;g&#x0251;.l&#x0251;n/|8|8|
|gallo|/&#0712;g&#x0251;.lo/|9|9|
|gandan|/&#0712;g&#x0251;n.d&#x0251;n/|A|10|
|gando|/&#0712;g&#x0251;n.do/|B|11|
|gellan|/&#0712;g&#x025B;.l&#x0251;n/|C|12|
|gello|/&#0712;g&#x025B;.lo/|D|13|
|gendan|/&#0712;g&#x025B;n.d&#x0251;n/|E|14|
|gendo|/&#0712;g&#x025B;n.do/|F|15|

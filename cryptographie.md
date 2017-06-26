# cryptographie
## chiffre de César

>#### Comment encoder avec le chiffre de César ? (Principe de chiffrement)
>Le code César est en fait une simple substitution monoalphabétique, c'est-à-dire qu'une lettre est remplacée par une seule autre. Le code César a la particularité qu'il est basé sur un simple décalage de l'alphabet.
>#### Quels sont les autres noms du Code César?
>###### Dans le code Helène, L vaut N (Hélène LN), le décalage est de 2
>###### Dans le code Oeufs Pourris, E vaut I (Oeufs pourris, E pour I), le décalage est de 4
>###### Dans le code KO, K vaut O (KO : Knock Out), le décalage est de 4
>###### Dans le code Pété, P vaut T (Pété PT), le décalage est de 4
>###### Dans le code Hervé, R vaut V (Hervé RV), le décalage est de 4
>###### Dans le code Jeux Olympiques, J vaut O (JO : jeux olympiques), le décalage est de 5
>###### Dans le code Agé, A vaut G (Agé AG), le décalage est de 6
>###### Dans le code Eiffel, F vaut L (Eiffel FL), le décalage est de 6
>###### Dans le code PV, P vaut V (Procès Verbal PV), le décalage est de 6
>###### Dans le code WC, W vaut C (WC : Water Closet), le décalage est de 6
>###### Dans le code Avocat, A vaut K (Avocat), le décalage est de 10
>###### Dans le code Acheté, H vaut T (Acheté HT), le décalage est de 12
>###### Dans le code J'y vais, J vaut V (J'y vais JV), le décalage est de 12
>###### Dans le code ROT13, l'alphabet devient réversible, le décalage est de 13
>###### Dans le code Baden Powell (fondateur du scoutisme, B vaut P, le décalage est de 14
>###### Dans le code Hergé/RG, R vaut G (Hergé Renseignements Généraux RG), le décalage est de 15
>###### Dans le code Déesse, D vaut S (Déesse DS), le décalage est de 15
>###### Dans le code Happé, A vaut P (happé), le décalage est de 15
>###### Dans le code Cassé, K vaut C (Cassé KC), le décalage est de 18
>###### Dans le code Meuh, M vaut E (Meuuuh ME), le décalage est de 18
>###### Dans le code A voté, A vaut T (a voté), le décalage est de 19

>#### Quand le code César a-t-il été inventé ?
>On l'ignore mais César est né en 100 av. JC

## Code ACSII

>#### Comment encoder avec la table ASCII ? (Principe de chiffrement)
>Le chiffrement consiste a remplacer chaque caractère par sa valeur dans la table ASCII. Les caractères n'existant pas dans la table ne peuvent pas être codés.
>
>dCode s'écrit 1100100 1000011 1101111 1100100 1100101 en binaire et 100 67 111 100 101 en décimal.
>#### Comment décoder par table ASCII ? (Principe de déchiffrement)
>Le déchiffrement consiste à remplacer chaque valeur par le caractère correspondant dans la table ASCII.
1100100 1000011 1101111 1100100 1100101 devient dCode.
>#### Comment reconnaitre le chiffre ASCII ?
>Le message est généralement écrit soit en binaire, soit en décimal, soit en hexadécimal.
>Les valeurs les plus courantes doivent correspondre aux caractères courant tels que les lettres (entre 65 et 122 en décimal)
>Comment passer d'une lettre ASCII minuscule à une majuscule ?
>Dans le code ASCII il y a une différence de 32 entre une lettre majuscule et une lettre minuscule. Il faut donc ajouter 32 au code ASCII d'une majuscule pour obtenir une minuscule et soustraire 32 au code ASCII d'une minuscule pour avoir une majuscule.
A (65) et a (97)
>#### Qu'est-ce que la table ASCII ?
>
>##### Table ASCII 7 bits complète

Décimal | Octal | Hex | Binaire | Caractère | Info
---|---|---|---|---|---
000 | 000 | 00 | 0000000 | NUL | (Null char.)
001|001|01|0000001|SOH|(Start of Header)
002|002|02|0000010|STX|(Start of Text)
003|003|03|0000011|ETX|(End of Text)
004|004|04|0000100|EOT|(End of Transmission)
005|005|05|0000101|ENQ|(Enquiry)
006|006|06|0000110|ACK|(Acknowledgment)
007|007|07|0000111|BEL|(Bell)
008|010|08|0001000|BS|(Backspace)
009|011|09|0001001|HT|(Horizontal Tab)
010|012|0A|0001010|LF|(Line Feed)
011|013|0B|0001011|VT|(Vertical Tab)
012|014|0C|0001100|FF|(Form Feed)
013|015|0D|0001101|CR|(Carriage Return)
014|016|0E|0001110|SO|(Shift Out)
015|017|0F|0001111|SI|(Shift In)
016|020|10|0010000|DLE|(Data Link Escape)
017|021|11|0010001|DC1|(XON)(Device Control 1)
018|022|12|0010010|DC2|(Device Control 2)
019|023|13|0010011|DC3|(XOFF)(Device Control 3)
020|024|14|0010100|DC4|(Device Control 4)
021|025|15|0010101|NAK|(Negative Acknowledgement)
022|026|16|0010110|SYN|(Synchronous Idle)
023|027|17|0010111|ETB|(End of Trans. Block)
024|030|18|0011000|CAN|(Cancel)
025|031|19|0011001|EM|(End of Medium)
026|032|1A|0011010|SUB|(Substitute)
027|033|1B|0011011|ESC|(Escape)
028|034|1C|0011100|FS|(File Separator)
029|035|1D|0011101|GS|(Group Separator)
030|036|1E|0011110|RS|(Request to Send)(Record Separator)
031|037|1F|0011111|US|(Unit Separator)
032|040|20|0100000|SP|(Space)
033|041|21|0100001|!|
034|042|22|0100010|"|
035|043|23|0100011|#|	
036|044|24|0100100|$|	
037|045|25|0100101|%|	
038|046|26|0100110|&|	
039|047|27|0100111|'|	
040|050|28|0101000|(|	
041|051|29|0101001|)|	
042|052|2A|0101010|\*|	
043|053|2B|0101011|+|	
044|054|2C|0101100|,|	
045|055|2D|0101101|-|	
046|056|2E|0101110|.|	
047|057|2F|0101111|/|	
048|060|30|0110000|0|	
049|061|31|0110001|1|	
050|062|32|0110010|2|	
051|063|33|0110011|3|	
052|064|34|0110100|4|	
053|065|35|0110101|5|	
054|066|36|0110110|6|	
055|067|37|0110111|7|	
056|070|38|0111000|8|	
057|071|39|0111001|9|	
058|072|3A|0111010|:|	
059|073|3B|0111011|;|	
060|074|3C|0111100|<|	
061|075|3D|0111101|=|	
062|076|3E|0111110|>|	
063|077|3F|0111111|?|	
064|100|40|1000000|@|	
065|101|41|1000001|A|	
066|102|42|1000010|B|	
067|103|43|1000011|C|	
068|104|44|1000100|D|	
069|105|45|1000101|E|	
070|106|46|1000110|F|	
071|107|47|1000111|G|	
072|110|48|1001000|H|	
073|111|49|1001001|I|	
074|112|4A|1001010|J|	
075|113|4B|1001011|K|	
076|114|4C|1001100|L|	
077|115|4D|1001101|M|	
078|116|4E|1001110|N|	
079|117|4F|1001111|O|	
080|120|50|1010000|P|	
081|121|51|1010001|Q|	
082|122|52|1010010|R|	
083|123|53|1010011|S|	
084|124|54|1010100|T|	
085|125|55|1010101|U|	
086|126|56|1010110|V|	
087|127|57|1010111|W|	
088|130|58|1011000|X|	
089|131|59|1011001|Y|	
090|132|5A|1011010|Z|	
091|133|5B|1011011|[|	
092|134|5C|1011100|\|	
093|135|5D|1011101|]|	
094|136|5E|1011110|^|	
095|137|5F|1011111|\_|	
096|140|60|1100000|\`|	
097|141|61|1100001|a|
098|142|62|1100010|b|
099|143|63|1100011|c|
100|144|64|1100100|d|	
101|145|65|1100101|e|	
102|146|66|1100110|f|	
103|147|67|1100111|g|	
104|150|68|1101000|h|	
105|151|69|1101001|i|	
106|152|6A|1101010|j|	
107|153|6B|1101011|k|	
108|154|6C|1101100|l|	
109|155|6D|1101101|m|	
110|156|6E|1101110|n|	
111|157|6F|1101111|o|	
112|160|70|1110000|p|	
113|161|71|1110001|q|	
114|162|72|1110010|r|	
115|163|73|1110011|s|	
116|164|74|1110100|t|	
117|165|75|1110101|u|	
118|166|76|1110110|v|	
119|167|77|1110111|w|	
120|170|78|1111000|x|	
121|171|79|1111001|y|	
122|172|7A|1111010|z|	
123|173|7B|1111011|{|	
124|174|7C|1111100|||	
125|175|7D|1111101|}|	
126|176|7E|1111110|~|	
127|177|7F|1111111|DEL|

## décalage ASCII
>#### Principe de chiffrement
>La table ASCII est composée de 128 caractères, il est possible de décaler ceux-ci d'un rang N pour obtenir un autre caractères.
>#### Principe de déchiffrement
>Il suffit de décaler la table ASCII dans le sens inverse du chiffrement.

## Enigma ([wiki](http://bit.ly/2sSesOG))
>#### Comment encoder avec Enigma ? (Principe de chiffrement)
>dCode propose de coder/décoder avec 3 types de machines (Wehrmacht/Luftwaffe à 3 rotors et Kriegsmarine à 3 ou 4 rotors). Chaque modèle fonctionne avec certains rotors et réflecteurs.

Machine|Rotors|Réflecteurs
---------------|----------------|----------------
Wehrmacht / Luftwaffe 3|I, II, III, IV et V|B ou C
Kriegsmarine 3|I, II, III, IV, V, VI, VII et VIII|B ou C
Kriegsmarine 4|I, II, III, IV, V, VI, VII, VIII, Beta et Gamma|BThin ou CThin

>Les rotors ont des encoches pour l'entrainement, pour le rotor I, le passage de Q à R entraîne le rotor suivant, les lettres d'entrainement changent en fonction des rotors et ne peuvent pas être configurées ici.
>Les rotors peuvent être montés dans n'importe quel ordre mais Beta et Gamma ne peuvent être qu'en position 4 et doivent s'accompagner des réflecteurs B Thin ou C Thin.
>Un rotor peut avoir une position initiale variable (il y a 26 positions) qu'il faut configurer à chaque usage. Les rotors sont équipés d'une roue alphabet, qui était fixe dans les premières machines Enigma, mais qui peut se déplacer sur la roue dans les versions suivantes, sa position est appelée Ringstellung.
>#### Comment reconnaitre le chiffre Enigma ?
>Le message chiffré n'est constitué que de lettres et n'a aucune lettre initiale identique à la lettre chiffrée.
>#### Quelle est la différence entre la position initiale des rotors et la position de la roue alphabet ?
>Certains rotors ont la roue sur laquelle il y a un alphabet qui est fixe, dans ce cas rotor et roue sont la même chose, mais parfois la roue n'est pas fixe et peut être décalée par rapport au rotor.
>#### Quand Enigma a-t-il été inventé ?
>Vers 1920

# asciituring
🇩🇪
Dies ist eine Turing-Maschine, die in der Lage ist, 4-Bit Binärzahlen in Hexadezimalzahlen und anschließend anhand des ASCII-Standards in Text umzuwandeln. 
Sie kann eine reine Abfolge von Nullen und Einsen ohne Leerzeichen, oder eine mit Leerzeichen in 8-Bit geteilte Eingabe ebenso verarbeiten, wie eine, die in 4-Bit geteilt ist, braucht hierzu aber deutlich länger, da sie einmal den kompletten Input in 4-Bit-Gruppen spaltet, und dabei sehr viel Zeit damit verbringt, ihn zu verschieben.
Es ist auch möglich, direkt eine Eingabe in Hexadezimal zahlen zu tätigen, und den Binär-dekodierungsprozess zu überspringen. Hierzu muss `0x` an den Anfang gesetzt werden, und die Zeichenkette darf nicht unterbrochen sein.
Sie wurde für diesen Turing-Maschinen-Simulator geschrieben: https://morphett.info/turing/turing.html

🇫🇷
Ceci est une machine de Turing qui est capable de convertir les nombres binaires de 4 bits en nombres hexadécimaux et puis en texte lisible s’il a été encodé en ASCII.
Elle est capable de traiter une entrée composée d’une pure séquence de zéros et de uns, ou une entrée coupée en octets. Malheureusement elle est beaucoup plus lente avec ces types d’entrée, car elle doit d’abord découper les données en groupes de 4 bits, ce qui nécessite de déplacer le texte entier, un caractère à la fois. Par conséquence elle perd beaucoup de temps en déplaçant la tête de lecture d’un bout à l’autre.
Il est possible de donner une entrée déjà en format hexadécimale, afin de sauter le procès de décodage des nombres binaires. Elle doit commencer par `0x` et elle ne doit pas contenir d’espace.
Je l’ai créée pour fonctionner dans le simulateur de machine de Turing disponible sur le lien suivant: https://morphett.info/turing/turing.html

🏴󠁧󠁢󠁥󠁮󠁧󠁿
This is a Turing machine that is capable of converting 4 bit binary numbers to hexadecimal numbers and then to legible text, provided it was encoded using ASCII.
It is able to process input composed of just ones and zeroes, as well as input split into 8 bit groups. Unfortunately it is a lot slower when input is provided this way, because it will spend a lot of time converting the input into 4-bit groups, during which it will move the entire text one character at a time and as such it loses a lot of time moving the head back and forth.
It can also skip the binary decoding process when given input already in hexadecimal format. It must begin with `0x` and mustn’t contain any spaces.
I’ve written it to work with the following Turing machine simulator: https://morphett.info/turing/turing.html


# TODO
- [ ] Das ganze so umschreiben, dass bereits dekodiertes links des noch enkodierten auf frei gewordenem Platz geschrieben wird, um den Kopf nicht mehr so viel bewegen zu müssen

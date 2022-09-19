# Based
#picoCTF2019 #GeneralSkills #netcat #bases #examenParcial1
## Objetivo
To get truly 1337, you must understand different data encodings, such as hexadecimal or binary. Can you get the flag from this program to prove you are on the way to becoming 1337? Connect with `nc jupiter.challenges.picoctf.org 29221`.
## Solución
Tras ejecutar la conexión por netcat al servidor dado se nos da una serie de textos decodificados en distintas bases.
- Binario
- Octal
- Hexadecimal
Cada intento da distintas palabras cifradas, ergo cada intento debes descifrar palabras distintas.
```bash
┌──(kali㉿kali)-[~]
└─$ nc -v jupiter.challenges.picoctf.org 29221
DNS fwd/rev mismatch: jupiter.challenges.picoctf.org != ec2-3-131-60-8.us-east-2.compute.amazonaws.com
jupiter.challenges.picoctf.org [3.131.60.8] 29221 (?) open
Let us see how data is stored
nurse
Please give the 01101110 01110101 01110010 01110011 01100101 as a word.
...
you have 45 seconds.....

Input:
nurse
Please give me the  157 166 145 156 as a word.
Input:
oven
Please give me the 6e75727365 as a word.
Input:
nurse
You've beaten the challenge
Flag: picoCTF{learning_about_converting_values_00a975ff}
```
==**picoCTF{learning_about_converting_values_00a975ff}**==
## Notas adicionales
Para este reto decidí utilizar páginas online que permitan decodificar las distintas bases dadas directamente a strings.
## Referencias
- Binario a texto:
	https://www.traductorbinario.com/
- Octal a texto:
	https://photo333.com/octal-to-text-es.php
- Hexadecimal a texto:
	https://www.convertstring.com/es/EncodeDecode/HexDecode
# Glitch Cat
#Beginner_picoMini_2022 #GeneralSkills #netcat #python #shell 
## Objetivo
Our flag printing service has started glitching! `$ nc saturn.picoctf.net 53933`
## Solución
Al conectarnos mediante NetCat obtenemos lo siguiente:
```bash
┌──(kali㉿kali)-[~/Downloads]
└─$ nc saturn.picoctf.net 53933  
'picoCTF{gl17ch_m3_n07_' + chr(0x61) + chr(0x34) + chr(0x33) + chr(0x39) + chr(0x32) + chr(0x64) + chr(0x32) + chr(0x65) + '}'

```
Parece ser ASCII.
Según el interprete de python...
```bash
┌──(kali㉿kali)-[~]
└─$ python
Python 3.10.5 (main, Jun  8 2022, 09:26:22) [GCC 11.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> chr(0x61)
'a'
>>> chr(0x34)
'4'
>>> chr(0x33)
'3'
>>> chr(0x39)
'9'
>>> chr(0x32)
'2'
>>> chr(0x64)
'd'
>>> chr(0x32)
'2'
>>> chr(0x65)
'e'
```
Bandera: ==**picoCTF{gl17ch_m3_n07_a4392d2e}**==
## Notas adicionales

## Referencias

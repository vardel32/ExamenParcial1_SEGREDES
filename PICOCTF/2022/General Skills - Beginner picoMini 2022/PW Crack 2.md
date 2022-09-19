# PW Crack 2
#Beginner_picoMini_2022 #GeneralSkills #password_cracking
## Objetivo
Can you crack the password to get the flag? Download the password checker [here](https://artifacts.picoctf.net/c/17/level2.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/17/level2.flag.txt.enc) in the same directory too.
## Solución
Este password checker ya es un poco más elegante, contiene la contraseña cifrada en código ASCII.
```python
if( user_pw == chr(0x34) + chr(0x65) + chr(0x63) + chr(0x39) ):
```
Utilizando el interprete de python...
```python
>>> print (chr(0x34) + chr(0x65) + chr(0x63) + chr(0x39))
4ec9
```
```bash
┌──(kali㉿kali)-[~/Downloads]
└─$ python level2.py          
Please enter correct password for flag: 4ec9
Welcome back... your flag, user:
picoCTF{tr45h_51ng1ng_9701e681}
```
Bandera: ==**picoCTF{tr45h_51ng1ng_9701e681}**==
## Notas adicionales

## Referencias

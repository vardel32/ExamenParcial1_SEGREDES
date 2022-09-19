# Lets Warm Up
#picoCTF2019 #GeneralSkills #examenParcial1
## Objetivo
If I told you a word started with 0x70 in hexadecimal, what would it start with in ASCII?
## Solución
```bash
┌──(kali㉿kali)-[~]
└─$ python
Python 3.10.5 (main, Jun  8 2022, 09:26:22) [GCC 11.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> int(0x70)
112
>>> chr(112)
'p'
>>> 

```
BANDERA  = picoCTF{p}.
## Notas adicionales

## Referencias
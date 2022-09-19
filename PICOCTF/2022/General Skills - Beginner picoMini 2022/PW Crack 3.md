# ### PW Crack 3
#Beginner_picoMini_2022 #GeneralSkills #password_cracking #hashing
## Objetivo
Can you crack the password to get the flag? Download the password checker [here](https://artifacts.picoctf.net/c/24/level3.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/24/level3.flag.txt.enc) and the [hash](https://artifacts.picoctf.net/c/24/level3.hash.bin) in the same directory too. There are 7 potential passwords with 1 being correct. You can find these by examining the password checker script.
## Solución
Revisando el password checker nos encontramos con que existen siete posibles contraseñas, siendo solo una de ellas la correcta.
- "f09e"
- "4dcf"
- "87ab"
- "dba8"
- "752e"
- "3961"
- "f159"
Probando las distintas contraseñas de una en una descubrimos que la contraseña correcta es `dba8`
```bash
Please enter correct password for flag: dba8
Welcome back... your flag, user:
picoCTF{m45h_fl1ng1ng_cd6ed2eb}

```
Bandera: ==**picoCTF{m45h_fl1ng1ng_cd6ed2eb}**==.
## Notas adicionales

## Referencias

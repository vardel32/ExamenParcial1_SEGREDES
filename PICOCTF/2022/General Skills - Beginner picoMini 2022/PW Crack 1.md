# PW Crack 1
#Beginner_picoMini_2022 #GeneralSkills #password_cracking
## Objetivo
Can you crack the password to get the flag? Download the password checker [here](https://artifacts.picoctf.net/c/51/level1.py) and you'll need the encrypted [flag](https://artifacts.picoctf.net/c/51/level1.flag.txt.enc) in the same directory too.
## Solución
Se descargan ambos archivos y primeramente inspeccionamos el archivo `level1.py` para entender un poco mejor como funciona el password checker.
Mediante un cat podemos ver la siguiente linea de código:
```python
    if( user_pw == "691d"):
```
Es evidente que la contraseña es "691d".
```bash
┌──(kali㉿kali)-[~/Downloads]
└─$ python level1.py 
Please enter correct password for flag: 691d
Welcome back... your flag, user:
picoCTF{545h_r1ng1ng_56891419}

```
Bandera: ==**picoCTF{545h_r1ng1ng_56891419}**==
## Notas adicionales

## Referencias

# 2Warm
#picoCTF2019 #GeneralSkills #examenParcial1
## Objetivo
Can you convert the number 42 (base 10) to binary (base 2)?
## Solución
 ```bash
┌──(kali㉿kali)-[~]
└─$ python
Python 3.10.5 (main, Jun  8 2022, 09:26:22) [GCC 11.3.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> print(bin(42))
0b101010
 ```
 
 La bandera picoCTF quedaría de la siguiente manera:
**==picoCTF{101010}==**.
## Notas adicionales
Existe un pequeño **error** en el binario que devuelve python, ya que lo regresa con un 0 y 'b' de más.
## Referencias
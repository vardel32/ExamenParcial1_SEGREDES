# fixme2.py
#Beginner_picoMini_2022 #GeneralSkills #python 
## Objetivo
Fix the syntax error in the Python script to print the flag. [Download Python script](https://artifacts.picoctf.net/c/67/fixme2.py)
## Solución
El error se encontraba en la siguiente linea:
```python
# Check that flag is not empty
if flag = "":
  print('String XOR encountered a problem, quitting.')

```
Ya que el operador de asignación `=` y el operador de comparación de igualdad `==` no tienen la misma función.
Se soluciona ese error de sintaxis y tenemos...
```bash
┌──(kali㉿kali)-[~/Downloads]
└─$ python fixme2.py       
That is correct! Here's your flag: picoCTF{3qu4l1ty_n0t_4551gnm3nt_f6a5aefc}
```
Bandera: ==**picoCTF{3qu4l1ty_n0t_4551gnm3nt_f6a5aefc}**==
## Notas adicionales

## Referencias

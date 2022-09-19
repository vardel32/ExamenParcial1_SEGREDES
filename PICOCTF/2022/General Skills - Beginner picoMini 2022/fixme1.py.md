# fixme1.py
#Beginner_picoMini_2022 #GeneralSkills #python 
## Objetivo
Fix the syntax error in this Python script to print the flag. [Download Python script](https://artifacts.picoctf.net/c/38/fixme1.py)
## Solución
El error radicaba en la identación de la última linea de texto del archivo fuente, más particularmente la siguiente:
```python
  print('That is correct! Here\'s your flag: ' + flag)

```
Evidentemente la identación no es la adecuada. Al solucionarlo y ejecutar el archivo nos da lo siguiente:
```bash
┌──(kali㉿kali)-[~/Downloads]
└─$ python fixme1.py 
That is correct! Here's your flag: picoCTF{1nd3nt1ty_cr1515_09ee727a}

```
Bandera ==**picoCTF{1nd3nt1ty_cr1515_09ee727a}**==
## Notas adicionales

## Referencias
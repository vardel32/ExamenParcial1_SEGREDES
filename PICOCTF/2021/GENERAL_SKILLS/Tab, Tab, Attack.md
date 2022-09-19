# ### Tab, Tab, Attack
#GeneralSkills #picoCTF2021 #examenParcial1 #Descompresion 
## Objetivo
Using tabcomplete in the Terminal will add years to your life, esp. when dealing with long rambling directory structures and filenames: [Addadshashanammu.zip](https://mercury.picoctf.net/static/3afd18a65e42b80526aa87f9766c588b/Addadshashanammu.zip)
## Solución
```bash
┌──(kali㉿kali)-[~/…/Assurnabitashpi/Maelkashishi/Onnissiralis/Ularradallaku]
└─$ cat fang-of-haynekhtnamet | strings | grep picoCTF
*ZAP!* picoCTF{l3v3l_up!_t4k3_4_r35t!_d32e018c}

```
Bandera: ==**picoCTF{l3v3l_up!_t4k3_4_r35t!_d32e018c}**==
## Notas adicionales
Se puede saltar la tarea de estar moviendote entre directorios individuales, ya que al momento de descomprimir el archivo zip se muestran las carpetas y los archivos creados.
Se puede hacer un cd directo al ultimo directorio copiando y pegando la ruta.
## Referencias
Unzip:
https://www.hostinger.mx/tutoriales/comando-unzip-linux
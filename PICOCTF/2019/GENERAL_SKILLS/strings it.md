# Strings it
#picoCTF2019 #GeneralSkills #examenParcial1
## Objetivo
Can you find the flag in [file](https://jupiter.challenges.picoctf.org/static/5bd86036f013ac3b9c958499adf3e2e2/strings) without running it?
## Solución
Después de mostrar el contenido de un archivo con un comando que permita verlo, como _cat_ o _strings_ se puede utilizar el comando _grep_ para filtrar por palabras clave.
```bash
┌──(kali㉿kali)-[~/Downloads]
└─$ strings strings|grep picoCTF
picoCTF{5tRIng5_1T_827aee91}
```
==**picoCTF{5tRIng5_1T_827aee91}**==
## Notas adicionales

## Referencias
Procedimiento hecho en el reto Bandit [[Nivel 7 - 8]]
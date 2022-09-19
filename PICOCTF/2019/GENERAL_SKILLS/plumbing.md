# Titulo
#picoCTF2019 #GeneralSkills #netcat #examenParcial1
## Objetivo
Sometimes you need to handle process data outside of a file. Can you find a way to keep the output from this program and search for the flag? Connect to `jupiter.challenges.picoctf.org 7480`.
## Solución
Tras ejecutar la conexión de forma simple, sin otro comando además de _nc_ la conexión nos devuelve un montón de lineas de texto entre las cuales debería estar la bandera.
Ya que buscar de forma manual sería muy complicado una vez más recurrimos al comando _grep_ para filtrar los resultados.
```bash
┌──(kali㉿kali)-[~]
└─$ nc -v jupiter.challenges.picoctf.org 7480 | grep picoCTF
DNS fwd/rev mismatch: jupiter.challenges.picoctf.org != ec2-3-131-60-8.us-east-2.compute.amazonaws.com
jupiter.challenges.picoctf.org [3.131.60.8] 7480 (?) open
picoCTF{digital_plumb3r_06e9d954}

```
==**picoCTF{digital_plumb3r_06e9d954}**==
## Notas adicionales
Se pueden aplicar comandos después del mismo _nc_ que permitan hacer procesos con la conexión establecida.
## Referencias
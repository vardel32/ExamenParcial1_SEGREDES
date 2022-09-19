# First Grep
#picoCTF2019 #GeneralSkills #examenParcial1
## Objetivo
Can you find the flag in [file](https://jupiter.challenges.picoctf.org/static/495d43ee4a2b9f345a4307d053b4d88d/file)? This would be really tedious to look through manually, something tells me there is a better way.
## Solución
Se descarga el archivo proporcionado con el comando wget.
```bash
┌──(kali㉿kali)-[~/Downloads]
└─$ wget https://jupiter.challenges.picoctf.org/static/495d43ee4a2b9f345a4307d053b4d88d/file
--2022-09-15 12:13:37--  https://jupiter.challenges.picoctf.org/static/495d43ee4a2b9f345a4307d053b4d88d/file
Resolving jupiter.challenges.picoctf.org (jupiter.challenges.picoctf.org)... 3.131.60.8
Connecting to jupiter.challenges.picoctf.org (jupiter.challenges.picoctf.org)|3.131.60.8|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 14551 (14K) [application/octet-stream]
Saving to: ‘file’

file                 100%[===================>]  14.21K  --.-KB/s    in 0s      

2022-09-15 12:13:37 (273 MB/s) - ‘file’ saved [14551/14551]
```
Si se hace un _cat_ unicamente al archivo _file_ se obtiene un texto enorme en el cual se encuentra la bandera de este reto. Buscarla de forma manual sería muy complicado así que se utiliza el comando _grep_ en union al comando _cat_.
```bash
┌──(kali㉿kali)-[~/Downloads]
└─$ cat file | grep picoCTF
picoCTF{grep_is_good_to_find_things_dba08a45}
```
==**picoCTF{grep_is_good_to_find_things_dba08a45}**==
## Notas adicionales

## Referencias

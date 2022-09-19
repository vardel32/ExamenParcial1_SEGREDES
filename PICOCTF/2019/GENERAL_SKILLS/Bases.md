# Bases
#picoCTF2019  #GeneralSkills #bases #examenParcial1
## Objetivo
What does this `bDNhcm5fdGgzX3IwcDM1` mean? I think it has something to do with bases.
## Solución
```bash
┌──(kali㉿kali)-[~]
└─$ echo 'bDNhcm5fdGgzX3IwcDM1' | base64 -d
l3arn_th3_r0p35  
```
==**picoCTF{l3arn_th3_r0p35}**==
## Notas adicionales
Aparentemente base64 es un tipo de cifrado habitual en los concursos CTF.
## Referencias
https://linuxhint.com/bash_base64_encode_decode/
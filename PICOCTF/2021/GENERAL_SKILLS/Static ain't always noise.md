# Static ain't always noise
#GeneralSkills #picoCTF2021 #examenParcial1 
## Objetivo
Can you look at the data in this binary: [static](https://mercury.picoctf.net/static/ff4e569d6b49b92d090796d4631a2577/static)? This [BASH script](https://mercury.picoctf.net/static/ff4e569d6b49b92d090796d4631a2577/ltdis.sh) might help!
## Solución
Se proporciona un archivo binario, al leerlo mediante un _cat_ únicamente, es obvio que no se podrá hacer la lectura satisfactoria.
Así que se utiliza la siguiente secuencia de comandos.
```bash
┌──(kali㉿kali)-[~/Downloads]
└─$ cat static | strings | grep picoCTF
picoCTF{d15a5m_t34s3r_ccb2b43e}

```
Bandera: ==**picoCTF{d15a5m_t34s3r_ccb2b43e}**==
## Notas adicionales

## Referencias

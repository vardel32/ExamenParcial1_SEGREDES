# Obedient Cat
#GeneralSkills #picoCTF2021 #examenParcial1 
## Objetivo
This file has a flag in plain sight (aka "in-the-clear").
## Solución

```bash
┌──(kali㉿kali)-[~/Downloads]
└─$ wget https://mercury.picoctf.net/static/fb851c1858cc762bd4eed569013d7f00/flag
--2022-09-13 10:22:30--  https://mercury.picoctf.net/static/fb851c1858cc762bd4eed569013d7f00/flag
Resolving mercury.picoctf.net (mercury.picoctf.net)... 18.189.209.142
Connecting to mercury.picoctf.net (mercury.picoctf.net)|18.189.209.142|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 34 [application/octet-stream]
Saving to: ‘flag’

flag             100%[==========>]      34  --.-KB/s    in 0s      

2022-09-13 10:22:30 (38.5 MB/s) - ‘flag’ saved [34/34]

                                                                    
┌──(kali㉿kali)-[~/Downloads]
└─$ cat flag
picoCTF{s4n1ty_v3r1f13d_28e8376d}
                                                                    
┌──(kali㉿kali)-[~/Downloads]
└─$ 

```
 picoCTF{s4n1ty_v3r1f13d_28e8376d}
## Notas adicionales

## Referencias
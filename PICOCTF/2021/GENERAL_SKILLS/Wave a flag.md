# Wave a flag
#GeneralSkills #picoCTF2021 #examenParcial1 
## Objetivo
Can you invoke help flags for a tool or binary? [This program](https://mercury.picoctf.net/static/a00f554b16385d9970dae424f66ee1ab/warm) has extraordinarily helpful information...
## Solución
```bash
┌──(kali㉿kali)-[~/Downloads]
└─$ file warm
warm: ELF 64-bit LSB pie executable, x86-64, version 1 (SYSV), dynamically linked, interpreter /lib64/ld-linux-x86-64.so.2, for GNU/Linux 3.2.0, BuildID[sha1]=985d9586d46e8651ab66c2fbb5a5473492466aa3, with debug_info, not stripped
                                                                    
┌──(kali㉿kali)-[~/Downloads]
└─$ chmod +x warm     
                                                                          
┌──(kali㉿kali)-[~/Downloads]
└─$ ./warm -h
Oh, help? I actually don't do much, but I do have this flag here: picoCTF{b1scu1ts_4nd_gr4vy_18788aaa}
                                                                          
┌──(kali㉿kali)-[~/Downloads]
└─$ 

```
picoCTF{b1scu1ts_4nd_gr4vy_18788aaa}
## Notas adicionales

## Referencias
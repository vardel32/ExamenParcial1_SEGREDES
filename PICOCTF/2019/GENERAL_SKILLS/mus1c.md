# mus1c
#picoCTF2019 #GeneralSkills #PorGusto
## Objetivo
I wrote you a [song](https://jupiter.challenges.picoctf.org/static/c594d8d915de0129d92b4c41e25a2313/lyrics.txt). Put it in the picoCTF{} flag format.
## Solución
Se nos indica algo relacionado a "rockstar" en la pista proporcionada en este reto.
Investigando nos encontramos con una pagina de internet un poco peculiar.
![[mus1c_picoCTF_2019_generalSkills.png]]
La finalidad de este sitio no me queda del todo clara aún. Sin embargo si introducimos la _letra musical_ proporcionada en el archivo _lyrics.txt_ dado en el reto obtenemos una salida que parece ser código _ASCII_.
Haciendo la traducción mediante python obtenemos lo siguiente:
```bash
>>> chr(114)
'r'
>>> chr(114)
'r'                                                                              
>>> chr(114)                                                                     
'r'                                                                              
>>> chr(111)                                                                    
'o'                                                                              
>>> chr(99)                                                                   
'c'                                                                              
>>> chr(107)
'k'
>>> chr(110)
'n'
>>> chr(114)
'r'
>>> chr(110)
'n'
>>> chr(48)
'0'
>>> chr(49)
'1'
>>> chr(49)
'1'
>>> chr(51)
'3'
>>> chr(114)
'r'
```
rrrocknrn0113r
Acomodado en el formato de la bandera:
==**picoCTF{rrrocknrn0113r}**==
## Notas adicionales

## Referencias
# Nice netcat...
#GeneralSkills #picoCTF2021 #examenParcial1 
## Objetivo
There is a nice program that you can talk to by using this command in a shell: `$ nc mercury.picoctf.net 22902`, but it doesn't speak English...
## Solución
Al conectarse a la dirección proporcionada por el reto se nos muestra lo siguiente:
```bash
┌──(kali㉿kali)-[~]
└─$ nc mercury.picoctf.net 22902
112 
105 
99 
111 
67 
84 
70 
123 
103 
48 
48 
100 
95 
107 
49 
116 
116 
121 
33 
95 
110 
49 
99 
51 
95 
107 
49 
116 
116 
121 
33 
95 
100 
51 
100 
102 
100 
54 
100 
102 
125 
10 
```
Creando un arreglo que almacene los códigos ASCII y después creando un ciclo que recorra este arreglo y haga la transformación obtenemos lo siguiente:
```python
>>> lista_de_caracteres = [112, 105, 99, 111, 67, 84, 70, 123, 103, 48, 48, 100,95,107,49,116,116,121,33,95,110,49,99,51,95,107,49,116,116,121,33,95,100,51,100,102,100,54,100,102,125,10]
>>> for i in range(len(lista_de_caracteres)): print(chr(lista_de_caracteres[i]))
... 
p
i
c
o
C
T
F
{
g
0
0
d
_
k
1
t
t
y
!
_
n
1
c
3
_
k
1
t
t
y
!
_
d
3
d
f
d
6
d
f
}

```
Bandera: ==**picoCTF{g00d_k1tty!_n1c3_k1tty!_d3dfd6df}**==___
## Notas adicionales
## Referencias

# flag_shop
#picoCTF2019 #GeneralSkills #PorGusto
## Objetivo
There's a flag shop selling stuff, can you buy a flag? [Source](https://jupiter.challenges.picoctf.org/static/64e724ad327f83ad833d9c6baa072b1f/store.c). Connect with `nc jupiter.challenges.picoctf.org 4906`.
## Solución
En el menu de compra de la bandera `Defintely not the flag Flag` si se intenta hacer una compra de varios millones de banderas el total re la compra resulta en un número negativo.
Esto al saturar la varible _int total_cost_.
Este resultado negativo se ve reflejado en la suma de este resultado al balance de cuenta, ya que el balance de la cuenta se ve afectado después de hacer una transferencia.
==**picoCTF{m0n3y_bag5_9c5fac9b}**==

## Notas adicionales

## Referencias
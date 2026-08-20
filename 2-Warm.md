**Descripción:**
Can you convert the number 42 (base 10) to binary (base 2)?

**Solución1:**
si,
![[Pasted image 20260818232015.png|224]]
hay que poner 8 bits en base dos y conforme a eso llenar con 1 para completar el 42 con esos multiplos
0/128,0/64,1/32,0/16,1/8,0/4,1/2,0/1
**Solución2**:
si,
podemos usar la función de conversión de decimal a binario de python
numerillo = 42
pinario = bin(numerillo)
print(pinario)
101010
![[Pasted image 20260818232323.png]]
**Notas adicionales:**
siempre hay que tener en cuenta el formato de la bandera para que sea aceptada.
aún no me acostumbro a obsidian, prefiero el bloc de notas.
el formato de la bandera es del tipo 'picoCTF{101010}'
**Referencias:**
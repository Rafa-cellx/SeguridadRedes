**Descripción:**
Do you know how to move between directories and read files in the shell? Start the container, `ssh` to it, and then `ls` once connected to begin.

Login via `ssh` as `ctf-player` with the password, `8c606eb1` on the host `wily-courier.picoctf.net` and port `58650`.
**Solución1:**
hacemos una conexión a ese servidor
ssh ctf-player@wily-courier.picoctf.net -p 58650, le damos que si, ahora buscaremos la bandera en distintas raices
1era la buscamos en "1of3.flag.txt"
2da la buscamos en "2of3.flag.txt" pero para leer ese archivo lo buscamos al inicio
3era la buscamos en "3of3.flag.txt"pero para leer ese archivo la buscamos en home con la virgulilla
![[Pasted image 20260824114014.png]]
picoCTF{xxsh_0ut_0f_//4t3r_0b24fc4f}


**Notas adicionales:**
- ctrl + L borra la pantallla
- clear borra la pantalla
**Referencias:**
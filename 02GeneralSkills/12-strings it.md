**Descripción:**
Can you find the flag in [file](https://challenge-files.picoctf.net/c_fickle_tempest/6577d3f1500aebcd300787bd5d96216b30aed379c811f5e83e888f897da4a3d5/strings) without running it?

**Solución1:**
si, voy a la ubicación del archivo y con el comando strings buscamos cadenas de texto y en ese mismo comando usamos grep para buscar la palabra clave "pico" y encontrar la bandera
picoCTF{5tRIng5_1T_d6306c19}
![[Pasted image 20260823193355.png]]

**Notas adicionales:**
strings:
muestra las cadenas(caracteres imprimibles en un archivo binario)
**Referencias:**
https://labex.io/es/tutorials/linux-linux-strings-command-with-practical-examples-422934
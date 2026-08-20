**Descripción:**
Sometimes you need to handle process data outside of a file. Can you find a way to keep the output from this program and search for the flag?


**Solución1:**
hacemos la conexión y guardamos el contenido del archivo
*nc fickle-tempest.picoctf.net 64689 > jew.txt*
luego leemos el contenido de ese archivo mientras a la vez buscamos la bandera, de la sig manera
*cat jew.txt | grep pico*
![[Pasted image 20260819171807.png]]
picoCTF{digital_plumb3r_d3246b6B}


**Solución2:**

**Notas adicionales:**
-se utiliza para redirigir la salida de cualquier comando a un archivo de texto
-  | la barra vertical o también llamado pipe redirige la salida de un comando a otro comando

**Referencias:**
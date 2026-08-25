**Descripción:**
Unzip this archive and find the file named 'uber-secret.txt'

**Solución1:**
![[Pasted image 20260824180533.png]]
Primero descargo el archivo con "wget", luego lo descomprimo en una carpeta concreta con "unzip", despues uso el comando "find", para encontrar el archivo "uber-secret.txt", uso "cd" para ir donde esta y finalmente leo su "cat"
picoCTF{f1nd_15_f457_ab443fd1}


**Notas adicionales:**
- el comando "find" busca entre todos los archivos por el  nombre que se puso dentro de ese directorio y devuelve una ruta.

**Referencias:**
https://askubuntu.com/questions/144698/find-a-file-by-name-using-command-line
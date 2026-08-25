**Descripción:**
Unzip this archive and find the flag.


**Solución1:**
![[Pasted image 20260824175242.png]]
Primero baje el archivo con wget,  luego lo descomprimi en una carpeta concreta, despues use grep de forma recursiva(grep -r "pico") para que buscara la bandera en todos los distintos archivos.
picoCTF{gr3p_15_m4g1c_ef8790dc}




**Notas adicionales:**
- había que instalar el unzip
- hay que practicar los comandos de linux y conocer que significan las letras (-r,-h,-a,etc)antes de los archivos.
- -r significa que algo siga de manera recursiva
**Referencias:**
https://askubuntu.com/questions/86849/how-to-unzip-a-zip-file-from-the-terminal
https://stackoverflow.com/questions/1987926/how-do-i-recursively-grep-all-directories-and-subdirectories
**Descripción:**
Someone's commits seems to be preventing the program from working. Who is it?

You can download the challenge files here:

**Solución1:**
![[Pasted image 20260829211423.png]]
descargo el zip con wget, lo descomprimo, luego uso el cat en "message.py" para ver sus contenidos pero solo tiene un hola mundo, entonces uso un "git blame" para ver que cambios se hicierón en el archivo
picoCTF{@sk_th3_1nt3rn_2c6bf174}

**Notas adicionales:**
- git blame(auditar el archivo linea por linea y saber que commit y autor hizo cada cambio)
**Referencias:**
https://primer.picoctf.org/#_git_version_control
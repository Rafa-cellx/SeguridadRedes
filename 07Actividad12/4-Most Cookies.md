**Descripción:**
Alright, enough of using my own encryption. Flask session cookies should be plenty secure!

**Solución1:**
cree un amiente de desarrollo, luego lo active  y luego algo de las cookies
![[Pasted image 20260921113044.png]]
usando el arreglo de posibles contraseñas hice que me devolviera la que tenia el valor de admin, luego use el "flask-unsign" con el valor de la llave y eso me devolvio una nueva cookie
![[Pasted image 20260921231038.png]]
finalmente puse la nueva cookie en la pagina, la recargue y obtuve la flag
![[Pasted image 20260921231128.png]]
picoCTF{cO0ki3s_yum_b8a89e75}
**Solución2:**

**Notas adicionales:**

**Referencias:**

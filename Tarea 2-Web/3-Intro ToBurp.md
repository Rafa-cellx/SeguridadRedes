**Descripción:**
This website puts a two-factor prompt between you and the flag. Register an account, then take a close look at the requests your browser is actually sending.

**Solución1:**
fui a la pagina, e hice una cuenta

![[Pasted image 20260926214733.png]]
luego en el paso de 2da autenticación con una OTP(One time Password)
![[Pasted image 20260926214818.png]]
me dijo que era invalida
![[Pasted image 20260926214843.png]]
entonces volvi a la pagina de la OTP, pero con el burpsuite abierto intercepte la solicitud del metodo POST, y basto con borrar  la variable UTP=hola, volver a enviar la petición y obtener la bandera
![[Pasted image 20260926214503.png]]

**Solución2:**

**Notas adicionales:**
- el BurpSuite es util para analizar peticiones de sitios web, como ver que se manda y por ejemplo en los metodos post estan los metodos de autenticación
- creo que burp necesita un proxy para funcionar o cambiar la configuración del OS.

**Referencias:**
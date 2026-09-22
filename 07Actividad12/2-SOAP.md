**Descripción:**
The web project was rushed and no security assessment was done. Can you read the /etc/passwd file?

**Solución1:**
![[Pasted image 20260921193513.png]]
fui al sitio y con un proxy corriendo junto con el burp suite para que atrapara las peticiones, abri la del metodo post:
![[Pasted image 20260921193704.png]]
ahí agregue un payload y la volvi a mandar, entonces me dio la bandera
![[Pasted image 20260921193614.png]]
picoCTF{XML_3xtern@l_3nt1t1ty_540f4f1e}

**Solución2:**

**Notas adicionales:**

**Referencias:**
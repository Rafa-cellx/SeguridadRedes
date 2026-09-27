**Descripción:**
Can you get the flag? Go to this [website](http://xebec.cylabacademy.net:23379/) and see what you can discover.

**Solución1:**
fui al sitio
![[Pasted image 20260926220931.png]]
le di a continuar, pero me dijo que no podia
![[Pasted image 20260926220942.png]]
revisando el codigo me di cuenta de que el el metodo "continueAsGuest()" en el boton es el que deja continuar,  e inspeccionando el "guest.js"


![[Pasted image 20260926221001.png]]

inspeccionando el "guest.js" vi como funcionaba el metodo "continueAsGuest()", ahí vi que la cookie tiene valor de 0, pero si la cambio a 1 que pasara?
![[Pasted image 20260926221018.png]]
pues editando el valor de la cookie = 1, me dejo entrar y me dio la bandera
![[Pasted image 20260926221442.png]]
academy{gr4d3_A_c00k13_7bcbf214}

**Solución2:**

**Notas adicionales:**

**Referencias:**

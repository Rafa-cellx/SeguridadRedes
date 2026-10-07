**Descripción:**
I've hidden a flag in this file. Can you find it? [Forensics_is_fun.pptm](https://challenge-files.cylabacademy.net/library/ef35dfe613527d28fe872d94179b53bc1a0497ddecf57e51d160c910be3a8e8a/Forensics_is_fun.pptm)

**Solución1:**
descargamos el archivo con wget
![[Pasted image 20261006224007.png]]
luego analizamos su contenido con binwalk y vemos que hay un archivo al final con el nombre de hidden:
![[Pasted image 20261006224128.png]]
vemos que hay un string de base64, pues lo convertimos y podemos ver la bandera:
![[Pasted image 20261006224547.png]]
academy{D1d_u_kn0w_ppts_r_z1p5}
**Solución2:**

**Notas adicionales:**

**Referencias:**
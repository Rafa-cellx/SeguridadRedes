**Descripción:**
I found a web app that can help process images: PNG images only!

**Solución1:**
voy a la pagina y admite archivos .png, entonces tenemos que hacer un archivo .php con inyección de codigo, el contenido de ese archivo es:
![[Pasted image 20260921112251.png]]


![[Pasted image 20260921111848.png]]
despues de crear ese archivo con ese contenido, lo subi a la pagina
![[Pasted image 20260921111920.png]]
luego en la ruta me fui  a la sección "uploads", luego ahí desde la terminal dije que me leyere el contenido de ese .txt y ahí es donde encontre la bandera
http://atlas.picoctf.net:60352/uploads/webshell.png.php?cmd=cat%20../G4ZTCOJYMJSDS.txt

![[Pasted image 20260921112140.png]]

picoCTF{c3rt!fi3d_Xp3rt_tr1ckst3r_73198bd9}
**Solución2:**

**Notas adicionales:**

**Referencias:**
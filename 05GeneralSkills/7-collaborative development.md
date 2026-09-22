**Descripción:**
My team has been working very hard on new features for our flag printing program! I wonder how they'll work together?

You can download the challenge files here:

**Solución1:**
primero baje el zip, luego vi que había 3 ramas de trabajo ![[Pasted image 20260829214739.png]]
en c/u de estas se encuentra el archivo flag.py, cada una tiene una parte de la bandera, al intentar imprimir esa bandera desde main sale incompleta, por lo cual tuve que fusionar las tras ramas con 
![[Pasted image 20260829214824.png]]
donde encontre los conflictos entre archivos y complete la bandera, para guardar los cambios hice "git add flag.py" y git commit -m "resueltos conflictos de las 3 ramas", finalmente obtuve la bandera revisando el contenido del archivo desde la rama principal
picoCTF{t3@mw0rk_m@k3s_th3_dr3@m_w0rk_7ae8dd33}

**Solución2:**

**Notas adicionales:**
- git checkout "nombre rama"(permite navegar entre ramas)
- git branch -a(permite ver las ramas existentes)
- git merge (fusiona tantas ramas como argumentos pero dejando estacios entre ellas)
- git merge --abort(cancela una operación de fusión)

**Referencias:**
https://primer.picoctf.org/#_git_version_control
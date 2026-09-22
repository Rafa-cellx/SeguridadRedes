**Descripción:**
Can you read files in the root file?
The system admin has provisioned an account for you on the main server:
`ssh -p 60864 [picoplayer@saturn.picoctf.net](mailto:picoplayer@saturn.picoctf.net)`

Password: `NBD+zO8s4y`

**Solución1:**
me conecte al servidor, luego vi el usuario que tenia con whoami, ademas de ver los permisos de los distintos directorios con "ls -l", la bandera debía estar en "root" o "challange" no había manera de entrar, entonces viendo que podia usar vim en root, entre para ver los archivos y  entrando a "flag.txt" pude encontrar la bandera
![[Pasted image 20260829231245.png]]

**Notas adicionales:**
- vim es un editor como nano o algo así
- ls -l (nos permite ver los archivos y sus permisos)
- whoami(me permite ver el usuario que soy)

**Referencias:**
https://github.com/snwau/picoCTF-2023-Writeup/blob/main/General%20Skills/Permissions/Permissions.md
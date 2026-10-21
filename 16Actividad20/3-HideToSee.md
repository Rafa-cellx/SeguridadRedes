**Descripción:**
How about some hide and seek heh? Look at this image [here](https://challenge-files.cylabacademy.net/library/35a4ec81431496dc1a605de8b2abd0bb1819d055057d7fde4e191a2009b63ad2/atbash.jpg).
**Solución 1:**
bajamos el archivo y abrimos la imagen 
![[Pasted image 20261021111605.png]]
luego usando steghide para extraer un archivo de atbash.jpg:
![[Pasted image 20261021112120.png]]
luego leyendo el archivo encriptado "encrypted.txt":

sdlmxd@sdlmxd-HP-Laptop-15-dw0xxx:~/HideToSee$ cat encrypted.txt
zxzwvnb{zgyzhs_xizxp_wxyx498z}

parece que tenemos la bandera encriptada, la llevamos a cyberchef para descifrarla
![[Pasted image 20261021112443.png]]

obtenemos la bandera:
academy{atbash_crack_dcbc498a}




**Solución 2:**

**Referencias:**  


**Notas:**
**Descripción:**
I have these 2 images, can you make a flag out of them? [scrambled1.png](https://challenge-files.cylabacademy.net/library/fa686cfe375627b0131e670a19ec4775a873562ee3006dae8a40796e3e2b5e3c/scrambled1.png) [scrambled2.png](https://challenge-files.cylabacademy.net/library/fa686cfe375627b0131e670a19ec4775a873562ee3006dae8a40796e3e2b5e3c/scrambled2.png)
**Solución 1:**
descargo las 2 imagenes en una carpeta
![[Pasted image 20261021102409.png]]
abrimos las imagenes y parecen ser solo ruido o defectuosas
![[Pasted image 20261021102608.png]]
hice el script "exploit.py" para  convertir las dos imagenes a matrizes, sumarlas quitar el ruido y generar una nueva imagen:
from PIL import Image
import numpy as np

img1 = Image.open( 'scrambled1.png')
img2 = Image.open( 'scrambled2.png')
matriz1 = np.asarray (img1)
matriz2 = np.asarray (img2)

mflag = matriz1 + matriz2

resultado = Image.fromarray(mflag)
resultado.save('flag.png')


Aca la foto:
![[Pasted image 20261021103819.png]]
la bandera es: academy{2f16d0c4}

**Solución 2:**

**Referencias:**  


**Notas:**
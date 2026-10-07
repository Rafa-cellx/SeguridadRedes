**Descripción:**
We found this [packet capture](https://challenge-files.cylabacademy.net/library/2d15538465c5948f0f0626d0cdd271f74363c00aa99d694730fe98331946ab88/webnet0-capture.pcap) and [key](https://challenge-files.cylabacademy.net/library/2d15538465c5948f0f0626d0cdd271f74363c00aa99d694730fe98331946ab88/picopico.key). Recover the flag.

**Solución1:**
Descargamos los archivos con wget
 instalamos el ssldump
 ![[Pasted image 20261006222325.png]]
 en la carpeta donde esten los archivos que descargamos vamos a ejecutar el siguiente comando:
 ![[Pasted image 20261006222404.png]]
 
**Flag**: academy{nongshim.shrimp.crackers}
**Solución2:**

**Notas adicionales:**
- -A 2 → sirve para que grep nos de los siguientes 2 renglones, porque solo con grep no sale la flag completa
**Referencias:**
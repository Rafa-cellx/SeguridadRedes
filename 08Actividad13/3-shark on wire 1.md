**Descripción:**
We found this [packet capture](https://challenge-files.cylabacademy.net/library/e64f2c2aaf9bf531af7be1787c1407c47a4cc7b57f251d5108a1151e9721a2d6/shark-on-wire-1-capture.pcap). Recover the flag.

**Solución1:**
abro el paquete con el wire shark
![[Pasted image 20260928222125.png]]
luego aplique un filtro para que me mostrara solo los datos, luego en click derecho(seguir)->UDP filtro, me mostro información de los canales, así me segui hasta el 6to (stream/secuencia) y ahí encontre la bandera
![[Pasted image 20260928224254.png]]
academy{StaT31355_636f6e6e}
**Solución2:**

**Notas adicionales:**

**Referencias:**
https://www.youtube.com/watch?v=w6SaDiZ8cPA
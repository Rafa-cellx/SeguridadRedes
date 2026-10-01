**Descripción:**
We found this [packet capture](https://challenge-files.cylabacademy.net/library/f76620763560ca0683be36e0ed4648743f969ab4d852fda0d8fb4d3ae21a173d/shark-on-wire-2-capture.pcap). Recover the flag that was pilfered from the network.

**Solución1:**
primero descargo el paquete con wget, luego revisando los paquetes(UDP) me doy cuenta que uno de ellos dice "start"
![[Pasted image 20261001000102.png]]

habiendo filtrado por "ip.addr == 10.0.0.66", me doy cuenta de que todos los numeros de la columna de info empiezan or they start with a 5
![[Pasted image 20261001000310.png]]
habiendolo convertido de ascii a texto:
![[Pasted image 20261001001647.png]]
academy{p1LLf3r3d_data_v1a_st3g0}
**Solución2:**

**Notas adicionales:**

**Referencias:**
https://www.youtube.com/watch?v=e_k9fFqu-BU
https://codeshack.io/ascii-to-text-converter/
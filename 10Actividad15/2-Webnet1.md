**Descripción:**
We found this [packet capture](https://challenge-files.cylabacademy.net/library/afb7599dd63cad30a04eb98d0e4057608120371eb3e8943b632505e32c8b622c/webnet1-capture.pcap) and [key](https://challenge-files.cylabacademy.net/library/afb7599dd63cad30a04eb98d0e4057608120371eb3e8943b632505e32c8b622c/picopico.key). Recover the flag.


**Solución1:**
descargue el paquete y lo abri con wireshark
![[Pasted image 20261006222530.png]]
pasamos la key que nos dieron al protocolo TLS, para eso primero entramos a la "Edición"
preferencias->Protocolos->TLS-> importamos la key

luego vamos a la sección "Archivo"->Exportar objetos->HTTP  y guardamos el archivo "Vulture.jpg"
finalmente el la terminal vamos a la carpeta donde esta el archivo, estando ahí ejecutamos el sig comando, y en la salida de la propiedad de Artista nos daran la bandera:
![[Pasted image 20261006222813.png]]

academy{honey.roasted.peanuts}
**Solución2:**

**Notas adicionales:**

**Referencias:**
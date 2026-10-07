**Descripción:**
We found this file. Recover the flag. [tunn3l_v1s10n](https://challenge-files.cylabacademy.net/library/3b5add918cb4cf98fa62ef4e05eb8c55c6c9ae547a939c6be992ee3aa656ee69/tunn3l_v1s10n)

**Solución1:**
despues de haber descargado el archivo puedo ver que es un BMP(bit map image)
![[Pasted image 20261005141443.png]]
entonces busque el hexmap de un archivo BMP para comparar el formato de los encabezados y me di cuenta de que los bytes(azules) son diferentes a los bytes(rojos) del archivo del ejemplo, entonces los cambie para dejarlos como en los rojos
![[Pasted image 20261005143957.png]]
para esto descargue GHex, se me hizo mas facil de usar pues no tengo que calcular bytes como en hexedit
![[Pasted image 20261005145917.png]]
ahora el archivo se puede abrir pero sale esto, parece que la imagen esta recortada, entonces revisemos sus metadatos con exiftool y veamos cuanto debe de medir para ver si cambiamos mas bytes
![[Pasted image 20261005150016.png]]
podemos ver que el ancho:1134 y su alto:306
![[Pasted image 20261005150715.png]]
ahora queremos hacer la imagen mas alta para ver que mas tiene, entonces con el conversor de hexadecimal de python convertimos 850 a hex y cambiamos el bit correspondiente en el BMP
![[Pasted image 20261005151609.png]]
finalmente despues de probar varias combinaciones me di cuenta que la altura max = 850 y el ancho = 1134 lo maximo
![[Pasted image 20261005162944.png]]
entonces no importa lo que haga no se puede ver toda la bandera, por que al actualizar este reto cortaron la bandera sin considerar que ya no se pueden modificar las dimensiónes de la imagen, así que con lo que pude ver da la bandera y buscar en linea la deduje y queda tal que así:
academy{qu1t3_a_v13w_2020}
**Solución2:**

**Notas adicionales:**

**Referencias:**
https://medium.com/@siyam.exe/day-12-tunn3l-v1s10n-picoctf-forensics-writeup-ede7bc2e26a5
https://www.youtube.com/watch?v=d63buMlAUHM&t=4s
**Descripción:**
Do you think you can log us in? Try to see if you can login!

**Solución1:**
![[Pasted image 20260914103529.png]]
![[Pasted image 20260914103117.png]]
fui a la pagina web, luego insepeccionando la pagina, justo en el recuadro de login, se puede cambiar el parametro de entrada = 1, entonces no importa que ponga en password o nombre pues al encontrar = 1, me deja entrar y ver la bandera

picoCTF{s0m3_SQL_85832275}
**Solución2:**
también se puede hacer desde la terminal haciendo que se hagoa un curl y busque la bandera en la pagina, este es el comando:
"curl -s [http://fickle-tempest.picoctf.net:56133/login.php](http://fickle-tempest.picoctf.net:56133/login.php) -d "username=admin'&password=hola&debug=1"", pero no me funciono

**Notas adicionales:**

**Referencias:**
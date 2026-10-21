**Descripción:**
We found this weird message being passed around on the servers, we think we have a working decryption scheme. Download the message [here](https://challenge-files.cylabacademy.net/library/23b095a85da350dcda44aefdf5a62785a023f5d4570374d08eef71aefd096f7f/message.txt).

Take each number mod 37 and map it to the following character set: 0-25 is the alphabet (uppercase), 26-35 are the decimal digits, and 36 is an underscore.

Wrap your decrypted message in the academy flag format (i.e. `academy{decrypted_message}`)
**Solución 1:**
bajo el archivo y sale lo siguiente:
"sdlmxd@sdlmxd-HP-Laptop-15-dw0xxx:~/basic-mod1$ cat message.txt
91 396 316 198 225 369 50 369 350 63 205 346 299 406 330 397 335 374 71 111 179 64 "

podemos descifrar esos numeros con el sig script:
arch = open('message.txt').read().split()
flag = ''
for c in arch:
	n = int(c)
	m = n % 37
	if m>=0 and m<=25:
		l = chr(m + 65)
	elif m>=26 and m<=35:
		l = chr( m + 22 )
	else:
		l = '_'

	flag += l

	print(f'(c) - (m) - {l}')

print('academy{'+flag+'}')

y obtenemos  la bandera :
academy{R0UND_N_R0UND_81CE8A51}

**Solución 2:**

**Referencias:**  


**Notas:**
# SI_Bitacora4_Martinez_Cossio_Marcos#

## Creamos la carpeta en visual Studio
Que se llame: SI_BITACORA4_MARTINEZ_COSSIO_MARCOS y cramos un archivo yml que se llame docker-compose.yml
Una vez tengas el codigo, presionamos control+ñ y se abre la terminal, ponemos docker-compose up -d al principio me a dado un problema que era que no se me ejecutaba el comando docker-compose ip -d y era por no tener el docker abierto, una vez abierto el docker se ha ejecutado correctamente:


<img width="642" height="207" alt="image" src="https://github.com/user-attachments/assets/7a88cba6-88d5-41ad-8426-c32c62f17323" />
 y esto era lo que me daba al no tener el docker abierto:

 
 <img width="646" height="147" alt="image" src="https://github.com/user-attachments/assets/e01d75fa-785f-4fa6-a54d-de65f0af9969" />


 ## PASO A:

Conéctate al contenedor usando ssh alumno@localhost -p 2222. Evalúa el uso de localhost o 127.0.0.1. La contraseña es sistemas_informaticos

Lo que he cambiado a sido que he quitado del alumno@localhost a alumno@127.0.0.1 y ponemos que la contraseña que es sistemas_informaticos.



<img width="541" height="82" alt="image" src="https://github.com/user-attachments/assets/5716071e-b693-4e02-a5c0-2f049642f2b9" />


## Paso B 
(Generación de Identidad): En tu máquina anfitriona, genera un par de llaves: ssh-keygen -t ed25519 -C "tu_correo@ejemplo.com"


Se genera:
<img width="496" height="36" alt="image" src="https://github.com/user-attachments/assets/fd3a9f2a-1de0-44cf-9af2-b830733b7551" />


## Paso C (Transferencia): Copia tu llave pública al servidor. Puedes usar ssh-copy-id -p 2222 alumno@localhost o hacerlo manualmente pegando el contenido en ~/.ssh/authorized_keys dentro del contenedor.

Generado:
<img width="645" height="76" alt="image" src="https://github.com/user-attachments/assets/4d432509-b2c3-4e77-8d6c-9127f4756a7f" />


## Ubuntu

Ahora poniendo http://localhost:3000 me sale el escritorio de Ubuntu
<img width="950" height="559" alt="image" src="https://github.com/user-attachments/assets/ea3c8422-79bf-43d6-805b-2bc7272de515" />


Y este es el mensaje que he escrito:
<img width="775" height="370" alt="image" src="https://github.com/user-attachments/assets/80a41f1c-1813-46c6-a7ba-e3dbdb07ccec" />









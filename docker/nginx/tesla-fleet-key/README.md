En esta carpeta debemos tener el certificado publico que nos pide tesla para registrar nuestra app de tesla en una region para la API de Tesla Fleet.

Comandos para generar las claves:

openssl ecparam -genkey -name prime256v1 -noout -out private-key.pem  
openssl ec -in private-key.pem -pubout -out public-key.pem

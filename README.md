## Llaves
Comandos para las llaves ([OPEN SSL](https://slproweb.com/products/Win32OpenSSL.html)), crear las llaves en la carpeta jwtKeys en resources
### Llave Privada
    openssl genrsa -out private_key.pem 4096
### Llave Pública
    openssl rsa -pubout -in private_key.pem -out public_key.pem


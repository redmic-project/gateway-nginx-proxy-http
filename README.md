# Nginx proxy HTTP

Nginx service configured to redirect HTTP requests to HTTPS endoint and allow certificates validation


## Volúmenes

### acme-vol

Se prepara para que *certificates-manager* pueda escribir en él los ficheros generados para la validación del certificado, con el fin de que el servidor web sea capaz de responder a los *challenges* con ellos. No será necesario si se realiza validación a través de registros DNS.

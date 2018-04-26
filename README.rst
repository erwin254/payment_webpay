Webpay Payment Gateway
======================

Basado en payment_webpay from https://github.com/dansanti/payment_webpay.git

Mejoras Incorporadas
--------------------

- Compatible con modulos del backend partner_vat_unique y tko_
- Nos basamos en payment_paypal y payment_ogone
- Funcional
- Falta enviar Detalle completo, solamente se está enviando detalle demo
- Falta Procesar las respuestas de Webpay
- Se modifica a medida de Odoo la librería wsse

Se deben instalar las Librerías

 En Debian/Ubuntu:

sudo apt-get install libssl-dev libxml2-dev libxmlsec1-dev

 Sistemas basados en RedHat:

sudo yum install openssl-devel libxml2-devel xmlsec1-devel xmlsec1-openssl-devel libtool-ltdl-devel

Se puede utilizar el usuario demo y certificados entregados en ( no van adjuntos en el proyecto)

http://www.transbankdevelopers.cl/?m=sdk

Ejemplo datos de uso:
Pago Exitoso
Dato 	                    Valor
N° Tarjeta de Crédito 	  4051885600446623
Año de Expiración 	      Cualquiera
Mes de Expiración 	      Cualquiera
CVV 	                    123
En la simulación del banco usar: 	
Rut 	                    11.111.111-1
Clave 	                  123

Pago Rechazado
Dato 	                    Valor
N° Tarjeta de Crédito 	  5186059559590568
Año de Expiración 	      Cualquiera
Mes de Expiración 	      Cualquiera
CVV 	                    123

En la simulación del banco usar: 	
Rut 	11.111.111-1
Clave 	123

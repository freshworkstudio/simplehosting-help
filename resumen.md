# Resumen
- Primeros pasos
    - [Comprar dominio](#comprar-dominio)
    - [Activa tu cuenta en Simplehosting](#activa-tu-cuenta-simplehosting)
    - [Cambiar DNS](#cambiar-dns)
    - [Sube tu web](#sube-tu-web)
    - [Configura tus correos](#configura-tus-correos)

<a name="comprar-dominio"></a>
 ## Comprar dominio
 
 Antes de empezar, debes comprar un dominio. 
 Estos los puedes adquirir en plataformas como: 
 
 <div class="content-list" markdown="1">
 - [NIC Chile](http://nic.cl)
 - [GoDaddy](http://godaddy.com)
 - [Namecheap](https://namecheap.com)
 - y muchos otros
 </div>
 Si eres de Chile y quieres comprar un dominio `.cl`, te recomendamos usar NIC Chile.
 
 > {note} IMPORTANTE: Simplehosting no tiene relación comercial con ninguna de las empresas antes mencionadas.
  
<a name="activa-tu-cuenta"></a>
## Activa tu cuenta en Simplehosting
Ahora que ya tienes tu dominio, ingresa a [SimpleHosting](https://www.simplehosting.cl) y activa tu cuenta.
![Crea tu cuenta](https://s3-sa-east-1.amazonaws.com/simplehosting.cl/images/crea-tu-cuenta.gif)

<a name="cambiar-dns"></a>
## Cambiando los DNS
Una vez que ya activaste tu cuenta para tu dominio, solo debes configurar los DNS para que apunten a los de simplehosting.

### DNS de simplehosting
| IP            | DNS                        |
|---------------|:--------------------------:|
| 45.55.238.43  |  ns1.simplehosting.cl      |
| 45.55.182.197 |  ns2.simplehosting.cl      |

### Ejemplo de configuración en NIC Chile
Si lo compraste en NIC Chile, este ejemplo te ayudará: 

![Screencast NIC CHILE](https://s3-sa-east-1.amazonaws.com/simplehosting.cl/images/nic-cambio-dns.gif)

> {tip} Una vez que realices este proceso, los DNS se pueden demorar hasta 24 horas en actualizar, aunque normalmente basta con unos 30 minutos. 

Este cambio permite que tu dominio apunte a nuestro servidor. Sin esto, no funcionará ni tu web, ni tus correos ni tu ftp. 

<a name="sube-tu-web"></a>
## Sube tu web
Cuando los DNS estén actualizados, si entrar a tu dominio desde cualquier navegador web (Google Chrome, Firefox, etc) llegarás a nuestro servidor pero este no mostrará nada más que unos links. 
Es momento de subir tu sitio web. 

### ¿Ya tienes un sitio web construido? 
En este caso debes subir los archivos de tu sitio web por FTP. 

### No tengo una web. ¿Cómo creo una?
Construir un sitio web está fuera de los alcances de nuestro servicio de hosting. Puedes encontrar muchísima información y proveedores que pueden crear una web increíble para ti o tu negocio. 
De todas formas, si tienes conocimientos básicos, todos nuestros planes incluyen `softaculous`, herramienta de cPanel que te permite instalar herramientas como Wordpress, Prestashop, Foros o el software que necesites. 

Instalar Wordpress usando Softaculous es una de las mejores formas de crear tu web desde cero. 

<a name="configura-tus-correos"></a>
## Configura tus correos
### G Suite
Si bien nuestro servicio ofrece un servidor de correos en donde puedes gestionar las cuentas de email de tu empresa, recomendamos usar un servicio externo como [Google Suite](https://gsuite.google.com/) que te entragará muchas más herramientas y espacio de almacenamiento. ¿Necesitas asesoría? Contáctanos para poder asesorarte.     

### Usando Simplehosting
Para crear las cuentas usando nuestro servicio, debes ingresar a tu cPanel y en la sección "correo electrónico" encontrarás las herramientas que te permite crear, editar y eliminar cuentas de correo, además de las configuraciones para hacer conectar tu iPhone, Android u Outlook. 
![Crea tu cuenta](https://s3-sa-east-1.amazonaws.com/simplehosting.cl/images/crea-tu-cuenta-de-correo.gif)


# Notas

## 14/02/2023


## 28/02/2023

El día de hoy solo vimos exposiciones de bitacoras de certificaciones y por ultimo de snifers. 


## 03/02/2023

El día de hoy hicimos hay exposiones

El primero en exponer fue 

### Porotocolo SSH 
- Es un protocolo de administración de archivos, este encripta los archivos y permite el servicio de gestionar usuarios remotos. 
- Se creo para remplñazar el **Telet** 
- Es un cirado de extremo a extremo
- El que se usa generalmente es la simetrica la cual el cliente tiene la llave
- La seguridad es robusta
- Trasferencia de archivos segura 
- usa SFTP para transferir archivos 
- Se utiliza para crearfirmas digitales 

### DNS

- Traduce los nombres de dominio a direcciones ip para que los dipositivos puedan acceder a un sitio web.
- Se genera una dirección bidireccional
- hay una compilación de ip a url 
- Ejemplos de servidores DNS Gratuitos
  - OpenDNS
  - Google Pulic DNS
  - Norton ConectSafe

### NFS

- Sistemas de archivos de Red fue creado en 1984
  - Permite al usuario modificar un archivo de manera remota
- Permite al admnistrador poner en un servidor archivos que sean necesarios para acceder de manera remota
- Es una relación uno a uno con el cliente y el servidor.
- las versiones más usadas  NFSV2 NFV3(da problemas a lo largo) NFSV4(es caro) 
- Usan tpc y udp
- Tamaños de archivos varían.
- NFSV4 usa kerberos 
- NFSV4 el más seguro
- NFSV4 usa el puerto 2049 
  - Demonios NFS
    - Hace que tenga una seguridad infalible 
- Comandos nfs
  - null
  - creat
  - read y write
  - mkdir y rmdir
  - access
  - mkod
  - readdluss
- Ventanjas
  - Distintos clientes pueden acceder a los archivos
  - Reduce la necesidad de tener espacio 
  - Cualquier usuario puede modificar archivos
  - Compatibilidad de equipos
- Desventajas 
  - Seguridad solo hay que usarlo en rede segura y detrás de un firewall
  - reqiere de una gran sobrecarpar aara los datos
  - no es sencillo bloquear archivos de dar permisos 
- **Conclusión** *Es el más utilizado en la **NUBE***

### DHCP
- Es un protocolo de configuración 
- Fue creado en 1993
- Protocolo de configuración dinámica de hosto
- Es un protocolo de cliente servidor proporciona un host de protocolo de internet asigna macara de subred
- el host TCP/IIP solicita una asignación de dirección el servidor verifica si el cliente eseta en lamisma red pues si es así le otroga una dirección. 
- Parámetros
  - Dirección IP
  - Máscara de subred
  - Puerta de enlace predeterminada
  - Servidoeres DNS 
  - Tiempo de arrendamiento
  - Nombre del dominio 
- Tipos de asignación 
  - manual/ estática
  - Automática
- Ventajas
  - Minimiza errores de configuración IP
  - Dispositivos Móviles control eficaz de los cambios de dirección IP
  - Configuración de TCP/IP automatizada
  - Define la ocnfiguración desde una ubicación central.

## 07/03/2023

El día de hoy se siguen con las exposiciones faltantes
**Vamos a tener que entragar un proyecto de instalación de oficinas, instalación eléctrica y la instalación de red y tenemos que ubicar los centros de carga los nodos los tipos de nodos si van a pasar por el piso por el techo si usamos canalestar después los materiales y costo Direcciones IP**


### Protocolo SMTP, POP IMAP y SASL

- Es un protocolo de red tilizado para transferencia de archivosde corresos electrónicos entre computadorea u ottros dispotivos Utiliza el puerto 25
- POP (post office protocol) estaalece una coneción entre ciente y servidor cde correo eléctonicoa para obetner getinar el vio de mensajes 
- IMAP internet message access protocol
  - viene a sustituir el pop 
  - antes en el pop guardabas el cliente e los correos entonces este ya no se guarda de manrea tuomatica y entonces el servidoer los guarda ahora entonces no pierdes información puerto 993 es el actualmente utilizado por los servicios tradicionales
- ASL 
  - Framewrok de capa de asegurida utoizada para autentificación y autoriczación mutua entre un cliente con el servidor, mediante varios mecanimsmos de autenticación y otros protocolos de cifrado 

### FTP y TFPT
- Protocolo de transferencia de archivos
  - archivos de texto y binario 
- Cómo funciona 
  - se conectarn dos computadoras se puede iniciar en modo de autenticado y un usuario anonimo
- TFTP 
  - no pide autenticación 
  - el servidor no envía un nuevo bloque hasta que reciba el paquete de confirmación del bloque anterior
- Diferencias
  - Seguridad
  - FTP más rápido
  - FTP maneja archivos más grandes TFPT solo puede manejar archivos de texto pequeños

### Proxy

- Un intermediario que nos sirve para comunicarnos entre dispositos e internet
- Es no tener contacto directo con las cosas que queramos acceder
- Controlar el acceso a internet, limtiando los derechos d elos usarios o proporcinando permisos determinados
- REgistrar y moitorizar el tráfico online
- Filtrar la infrmación para no responder solicitudes peligrosas
- Para proteger nuestras conexiones, bloquea anomizar nuesetra dirección IP, además de bloquear cookies, scripts y otros elementos que puedan resultan peligrosos o que impidan que disfrutemo de una navegación privada.
- Diferencia con un VPN 
  - Redirige todo el tráfico de red
  - encambio el proxy solo redirige la app o web
  - El proxy no está encriptado a diferencia del VPN


### HTTP y HTTPS

- protocolo de transferencia de hipertexto esta basado en un sistema muy sencillo de omunicación que permite la transferencia de información en internet
- función:
  - cliente servidor primero el url el servidor hace la petición y después da la respuesta y nos manda a la página web del usuario 
  - utiliza el puerto 80
  - se conforma como el dns 
- https
  - una versión más segura utiliza la encriptación entre el navegador y el servidor y el tráfico de ser intervenido pues no afectaria porque está encriptado
  utiliza el sifrado ssl y tls para 
  - Uitliza el puerto 443 y utiliza certificados digitales para autenticar el servidos web 
- Diferencias
  - la diferenica de la S
  - Nivel de seguridad es más bajo de http 
  - en https si requiere validación de dominio


## 17/03/2023

El día d ehoy se hacen expocisiones de distintos dispositivos.

### Router

- Pues empiezan definiendo qué es un router entonces hablan de cuál es su función y etc
- ventajas
  - comparte la coneción a internet 
  - enrutamiento eficiente
  - seguridad
- Desventajas
  - costo 
  - configuración 
  - fallos técnicos
  - vulnerabilidades de seguridad


### Brouters
Convinación entre un router y un switch
- unir diferentes segmentos de red y en caos de reciir información y no manejar el protocolo entonces si no tlo tiene y básicamente empieza a utilzar el meto de **bridge** para poder adaptarse a la informaicón y no perter paquetes de datos
- Diferencia entre un router y un **brouter**
  - necesita más capacidad de procesamiento
  - costo ya que tiene mas funciones a diferencia de un router 
  - Topologia de red, este tiene limitaciones de topologias 
- Funcionamiento
  - fución de un router pero a diferencia es que 
- Tipos
  - de software, un dispositivo que no es un brouters adquiere la función de brouters 
  - hardware el cua l es el dispositov enbebido para funcionar como se define
  - integrados son dispotivos que conmbinad las funciones de brouter un swithc y otors componente de red en uno solo unidad
  - de borde son loq eu se utulian en la conexión entre redes de diferente proveedores
  - acceso utilizan en las conexiónes entre la red de un proveedor y los sdispositov ifnlaes de los usuarios
- PROTOCOLOS QUE UTILIZA
  - rid 
  - ospf
  - bgp
  - wigrp
  - s-is
- topologias utilizadas en brouters
  - may 
  - estrella
  - artificial
- Aplicaciones de la vida real
  - fabricar varios segmentos de red
  - video conferencias para enrutar el tráfico de video y audio 
  - distribución de redes elécticas inteligentes 
  - sistemas de control industrial intercambia diferentes dispotivos y controladores 
  - VoIP enrutar el tráfico de voz a través de la red 

### firewall
es un dispositivo de seguridad de la red entrante y saliente
- han constituido la primera línea de seguridad desde hace 25 años
- primera línea de defensa entre redes
- tipos 
  - proxi
  - activa
  - administración indetificada de amenzas
  - próxima generación
  - controlado de amenazas
- no tiene una protección interna
- siempre mantener actializado ya que nos previene de nuevas vulnerabilidades
- necesita trabajar con un detector de virus 
- limita los puertos y host accesiboes par auna lista de permitod por defecto
- tener copias de seguridad dentro d elos datos de os host y esto previene de la perdida de datos 


### Proxy
intermediario que actúa com onitermediaro entre el cliente y otros servidores o recursos de internet. cuando te conectas a través dde el tu solicitud se envía primero al servidor proxy, que luego actua en tu nombre para solicitar y recibir información de los sercidores que eseaa acceder. estos significa que tu conexión no se comparten directamente quién solicito la información 
- un protocolo proxy es un conjunto de reglas y procedimientos que se utilizan para cominicar un clinete con un servicor proxy 
- existen varios protocolos de proxy
  - http
  - socks
  - ftp 
  - ssl
- Desventajas
  - velocidas disminuyes
  - seguridad de seguridad 
  - falta de privacidad 
  - depentendia del servidor proxy 
  - incompatibilidad con ciertos servicios

### Gateway 


### MODEM 





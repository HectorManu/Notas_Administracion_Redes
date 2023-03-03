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
  - 
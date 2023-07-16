---
label: AdguardDNS
title: AdguardDNS
icon: shield-check
layout: default
---

# Bloquea Adware, Malware y mas con AdguardDNS

![](https://i.postimg.cc/FHRcd740/Header-tutos-4.png)

> **¿Tienes una petición o duda durante el tutorial?**       
> *Hazlo desde* [!badge variant="contrast" icon="feed-rocket" text="Discord"](https://discord.gg/hVKeY3uEru) 

---

## Tutorial con DNS publica (solo bloquea anuncios)

Este tutorial es para bloquear los anuncios de tu dispositivo sin ningun programa.

### Pasos:

+++ 📱 Android

1. Vamos a los ajustes de red (Wifi & Internet) de nuestro telefono y buscamos la opcion llamada DNS privado.
> *Esto solo funciona para android 9 en adelante, si tu dispositivo es anterior a ese:*

2. Copia lo siguiente y pegalo     
- *Bloquea anuncios*
``` 
dns.adguard-dns.com
```
- *Bloquea anuncios y sitios xxx*
```
family.adguard-dns.com
```

3. Guardamos y listo, ya no tendras anuncios.
> *Algunas veces es necesario desactivarlo para apps que funcionan sin datos o para acceder a wifis publicos con claves. Luego de que tengas internet, lo vuelves a activar.*

+++ 📴 iOS

1. Abre la applicacion de ajustes de tu dispositivo iOS

2. Ve a la opcion de perfil destacado y en perfil descargado.

- [!button variant="success" target="blank" corners="pill" text="Bloquea anuncios"](https://github.com/NOIR-DexPrkr/dexco-files/raw/main/uploads/iOS%20cofig%20dns/adguard-dns.mobileconfig)

- [!button variant="success" target="blank" corners="pill" text="Bloquea anuncios + XXX"](https://github.com/NOIR-DexPrkr/dexco-files/raw/main/uploads/iOS%20cofig%20dns/adguard-dns-family.mobileconfig)

4. Selecciona uno de los siguientes perfiles y aplica la configuracion dando en instalar.

5. Eso es todo, ya no tienes anuncios.

+++ 🖥 Windows

1. Ve al menú Inicio → Panel de control.

2. Selecciona Red e Internet, haz clic en Centro de redes y recursos compartidos.

3. En el panel izquierdo, selecciona Cambiar la configuración del adaptador y haz clic derecho en la red a la que estás conectado.

4. En la barra de opciones, selecciona Cambiar la configuración de esta conexión. Como alternativa, haga click con el botón derecho en el icono de la conexión y seleccione Propiedades.

5. Selecciona Protocolo de Internet versión 4 (TCP/IPv4) y haz clic en Propiedades.

6. Selecciona Usar las siguientes direcciones del servidor DNS y escribe las siguientes en el orden que estan.    
- *Bloquea anuncios*
```
94.140.14.14
```
```
94.140.15.15
``` 
- *Bloquea anuncios + XXX*
```
94.140.14.15
```
```
94.140.15.16
``` 

+++ 😉 Otros 

Para mas dispositivos e informacion mas clara ve a [este link](https://adguard-dns.io/es/public-dns.html) y ve a la seccion de configuracion manual.

+++

---

## Tutorial con DNS privada + Personalización

Controla todo el tráfico web en tus dispositivos, bloquea anuncios, rastreadores y dominios maliciosos. 

### Pasos

1. Nos vamos al siguiente [link](https://adguard-dns.io/es/dashboard/auth)

2. Nos registramos y una vez adentro del panel de control seleccionamos "Conectar dispositivo".    
==- Ver imagen de ejemplo     
![](https://i.postimg.cc/g0fQ82KS/2023-07-16-17-32-57.png)

===

3. Seleccionamos el tipo de dispositivo, le ponemos un nombre y continuamos.      

4. Escogemos la opcion manual y seguimos los pasos de configuracion, los cuales la pagina te dara paso a paso con imagenes.     
==- Ver imagen de ejemplo     
![](https://i.postimg.cc/RZZkz8FR/2023-07-16-17-38-53.png)

===

5. Si hiciste todos los pasos correctamete y le diste a "He conectado el dispositivo", entonces podemos continuar con la configuracion.

6. Seleccionamos la opcion "listas de bloqueo" desde el panel inicial.     
==- Ver imagen de ejemplo
![](https://i.postimg.cc/nhS6Vk9t/2023-07-16-17-43-43.png)

===

7. Lo que sigue aqui es que selecciones las listas que desees, sobre todo las de la seccion seguridad.

==- Ver imagen de ejemplo
![](https://i.postimg.cc/KYKC1Mt3/2023-07-16-17-45-09.png)

===

8. Una vez termines todo la lista debe verse como la del ejemplo a continuacion.

==- Ver ejemplo de resultados      
![](https://i.postimg.cc/j5P9XYgs/2023-07-16-17-47-00.png)

=== 

Eso seria todo, ahora tus dispositivos estan seguros contra todo tipo de anuncios, malware, spyware, pishing, etc.

---
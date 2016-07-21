# Disclaimer
*Éste proyecto pretende explicar como configurar un centro multimedia (mediacenter) completo, una estación de juegos y un servidor de descargas. Todo en uno. __Queda prohibido cualquier uso orientado a piratear/robar contenido con derechos de autor/terceros sin expreso consentimiento.__ Éste proyecto está basado en un conjunto de software gratuito que se puede encontrar fácilmente en internet. Éste proyecto no tiene ningún fin lucrativo, su único fin es enseñar y educar sobre la configuración y uso de los distintos programas.*

# Introducción
Éste proyecto permite instalar en pocos minutos una imagen pre-configurada para **Raspberry 2** y **Raspberry 3** con las siguientes opciones:

- Centro multimedia usando Kodi 16.1 Jarvis
- Centro de juegos y emuladores usando RetroPie 4.0
- Centro de juegos en streaming usando Moonlight 2.2.1
- Centro de descargas usando Transmission y PyLoad
- Estación de trabajo con XFCE y navegador Firefox
- Reproductor de vídeos para películas y series con subtítulos
- Reproductor de canales de TV a la carta y en streaming
- Reproductor de contenido multimedia deportivo usando AceStream y SopCast
- Reproductor de música, videoclips y radio online
- Y mucho más...

# Materiales necesarios
- [Raspberry Pi 3](https://www.amazon.es/Raspberry-Modelo-GHz-Quad-core-Cortex-A53/dp/B01CD5VC92/ref=sr_1_1?ie=UTF8&qid=1469090832&sr=8-1&keywords=raspberry) - Quadcore 1200MHz @ 1Gb RAM
- Tarjeta microSD SDHC 6Gb, recomiendo [SanDisk SDSQXNE-032G-GN6AA](https://www.amazon.es/gp/product/B013CP5A0Y/ref=oh_aui_detailpage_o02_s00?ie=UTF8&psc=1)
- Cargador de corriente micro USB, 5V y 3A, recomiendo [éste modelo](https://www.amazon.es/Aukru-3000mA-Cargador-Adaptador-Raspberry/dp/B01566WOAG/ref=sr_1_13?ie=UTF8&qid=1469090832&sr=8-13&keywords=raspberry)
- Caja protectora, recomiendo [ésta caja con ventilador](https://www.amazon.es/TRIXES-transparente-ventilador-enfriamiento-Raspberry/dp/B01BKIQJD2/ref=sr_1_22?ie=UTF8&qid=1469090864&sr=8-22&keywords=raspberry)
- [Cable HDMI](https://www.amazon.es/AmazonBasics-Cable-velocidad-est%C3%A1ndar-reciente/dp/B014I8SSD0/ref=sr_1_1?s=electronics-accessories&ie=UTF8&qid=1469091932&sr=1-1&keywords=cable+hdmi)

# Materiales recomendados
- [Interruptor USB](http://www.ebay.es/itm/Switched-microUSB-extension-lead-Raspberry-Pi-etc-Power-Cable/171305347085?_trksid=p2047675.c100005.m1851&_trkparms=aid%3D222007%26algo%3DSIC.MBE%26ao%3D1%26asc%3D20140620091323%26meid%3Dd9ed3dfdcbda43208e646caa71adf5b5%26pid%3D100005%26rk%3D3%26rkt%3D6%26mehot%3Dpp%26sd%3D171411830547) para apagar la Raspberry
- Disipadores de [cobre](https://www.amazon.es/enfriamiento-disipador-t%C3%A9rmico-disipadores-Raspberry/dp/B00LSF9ZKW/ref=sr_1_64?ie=UTF8&qid=1469090886&sr=8-64&keywords=raspberry) o [aluminio](https://www.amazon.es/Aukru-Disipador-Raspberry-aluminio-unidades/dp/B00ILK6DMA/ref=sr_1_9?ie=UTF8&qid=1469090832&sr=8-9&keywords=raspberry)
- Teclado inalámbrico, recomiendo [Logitech K400](https://www.amazon.es/Logitech-K400-Plus-inal%C3%A1mbrico-incorporado/dp/B00XYTTEAQ/ref=sr_1_1?ie=UTF8&qid=1469090931&sr=8-1&keywords=logitech+k400)

Recomiendo hacer el montaje usando cable de red ethernet. Si no disponemos de conexión por cable en el salón, podemos realizar el montaje usando el wifi integrado de la Raspberry 3, pero no lo recomiendo

# Contenido del MediaCenter
### FALTA ACTUALIZAR ÉSTA SECCIÓN

Mediacenter Kodi 16.1 Jarvis, compilación arm7
Valido RaspberryPi 2 y RaspberryPi 3

**REPOSITORIOS**
- Kodi Addon Repo
- SuperRepo
- TVAddons

**PROGRAMAS**
- AddonInstaller -> Instalador gráfico de addons
- Backup -> Permite salvar y restaurar un backup de tu OpenELEC en la nube
- Maintenance Tool -> Varios tweaks para limpiar la cache y optimizar la memoria de OpenELEC
- Pulsar Providers -> ExtraTorrent + KickAss + Magnetdl + ThePirateBay + Torrentdb + TorrentHound + TorrentZ + Divxatope + Divxtotal + EliteTorrent
- Provider Manager -> Edita simultaneamente todos los providers de Pulsar
- Transmission -> Cliente de descargas Torrent
- Unrar -> Descompresor RAR
- Inadyn -> Updater de servicios DynDNS, No-Ip y similares

**MUSICA**
- VEVO -> Música y videoclips organizados por temática, artista, shows, ...
- TuneIn Radio -> Acceso a cualquier radio online de todo el mundo, música en directo

**VIDEO**
- Catoal -> Canales de TV en streaming, contenido nacional e internacional
- LiveStreamsPro + AdryanList -> Canales de TV en streaming, contenido nacional e internacional
- MEGA -> Gestor de descargas del conocido MEGA
- pelisalacarta -> El mejor addon para ver películas, con acceso a EliteTorrent, Divxatope, ...
- Pulsar -> El mejor reproductor, visualiza contenido sin esperar a completar la descarga
- Plexus-Streams -> Reproductor de enlaces AceStream y SopCast, para contenido deportivo
- tvalacarta -> Acceso a todo el contenido de la TV bajo demanda (a la carta)
- cCloudTV -> Listado de canales de TV en streaming, mucho contenido
- Genesis -> Completísimo addon con contenido de películas y series, todo en inglés VO
- PleXBMC -> Cliente de Plex para Kodi, gestiona y visualiza toda tu biblioteca Plex
- XBMCtorrent -> Igual que Pulsar, permite ver contenido torrent sin esperar a descargar
- YouTube -> No lo conoces?

**SCRAPERS**
- The Movie atabase
- The TVDB
Los scrapers descargan automáticamente la información, portada, sinopsis, reparto, puntuaciones, .... de cualquier película o serie que visualicemos

SUBTITULOS
- Addic7ed.com
- OpenSubtitles.org
- Subdivx.com
- TuSubtitulo

LETRAS/LYRIC
- CU LRC Lyrics

# Más información
- Viene todo preconfigurado para enchufar y usar
- Configuración personalizada para Spanish: Layout, Audio, Video y Subtítulos
- Ethernet con IP automática (DHCP)
- Protocolos SSH y SMB (Samba) habilitados (usuario = root / password = root)
- Skin Confluence
- Transmission tuneado para maximizar su velocidad de torrents
- Icono atrás/subir directorio oculto
- Mostrar extensión en ficheros habilitado
- Permitir renombrar y borrar ficheros habilitado
- Acceso por Zeroconf habilitado (para control remoto desde smartphone)
- Protocolo AirPlay deshabilitado (mejora rendimiento)
- Addon de ElTiempo deshabilitado (mejora rendimiento)
- Lector de noticias RSS deshabilitado (mejora rendimiento)
- Biblioteca compartida por UPnP deshabilitado (mejora rendimiento)
- Hack para librería librtmp de SuperCeleron (updated: 22/07/2015)

---

# PASO 1: Instalación
1. Descargar la imágen preconfigurada [Mediacenter-AikonCWD-v6.img](#)
2. Grabar la imagen en tu tarjeta microUSB:
  - Desde Windows: Utilizar el programa [win32diskimager](https://sourceforge.net/projects/win32diskimager/)
  - Desde Linux/Mac: `sudo dd if=/ruta/Mediacenter-AikonCWD-v6.img of=/dev/mmcblk0 bs=4M; sync`
3. Introduce tu microUSB con la imagen grabada en tu Raspberry
4. Enchufa el cable de alimentación
5. La Raspberry se encenderá, aparecerá la imágen inicial de *garlic-dog*
6. La Raspberry se reiniciará automáticamente, volverás a ver la imagen inicial de *garlic-dog*
7. El mediacenter Kodi arrancará automáticamente
8. Pulsamos el botón situado en la esquina inferior izquierda, seleccionamos **salir** para cerrar Kodi
9. Verificar que la imagen ocupa el 100% de tu microSD con el comando `df -h` (opcional)

Tras salir de Kodi estaremos en la consola, si en lugar de la consola vemos el fondo totalmente negro es posible que haya saltado el salvapantallas, pulsa una tecla en tu teclado y la consola aparecerá de nuevo

# PASO 2: Configurar IP Estática
1. Editamos el fichero de configuración con el comando `nano /etc/dhcpcd.conf`
2. Quitamos el comentario (#) que hay al principio de cada línea:
```
interface eth0
static ip_address=192.168.1.100/24
static routers=192.168.1.1
static domain_name_servers=8.8.8.8
```
Puede que el router de tu casa tenga otra dirección (por ejemplo 192.168.0.1), personaliza éste fichero para adaptarlo según el caso. Si tienes intención de utilizar el wifi, repite los mismos pasos aplicándo a la sección **interface wlan0**

Una vez finalizado, guarda los cambios en el fichero, para ello pulsa: <kbd>CTRL</kbd>+<kbd>X</kbd>, luego <kbd>Y</kbd> y finalmente <kbd>Intro</kbd>

#PASO 3: Cambiar el password de root
El usuario por defecto de ésta imagen es **root**, su contraseña original es **aikoncwd**. Recomiendo encarecidamente que cambies ese password, para ello escribe el comando `passwd root`, a continuación escribe tu nuevo password 2 veces. Recuerda que éste usuario/password lo utilizarás para acceder a la Raspberry por SSH o sFTP (FileZilla), también lo usarás si pretendes controlar Kodi desde tu smartphone, etc...

#PASO 4: Configurar Transmission (opcional)
Falta completar...

#PASO 5: Configurar PyLoad (opcional)
Falta completar...

#Cosas que me falta escribir:
- Recomendaciones
- Puertos router
- App para controlar Kodi desde smartphone
- Plex
- Acceso por Samba (SMB)
- Uso del nuevo pelisalacarta (libtorrent)
- RetroPie, Emulationstation y emuladores
- Configuración del mando xbox360usb
- Copiar roms y bios
- Moonlight y Steam
- Personalizar los script de arranque d emoonlight
- Crear un mappeado de botones para moonlight
- Overclock y benchmark
- Uso del Desktop y Firefox
- Enseñar tmux, irssi, crawl, htop, wavemon, etc...
- Hyperion

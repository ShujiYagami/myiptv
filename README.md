# Shuji IPTV


1. Ajustar el Nombre del Canal
```sh
#EXTINF:-1 tvg-name="Mi Canal Favorito", Canal 1
http://ejemplostream.com/stream1
```

2. Añadir logotipos
```sh
#EXTINF:-1 tvg-logo="http://ejemplo.com/logo1.png", Canal 1
http://ejemplostream.com/stream1
```

3. Agrupar Canales
```sh
#EXTINF:-1 group-title="Noticias", Canal de Noticias
http://ejemplostream.com/noticias
#EXTINF:-1 group-title="Deportes", Canal de Deportes
http://ejemplostream.com/deportes
```

4. Añadir Grupos de Canales (alternativa a group-title)
```sh
#EXTINF:-1 group-title="Noticias", Canal de Noticias
#EXTGRP:Noticias
http://ejemplostream.com/noticias
#EXTINF:-1 group-title="Deportes", Canal de Deportes
#EXTGRP:Deportes
http://ejemplostream.com/deportes
```

5. Añadir Información EPG (Guía Electrónica de Programas)
```sh
#EXTINF:-1 tvg-id="canal1epg", Canal 1
http://ejemplostream.com/stream1
```

6. Establecer Idioma del Canal

```sh
#EXTINF:-1 tvg-language="Español", Canal 1
http://ejemplostream.com/stream1
```

7. Incluir Información del País

```sh
#EXTINF:-1 tvg-country="ES", Canal 1
http://ejemplostream.com/stream1
```

8. Añadir Información EPG (Guía Electrónica de Programas)
Source: [https://epg.best/https://epg.best/available-channels](https://epg.best/available-channels)
   
```sh
#EXTINF:-1 tvg-id="canal1epg", Canal 1
http://ejemplostream.com/stream1
```

9. Añadir XML de EPG
```sh
#EXTM3U x-tvg-url="https://xmltv.net/guides/default.xml, https://xmltv.net/guides/channel-guide.xml"
```

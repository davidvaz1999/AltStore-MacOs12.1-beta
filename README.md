# AltStore-MacOs12.1-beta
# Mail AltServer pluggin para la beta 21C5045a (12.1) de MacOS Monterey  
# Compatible también con la versión RC (final) 21C51 12.1 (MacOS Monterey)


Reemplazar /Library/Mail/Bundles/AltPlugin.mailbundle con el contenido de este repositorio

Posteriormente ejecutar en Terminal los siguientes comandos:

> sudo codesign -f -s - /Library/Mail/Bundles/AltPlugin.mailbundle

> sudo spctl --master-disable



Probado y funcionando en:

> Macbook Pro M1 2020


![GIF](https://raw.githubusercontent.com/davidvaz1999/AltStore-MacOs12.1-beta/main/demostracion.gif)
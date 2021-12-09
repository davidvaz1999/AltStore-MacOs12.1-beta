# AltStore-MacOs12.1-beta

Reemplazar /Library/Mail/Bundles/AltPlugin.mailbundle con el contenido de este repositorio

Posteriormente ejecutar en Terminal los siguientes comandos:

sudo codesign -f -s - /Library/Mail/Bundles/AltPlugin.mailbundle
sudo spctl --master-disable
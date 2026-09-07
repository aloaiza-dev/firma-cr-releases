# FirmaCR — RELEASES

Punto de distribución pública para [FirmaCR](https://github.com/aloaiza-dev/firma-cr),
una aplicación para macOS destinada a firmar y verificar archivos PDF utilizando
la tarjeta de firma digital de Costa Rica.

Este repositorio contiene únicamente el *appcast* de Sparkle y los archivos
comprimidos de los lanzamientos firmados. El código fuente se encuentra en
un repositorio privado independiente.

Cada archivo comprimido está firmado con una clave EdDSA. La aplicación verifica
dicha firma antes de realizar cualquier instalación; por lo tanto, se rechaza
cualquier descarga que haya sido alterada, independientemente de cómo se haya
obtenido.

## Appcast

https://raw.githubusercontent.com/aloaiza-dev/firma-cr-releases/main/appcast.xml

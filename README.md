# Pasos de instalación #

## Instalar google chrome v64_61.0.3163.79: ##

1. Descargar google chrome de https://www.slimjet.com/chrome/download-chrome.php?file=lnx%2Fchrome64_61.0.3163.79.deb
2. Desinstalar google chrome actual `sudo apt-get purge google-chrome-stable` 
3. Instalar google chrome antiguo `sudo dpkg -i chrome64_61.0.3163.79.deb`

- - - -

## Instalar chromedriver v2.33 modificado ##

__Nota:__ El binario de chromedriver fue modificado para remover la variable 
$cdc de chromedriver usando vim https://stackoverflow.com/a/52108199/7663274

1. Mover el chromedriver a /usr/bin/ `sudo mv chromedriver /usr/bin/`
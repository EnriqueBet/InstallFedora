# Gnome Extensions

## Requisitos:
 
 1. Instala gnome-tweak-tool usando el siguiente comando:
 ```
 $ sudo dnf install gnome-tweak-tool
 ```
 2. Correr gnome-tweak-tool. Si el programa no corre, debes editar con perimos de superusuario el archivo: 
 /usr/bin/gnome-tweak-tool, sustituir la linea 1 que debe decir:
 ```
 #!/usr/bin/env python
 ```
 
 por esta linea:
  ```
 #!/usr/bin/python
 ```
 guarda el arhcivo y lanza de nuevo gnome-tweak-tool. Cierra gnome-tweak-tool
 
## Instalar una extension

Visita el sitio: https://extensions.gnome.org/

 Extensiones favoritas:
 - Caffeine. Ayuda a desactivar el screen saver en gnome
 - Pomodoro. Ayuda a medir el tiempo de trabajo
 
 Para instalar una extensión sólo activa el switch de la extension hacia ON, es probable que después de activar una extensión
 debas activarla de nuevo en la app gnome-tweak-tool, en la sección Extensions
 
 # Terminal Pimps
 
 ## Powershell
 
 Para instalar powershell debes usar este tutorial:
 https://fedoramagazine.org/add-power-terminal-powerline/
 
 En tu caso sólo usaras la parte que deice Powerline for shell

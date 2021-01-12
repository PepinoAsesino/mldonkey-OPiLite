# orangepilite
 Probado en Armbian 20.11.6 Focal with Linux 5.10.4-sunxi con una Orange Pi Lite. Se ejecuta como root (puedes crear otro usuario y modificarlo en el script, pero en mi caso no me interesa).
 
## Instruciones
Copiamos el script de inicio para que arranque al encender/reiniciar la pi:

mldonkey-OPiLite/etc/default/mldonkey → /etc/default/mldonkey  
mldonkey-OPiLite/etc/default/mldonkey → /etc/default/mldonkey  

Iniciamos el daemon:

    /etc/init.d/mldonkey start
Tras unos segundos se iniciará el programa y se creará la configuración en /root/.mldonkey
Accedemos a la interfaz web desde http://ipdelapi:4080/ y ya podremos configurarlo para empezar a utilizarlo.

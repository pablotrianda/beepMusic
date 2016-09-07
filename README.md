# BeepMusic
![Alt text](https://s11.postimg.org/l2tqqodbn/Captura_de_pantalla_de_2016_09_07_10_13_37.png?raw=true "")
## Instalacion
1. Instalar el paquete beep:
      * `sudo apt install beep`
2. Para poder usarlo: (solo servira hasta el reinicio)
      * `sudo modprobe pcspkr`
      * Para hacer esto permanente hay que habilitar la carga de pcspkr permanentemente:
        * editar `/etc/modprobe.d/blacklist.conf` y comentar `blacklist pcspkr` 
3. Clonar este repositorio
4. Ejecutar `./beep_sound.sh`






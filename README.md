# SKYPE
Docker imagen SKYPE para utilizar el prgrama Skype V4.3

# USAGE
docker run --name skype -it -v /tmp/.X11-unix:/tmp/.X11-unix -e DISPLAY=unix$DISPLAY --device /dev/snd javi98/skype

# Problem does not start skype
Antes de arrancar el contenedor tienes que ejecutar el siguiente comando:   xhost + 

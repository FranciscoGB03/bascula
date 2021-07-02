# Báscula
#Configuración de bascula en Raspberry
#1. Habilitar puertos seriales y deshabilitar acceso de raspbian por serial
#Para ello se debe abrir una terminal y colocar:
#sudo raspi-config
#saldra una pantalla con herramientas de configuración
#seleccionar la opcion 3 Interface Options
#después seleccionar la opción: P6 Serial Port
#saldrá la siguiente pregunta: Would you like a login shell to be accessible over serial? seleccionamos: No y damos enter
# acontinuación saldra la pregunta: Would you like the serial port hardware to be enabled? seleccionamos Si y damos enter
# aparecerá un resumen con lo que hemos seleccionado:
  The serial login shell is disable
  The serial interface is enabled
si todo esta bien damos aceptar.
#nos regresará al menu principal, seleccionamos finish.
#pedirá reiniciar la raspberry, le damos si

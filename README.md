# Burritaco

Creada por el equipo de desarrollo Futuchi, Burritaco es una aplicación web que permite conocer la percepción de los usuarios de Twitter sobre la congestión de tránsito en las comunas de la región Metropolitana.

Futuchile está integrado por:

1. Marcelo Morales
2. Sebastián Vallejos
3. Marcelo Muñoz
4. Javier Vásquez
5. Arthur Peña
6. Nicolás Olivares

Instrucciones:
1. Para compilar: gradle jar
2. Para ejecutar: java -cp build/libs/Burritaco-streaming-1.0.jar cl.citiaps.twitter.streaming.TwitterStreaming

NO OLVIDAR modificar twitter4j.properties para agregar parámetros de autenticación

## Instalar Screen
* sudo apt install Screen
### Comandos de screen: 
* screen -S NombreScreenNueva -> Nuevo bash
* Ctrl + A + D -> Detach el screen
* screen -ls -> Lista de screen en ejecución
* screen -R NombreScreen -> Reattach al screen

Para compilar

  gradle jar

Para ejecutar

  java -cp build/libs/twitter-streaming-1.0.jar cl.citiaps.twitter.streaming.TwitterStreaming

 NO OLVIDAR modificar twitter4j.properties para agregar parámetros de autenticación

 Instalar Screen:

 sudo apt install Screen

 Comandos de screen:

  screen -S NombreScreenNueva -> Nuevo bash

  Ctrl + A + D -> Detach el screen

  screen -ls -> Lista de screen en ejecución

  screen -R NombreScreen -> Reattach al screen

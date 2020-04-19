# -COVIDMAPS
Solucion proyecto final telematica solucionado por Sebastian Ramirez Arboleda id:000394280.
# -Descripcion sobre la aplicacion...
el nombre de la aplicacion es covidmaps,esta realizada sobre la aplicacion Appinvetor,la idea sobre esta aplicacion es hacer un senso sobre la poblacion con la terrible enfermedad de el momento,para asi tener mas cuidado y cada vez mas ser mas conciente sobre el gran peligro que es el coronavirus...
# -Appinventor
el Appinventor es una aplicacion desarrollada por google laps, el cual es una herramienta para programar el la plataforma de android,con un lenguaje de programacion por bloques,lo cual lo hace muy intuitivo ,ademas lo convierte en una herramienta muy util si no se tiene un computador con cierta potencia de computo,ademas de que esta programado en java.
# -Arquitectura
# -Dockerfile
El Dockerfile se encargara de enviar o mas bien montar los archivos al servidor, relacionandose con los contenedores, Levantara los servicios necesarios y ejecutará el archivo .py por debajo de memoria.
# -Proyect.py
aqui se guardara toda la informacion respectiva a el proyecto, este recivira los archivos enviados por los usuarios mediante un metodo llamado post el cual se encuentra implementado en la aplicacion, con los datos brindados por la gente y el uso de una base de datos tomada de internet la cual es el tiempo real,se podran realizar graficos que muestren la peligrosidad de una zona x...
# - Base de datos
Esta base de datos tendrá la información de los casos confirmados de covid-19 en la ciudad incluyendo los datos dados por los usuarios enfermos o con sospechas ademas de el uso de los datos suministrados por internet y mismos usuarios de la aplicación.
# -Contenedor en Docker
para el contenedor se usara ubuntu server 18.04 en el se instalara apache ademas de flask pip y python,todo despues de actualizarlo para poder tener un uso optimo.
# -Tipo de servidor y bloqueos de seguridad
Se usuará el UFW como el firewall del sistema habilitando el puerto 80. Si el servicio se va montar en una red de servidores en la nube (como AWS) se activara el puerto 22 y se haran las configuraciones de los grupos de seguridad respectivos.

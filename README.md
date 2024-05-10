# AjustadorSRT
Este programa permite ajustar archivos de subtítulos de extensión .srt para quitar saltos de tiempo que puedan tener, creando un nuevo archivo con las marcas de tiempo cambiadas.

## MANUAL DE USO DE AJUSTADOR DE SUBTITULOS .SRT

### ANTES DE USAR EL PROGRAMA:
- Asegúrese de que el archivo .srt que desea cambiar está en la misma carpeta que el ejecutable (archivo .exe) del programa
- Apunte el momento en el que los subtítulos dejan de estar sincronizados con el video, así como el desfase que hay entre ambos en minutos y segundos
- Entre al archivo .srt y busque el número al que se corresponde este momento: esto es, el número entero que aparece al principio del "párrafo" en el que se encuentra la primera línea o líneas desajustadas, justo encima de las marcas de tiempo

Una vez tenga apuntados el número de párrafo, la diferencia de tiempo y el nombre del archivo que quiere editar, estará listo para poder usar el programa

### EL PROGRAMA
- Tras ejecutar el archivo .exe, irán apareciendo instrucciones sobre los datos que debe introducir en cada momento:
	- Nombre del archivo: el nombre del archivo .srt que quiere editar, con la extensión (el ".srt" del final) INCLUIDA. Si este nombre se introduce incorrectamente, el programa no podrá encontrar el archivo y por tanto no podrá editarlo.
	- Número de línea: el número correspondiente al párrafo del archivo .srt a partir del cual quiere mover los subtitulos (la linea introducida será la primera en ser editada, por lo que debe introducir la primera línea desajustada, NO la última ajustada)
	- Minutos/segundos: introduzca cada numero en el campo correspondiente. Introduzca el número en positivo/sin signo si quiere que los subtítulos salgan más tarde, y en negativo/con un signo - si quiere que salgan antes. El signo - debe ponerse en ambos campos, tanto minutos como segundos (ejemplo: introducir "-2" y "-30" para que los subtítulos aparezcan 2 minutos y 30 segundos antes).

Si todos los datos se han introducido correctamente, después de unos segundos aparecerá un mensaje del tipo: `">> ARCHIVO "[NOMBRE]_EDIT.srt" GENERADO CON EXITO"` si la ejecución ha sido exitosa. 
Después de esto, el archivo estará listo para ser usado (cambiando el nombre si es necesario)

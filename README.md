# adminfacesarchetype
adminfacesarchetype, genera proyecto web basado en adminfaces
Este usa Adminfaces
https://adminfaces.github.io/site/

Pasos para usar:

0. Verificar que exista el archivo settings.xml en el directorio .m2
1. configurar el path de Maven
1. clonar el proyecto
2. Ejecutar
3.

Crear un proyecto web basado en adminfaces

 mvn archetype:generate -Dfilter=com.avbravo:adminfacesarchetype-archetype -DarchetypeVersion=0.2

Responder a las preguntas
1: local -> com.avbravo:myshowcase-archetype (myshowcase-archetype)
Choose a number or apply filter (format: [groupId:]artifactId, case sensitive contains): : 1
-->Define value for property 'groupId': 
com.avbravo                                        
-->Define value for property 'artifactId': 
adminfacesarchetype
-->Define value for property 'version' 1.0-SNAPSHOT: 
 0.1
-->Define value for property 'package' com.avbravo: 
 com.avbravo
Confirm properties configuration:

Responder Y a la pregunta de confirmacion

Esto genera el nuevo proyecto basado en adminfaces con todos los componentes. Sugerencia es un proyecto de ejemplo
el creara todos los paquetes y los incluira en los nuevos paquetes que especifico 
borrelos para evitar conflictos.
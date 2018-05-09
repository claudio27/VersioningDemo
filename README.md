###Comandos a usar

	mvn package

Ejecutar el jar con dependencias que esta en target/

	java -jar ...


	mvn release:prepare

Si hay cambios antes de subir el archivo, borra el archivo 'release.properties'

	mvn release:clean

Agregar los cambios si se quiere, y hacer push

	mvn release:prepare

	mvn release:perform ( para construir la version localmente, va a git hace checkout al directorio local y la construye el release)


	java -jar target/checkout/target/Version....jar (Fijarse que no dice snapshot en ninguna parte)

	url video explicativo : https://www.youtube.com/watch?v=8j7Jn2uHK3Y

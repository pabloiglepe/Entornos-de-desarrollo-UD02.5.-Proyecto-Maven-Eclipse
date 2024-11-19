# Entornos-de-desarrollo
Ejercicio UD02.5. Proyecto Maven - Eclipse

1. En primer lugar lo que he hecho es instalar Maen en mi equipo y añadirlo a las variables de entorno y al path. Luego de eso me he asegurado que funcionaba ejecutando el comando:
			'mvn --version'

2. Para el ejercicio 2, antes de crear el proyecto Maven, he resuelto el cómo hacer la sucesión de Fibonacci en java. En mi caso he utilizado recursividad.
	- Una vez resuelto el algortimo, he procedido a crear el proyecto en Maven siguiendo las reglas de nombrado dadas en el ennunciado. En mi caso lo he creado por terminal usando el comando:
			'mvn archetype:generate -DgroupId=es.iessoterohernandez.daw.endes -DartifactId=fibonacci -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.5 -DinteractiveMode=false'
		Luego de crear el proyecto he desarrollado el código fuente en la clase Fibonacci.java que se encuentra dentro del src/main/java

	- Para generar el artefacto: una vez he desarrollado el código fuente, por terminal le he indicado la ruta del proyecto fibonacci, he generado el artefacto. Para ello he usado los siguientes comandos por terminal:
			'cd C:\Users\trendingpc\Desktop\WP_Entorno\fibonacci'
			'mvn package'



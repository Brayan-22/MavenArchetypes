# Arquetipo en maven para proyectos web java

Realización de un Arquetipo de maven para construir la estructura básica para un proyecto web en java con servlets.



## Instalacion

Instalación del arquetipo en repositorio local de maven o carpeta .m2

Ejecutar los siguientes comandos de maven una vez se está en la carpeta raíz archetype-webapplication
```bash
mvn clean -f .\pom.xml
```

```bash
mvn install -f .\pom.xml
```

El arquetipo quedará guardado en la carpeta repository del directorio .m2 de maven

Para crear un proyecto mediante comandos de maven por consola, con el arquetipo instalado :

```bash
mvn archetype:generate -DarchetypeGroupId=com.arquetipos -DarchetypeArtifactId=archetype-webapplication -Darchety
peVersion=1.0.0 -DgroupId=<DominioDeTuProyecto> -DartifactId=<Nombre de tu proyecto> -Dversion=<Version de tu proyecto>
```
Si usa maven con un IDE, el entorno detectará el arquetipo en su sistema y le ayudará a generar el proyecto sin comandos.

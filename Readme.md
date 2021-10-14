#**Docker Compose Bind9**
***
+Version
Especificamos la versión de Docker Compose a utilizar
+Services
Especificamos opciones para la creación del contenedor
    +nombre
    Introducimos el nombre que deseamos ponerle al contenedor
        +image
        Especificamos la imagen que deseamos utilizar. Podemos añadir la version concreta.
        +Ports
        Puertos a utilizar, con el formato host:contenedor. Se pueden añadir los que necesitemos
        +Volumes
        Asignacion de rutas de volumenes nombrevolumen:ruta
+Volumes
Declaracion de volumenes
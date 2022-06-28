# Taller ARSW Inter (Tablero Multiusuario React con WebSockets)

## Autor
**Julian Adolfo Peña Marin**

## Descripcion
La aplicacion es un tablero multiusuario desarrollado en react, con la finalidad de que los usuarios puedan dibujar y todos puedan ver que es lo que se dibuja, para esto:

 * Cada usuario dibuja con color diferente para que se distinga.
 * Hay un boton de borrar, que elimina todo lo que se dibujo.
 * Para dibujar se utiliza el mouse, leyendo los eventos del mismo.
 * Adicionalmente se utilizaron WebSockets

## Documentacion
Para obtener la documentacion del proyecto, con el siguiente comando se puede generar:

```
    mvn javadoc:javadoc
```

## Como Correrlo
Primero se debe clonar el repositorio, para esto puede utilizar el siguiente comando de git, con la url del repositorio que se quiere clonar, como se muestra a continuación

```
    git clone https://github.com/JulianP-24/Taller-Tablero-WebSockets-inter.git
```

Una vez clonado para generar el JAR, debe poner el siguiente comando

```
    mvn package
```

## Link heroku

https://arcane-lowlands-67341.herokuapp.com/


## Built con

* [Maven](https://maven.apache.org/) - Dependency Management
* [JAVA JDK 8](http://www.oracle.com/technetwork/java/javase/overview/index.html) - construcción


## Licencia

This project is licensed under the GNU General Public License - see the [LICENSE](LICENSE) file for details

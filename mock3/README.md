# Mockup 3

La maqueta de este sitio está optimizada para visualizarse tanto en computadora, tablet y teléfono.

La hoja de estilos está hecha con sass.

### Instrucciones para ejecutarlo

**Instalar SASS**
+ Es necesario instalar ruby primero, escribe en la terminal el siguiente comando: 
```
sudo apt-get install ruby-full 
```

+ Para instalar SASS escribe en la terminal el siguiente comando:

```
sudo gem install sass 
```

**Ejecutar la hoja de estilos**
+ Es necesario estar situados en la carpeta dónde está nuestro archivo sass. (En este caso ./css)
+ En la terminal, sobre ese directorio de trabajo ejecuta el siguiente comando
```
sass [nombre.scss] [nombre.css]
```

En este caso particular el archivo de sass se llama *main.scss* y la hoja de estilos está referenciada en el .html como *main.css*, por lo que el comando sea:
```
sass main.scss main.css
```

# Tarea 1
Tras haber hecho un fork de la rama de trabajo y haberlo descargado, he configurado el upstream así como la rama dev y he creado el directorio capturas y el fichero DIARIO.md. Luego he hecho un commit seguido de un push para subirlo a mi rama.

Un fork es una copia completa de un repositorio en otro dentro de GitHub y manteniendo una conexión con el repositorio original.

Se denomina upstream al repositorio remoto original del que se sacó la copia.


![Captura de consola](capturas/Captura1.png)
![Captura de la rama dev](capturas/Captura2c.png)

# Tarea 2
Se ha añadido una nueva rama (feature/opcion-5) a partir de la rama **dev** en la que se ha añadido una 5 opción y actualizada la 3ª opción, modificando el fichero src/app.tsx.
Se trabaja desde la rama **dev** para que en todo momento tengamos la rama **main** disponible por si fuera necesario realizar alguna modificación en ella sin que esté afectada por las modificaciones de desarrollo.
![Captura de la aplicaión funcionando](capturas/Tarea2a.png)

# Tarea 3
Se ha añadido una nueva rama (feature/opcion-6) a partir de la rama **dev** en la que se ha añadido una 6ª opción así como se ha actualizado loa 3ª opción. Esto se ha hecho modificando el fichero src/app.tsx.
Un **conflicto** en git es cuando dos ramas distintas que parten de la misma base y modificando la misma línea de un mismo fichero tratan de trasladar sus cambios a la rama original. El conflicto surge al no saber qué modificación de las que han hecho simultáneamente es la que debe permanecer.

# Tarea 4
Se ha hecho un Pull Request de la rama feature/opcion-5 hacia **dev** revisando los cambios introducidos.
![Captura del diff del PR](capturas/Tarea4c.png)

# Tarea 5
Se ha realizado un fetch de la rama **dev** sobre la rama feature/opcion-6 intentando realizar un merge de la última sobre **dev**. Al dar un fallo hubo que resolver los conflictos manualmente.
Los indicadores **<<<<<<<**, **=======** y **>>>>>>>** permiten identificar las secciones que provocan el conflico en ambas ramas.
Los datos de la rama entrante (a realizar el merge) que provocan el conflicto con la rama del repositorio están delimitados entre los marcadores: **<<<<<<<**, **=======**.
Los datos de la rama del repositorio (hacia donde se va a realizar el merge) que provocan el conflicto con la rama local están delimitados entre los marcadores: **=======** y **>>>>>>>**.
Para solucionarlo, se aceptaron los **cambios de la rama entrante** en la descripción de la opción 3 y **ambos** para las opciones 5 y 6 (ya que estaban cada una en una rama distinta).
![Captura del PR de feature/opcion-6 mostrando el error](capturas/Tarea5a.png)
![Captura marcadores de conflicto en VSCode](capturas/Tarea5b2.png)
![Captura de la aplicación funcionando](capturas/Tarea5c.png)

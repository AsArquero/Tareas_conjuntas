# METODOLOGÍA

PASO 1. Utilizando el comando cp hemos creado nuevos archivos Index con título "pie" y "cabecera". 

- Comandos empleados: "cp index.html pie.html" y "cp index.html cabecera.html".

PASO 2: Para la elaboración del cuerpo, sin embargo, lo que hemos hecho es convertir nuestras prácticas markdown en prácticas con lenguaje html. Para ello hemos utilizado el comando "pandoc.exe".
 
- Ejemplo: pandoc.exe ../ejercicios/Practica-1-Comentario.md -o Practica-1-Comentario.html
 
PASO 3. Los archivos html resultantes los hemos renombrado como ...-base con "mv". 

- Ejemplo: mv Practica-1-Comentario.html Practica-1-Comentario-base.html. 

PASO 4. La unión de todos los archivos del cuerpo se ha conseguido mediante el comando "cat". Los hemos juntado unificando las 8 prácticas (las 4 de Miguel Ángel y las 4 de Adrián) en un solo archivo. Miguel Ángel se ha encargado de hacer el comando cat desde su ordenador utilizando los archivos que Adrián había subido a GitHub. Para ello empleó "git clone" y, de este modo, descargó los archivos html de las prácticas de Adrián en su propio pc (los movió a su repositorio para tenerlos todos juntos en una misma carpeta). Al disponer de los 8 archivos necesarios ya solo había que concatenarlos.
 
- Comando utilizado para la concatenación: "cat cabecera.html Practica-1-Comentario-base.html Practica-2-Comentario-base.html Practica-3-visualizacion-base.html Practica-4-historia-periodismo-datos-base.html Practica_1_Adri-base.html Practica_2_Adri-base.html Practica_3_Adri-base.html Practica_4_Adri-base.html pie.html> Trabajo-final.html".

PASO 5. ¡Eureka! El comando "cat" funcionó. El trabajo, no obstante, aún no ha terminado. Después de realizar la concatenación descubrimos que había un importante número de errores que debíamos corregir (imágenes demasiado grandes o que no se veían, textos fuera de lugar, escasa diferenciación entre prácticas...).

Desde nano empezamos a corregir los fallos en el archivo concatenado.
- "Lang": de "en" a "es" para cambiar el idioma a español.
- En "title" pusimos "Trabajo Final".
- Creamos un nuevo "<h1 id="trabajo-final">Trabajo Final" para el título.
- En "navbar-brand" hemos cambiado "Fixed-navbar" por nuestros nombres.
- En "nav-link active" hemos cambiado "home" por "Periodismo de Datos".
- En "nav-link" hemos cambiado "link" por "Trabajo Final".
- En "nav-link disabled" hemos cambiado "disabled" por "Metodología.html".
- Hemos creado un índice siguiendo la estructura del encontrado en index.html. En las líneas superiores a las de cada uno de los apartados que queríamos convertir en enlaces al índice hemos escrito "<p><a id="codigo_correspondiente_del_indice_sin_#"></a></p>". También hemos cambiado los títulos de las prácticas para que quedara todo mucho más claro.
- Hemos resaltado los títulos sybrayándolos con el comando "<u>". Ejemplo: "<u>Práctica 1 - Miguel</u></h1>".
- Hemos eliminado algunas frases que no cuadraban en el conjunto de la página y hemos corregido algunas palabras sueltas. Justo a la derecha de la primera imagen de Miguel y de la primera imagen de Adrián, por ejemplo, nos aparecía una línea descolgada. Esto se debía a que faltaba añadir "<p>" al inicio de la sentencia. 
- Las imágenes de las prácticas de Miguel las hemos hecho más pequeñas añadiendo con nano width="1200" a sus respectivas líneas.

PASO 6: Añadir las metodologías.
El archivo que ahora estamos escribiendo lo hemos pasado a html utilizando el comando "pandoc.exe" y lo hemos concatenado al resto del trabajo. Los comandos empleados han sido los descritos en los pasos 2, 3 y 4 de esta metodología.

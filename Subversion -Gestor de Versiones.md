# GESTOR DE VERSIONES SUBVERSIÓN #
## Introducción ##
Hoy en día el manejo de la información es mas eficiente y confiable, por ende 
aquí se hace mención del sistema de control de versiones; es una herramienta 
que registra todos los cambios hechos en uno o más proyectos, guardando así 
versiones del producto en todas sus fases del desarrollo. Las versiones son 
como fotografías que registran su estado en ese momento del tiempo y se van 
guardando a medida que se hacen modificaciones al código fuente. También se mencionara el gestor de versiones Subversión.
Subversión es un sistema diseñado para reemplazar otro sistema de control de versiones llamado CVS. CVS es el sistema de control de versiones usado en gran 
parte del mundo de la programación de fuente abierta. Varios de los comandos 
que utilizaremos aquí también son válidos en CVS.

## Historia ##
* Fue lanzado en el año 2000 bajo una licencia Apache/BSD y su última versión 
estable fue liberada en febrero de este mismo año,
* El Objetivo fue mejorar CVS.
* Versión 1.0 liberada en 2004. Contemplaba todas de las     funcionalidades 
de CVS y muchas mejoras
* Grandes proyectos y empresas lo adoptaron: KDE, GCC, Python, Samba, Mono,
PuTTy, Zope, Plone, CUPS, etc. Google y Sourceforge lo ofrecen como servicio.

## Características ##
Subversión proporciona:


- **Versionado de directorios**
Subversion implementa un sistema de ficheros versionado “virtual ” que sigue 
los cambios sobre árboles de directorios completos a través del tiempo. Ambos, ficheros y directorios, se encuentran bajo el control de versiones.



- **Verdadero historial de versiones**
Con Subversion, usted puede añadir, borrar, copiar, y renombrar ficheros y directorios. Y cada fichero nuevo añadido comienza con un historial nuevo, 
limpio y completamente suyo.

- **Envíos atómicos**
Una colección cualquiera de modificaciones o bien entra por completo al 
repositorio, o bien no lo hace en absoluto. Ésto permite a los desarrolladores construir y enviar los cambios como fragmentos lógicos e impide que ocurran 
problemas cuando sólo una parte de los cambios enviados lo hace con éxito.

- **Versionado de metadatos**
Cada fichero y directorio tiene un conjunto de propiedades; claves y sus 
valores asociado a él. Usted puede crear y almacenar cualquier par arbitrario 
de clave/valor que desee. Las propiedades son versionadas a través del tiempo, 
al igual que el contenido de los ficheros.

- **Elección de las capas de red**
Subversión tiene una noción abstracta del acceso al repositorio, facilitando a 
las personas implementar nuevos mecanismos de red. Subversion puede conectarse 
al servidor HTTP Apache como un módulo de extensión. Ésto proporciona a 
Subversión una gran ventaja en estabilidad e interoperabilidad, y acceso 
instantáneo a las características existentes que ofrece este 
servidor—autenticación, autorización, compresión de la conexión, etcétera. 
También tiene disponible un servidor de Subversión independiente, y más ligero. 
Este servidor habla un protocolo propio, el cual puede ser encaminado fácilmente 
a través de un túnel SSH.

- **Manipulación consistente de datos**
Subversión expresa las diferencias del fichero usando un algoritmo de 
diferenciación binario, que funciona idénticamente con ficheros de texto 
(legibles para humanos) y ficheros binarios (ilegibles para humanos). Ambos 
tipos de ficheros son almacenados igualmente comprimidos en el repositorio, 
y las diferencias son transmitidas en ambas direcciones a través de la red.

- **Ramificación y etiquetado eficientes**
El coste de ramificación y etiquetado no necesita ser proporcional al tamaño del proyecto. Subversión crea ramas y etiquetas simplemente copiando el proyecto, 
usando un mecanismo similar al enlace duro. De este modo estas operaciones toman solamente una cantidad de tiempo pequeña y constante.

- **Hackability**
Subversión no tiene un equipaje histórico; está implementado como una colección de bibliotecas compartidas en C con APIs bien definidas. Ésto hace a Subversión extremadamente fácil de mantener y reutilizable por otras aplicaciones y lenguajes.

- **Arquitectura de Subversión**
![](http://image.slidesharecdn.com/presentacion-nuestra-1234631356296993-3/95/control-de-versiones-con-subversion-9-728.jpg?cb=1234609891)

## Comandos y descripcion ##
1. Crear copia local (checkout)— Se puede especificar una revisión o fecha 
particular
2. Actualizar la copia de trabajo (update)— Permite recuperar las ultimas modificaciones del repositorio
3. Hacer cambios— Add, delete, copy, move.
4. Examinar cambios — status, diff, revert
5. Fusionar cambios — merge, resolved
6. Enviar cambios (commit)— Requiere un mensaje 'log' que detalle las 
modificaciones hechas
7. Copia de trabajo — Es la copia local de los archivos de un repositorio, en un momento del tiempo o revisión específicos.
8. Check-out (co) — Crea una copia de trabajo local desde el repositorio. Se 
puede especificar una revisión específica.
9.  Commit (ci)— Cuando una copia de los cambios hechos a una copia local es integrada sobre repositorio.
10.  Import — Una importación es la acción de copiar un árbol de directorios
local (que no es en ese momento una copia de trabajo) en el
repositorio por primera vez.
11.  Actualizar (update)— Una actualización integra los cambios que han sido 
hechos en el repositorio (por ejemplo por otras personas) en la copia de
trabajo local.
12. Conflicto — Ocurre cuando se realizan dos cambios al mismo documento, y el
sistema es incapaz de reconciliar los mismos.
13. Resolver— La intervención del usuario para atender un conflicto entre
diferentes cambios al mismo documento.


## Conclusiones ##
El gestor de versiones Subversión es una mejora de CVS, que maneja mejor los 
archivos y directorios a través de copias y renombrados. El tiempo en resolver 
los conflictos es mucho menor que el tiempo perdido por un sistema de bloqueos.
Y como ya se sabe los gestores de versiones son de gran ayuda para trabajar en 
paralelo con otros usuarios en un mismo tema.

## Bibliografia ##
[http://www.monografias.com/trabajos78/subversion-control-versiones/subversion-control-versiones2.shtml](http://www.monografias.com/trabajos78/subversion-control-versiones/subversion-control-versiones2.shtml)

[https://mgaitan.github.io/downloads/charla-svn.pdf](https://mgaitan.github.io/downloads/charla-svn.pdf)





 



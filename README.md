guides
======

Poderopedia Geek Guides

Contenidos
* [Repositorios] (#repositorios)
* [HTML y CSS] (#html-y-css)
* [Javascript] (#javascript)
* [Python] (#python)

## Repositorios
-------------------

* Documentar desde el inicio el proyecto, indicando las librerías requeridas y cada uno de los pasos de configuración
* Documentar cualquier condición necesaria para el funcionamiento de la aplicación, incluídos CronJobs y variables de ambiente.

## HTML y CSS
-------------------

* La codificación del archivo HTML debe ser utf-8
* Los IDs de cada elemento debe indicarse utilizando minúsculas y guiones entre palabras ``minusculas-con-guion`` y sin utilizar acentos
* Los nombres de los IDs deben ser consistentes con la jerarquia del DOM y deben nombrarse desde los más general a lo particular ``barra-azul`` y no ``azul-barra``
* Se deben incluir los CCS dentro del minificador utilizando ``response.files.append()``.
* Se debe utilizar fast_download para las URL de ``src`` en los tag ``<IMG>``
* Google Analytics debe ir antes del tag ``</HEAD>`` [?](http://support.google.com/googleanalytics/bin/answer.py?hl=en&answer=174090)
* Poner los modales en el footer.

##Javascript
-------------------

###General

* Usar indentación de Python (4-espacios) para hacer consistente los IDE y facilitar la lectura del código.
* Los nombres de las variables deben ser en ``minusculas_con_underscore`` y sin acentos
* Las variables estáticas deben ser en ``MAYUSCULAS_CON_UDERSCORES``, y sin acentos.
* Todas las variables globales deben ser definidas al comienzo del documento.
* Todas las variables deben ser limitadas al contexto usuando ``var``.
* Declarar sólo una variable por línea.
* Finalizar todas las sentencias con puntoycoma.
* Usar espacios después de apertura y antes de cada cierre de llave ``{ }`` o corchete ``[ ]``  
en cada declaración de objetos, funciones y arreglos, por ejemplo: ``{ [ foo ] }``.
* No usar espacios después de cada parátesis circular, por ejemplo: ``if (a>b) {`` y no ``if ( a>b ) {``
* Acceder a las propiedas de una estructura de datos, utilizando la sintaxis de corchetes ``data["propiedad"]`` 
en vez de ``data.propiedad``
* Usar ``===`` en vez de ``==`` [?](http://www.impressivewebs.com/why-use-triple-equals-javascipt/)
* Usar comillas simples ``'strings'`` para strings.







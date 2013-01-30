Introducción
------------

PHP es un lenguaje de servidor creado en por el programador canadiense Rasmus Lerdorf.
El objetivo principal de este lenguaje es facilitar la creación de sitios web de forma rápida y sencilla.
PHP además nos permite crear potentes scripts que funcionan en entorno de línea de comandos e incluso aplicaciones de escritorio, aunque para entornos de escritorio contamos con lenguajes y entornos de programación más adecuadas que PHP.

Debido a su sintaxis, a que es un lenguaje no tipado y que sufre de un catálogo de funciones que no siempre se usar de forma uniforme, PHP ha sido muy criticado por programadores de otros lenguajes como Ruby, Java o Python.
Lo cierto es que PHP es un lenguaje que nos da mucha libertad y rapidez para crear sitios y aplicaciones web, y cómo pudimos aprender en la película Spiderman de Sam Raimi: "un gran poder conlleva una gran responsabilidad".
Al ser el lenguaje más utilizado para programar sitios web, después claro está de html y javascript, muchos programadores no asumieron de forma seria su responsabilidad contribuyendo a que PHP adquiriese entre algunos círculos de programadores una fama inmerecida.
Por suerte, PHP va contando con cada vez mejores programadores, en parte gracias a la aparición de Frameworks de desarrollo como Symfony2 y Zend Framework.


## Requisitos e instalación

Para que php funcione en un ordenador o servidor, debe estar instalado en el mismo.
PHP dispone instalaoores para Windows, MacOSX y Linus, además de otros sistemas tipo UNIX como AS/400.
Consulte el capítulo dedicado a la instalación para conocer cómo disponer de php en su ordenador.

Si lo que queremos es programar sitios web, lo más sencillo es contratar un servicio de hosting en lugar de instalar php en nuestro ordenador. 
Al ser el lenguaje más utilizado de Internet, PHP viene instalado en prácticamente cualquier servicio de hosting normal, por lo que tan sólo nos tendremos que preocupar de la versión que tienen instalada.


### Versiones

PHP dispone de una comunidad muy grande de programadores que están contínuamente mejorando el lenguaje, corrijiendo errores y añadiendo nuevas funcionalidades.
En el sitio php.net podemos ver qué versión es la más reciente y consultar las mejoras que se han introducido.

Es muy recomendable fijarse en la versión de PHP que nuestro hosting o servidor tiene instalada, ya que las nuevas versiones corrijen fallos de seguridad y rendimiento importantes, además de añadir nuevas funcionalidades.

Si disponemos de un servicio de hosting y queremos ver de forma rápida qué versión de PHP tenemos instalada, bastaría con crear un archivo con extensión ".php", por ejemplo info.php, con el siguiente código en su interior:

  <?php
    phpinfo();
  ?>

Con este sencillo código podremos acceder a nuestro sitio web mediante http://nuestro-dominio.com/info.php y ver la versión de PHP y las extensiones instaladas, además de visualizar las variables de entorno de nuestro servidor, que explicaremos más adelante.


### Extensiones

Las extensiones son librerías que se instalan en el servidor y que dotan de funcionalidad extra a PHP, funcionalidad que podemos utilizar desde el código de nuestro sitio web.
Un ejemplo de extensión que suele necesitar instalarse es PDO, una extensión que nos permite trabajar con las bases de datos más conocidas y utilizadas.
Veremos cómo utilizar e instalar esta extensión en más detalle en el capítulo dedicado a bases de datos.




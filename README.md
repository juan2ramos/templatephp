# template-php

1. Escribimos en la terminal composer init
2. Ingresar todos los datos
3. Añadir en el archivo composer.json despues de   "require": {},
~~~
"autoload": {
  "psr-4":{
    "App\\": "app/"
  }
}
~~~
4. Crear la carpeta public y app en la raiz
5. en public crear el archivo index.php y requerimos el archivo autoload de composer
~~~
require '../vendor/autoload.php';
~~~
6. Escribimos en la terminal composer dump

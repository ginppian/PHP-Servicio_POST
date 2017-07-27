PHP Servicio POST
=================

## Definición

<p align="justify">
	Se busca consumir un servicio <i>POST</i> con <i>PHP</i>.
</p>


* Agregamos nuestro código al servidor;

```php
<?php

if($_POST){

        $nombre = htmlspecialchars($_POST['nombre']);
        echo "Hola $nombre";

}
```

* Probamos con POSTMAN

<p align="center">
	<img src="https://github.com/ginppian/PHP-Servicio_POST/blob/master/imgs/img1.png" width="884" height="575">
</p>


## Fuente

<a href="https://www.youtube.com/watch?v=T8JM7p87NS8">Submit Form</a>

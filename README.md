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

        $nombre = $_POST['nombre'];
        echo "Hola $nombre";

}
```

* Probamos con POSTMAN

<p align="center">
	<img src="" width="884" height="575">
</p>


## Fuente

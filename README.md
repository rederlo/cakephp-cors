#Instalation

```php

composer require rederlo/cakephp-cors

```

```php  
//in config/Boostrap.php
DispatcherFactory::add('Cors.Cors', ['priority' => 1]);
```

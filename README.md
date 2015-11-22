# Integrating Whoops with Phalcon

The provider uses the default Phalcon DI unless you pass a DI instance into the constructor.

```php
new Whoops\Provider\Phalcon\WhoopsServiceProvider();

// --- or ---

$di = new Phalcon\DI\FactoryDefault();
new Whoops\Provider\Phalcon\WhoopsServiceProvider($di);
```

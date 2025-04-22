# Just Blade

### Laravel's Blade standalone

Blade templating engine for use outside of Laravel

```bash
composer require webpup/just-blade
```

### Howto use it
How to use it in your plain php projects
```php
$views = THEME_PATH . '/views';
$cache = THEME_PATH . '/storage/cache';

$blade = new \Just\Blade($views, $cache);
$blade->render($template, $data);
```


## Docs
[webpup.github.io/just-blade](https://webpup.github.io/just-blade)
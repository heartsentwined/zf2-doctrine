# zf2-doctrine

wrapper for DoctrineORMModule + DoctrineModule's CLI, tailored for yaml config files

The official CLI looks for `config/application.config.php`. This wrapper looks for `config/application.config.yml`.

# Installation

[Composer](http://getcomposer.org/):

`"minimum-stability": "dev"` is required because `DoctrineORMModule` still has frequent updates.

```json
{
    "minimum-stability": "dev",
    "require": {
        "yalesov/zf2-doctrine": "2.*"
    }
}
```

# Usage

Call (modified) CLI at `vendor/bin/doctrine-cli`.

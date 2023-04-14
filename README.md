# drupal-grumphp

## Installation

Add default grumphp.yml path to composer or copy to root folder:

```
composer config extra.grumphp --json '{"config-default-path": "vendor/hinternet/drupal-grumphp/configs/grumphp.yml"}' ;
```

```
composer config extra.grumphp --json '{"config-default-path": "vendor/hinternet/drupal-grumphp/configs/grumphp.yml"}' ;
composer require --dev hinternet/drupal-grumphp -W
```


or manually add to composer.json:

```json
    ...
    "extra": {
        "grumphp": {
            "config-default-path": "vendor/hinternet/drupal-grumphp/configs/grumphp.yml"
        },
        ...
    },
    ...
```

or to let composer scaffold do the work for you, add this to composer.json:

```json
    ...
    "extra": {
        "drupal-scaffold": {
            "allowed-packages": [
                "hinternet/drupal-grumphp"
            ],
            ...
        },
    ...
```

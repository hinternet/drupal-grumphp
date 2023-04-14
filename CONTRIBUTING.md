# How to contribute

Clone this repo:
````bash
git clone git@github.com:hinternet/drupal-grumphp.git
````

Add to your composer:
````json
"repositories": [
    {
        "name": "hinternet/drupal-grumphp",
        "type": "path",
        "url": "private-files/drupal-grumphp",
        "options": {
            "symlink": true
        }
    }
]
````

Run in shell:
````bash
composer require  hinternet/drupal-grumphp --dev
````

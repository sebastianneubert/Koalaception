# Koalaception
Koalmon integration for Codeception


```
// This is global bootstrap for autoloading
include_once 'phar://' . __DIR__ . "/../module/KoalamonReporter/KoalamonReporter.phar/vendor/autoload.php";
```

```
# codeception.yml
extensions:
    enabled:
        - Koalamon\Extension\KoalamonReporter
    config:
        Koalamon\Extension\KoalamonReporter:
            api_key: 98208A01-9F93-4B54-B442-**********
            system: www.koalamon.com
            url: http://drupal-jenkins/
```

PHP Generator
---

This is universal php generator what can
generate different templates based on 
generator classes what you may create.

Installation
---

For installation you may do like this in your composer.json:
```
$ composer require kosuha606/generator
```

Usage in Yii2
---

For Yii2 you may use GeneratorController - it is the command
what can get scenarios of .php files like so:
```
<?php

return [
    [
        'class' => GeneratorEntityFiles::class,
        'base' => 'Log',
        'fields' => [
            'level',
            'category',
            'log_time',
            'prefix',
            'message',
        ]
    ]
];
```

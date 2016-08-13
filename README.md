## Yii1- PHP Vars to Jacascript
Transform PHP Vars to JavaScript

ported from http://github.com/laracasts/PHP-Vars-To-Js-Transformer


## How to use 

Put `Js.php` in `components` directory

and use it like this : 

```php
        $js = new Js();

        $testClass = new \stdClass();
        $testClass->aa = 'saeed';
        $testClass->test = 'test';

        $js->put(['testVars' => $testClass, 'age' => 22, 'amount' => 22.3]);
```

for more information take a look at : https://github.com/laracasts/PHP-Vars-To-Js-Transformer

Usage
================

```php
echo \russ666\widgets\Countdown::widget([
    'datetime' => date('Y-m-d H:i:s', time() + 1000),
    'format' => '%M:%S',
    'events' => [
        'finish' => 'function(){location.reload()}',
    ],
])
```

Params
================

datetime
-----------------------
Datetime string to countdown

format
-----------------------
Datetime format for widget (http://hilios.github.io/jQuery.countdown/documentation.html#formatter)

events
-----------------------
Widget events (http://hilios.github.io/jQuery.countdown/documentation.html#events)

Plugin pages
================
Homepage - http://hilios.github.io/jQuery.countdown

GitHub - https://github.com/hilios/jQuery.countdown

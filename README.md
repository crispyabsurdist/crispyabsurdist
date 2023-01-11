```php
<?php

namespace MarkusHedenborn;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Triggerfish',
                'position' => 'senior web developer'         
            ]
        ];
    }

    public function getCurrentKnowledge(): array
    {
        return [
            Php::class,
            JavaScript::class,
            Laravel::class,
            TailwindCss::class,
            Aws::class,
	    Scss::class,
	    Sql::class,
        ];
    }

    public function TLDR(): array
    {
        return [
            'tldr' => [
	    	'name' => 'Markus Hedenborn',
                'country' => 'Sweden',
		'languages' => [Swedish, English],
                'ADHD' => true,
		'email' => 'lc19mj4x5@mozmail.com'
            ]
        ];
    }
}
```

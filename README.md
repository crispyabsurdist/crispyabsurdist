```php
<?php

namespace WhoAmI;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company'  => 'Triggerfish',
                'position' => 'senior web developer'
		'location' => 'remote'
            ]
        ];
    }

    public function getCurrentKnowledge(): array
    {
        return [
			Php::class,
			Laravel::class,
			JavaScript::class,
			Laravel::class,
			TailwindCss::class,
			Aws::class,
			Scss::class,
			Sql::class,
			Devops::class,
			Netsec::class,
			Scripting::class
        ];
    }

    public function tldr(): array
    {
        return [
            'data' => [
		'name' 	    => 'Markus Hedenborn',
		'country'   => 'Sweden',
		'languages' => ['Swedish', 'English'],
		'ADHD'      => true,
		'email'     => 'lc19mj4x5@mozmail.com'
            ]
        ];
    }
}
```

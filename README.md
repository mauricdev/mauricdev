```php
<?php

namespace Mauricdev;

class About extends Me
{
    public function getEstudios(): array
    {
        return [
            'Institución' => [
                'Instituto' => 'Duoc Uc',
                'Titulo' => 'Ingeniero en informática'         
            ]
        ];
    }

    public function getConocimiento(): array
    {
        return [
            Php::class,
            Javascript::class,
            Ajax::class,
            Laravel::class,
            Codeigniter::class,
            Webservice::class,
            Aspx:: class,
            Java::class,     
        ];
    }

    public function getFaseMotivadora(): string
    {
        return 'Si se puede imaginar se puede programar.';
    }
}
```

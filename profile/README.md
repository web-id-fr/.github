```php
<?php

class WebID
{
    public function __construct(
        public string $name = 'Web^ID',
        public string $catchPhrase = 'agence_tech_lead',
        public bool $isLarvelCertified = true,
        public array $stack = ['Laravel',  'React'],
        public string $jobOffersUrl = 'https://www.welcometothejungle.com/fr/companies/web-id/jobs'
    ) {}
}

var_dump(new WebID); die();
```
### Hi there 👋

```php
<?php

declare(strict_types=1);

namespace World;

class Alejandro implements IDeveloper, IInvestor, IEntrepreneur
{
    public function getStack(): array
    {
        return [
            'languages' => [
                ILanguage::PHP,
                ILanguage::JS,
                ILanguage::SQL,
            ],
            'frameworks' => [
                IFramework::LARAVEL,
                IFramework::LUMEN,
                IFramework::VUE,
                IFramework::PHPUNIT,
            ],
            'others' => [
                IArchitecture::CLEAN,
                IPlatform::DOCKER,
                IRdbms::MYSQL,
                IVcs::GIT,
            ],
        ];
    }

    public function getLearning(): array
    {
        return [
            IFramework::SYMFONY,
            ITech::BLOCKCHAIN,
        ];
    }
}
```
}

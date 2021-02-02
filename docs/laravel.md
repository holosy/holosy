# Laravel

`composer require holo-php/laravel-adapter`

```php
<?php
namespace Holo\Laravel;

use Holo\EntityManager;
use Holo\Entity;

class EntityManagerAdapter extends EntityManager
{
	public function save(Entity $entity)
	{
		$entity->save();
	}
}

```

---

[Back](index.md)
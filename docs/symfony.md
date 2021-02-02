# Symfony

`composer require holo-php/symfony-adapter`

```php
<?php
namespace Holo\Symfony;

use Holo\EntityManager;
use Holo\Entity;

class EntityManagerAdapter extends EntityManager
{
	public function save(Entity $entity)
	{
		$this->em->save($entity);
	}
}
```

---

[Back](index.md)
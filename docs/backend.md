# Backend

Language used is ```PHP >= 8```

As everything should be, each library will be **framework-less** dependent. 
To actually use it in a real application some **adapters** will be required, for testing [Laravel](https://github.com/laravel/laravel) and [Symfony](https://github.com/symfony/symfony) will be used.

To mantain it's **framework-less** principle a list of concerns will be handled over the **adapters**:
- Routing
- Queue 
- Events and Listeners
- Configuration
- ORM

## Configuration


## Routing
## Queue
## Events and Listeners



## Testing
Each push should be tested with Github Actions and deployed in a environment testable.

A holo/postman will be used to generate a .json containing all postman methods/calls to test to the environment

## Dependency
[Holo] requires a sets of [Symfony Components] 

---

[Back](index.md)

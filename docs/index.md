# Main

The purpose is to create an ecosystem of applications/tools that will give any user the ability to create and mantain a full customizable web application for a simple and generic purpose.

As such, this is not intended to build high complex web application such as games, tools or really demanding/specific applications.

Without any stored data the application will result in a blank page.

As the application start for the first time, the user will be asked what kind of application he needs to use. A lists of presets will be available, for example:
- Todo personal
- Blog
- Reservation of a Restaraunt 
- Ecommerce
- CRM


> A list of demo with the written presets

Presets are not mandatory, you can start with a blank project and add any feature later, whanever you want.

As you configure your application you'll be asked what kind of data you're going to handle (e.g. a Blog Article), what kind of actions you are going to add to interact with your data (Create, Edit, Publish article) and what should be your own Interface (Articles API, Admin CRUD article)

So there are 3 key aspects: **Data**, **Action**, **Interface**

You don't need to reinvent the wheel each time, a free marketplace will be browsable showing all available presets/seeds directly from Github. So you will be able to import each of them (Data, Action, Interface)
```@
@Note: Security issues
```

Each preset **IS NOT** mutually exclusive with the others, but a preset could intersect with another (e.g. Ecommerce and Warehouse System Manager), a step-by-step will be provided to resolve such conflicts


All of this will be open source, under MIT.

## Resources

- [Installation](installation.md)
- [Backend](backend.md)
- [Data](data.md)
- [Action](action.md)
- [Laravel](laravel.md)
- [Symfony](symfony.md)
- [Cases](cases.md)

---

[Back](index.md)
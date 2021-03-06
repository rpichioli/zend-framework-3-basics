# zend-framework-3-laboratories
>In development phase

The application is located at the `/src` folder.

I used the official **ZendSkeletonApplication**, installed by **composer** in the terminal. Exactly this way:
```
composer create-project -s dev zendframework/skeleton-application path/to/install
```

I'm using inside the `(root)/src` folder the command `composer serve` that executes a new local server in localhost under the port **8080** already running the app.

It's configured inside the **composer.json** file looking like: (You can execute it directly too)
```
"scripts": {
  (...)
  "serve": "php -S 0.0.0.0:8080 -t public public/index.php",
  (...)
},
```

You can see here some Zend Framework stuff like it's own structure, Zend/Db, Zend/Paginator, Zend/Navigation, AutoLoad, ModuleManager, Factory, Routes, CRUD, Test, and more...

I'm going back into ZF again for now (distant since it's first version sadly) and I would like to share my studies with everyone who wants to go into the framework too and understand more about it.

The project consists in improving the official ZF3 guides implementing it with the acquired knowledge while going a little bit deeper into each stuff.

If you have some suggestion or maybe something to pull request me - let me know!

See ya, Rodrigo.

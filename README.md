# hello_world
Hello World Package

reqiure the below package name and its dev-master version

"amolgunjal/hello-world": "dev-master"

In test.php

require_once __DIR__ . '/vendor/autoload.php'; // Autoload files using Composer autoload

use HelloWorld\HelloWorld;

echo HelloWorld::world();

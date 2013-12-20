Apache Thrift generated PHP
============
This is a project to hold the generated Apache Thrift library, along with a composer.json to make grabbing for your projects simple.

Composer usage
--------------
Create a composer.json file and add the follow json to load the 0.9.0 version of the generated Thrift PHP
```json
{
    "require": {
        "rmcfrazier/php_thrift": "0.9.0"
    }
}
```

Issue the composer install command
```bash
composer install
```

You should see the following output from composer
```bash
Loading composer repositories with package information
Installing dependencies

  - Installing rmcfrazier/php_thrift (0.9.0)
    Loading from cache
    
Writing lock file
Generating autoload files
```

All done.

Thrift library versions
--------------------
Each version will be in its own tag.

Versions in this repo
---------------------
- 0.9.0
- 0.9.1



# Project Scripts

There should be exactly one script for one type of projects managing all project-related tasks:

* `osm` for Osm project
* `mage2` for Magento 2 projects
* ...

All these scripts will share commands such as:

* `backup`
* `restore`
* `config:nginx`
* `config:phpstorm`
* `repos`
* `release`
* `update`
* ...

Reusable code can go to a reusable packages such as `osmscripts/project`, `osmscripts/phpstorm` and other.

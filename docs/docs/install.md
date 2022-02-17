## Installation
This is a Drupal installation so you should be able to install it following the instructions on Drupal.org.

 - [drupal.org/documentation/install](https://www.drupal.org/documentation/install)

## Requirements
Currently, there are no special requirements other than the Drupal 7.x core. You can find more on Drupal.org.

 - [drupal.org/requirements](https://www.drupal.org/requirements)
 
Furthermore we could **suggest** these software versions for a better experience.

 - php 5.4+
 - php ```memory_limit = 256M```

## Get the "complete" Drupal installation (recommended):

- Drupal.org: [drupal.org/project/soda](https://www.drupal.org/project/soda)

## Using Drush Make

Requires [drush](https://github.com/drush-ops/drush) version 6.x+.

Create a full version with drush make:

``` bash
git clone --branch 7.x-1.x git@github.com:drupal-soda/soda-profile.git
cd soda-profile
drush make --prepare-install build-soda.make webroot
cd webroot
drush site-install soda --db-url="mysql://DBUSER:DBPASS@localhost/DBNAME"
```

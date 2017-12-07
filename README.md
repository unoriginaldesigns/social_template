# Open Social template

This is a composer based installer for the [Open Social distribution](http://www.drupal.org/project/social).

## Prerequisites

1. [Composer](https://getcomposer.org/download/)
2. [Drupal VM](https://github.com/geerlingguy/drupal-vm)

It's just composer, isn't it awesome? :)

## Standalone installation of Open Social

```
composer create-project unoriginaldesigns/social_template:dev-master DIRECTORY --no-interaction
```


Composer will create a new directory called DIRECTORY. Inside you will find the html directory with the entire code base of [Open Social distribution](http://www.drupal.org/project/social). You should be able to install it like any other Drupal site. 


## DrupalVM intallation of Open Social

```
vagrant up
```

DrupalVM will run the `composer create-project ...` during its build cycle, no muss, no fuss.


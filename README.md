# FARE - The Free Architecture for Remote Education
This is the main codebase for FARE. 

## What
This repository contains a Drupal module, called FARE, which is a composition
of tools and functionalities for remote education. 
Each functionality is developed in a separate module in order to be easily
tested and deployed. 

## How To 
This is a Drupal 7.x module. As such, it requires a working installation of
Drupal. For development purposes, I suggest using the
[drupal-vm](https://github.com/geerlingguy/drupal-vm) project. 
Once the dev env is setup it is necessary to fix the dependencies.
If you are using `drush` it should clear the Drupal dependencies reading from
the `info` file.
However, some dependencies have to be installed locally by means of composer,
see the `composer.json` file. 
There is a dedicated repo for the theming of the module.

## Licensing
This code is licensed under a GNU Affero General Public License, v3.

## Author
Copyright (C) 2014-2018 libremente  
`<surf> AT <libremente> DOT eu`

# Notice
This repository contains the prototype version of the platform. The new version
is under development and will be published soon. 

# FARE - The Free Architecture for Remote Education
This is the main codebase for FARE. 
FARE is an e-learning web platform which stands in between a basic search
engine and a more complex LMS.
By leveraging the CMIS APIs, it draws from a heterogeneous set of repositories
located worldwide. Thanks to the integration with several other external modules
it can provide a novel learning experience. 

## What

--- This repo is a WIP, meaning that the several components will be added
regularly and, right now, it does **not** represent a working installation. If
you need a full working installation, contact me (see below contact info). ---

This repository contains a Drupal module, called FARE, which is a composition
of tools and functionalities for remote education. 
Each functionality is developed in a separate Drupal module in order to be easily
tested and deployed.  

These are the modules currently on GitHub:
* FARE (this repo)
* [FARE Salva](https://github.com/Open-Education-Polito/oep-fare-salva)
* [FARE Python](https://github.com/Open-Education-Polito/oep-fare-python)
* And many more to come.

Also, for the theming part of the module, a dedicated repo exists.

## How To 
This is a **Drupal 7.x** module.  As such, it requires a working installation
of Drupal.  For development purposes, I suggest using the
[drupal-vm](https://github.com/geerlingguy/drupal-vm) project.  Once the dev
env is setup it is necessary to fix the dependencies.  If you are installing
the module by means of `drush`, it should clear the Drupal dependencies reading
from the `info` file. If not, you should install the dependencies manually.
However, some dependencies have to be installed locally by means of composer,
see the `composer.json` file. 

## Dependencies
### Drupal 7.x Modules
* CMIS
* Big Blue Button
* Rules
* CAPTCHA
* Views

### External libs
* Mobiledetect

## Licensing
This code is licensed under a GNU Affero General Public License, v3.
See the `LICENSE.md` file for extended info, and the license files inside each
module's repository.

## Author
Copyright (C) 2014-2018 libremente  
`surf AT libremente DOT eu`

# Installing Drupal 8
The easiest way that I've found is to install Drupal with the amazing tool which is called [drupal-console](https://drupalconsole.com/).

## Installing Drupal Console globally
To install that tool globally just copy & paste the following line in your console:
>`composer global require drupal/console:@stable`

## Downloading Drupal with an option to select version
To download Drupal with an option to select version from interactive mode use:
>`drupal site:new project_name`

## Installing Drupal in the interactive mode
Before this step you need to create database and know credentials. You need to also have configured web server and PHP.

To install Drupal in the interactive mode use following command:
>`drupal site:install`

During installation **drupal-console** will ask you for some details.

## Generating custom module skeleton
To generate custom module skeleton in the interactive mode you can use:
>`drupal generate:module`

You have to provide some details regarding your custom module and at the end **drupal-console** will create necessary files for you.

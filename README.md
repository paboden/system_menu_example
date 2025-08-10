**Drupal 7**

# System menu example module

## Create your own menu in code

An example on how to create a system menu (non-delete-able menu) and examples of menu links to external sites, callback links to external sites, changing internal URL's to external URL's and examples of duplicating existing links in a new menu (like logout) completely from within a module.

This is an **EXAMPLE** only module. On its own, its not useful, but can be used as a framework for creating your own hardcoded Drupal menu.

## Why...wha...huh?

_So, What is this setup good for?_
 
The real power for this setup is if you want to be able to control a menu in code that has many external URL's or duplicate links (like logout or login) and you don't want to have to manually enter the menu items through the UI. 

This can be helpful in a multi-site setup where the menu is the same across all sites, and any changes to it you want to be able to immediately set up across all sites.

Drush makefile
==============

This draft file sketches out how we might build a drush makefile to setup all the basic parts of all our Drupal projects:

### Base installation
# Grab the most up-to-date version of Drupal

### Modules
# Add base modules

### Users
All configuration relating to users and profiles
* Configure a base group of users
* Pull a base set of user profile images and add them to the user profiles

### Content provisioning
It's tough to style and construct a site with no content in it so we should aim to get real content into the site as early as possible

* Create test content
Add devel modules
Add standard libraries
Apply standard settings and confirmations
- backup settings
- security
- theme and appearance settings
Apply fixes to known issues

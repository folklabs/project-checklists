Drush makefile
==============

This draft file sketches out how we might build a drush makefile to setup all the basic parts of all our Drupal projects:

### Base installation

* Grab the most up-to-date version of Drupal
* Set up a database with strong passwords
* Is it possible to automate getting this initial build into Git and then onto Pantheon using the terminal?

### Modules
* Add vital base modules
* Add fixes to base modules
* 

### Users
All configuration relating to users and profiles
* Configure a base group of users
* Pull a base set of user profile images and add them to the user profiles

### Content provisioning
It's tough to style and construct a site with no content in it so we should aim to get real content into the site as early as possible

### Developer tools
* Add devel modules
* Add standard libraries

### Themes
* Download base theme (Bootstrap)
* Add libraries and themer tools
* Configure base theme settings and set new theme as default

### Site configuration
* Apply standard settings and confirmations
- backup settings
- security
- theme and appearance settings
Apply fixes to known issues

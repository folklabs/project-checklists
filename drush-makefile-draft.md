Drush makefile
==============

This draft file sketches out how we might build a drush makefile to setup all the basic parts of all our Drupal projects:

#### Base installation

* Grab the most up-to-date version of Drupal
* Set up a database with strong passwords
* Is it possible to automate getting this initial build into Git and then onto Pantheon using the terminal?

#### Global modules
* Add vital base modules:
    * admin https://www.drupal.org/project/admin
    * *OR* admin_menu https://www.drupal.org/project/admin_menu *PLUS* 
    * views - https://www.drupal.org/project/views
    * rules - https://www.drupal.org/project/rules
    * token - https://www.drupal.org/project/token
    * eu_cookie_compliance - https://www.drupal.org/project/eu_cookie_compliance
    * iicture - https://www.drupal.org/project/picture
    * breakpoints - https://www.drupal.org/project/
    * insert - https://www.drupal.org/project/insert
    * module_filter - https://www.drupal.org/project/module_filter
    * google_analytics - https://www.drupal.org/project/google_analytics
    * responsive_menus - https://www.drupal.org/project/responsive_menus
    * adminimal_admin_menu - https://www.drupal.org/project/adminimal_admin_menu
    * admin_views - https://www.drupal.org/project/admin_views

#### Admin theme
    * https://www.drupal.org/project/adminimal_admin_menu

* Apply fixes to base modules

#### Users
All configuration relating to users and profiles
* Configure a base set of user types:
    * Authenticated user
    * Author
    * Editor / Community Manager
    * Administrator (as opposed to User-1)
* Create a sets of 5 users of each user type
* Upload a set of user profile images and add them to the user profiles

#### Content provisioning
It's tough to style and construct a site with no content in it so we should aim to get real content into the site as early as possible

#### Developer tools
* Add devel modules
* Add standard libraries

#### Themes
* Download base theme (Bootstrap)
* Add libraries and themer tools
* Configure base theme settings and set new theme as default

#### Site configuration
* Apply standard settings and confirmations
  * backup settings
  * & run an initial backup
  * security
  * run a cron job
* Apply fixes and patches to known issues

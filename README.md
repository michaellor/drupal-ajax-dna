#DNA Pair
####Drupal Code Review for Epicodus, 05.13.2016

###by Michael Lor

##Description

This is a module developed to fill the DNA pair of a user provided input in order to find the double helix pair. The input letter elements are limited to A,C,T,G; where A pairs with T and C pairs with G. The module employs input element validation in order to limit user input to correct inputs. The development of this portion of the project is developed with feature and unit testing using the Simpletest module.

This assignment also has a separate feature, utilizing ajax enabled views to partially load node information fields on a single page without navigating to the actual node urls.

Specific project goals include:

* Module Creation
* AJAX enabled Views
* Feature Testing
* Unit Testing

##Setup

* database: ajax_dna
* db admin: admin_ajax
* db admin pw: password
* login: admin
* pw: password

1) Clone repository to local drive.

2) Open MAMP and click on 'Open WebStart page'.

3) Click on the Tools dropdown at the top of the page and select phpMyAdmin.

4) Select the Import tab and click the Choose File button under the 'File to Import:' section to bring up the file selection window.

5) The database file for this project will be a .zip file located under the /db-backup folder in the project's root folder.

6) Once the database is uploaded, go back to MAMP and select the Preferences menu.

7) Under the Web Server tab, click on the folder icon next to 'Document Root:' and select the drupal core folder for this project.

8) Navigate to localhost:8888 in a web browser to open the project.

##Technologies Used
* Atom
* Drupal 7.43 (Feb 24 2016 Release)
* Drush
* Views
* Simpletest 
* AJAX
* phpMyAdmin
* MAMP
* Terminal

###License

Copyright (c) 2016 - This software is licensed under the MIT license

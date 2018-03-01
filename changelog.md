# Changelog
All notable changes to this project will be documented in this file.

## Rules
Team membership:  MS-Matthew Shew (Captain), JC-John Tee (teammate)
* Team conventions: Allman notation, markdown for changelog  
* Changelog Format: Read from newest to oldest


## [1.0.4] - 2018-03-01 MS
### Added
- oneitemx.php
- add item button


## [1.0.3] - 2018-03-01 JC
### Added
- Checkboxes for Maintenance page to complete jobs

## [1.0.2] - 2018-03-01 MS
### Added
- User roles (simple version)

### Edited
- autoload.php autoloads session library
- added roles to navbar

## [1.0.1] - 2018-03-01 JC
### Added
- Pagination navigation

### Edited
- Maintenance page to only show 10 items per page

[Released]
## [1.0.0] - 2018-02-15 -MS
### Edited
- ready for release

## [0.0.4] - 2018-02-15 -MS
### Added
- controller for help wanted page
- controller for maintenance page
- Parsedown.php from shared repo
- itemlist view
- oneitem view
- help wanted job listing

### Edited
- added parsedown to autoload libraries
- changed link routes
- simplified homepage.php

## [0.0.3] - 2018-02-15 -JC
### Added
- Tasks by priority and tasks by category views and controller.
- view for template_secondary.php
- view for by_category.php
- view for by_priority.php
- controller for views.php



## [0.0.2] - 2018-02-15 -MS
### Edited
- added task table to homepage view
- made my controller only use the 'pagebody' fragment if we haven't already built the content to used in a layout
- passed in task information to homepage view through Welcome controller


## [0.0.1] - 2018-02-15 -JC
### Added
- changelog document
- added application/models/tasks.php to pull from tasks.csv

### Edited
- application/config/autoload.php to autoload tasks.php

Change Log
==========

Change Log - v2.0.0 (Planned)
-------------------
## ForgeCP Frontend Views, Widgets, APIs and Libraries:
#### Views (account folder):
- [x] ts_servers.php
- [ ] backups.php
- [ ] twitter_settings.php

#### Widgets (js folder):
- [ ] widget_servers.js
- [ ] widget_backups.js

#### APIs (API folder):
##### Server APIs
- [ ] create_server.php
- [ ] delete_server.php
- [ ] load_servers.php
- [ ] update_server.php
- [ ] server_alerts.php
##### Backup APIs
- [ ] create_take.php
- [ ] delete_backup.php
- [ ] load_backup.php
- [ ] deploy_backup.php
##### Twitter APIs
- [ ] load_twitter_settings.php
- [ ] update_twitter_settings.php

Change Log - v0.2.1 (Fixes & Updates)
-------------------
#### Updates:
- Updated guzzle adapter
- Updated toin0u's digitalocean-v2
- Updated composer

#### Fixes:
- Fixed PHP error on loading Atoms due to outdated Vendor Dependencies

#### Instructions:
- Delete the vendor folder and replace with 0.2.1 vendor folder

Change Log - v0.2.0 (Atom Support Version 1 Implemented)
-------------------
## ForgeCP Frontend Views, Widgets, Forms:
#### Views (account folder):
- [x] dashboard.php - Displays Atoms
- [x] atom_details.php - Displays Atom's details
- [x] servers.php - renamed to ts_servers.php

#### Forms (forms folder):
- [x] table_atoms.php
- [x] form_atom.php

#### Widgets (js folder):
- [x] widget-atoms.js

## ForgeCP Backend API and Models:
#### API (API folder):
- [x] create_atom.php
- [x] delete_atom.php
- [x] update_atom.php

#### Models (Models folder):
- [x] languages - Updated
- [x] Vendor (Folder) - Required for do_functions.php & DigitalOceanV2 PHP
- [x] db_functions.php - Updated with Atom functions
- [x] secure_functions.php - Updated with Atom functions
- [x] do_functions.php - STILL IN DEVELOPMENT

## ForgeCP Install:
- [x] install_db.php - Support for Atoms complete out of the box!


Change Log - v0.1.1 (Implemented)
-------------------
## ForgeCP Theme Implementation
Public-pages which require ForgeCP theme:
- [x] login.php
- [x] register.php
- [x] forgot_password.php
- [x] resend_activation.php

Public-pages which DON'T require ForgeCP theme:
- [x] index.php

Private-pages which require ForgeCP theme:
- [x] To be determined later

#### Libraries (models/library folder):
- [X] ts3admin.class.php
- [X] Twitter.php
- [X] TwitterOAuth.php
- [X] OAuth.php


Change Log - v0.1.0 (Implemented)
-------------------
## ForgeCP Theme Implementation
- [x] login.php
- [x] register.php
- [x] forgot_password.php
- [x] resend_activation.php
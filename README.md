    ====================================
	  === PKP Translator Plugin
	  === Version: 2.0
	  === Author: Public Knowledge Project
	  ====================================

## About

This plugin permits translation maintenance from within the PKP application.

## License

This plugin is licensed under the GNU General Public License v2. See the file
COPYING for the complete terms of this license.

## System Requirements

This plugin is compatible with...
 - OJS 3.0 or newer
 - OMP 1.1.1 or newer

## Installation

To install the plugin:
 - Unpack the plugin tar.gz file to your `plugins/generic` directory
 - From your application's installation directory, run the upgrade script:
 ```   
 $ php tools/upgrade.php upgrade
 ```
   (NOTE: It is recommended to back up your database first.)
 - Enable the plugin by going to:
   `Management` > `Website Settings` > `Plugins` > `Generic Plugins`
   ...and selecting the Enable checkbox beside `Translator Plugin`

Note that this plugin must be able to read and write translation-related files
on the server.

## Contact/Support

Documentation, bug listings, and updates can be found on this plugin's homepage
at https://github.com/pkp/translator.

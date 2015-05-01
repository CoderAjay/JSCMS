/core - All files provided by core, that doesn't have an explicit reason to be in the / directory. More details futher down.

/libraries - 3rd party libraries, eg. a wysiwyg editor. Not included by core, but common enough to warrant inclusion here.

/modules - The directory into which all custom and contrib modules go.
Splitting this up into the sub-directories contrib and custom can make it easier to keep track of the modules. enough to warrant mention here.

/profile - contributed and custom profiles.

/themes - contributed and custom (sub)themes
sites/[domain OR default]/{modules,themes} - Site specific modules and themes can be moved into these directories to avoid them showing up on every site.
sites/[domain OR default]/files - Site specific files tend to go here. This could be files uploaded by users, such as images, but also includes the configuration, active as well as staged config. The configuration is read and written by Drupal, and should have the minimal amount of privileges required for the webserver, and the only the webserver, to read and modify them.
Details on the /core directory, primarily useful to know for new core hackers:

/core/assets - Various external libraries used by Core. jQuery, underscore, modernizer etc.

/core/misc - Frontend code that Drupal Core depends on.

/core/includes - Functionality that is to low level to be modular. Such as the module system itself.

/core/lib - Drupal Core classes.

/core/modules - Drupal Core modules.

/core/profiles - Drupal Core installation profiles. Minimal, Standard, Testing and Testing
multilingual installation profiles by default.

/core/scripts - Various CLI scripts, mostly used by developers.

/core/tests - Drupal Core tests.

/core/themes - Drupal Core themes.

/core/vendor - Backend libraries that Drupal Core depends on. (Symfony, Twig, etc)

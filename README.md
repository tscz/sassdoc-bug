# sassdoc-bug

Project to show that the verbose and strict flags are not read from the config file.

Steps to repoduce:
* If you start `npm run sassdoc:verboseworks` you can see that verbose mode is enabled because the cli parameter -v is used.
* If you start `npm run sassdoc:strictworks` you can see that strict mode is enabled because the cli parameter --strict is used.
* If you start `npm run sassdoc:doesntwork` you can see that verbose mode and strict mode are disabled even though they are enabled in the configuration in .sassdocrc.

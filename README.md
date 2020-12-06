# sassdoc-bug

Project to show that the verbose and strict flags are not read from the config file.

Steps to repoduce:
* If you start `npm run sassdoc:works` you can see that verbose mode and strict mode are enabled because the parameters -v and --strict are used.
* If you start `npm run sassdoc:doesntwork` you can see that verbose mode and strict mode are disabled even though they are enabled in the configuration in .sassdocrc.

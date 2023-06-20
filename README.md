# All In One WP Migration Fork ###

### (Edited from Version 6.77 for PHP 8.1 compatibility.) ###

This is the last version of the All In One WP Migration plugin to include import functionality functionality. Versions after this were also stripped of WP-CLI functionality. I fixed 'Return type of' deprecated warnings that showed up on PHP 8.1.

### (from Version 6.77) ###

This is the last version of the All In One WP Migration plugin to include import functionality functionality. Versions after this were also stripped of WP-CLI functionality.

The file upload size limit has been modified to be `32GB`. To change this you may define the limit in byes on line 284 in `constants.php` (if 32 Gigs doesn't float your boat). 

```php
// =================
// = Max File Size =
// =================
define( 'AI1WM_MAX_FILE_SIZE', 34359738368 );
```

If you'd like to review the changes that Servmask has made to this plugin, please refer to the SVN Repository to browse the revision history yourself [here](https://plugins.trac.wordpress.org/log/all-in-one-wp-migration).

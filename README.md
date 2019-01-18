# phpBB Extension - marttiphpbb PHP Ext Calendar

[Topic on phpbb.com](https://www.phpbb.com/community/viewtopic.php?f=456&t=)

## Description

This phpBB extension adds the dependency [fisharebest/ext-calendar](https://github.com/fisharebest/ext-calendar) which provides the PHP calendar functions written in plain PHP as a drop in when PHP on your server was not compiled with --calendar-enabled.

This could be useful when you use extensions from my [Calendar Set](https://github.com/marttiphpbb/phpbb-ext-calendarmono/blob/master/doc/calendar-set.md) as they all use PHP Calendar functions.

After install you should run `composer update` in the root of this extension. Or, alternatively, download the composer build with the vendor/ directory included from the latest [Release](https://github.com/marttiphpbb/phpbb-ext-phpextcalendar/releases)

## Requirements

* phpBB 3.2.1+
* PHP 7.1+

## Quick Install

You can install this on the latest release of phpBB 3.2 by following the steps below:

* Create `marttiphpbb/phpextcalendar` in the `ext` directory.
* Download and unpack the repository into `ext/marttiphpbb/phpextcalendar`
* Enable `PHP Ext Calendar` in the ACP at `Customise -> Manage extensions`.

## Uninstall

* Disable `PHP Ext Calendar` in the ACP at `Customise -> Extension Management -> Extensions`.
* To permanently uninstall, click `Delete Data`. Optionally delete the `/ext/marttiphpbb/phpextcalendar` directory.

## Support

* Report bugs and other issues to the [Issue Tracker](https://github.com/marttiphpbb/phpbb-ext-phpextcalendar/issues).

## License

[GPL-2.0](license.txt)

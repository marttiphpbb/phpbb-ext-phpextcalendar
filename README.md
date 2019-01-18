# phpBB Extension - marttiphpbb PHP Ext Calendar

[Topic on phpbb.com](https://www.phpbb.com/community/viewtopic.php?f=456&t=)

## Description

This phpBB extension adds the dependency [fisharebest/ext-calendar](https://github.com/fisharebest/ext-calendar) which provides the PHP calendar functions written in plain PHP as a drop in when PHP on your server was not compiled with --calendar-enabled.

This could be useful when you use extensions from my [Calendar Set] as they all use PHP Calendar functions.

## Requirements

* phpBB 3.2.1+
* PHP 7.1+

## Quick Install

You can install this on the latest release of phpBB 3.2 by following the steps below:

* Create `marttiphpbb/calendarmono` in the `ext` directory.
* Download and unpack the repository into `ext/marttiphpbb/calendarmono`
* Enable `Calendar Mono` in the ACP at `Customise -> Manage extensions`.

## Uninstall

* Disable `Calendar Mono` in the ACP at `Customise -> Extension Management -> Extensions`.
* To permanently uninstall, click `Delete Data`. Optionally delete the `/ext/marttiphpbb/calendarmono` directory.

## Support

* Report bugs and other issues to the [Issue Tracker](https://github.com/marttiphpbb/phpbb-ext-calendarmono/issues).

## License

[GPL-2.0](license.txt)

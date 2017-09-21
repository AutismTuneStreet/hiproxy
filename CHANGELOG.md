# Change Log

## [1.2.3] - 2017-09-21

### Added

* Add `requestId` for each request
* Show doc site url in `hiproxy` cmd and show new issue url in error msg

### Bugfix

* Response `data` event not emitted when use gzip

## [1.2.2] - 2017-09-18

### Added

* Change Hiproxy_Custom_CA_Certificate ext from pem to crt
* Add sub-command tips in help info

### Bugfix

* Plugins load error message has `undefined`

## [1.2.1] - 2017-09-12

### Added

* add `hiproxy init` CLI command
* Use `Hiproxy Custom CA` root certificate to issue `localhost` certificate

### Bugfix

* `send_file` directive bug

## [1.2.0] - 2017-09-04

### Added

* Regular expressions can omit the first `/` and last `/`
* Update proxy log format
* Use a more powerful syntax parser, and support main syntax error hints



## [1.1.9] - 2017-08-07

### Added

* Add built-in variable `$base_name` and `$dir_name`
* Add built-in API `enableConfFile` and `disableConfFile`

### Fixed

* Response 404 when use `alias` and the request has query string.
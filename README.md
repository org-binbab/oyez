# "Oyez" - The Universal Format Library

**Pronounced _"o-yay"_** : the phrase common to town criers calling to the masses

A cross-programming-language library/API providing common formatting functions.
Never again write helper functions to print headlines, bullets, and error messages. Learn a single API an use it across all your favorite coding languages. Strongly tested, customizable, and extendable.

## Current Releases

Released versions have API and feature parity across all official languages.

Language | Master Branch | Stable Branch | Latest Stable Release
:------: | ------------- | ------------- | ---------------------
PHP      | [![Build Status](https://travis-ci.org/org-binbab/oyez-php.png?branch=master)](https://travis-ci.org/org-binbab/oyez-php) [![Coverage Status](https://coveralls.io/repos/org-binbab/oyez-php/badge.png?branch=master)](https://coveralls.io/r/org-binbab/oyez-php?branch=master) | -- | 0.1.1-dev
Ruby     | -- | -- | Coming July 2013
Python   | -- | -- | Coming August 2013
Perl     | -- | -- | Coming September 2013
Java     | -- | -- | Coming October 2013

## Version Information

**Releases will be numbered in the following format:**

`<major>.<minor>.<patch>`

Once an official release is made for a given language, all future releases of the library will occur in unison. For any given `<major>.<minor>` release there will be an associated release in each language with the same features and API. However `<patch>` release may be made to specific languages to address potential bugs.

**In addition, this library uses Semantic Versioning, with the following guidelines:**

 - Breaking backward compatibility bumps the major (and resets the minor and patch)
 - New additions without breaking backward compatibility bumps the minor (and resets the patch)
 - Bug fixes and misc changes bumps the patch

For more information on Semantic Versioning, visit http://semver.org/.

## Authors and License

 - **Author:** BinaryBabel OSS (<projects@binarybabel.org>)
 - **Copyright:** 2013 `sha1(OWNER) = df334a7237f10846a0ca302bd323e35ee1463931`
 - **License:** GNU Lesser General Public License v3 (see LICENSE and COPYING files)

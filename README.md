# subject-identifier-attrs module

![Build Status](https://github.com/simplesamlphp/simplesamlphp-module-subjectidattrs/workflows/CI/badge.svg?branch=master)
[![Coverage Status](https://codecov.io/gh/simplesamlphp/simplesamlphp-module-subjectidattrs/branch/master/graph/badge.svg)](https://codecov.io/gh/simplesamlphp/simplesamlphp-module-subjectidattrs)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/simplesamlphp/simplesamlphp-module-subjectidattrs/badges/quality-score.png?branch=master)](https://scrutinizer-ci.com/g/simplesamlphp/simplesamlphp-module-subjectidattrs/?branch=master)
[![Type Coverage](https://shepherd.dev/github/simplesamlphp/simplesamlphp-module-subjectidattrs/coverage.svg)](https://shepherd.dev/github/simplesamlphp/simplesamlphp-module-subjectidattrs)
[![Psalm Level](https://shepherd.dev/github/simplesamlphp/simplesamlphp-module-subjectidattrs/level.svg)](https://shepherd.dev/github/simplesamlphp/simplesamlphp-module-subjectidattrs)

This module provides authproc-filters for releasing the attributes defined
in the [SAML V2.0 Subject Identifier Attributes Profile][specification].

## Installation

Once you have installed SimpleSAMLphp, installing this module is very simple.
Just execute the following command in the root of your SimpleSAMLphp
installation:

```bash
composer.phar require simplesamlphp/simplesamlphp-module-subjectidattrs:dev-master
```

where `dev-master` instructs Composer to install the `master` branch from the
Git repository. See the [releases][releases]
available if you want to use a stable version of the module.

Next thing you need to do is to enable the module: in `config.php`,
search for the `module.enable` key and set `subjectidattrs` to true:

```php
    'module.enable' => [
         'subjectidattrs' => true,
         …
    ],
```

[specification]: https://docs.oasis-open.org/security/saml-subject-id-attr/v1.0/saml-subject-id-attr-v1.0.pdf
[releases]: https://github.com/simplesamlphp/simplesamlphp-module-subjectidattrs/releases

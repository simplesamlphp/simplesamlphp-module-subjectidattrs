![Build Status](https://github.com/simplesamlphp/simplesamlphp-module-subjectidattrs/workflows/CI/badge.svg?branch=master)
[![Coverage Status](https://codecov.io/gh/simplesamlphp/simplesamlphp-module-subjectidattrs/branch/master/graph/badge.svg)](https://codecov.io/gh/simplesamlphp/simplesamlphp-module-subjectidattrs)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/simplesamlphp/simplesamlphp-module-subjectidattrs/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/simplesamlphp/simplesamlphp-module-subjectidattrs/?branch=master)

subject-identifier-attrs module
===============================

This module provides authproc-filters for releasing the attributes defined in the SAML V2.0 Subject Identifier Attributes Profile.
See https://docs.oasis-open.org/security/saml-subject-id-attr/v1.0/saml-subject-id-attr-v1.0.pdf

Installation
------------

Once you have installed SimpleSAMLphp, installing this module is very simple. Just execute the following
command in the root of your SimpleSAMLphp installation:

```
composer.phar require simplesamlphp/simplesamlphp-module-subjectidattrs:dev-master
```

where `dev-master` instructs Composer to install the `master` branch from the Git repository. See the
[releases](https://github.com/simplesamlphp/simplesamlphp-module-subjectidattrs/releases) available if you
want to use a stable version of the module.

This module is disabled by default. To enable it, configure it in the SimpleSAMLphp config.php under `module.enable`

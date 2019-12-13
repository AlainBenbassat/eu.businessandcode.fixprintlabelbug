# eu.businessandcode.fixprintlabelbug

Fixes a bug when printing mailing labels.

* See issue: https://lab.civicrm.org/dev/core/issues/1158
* See Pull Request: https://github.com/civicrm/civicrm-core/pull/14928

This extension implements the change using a code override.
So it can be enabled/disabled simply by enabling/disabling this extension.

The overridden file is CRM/Contact/Form/Task/Label.php




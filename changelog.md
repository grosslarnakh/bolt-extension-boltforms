# Changelog for Bolt Forms

* 2.0.3 (2015-02-21)

 * Fix: Correct match of 'submit' field (@rixbeck)
 * Allow additional fields to be added in PRE_SET_DATA handler (@rixbeck)

* 2.0.2 (2015-02-16)

 * Show a message if the form requested in {{ boltforms() }} is not found in the configuration
 * JSON encode arrays on database writes
 * Added the ability to use Contentype records for choice field value/labels

* 2.0.1 (2015-01-18)

 * Allow BoltForms to be Twig safe and used in HTML record fields (@bobdenotter)

* 2.0.0 (2014-12-17)

 * Initial release for Bolt 2.0.0

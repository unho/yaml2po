yaml2po
=======

Script for converting .yml or .yaml translation files to Gettext PO or POT

Developed from the homonymous script from http://git.openstreetmap.org/rails.git/tree/HEAD:/script/locale


Usage mode
----------

* Create a 'master' .pot file from source english translation
    yaml2po > translations.pot

* Create a language's .po from specified existing translation
    yaml2po de > de.po

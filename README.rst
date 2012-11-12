yaml2po
=======

Script for converting .yml or .yaml translation files to Gettext PO or POT

Developed from the homonymous script found in http://git.openstreetmap.org/rails.git/tree/HEAD:/script/locale


Usage mode
----------

* Create a 'master' .pot file from source english translation
    yaml2po -P en.yml > translations.pot
    
    -P option indicates the template YAML file (the english translation one)

* Create a language's .po from specified existing translation
    yaml2po -l de -t en.yml de.yml > de.po
    
    -l option indicates the language code in the YAML translation file
    
    -t option indicates the template YAML file (the english translation one)

License
-------

This software is licensed under the GNU General Public License 2.0 (http://www.gnu.org/licenses/old-licenses/gpl-2.0.txt), a copy of which can be found in the LICENSE file.



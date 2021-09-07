# LinkStitcher AGLDWG Drupal installer #

This repository contains an installer script for AGLDWG-flavoured
instances of LinkStitcher.

To use the script, you'll need:

  * bash
  * PHP 7.4
  * composer 2

Prepare an INI file based on the contents of the sample provided.
Let's say this is `my-drupal.ini`.

To run the installer:

```
./lst-agldwg-drupal-installer.sh -e my-drupal.ini
```

# sWADAH 2022 requires:

PHP 7.4-8.0 (not tested >PHP 8.1)

Current Version: 2022Y R6

End of support: 1 December 2025


## Installation

**Installation on Linux:**
https://ezpustaka.upsi.edu.my/i/wp-content/uploads/2022/08/Installing\_sWADAH\_docversion\_20220815.pdf

**Installation XAMPP for Windows (development only):**
https://ezpustaka.upsi.edu.my/i/wp-content/uploads/2023/07/Installing-sWADAH-for-XAMPP.pdf

**Upgrading:**
https://ezpustaka.upsi.edu.my/i/wp-content/uploads/2022/08/Updating\_sWADAH\_docversion\_20220815.pdf

## Configuration File

**Understanding config.default.php**
config.default.php is the default configuration file for sWADAH. Please do not alter any of the default values. Make a copy of it and rename it to config.user.php (see section below this)
As of sWADAH 2021X and all future version, config.default.php contains comprehensive instructions and documentations on how each settings works.

**Understanding config.user.php**
You may create config.user.php that will exist alongside with config.default.php.
You may assign your own values (all attributes and initial values can be refer back in config.default.php) so that when you are upgrading sWADAH, your configuration will remain. If you do not have this file, you have to start over. So the existence of config.user.php is to facilitate easy upgrading if ever config.default.php will change in the future releases. All values assigned in config.user.php will overwrite the one in config.default.php

**Integration with EZproxy**
Tutorial: https://ezpustaka.upsi.edu.my/i/wp-content/uploads/2024/06/sWADAH-%E2%80%93-Ezproxy-Standalone-Integration-Tutorial.pdf


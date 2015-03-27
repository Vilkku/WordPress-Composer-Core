# WordPress Composer Core
This is a [Composer](https://getcomposer.org/) project mainly intended for personal use. It serves as the initial package when creating new projects based on WordPress.

## Getting started

### Install Composer
    curl -sS https://getcomposer.org/installer | php

### Install Project
    php composer.phar install

### Configure WordPress
Copy public/wp-config-sample.php to public/wp-config.php, open the file and modify as required.

### Install WordPress
Navigate to public/ and follow the instructions.

### Modify .gitignore
Themes and plugins that you want to be handled by Git need to be explicitly un-ignored in .gitignore. For example:

    !public/wp-content/themes/name/

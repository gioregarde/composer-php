# composer
Basic instructions on how to install and use Composer Dependency Manager.
## installation
1. Download composer.phar [here](https://github.com/composer/composer/releases) and place it in ../build/composer.phar
2. Copy, rename and change permission. Check if file is executable.
```bash
    $ cd build/
    $ cp composer.phar composer
    $ chmod 755 composer
    $ ./composer
```
3. Install to a php project.
```bash
    $ cd <project_location>
    $ <composer_path>/./composer install
```
## Reference
* https://github.com/composer/composer
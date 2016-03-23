# Requirement
- php >= 5.6

# Installation
1. Download and Install PHP Composer.
    ```sh
    curl -sS https://getcomposer.org/installer | php
    ```

2. Next, run the Composer command to install the latest version.
    ```shell
    php composer.phar require sri-labs/gzone
    ```

    or add the following to your composer.json file.
    ```json
    {
        "require": {
            "sri-labs/gzone": "dev-master"
        }
    }
    ```

3. Then run Composer's install or update commands to complete installation.
    ```sh
    php composer.phar install
    ```

4. After installing, you need to require Composer's autoloader:

	```php
	require 'vendor/autoload.php';
	```

# Configuration


# Usage

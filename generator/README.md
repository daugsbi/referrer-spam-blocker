referrer-spam-blocker [![Build Status](https://travis-ci.org/Stevie-Ray/referrer-spam-blocker.svg)](https://travis-ci.org/Stevie-Ray/referrer-spam-blocker)
====================================

## Install

First, create a fork of the repository and copy the files to your local machine.

```sh
git clone https://github.com/yourname/referrer-spam-blocker.git
```

Install the [composer](https://getcomposer.org/) dependencies.

Tip: run these commands to globally install `composer` on your system:

```sh
curl -sS https://getcomposer.org/installer | php
mv composer.phar /usr/local/bin/composer
```

Use the `composer` install command in the `generator` folder:

```sh
cd generator
composer install
```


## Usage

In your CLI (or webbrowser) run the **generator/run.php** file to generate the files.
This can be done using a local server like [MAMP](https://www.mamp.info/en/) or on a remote server.

```sh
php generator/run.php
```

The new domains are now included in your local files. Commit and push your work to your repository and create a [pull request](https://github.com/Stevie-Ray/referrer-spam-blocker/pulls/).


## Contributing
 
If you'd like to add a new referrer spammer to the list, [click here to edit the domains.txt file](https://github.com/Stevie-Ray/referrer-spam-blocker/edit/master/generator/domains.txt) and create a pull request. Alternatively you can create a [new issue](https://github.com/Stevie-Ray/apache-nginx-referral-spam-blacklist/issues/new). In your issue or pull request please explain where the referrer domain appeared and why you think it is a spammer. **Please open one pull request per new domain**.
 
If you open a pull request, it is appreciated if you run the **generator/run.php** file. It sorts the domains, creates the files and checks if somebody already reported the domain.


## Like it?

- [Buy me a beer](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=4XC7KX75K6636) 🍺



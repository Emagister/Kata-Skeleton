# Kata Skeleton #

This is a kata skeleton. In order to setup properly a new kata follow the steps below

1. Download the last stable tag.

2. Configure your library dependencies in the ```composer.json``` located at the root of the kata. At the moment there is only one needed
   dependency, the Symfony class-loader.

3. Download composer

    ```$ wget http://getcomposer.org/composer.phar```

4. Install your dependencies

    ```$ php composer.phar install```

5. Rename the files ```test/bootstrap.php.dist``` to ```test/bootstrap.php``` and configure the required
   namespaces in order that your test could find the needed classes. If there are so many dependencies,
   maybe it will be useful to use the autoloader instead, provided by Composer and located at
   ```vendor/.composer/autoload.php``` (after installing all the packages).

6. Rename the file ```test/phpunit.xml.dist``` to ```test/phpunit.xml```.
7. You will find a standard test skeleton on ```test/README.md```
8. Start writting tests and implementing theme as usual, following the same directory/namespace structure
   that you will use for organize your source code.
9. If want to run your tests suites, execute

    ```$ phpunit -c test/```

If want to commit throught github, rename ```gitignore.dist``` to ```.gitignore``` and build your repo!

That's all! Have fun coding!
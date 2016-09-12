Blog50 - example

This is a simple Laravel app for a blog website to demonstrate key features of this web framework

Companion slides: https://www.dropbox.com/s/nmi8sryhnl8voqo/eouyang_cs50_laravel-seminar_slides.pdf?dl=0

It is recommended that you run this example on the CS50 Appliance
Setup

    Install composer (for dependency management)

curl -sS https://getcomposer.org/installer | php

sudo mv composer.phar /usr/local/bin/composer

    Download the repository.

Distribution code: git clone https://github.com/ericouyang/blog50.git

Completed example: git clone -b completed https://github.com/ericouyang/blog50.git

    Navigate into the new blog50 folder and install dependencies

composer install

    If you're running the completed example, you need to create the database called blog50 and then run

php artisan migrate

    Run the server using

php artisan serve

    Go to this in your browser

http://localhost:8000

## Photo-Upload

A Laravel-Boilerplate for the Technopathic Full-Stack Web Development series was used in the creation of this site.

This Photo-Upload is created for Back-End storage and retrieval of photos to a database.

## Getting Started
To reuse this code as a framework, fork this repo and clone it onto your local computer. Then run `composer install` to install all of the necessary libraries.
```
git clone https://github.com/CJacobson1986/Photo-Upload-BackEnd.git
cd Photo-Upload-BackEnd
composer install
```

Next you should generate a new Migration for your photos table `php artisan make:migration photos`.  Then you will generate a Model for your photos table `php artisan make:model Photo`. From there you should go ahead and generate a Controller `php artisan make:controller PhotosController`.  Then you will migrate the photos database table `php artisan migrate`. Next, you should change the .env.example file name to .env.

To start the server, simply do `php artisan serve`.


## Commands
To generate Controllers:
`php artisan make:controller Controller`

To migrate:
`php artisan migrate`

## Screenshot
![alt text](http://h4z.it/Image/f9d482_d-Screenshot.PNG "Php MyAdmin")
![alt text](http://h4z.it/Image/f8df7e_-Screenshot2.PNG "Postman")


## Author
Christopher Jacobson

## Thanks
Special thanks to Technopathic for his Laravel-Boilerplate and the original build scripts.

## License
MIT

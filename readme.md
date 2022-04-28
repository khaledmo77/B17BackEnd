
- Register
- Login
- Follow / Unfollow user
- Add new post
- Change profile picture
- View Single posts
- Upload Image
_______________________________
Create a database locally named B-17 utf8_general_ci
Download composer https://getcomposer.org/download/
Rename .env.example file to .envinside your project root and fill the database information. (windows wont let you do it, so you have to open your console cd your project root directory and run mv .env.example .env )
Open the console and cd your project root directory
Run composer install or php composer.phar install
Run php artisan key:generate
Run php artisan migrate
Run php artisan db:seed to run seeders, if any.
Run php artisan serve



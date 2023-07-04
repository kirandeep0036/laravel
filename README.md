# Laravel Admin Dashboard

[![PHP Version Require](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) 
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)

## 💻 About Project
I created <a href="https://laravel.com/docs/8.x/releases">Laravel 8</a> admin dashboard project from scratch. If you are a beginner and want to learn Laravel project from scratch, this is good sample project for you. Apart from that I used <a href="https://getbootstrap.com/">BootStrap 5 </a> for responsive view. I tried to cover below mentioned topic to of <a href="https://laravel.com/docs/8.x/releases">Laravel 8</a>:

### 💡 As you know <a href="https://laravel.com/docs/8.x/releases">Laravel 8</a> have a php MVC framework so I tried to cover mvc structure with login and register user modules. You will learn about:
▶ Laravel Routing with middleware and parameters

▶ Laravel page layout

▶ Laravel sub view page and call them

▶ How to extend layout and and pass paramters to layout

▶ How to call view blades and pass data to view blade 

▶ How to use php code in blade files

▶ How to redirect to route with paramters

▶ How to send the reponse message 

▶ How to set validations

▶ How to create middleware and use it

▶ How to handle error messages on blade files

▶ How to use admin login and normal user login



# ⭐ How to clone and setup Laravel project from GitHub

### ⪢ Step 1
Firstly, You have to copy the Github repository URL:
https://github.com/Kirandeep0036/laravel.git
It's a public repo, you don't need any credentials to download the project
screenshot(https://tinyurl.com/2d25da7o)

### ⪢ Step 2
Next is, open the project into your local editior then open the .env file and put you databse details:
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=
DB_USERNAME=
DB_PASSWORD=

### ⪢ Step 3
Then open your project editior terminal and the run command npm <b>npm install</b> and wait to complete it.

### ⪢ Step 4
Once you have done with your my sql details the run <b>php artisan migrate</b> command in your terminal. Its will create users table into your database. Then run command <b>php artisan serve</b> to run the project. Laravel local server URL:
http://localhost:8000/

<b>NOTE</b> You have to set role admin in database in users table that guest by default for each record. After that, Please use that this user to login into dashboard.

# ⭐ Some other useful commands of Laravel:
✅ To clear the cache: <b>php artisan optimize</b>

✅ Make new controller:<b> php artisan make:controller name_of_controller</b>

✅ Make new middleware: <b>php artisan make:middleware name_of_middleware</b>

✅ Make new model: <b>php artisan make:model name_of_model</b>

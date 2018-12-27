Hey, This is my own written php mvc based framework for you guys mean its totally free you can create your web app with it in mvc pattern !<br>


===========REQUIREMENTS==================<br>

PHP:           v7.0+<br>
MYSQL:         4.7.0.1+<br>
Web Server:    Apache/2.4.33<br>
PHP version:   7.2.5<br>
Apache Server: I used Xampp, You can use MAMP/WAMP etc<br>
<br>
==========What you have to change ? ============<br>
  <br>
  -----For Rewrite Access file------<br>
  You have to change few things first of all, Go to .htaccess file of Framework root folder->public, Change the line of code called:     RewriteBase /mbmvc/public which is code no# 4 of that file, change /mbmvc/public with your project name mean for example you have project folder with name of myproject then change mbmvc with myproject, I hope this make since, 
  
  <br>
  ------ For Database File----<br>
  You will see folder with name of app inside mbmvc of framework root, Then got to this folder called app/config/config.php there you will see database config code change following credentials with your credentials : <br>
  // DB Params<br>
define('DB_HOST', 'localhost');<br>
define('DB_USER', '_YOUR_USER_');<br>
define('DB_PASS', '_YOUR_PASS_');<br>
define('DB_NAME', '_YOUR_DBNAME_'); <br>   

 // App Root<br>
 define('APPROOT', dirname(dirname(__FILE__)));<br>

 // Url Root<br>
 define('URLROOT', '_YOUR_WEB_URL_');<br>

 //Site Name<br>
 define('SITENAME', '_YOUR_SITE_NAME_');<br>
 <br>
 <br>
 <br>
Thats all according to me for you to start with your project, If you still face any problem feel free to get in touch with me or create problem in comment section I will be happy to assist you !<br>

Thanks for reading<br>
Moiz



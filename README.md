Hey, This is my own written php mvc based framework for you guys mean its totally free you can create your web app with it in mvc pattern !


===========REQUIREMENTS==================

PHP:           v7.0+<br>
MYSQL:         4.7.0.1+
Web Server:    Apache/2.4.33
PHP version:   7.2.5
Apache Server: I used Xampp, You can use MAMP/WAMP etc

==========What you have to change ? ============
  
  -----For Rewrite Access file------
  You have to change few things first of all, Go to .htaccess file of Framework root folder->public, Change the line of code called:     RewriteBase /mbmvc/public which is code no# 4 of that file, change /mbmvc/public with your project name mean for example you have project folder with name of myproject then change mbmvc with myproject, I hope this make since, 
  
  
  ------ For Database File----
  You will see folder with name of app inside mbmvc of framework root, Then got to this folder called app/config/config.php there you will see database config code change following credentials with your credentials : 
  // DB Params
define('DB_HOST', 'localhost');
define('DB_USER', '_YOUR_USER_');
define('DB_PASS', '_YOUR_PASS_');
define('DB_NAME', '_YOUR_DBNAME_');    

 // App Root
 define('APPROOT', dirname(dirname(__FILE__)));

 // Url Root
 define('URLROOT', '_YOUR_WEB_URL_');

 //Site Name
 define('SITENAME', '_YOUR_SITE_NAME_');
 
 
 
Thats all according to me for you to start with your project, If you still face any problem feel free to get in touch with me or create problem in comment section I will be happy to assist you !

Thanks for reading
Moiz 



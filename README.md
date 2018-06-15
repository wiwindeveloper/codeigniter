# codeigniter
CRUD CI with JSON

# Instalation
1. Copy this file to localhost
2. Open the application - controller directory, then open the config.php. On the line $config['base_url'] = 'http://localhost/ajax_crud/'; change according to the name of your folder on localhost.
3. Still in the same directory as the number 2, open the file database.php then find the line below:

$db['default'] = array(
	'dsn'	=> '',
	'hostname' => 'localhost',
	'username' => 'root',
	'password' => '',
	'database' => 'crud',
	'dbdriver' => 'mysqli',
	'dbprefix' => '',
	'pconnect' => FALSE,
	'db_debug' => (ENVIRONMENT !== 'production'),
	'cache_on' => FALSE,
	'cachedir' => '',
	'char_set' => 'utf8',
	'dbcollat' => 'utf8_general_ci',
	'swap_pre' => '',
	'encrypt' => FALSE,
	'compress' => FALSE,
	'stricton' => FALSE,
	'failover' => array(),
	'save_queries' => TRUE
);


Change according to your hostname, username, password, and database name. If needed, you can rename the db driver as well.

4. Don't forget to change the route on route.php file, find line $route['default_controller'].

# Database
Move the ci_crud.sql file to your server database, here I am using MySQL.

# MVC
Here i am using MVC programming. so you can find the program files in the model, controller and view folder in the application directory.

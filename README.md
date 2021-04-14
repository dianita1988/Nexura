# Nexura
En el nuevo proyecto esta la base de datos final. esa la exportas al mysql, el proyecto esta construido en el framework llamado codeigniter  version 3.1.11 la version del php que lo desarrolle es la 7.2. para poder usar el aplicativo se debe descomprimir en la carpeta del servidor en mi caso yo uso el xammp y el proyecto  lo dejo en la carpeta htdocs.
una vez cargada la bd en mysql y el proyecto en el servidor.
Luego procedemos a ajustar unas cosas del proyecto para que pueda funcionar correctamente, vamos a configurar el archivo de la DB; colocamos los cambios necesarios por ejemplo si el xampp tiene un usuario o contraseña diferente al que esta en el proyecto se deberá de modificar. 
El archivo esta en la siguiente ruta: application/config/database.php  
Para finalizar hay que modificar el archivo que ejecuta la ruta del proyecto, es la siguiente Ruta:  application/config/config.php     
Estando en el archivo config.php modificamos lo siguiente  $config['base_url'] = 'aqui va la ruta de nuestro servidor local + el nombre del proyecto'  
por ejemplo :  $config['base_url'] = 'http://localhost/Empleados/';
Con estos cambios el programa debe funcionar correctamente. 

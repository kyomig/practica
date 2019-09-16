# PARTE 1: PROCESO DE INSTALACIÓN Y DISTRIBUCIÓN DE UNA APLICACIÓN WEB

creación de nuevo virtual-host "practica.aplicaciones.web" desde la consola con git clone para desplegar la aplicación de aplicaciones web en practica.
se añade en la linea del ip del host el dominio "practica.aplicaciones.web"
se comprueba el funcionamiento del ip y dominio ejecutando en la consola, desde el backend, un ping al dominio.
se comprueba la carga del dominio desde el navegador.


# PARTE 2: MÉTODOS PARA VERIFICAR LAS FUNCIONALIDADES

Musa-front: el archivo index.php de Musa, contiene un exit en la línea 10 por lo que no se podrá hacer la petición.

walaa-routing: El código de Walla no funciona ya que en index.php tiene un exit en la linea 4. No se llegará a ningun archivo diferente a index.php.

Alex_RoutingInterface: responde un fatal error, ya que no llama a las rutas ni a los controladores correspondientes, tampoco se encuentra el string ni array de rutas.

Jordi-HTML_Response: 

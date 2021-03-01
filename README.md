#  ----comandos de consola mysql----
[![logo mysql](https://download.logo.wine/logo/MySQL/MySQL-Logo.wine.png "logo mysql")](https://download.logo.wine/logo/MySQL/MySQL-Logo.wine.png "logo mysql")

- $mysql -u usuario -p =se usa para acceder a la consola

- mysql -u root = se suele usar para acceder a la consola cuando se usan paquetes como xamp.

- create database nombreDeBdd; = se usa para crear la bases de datos por ejemplo create databases hospital.

- use baseDD; = se usa para seleccionar una base de datos especificas por ejemplo use hospital;

- create table nombreTabla (seccion tipoDeDato(max de caracteres) opcion de relleno, primary key(seccion) ) type = tipo; = se usa para crear las tablas con sus secciones por ejemplo create table medicos ( nombre varchar(30) not null, edad INT , primary key (nombre)) type = innodb;

- show databases; = se usa para ver las bases de datos creadas.

- describe nombreDeTabla; = se usa para comprobar que la tabla fue creada como queriamos por ejemplo describe medicos.

- insert into nombreRegistro values ("jose cordoba" , 22); = este comando es para insertar nuevos registros en la base de datos.

- select (asterisco) from nombreTabla; = este comando se usa para verificar que los datos introducidos fueron creados de forma correcta por ejemplo select (asterisco) from medicos.
-  rename table nombreTabla to nuevoNombre; = se usa para renombrar tablas por ejemplo rename table farmacia to medicos;

- alter table nombreTabla change nombreCampo nuevoCampo datos; = se usa para cambiar nombres de campos por ejemplo alter empresa change empleado aprendiz varchar etc ;

- constraint fk_nombreLlaveforanea foreign key (nombreForeignKey) references nombreTabla1 (nombreFKtabla1) = se usa para agregar llaves foraneas y relacion entre dos tablas por ejemplo constraint fk_datos2 foreign key (clave) references datos1 (clave) esto se puede al momento de crear la tabla o agregarlo despues recuerda que los nombres de las llaves foraneas y primaria deben ser los mismos y los mismos datos y cantidad de caracteres. 

- alter table NombreTabla = se usa para alterar tablas agregando con add y borrando con drop y renombrando con rename y cambiar con changes.



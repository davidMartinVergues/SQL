# Curso SQL

## Comandos útiles

1. ```sql
   mysql -u NombreUsuario -p
   -- para loguearme en mysql
   ```
2. ```sql
   SHOW DATABASES;
   ```
3. ```sql
   SELECT * FROM mysql.user;
   -- nos da todos los usuarios en mysql
   ```
4. ```sql
   SELECT USER();
   -- Me muestra el usuario con el que estoy logueado en `mysql`
   ```
5. ```sql
   SELECT DATABASE();
   -- Me muestra con qué bbdd estoy trabajando
   ```
6. ```sql
   SHOW VARIABLES WHERE Variable_name = 'port';
   SHOW GLOBAL VARIABLES LIKE 'PORT'
   -- muestra el puerto en el que trabaja mysql
   ```
7. ```sql
   SHOW VARIABLES WHERE Variable_name = 'hostname';
   -- nombre del opdenador con el q estás conectado a mysql (pej david-pc)
   ```
8. ```sql
   CREATE DATABASE miprueba;
   -- crear un nuevo schema o base de datos
   ```
9. ```sql
   use miprueba;
   -- para usar una bbdd concreta
   ```
10. ```sql
    CREATE TABLE prueba (id_prueba int)
    --crear nueva tabla
11. ```sql
    SHOW tables;
    -- mostrar las tablas
    ```
12. ```sql
    describe prueba;
    -- obtener info de una tabla concreta
    ```
13. ```sql
    SELECT * from `node-app`.products;
    -- hacer una consulta especificando la bbdd o schema + tabla con notación de punto, la bbdd va entre tildes  ` ` 
    ```
13. ```sql
    use `node-app`;
      -- para fijar antes del script de SQL q usaremos la bbdd `node-app` tb entre ``
    ```

# CrudNet
Base de Datos Sql Server: clase conexion dentro de appsettings.json  (DefaultConnection) base de datos local

Dependencias utilizadas:
-Microsoft.AspNetCore.Mvc.Razor.RuntimeCompilation 5.0.17
-Microsoft.EntityFrameworkCore.SqlServer 5.0.0
-Microsoft.EntityFrameworkCore.Tools 5.0.0
-Microsoft.VisualStudio.Web.CodeGeneration.Design 5.0.2
-Swashbuckle.AspNetCore 5.0.0

Iniciar App:
La app es code first, se genera en la base de datos de acuerdo a el modelo, utilizando para ello la migracion 'add-migration nombreMigracion' 
y la actualizacion de la base de datos como tal 'update-database' utilizando la conexion 'DefaultConnection' para generar la bd y la tabla

Otros:
Se instalo materialize para el front su CDN e instalando con el comando de npm install materialize-css@next,
tambien se agregaron los iconos utilizando su CDN especifico para iconos 

Validacion al Insertar:
Se agrego la validacion para que al registrar no permita dejar campos vacios, evitar duplicados de Nro de Documento, y no utilizar una Fecha de Nacimiento Invalida

El ejercicio consistia en 
-Listar: https://localhost:44320/Persona
-Insertar: https://localhost:44320/Persona/Create
-Editar: https://localhost:44320/Persona/Edit/id
-Eliminar: https://localhost:44320/Persona/Delete/id
-Validacion de duplicados
-utilizando postman con la funciones GET como https://localhost:44320/Persona retorna un HTML cargado con la Lista de Personas Registradas




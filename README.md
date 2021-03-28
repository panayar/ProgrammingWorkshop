# ProgrammingWorkshop✨
![cropped-descarga](https://user-images.githubusercontent.com/71273441/112771551-fc6fae80-8ff1-11eb-9307-3c9515f6cbbd.png)

> Status : in process 

## Preguntas 
1. ¿Se puede eliminar una mascota (se muere)? no
2. ¿Se crea una cuenta para los diferentes roles, Y cómo sabríamos cual es su rol (Preguntar en formulario)?
3. ¿Veterinario para registrar también con CC y se puede identificar en un futuro?(Si)
4. ¿Esta información es pública y un usuario promedio puede verla (Solo funcionario)?
5. ¿Veterinario tendría acceso a los que registre  o a todos? (A los q registre)
6. ¿Agente solo chat?(si)
7. ¿Funcionario puede ver los chats?(no)

## Usuarios soportados 

### 5 tipos de usuarios:
- Propietario (Dueño de la mascota) 
- Veterinario (Persona encargada del bienestar de las mascotas)
- Funcionario de la alcaldía (Adquiere la info de las mascotas) 
- Agente (Comunicación con chat de dudas, comentarios,etc.)
- Usuario Anonimo (Persona del común que accede a la página)
- Desarrollador
- Administrador


## Requisitos Funcionalidades 👾

| RQF 001 | Requisito funcional  |
| --- | --- |
|  Nombre  | Validar Ingreso al Sistema |
| Descripción | El sistema controlará el acceso a este, permitiendo solo a usuarios autorizados acceder a la información dependiendo del rol asignado. |
| Usuarios |  Propietarios, Veterinario, Funcionario, Agente |


| RQF 002 | Requisito funcional  |
| --- | --- |
|  Nombre  | Gestionar Usuarios|
| Descripción | Creación de usuarios y contraseñas ¿? |
| Usuarios |  Administrador |


| RQF 003 | Requisito funcional | 
| --- | --- |
| Nombre | Añadir Mascota |
| Descripción | El sistema permitirá la creación de una nueva mascota con los datos requeridos|
|Usuarios |  Propietario,veterinario|

| RQF 004 | Requisito funcional | 
| --- | --- |
| Nombre | Chat con Agente|
| Descripción | El sistema creará un chat de forma bidireccional entre un agente y un usuario que tenga dudas, comentarios, etc.|
| Usuarios | Usuario, Agente, propietario|

 
|RQF 005 | Requisito funcional |
| --- | --- |
|Nombre | Chat con BOT|
|Descripción | El sistema creará un chat donde el usuario podrá reportar un caso donde sea por robo, si es peligroso, etc.|
|Usuarios | Usuario, propietario |



|RQF 006 | Requisito funcional |
| --- | --- |
|Nombre | Ver historial de chat |
|Descripción | El sistema permitirá ver la el historial del chat donde se muestran los mensajes de los ciudadanos |
|Usuarios | Funcionario|


|RQF 007 |Requisito funcional|
| --- | --- |
|Nombre | Buscar por filtros |
|Descripción| El sistema permitirá buscar la información mediante filtros como lo son raza, especie, microchip,etc.| 
|Usuarios | Funcionario|



|RQF 008|Requisito funcional|
| --- | --- |
|Nombre | Localización por mapa|
|Descripción| El sistema permitirá agregar o editar un animal con la ubicación de forma manual o seleccionando la ubicación en el mapa.|
|Usuarios | Usuario, veterinario ||


 
|RQF 009 | Requisito funcional |
| --- | --- |
|Nombre | Mostrar info Mascota|
|Descripción| El sistema permitirá mostrar la información de los animales |
|Usuarios | funcionario |


 
|RQF 010 | Requisito funcional |
| --- | --- |
|Nombre | Localización por mapa|
|Descripción| El sistema permitirá ingresar la ubicación de forma manual o seleccionando la ubicación en el mapa.|
|Usuarios | Usuario, veterinario |



|RQF 011| Requisito funcional |
| --- | --- |
|Nombre | Guardar los casos en archivo csv|
|Descripción| el sistema permitirá una vez terminado la explicación del caso por el usuario guardarlo en un archivo csv con la fecha de creación.|
|Usuarios | Desarrollador |



|RQF 012 | Requisito funcional |
| --- | --- |
|Nombre | Gestión seguridad de datos|
|Descripción| Permisos para acceder al sistema podrán ser cambiados únicamente por el administrador con acceso a la base de datos.|
|Usuarios | Administador| 


## Requisitos funcionales técnicos 👾


|RQFT001 | Requisito funcional técnico | 
| --- | --- |
|Nombre | Validación de Datos|
|Descripción | El sistema validará acceso a los datos de acuerdo con el rol de usuario autorizado |
|Usuarios | Desarrollador|



|RQFT002| Requisito funcional técnico | 
| --- | --- |
|Nombre | Diseño Login Propietario|
|Descripción | La página llevará impreso el logo del programa junto al logo de la universidad acompañado con los colores seleccionados donde pedirá su usuario y contraseña |correspondiente.|
|Usuarios | Desarrollador| 



|RQFT003 |Requisito funcional técnico | 
| --- | --- |
|Nombre | Diseño Login Veterinario| 
|Descripción | La página llevará impreso el logo del programa junto al logo de la universidad acompañado con los colores seleccionados (Pendiente esta parte)|
|Usuarios | Desarrollador| 



|RQFT004 | Requisito funcional técnico | 
| --- | --- |
|Nombre | Diseño Login Funcionario| 
|Descripción | La página llevará impreso el logo del programa junto al logo de la universidad acompañado de los colores seleccionados con el campo de la cedula para que el |funcionario la ingrese|
|Usuarios | Desarrollador| 



|RQFT005| Requisito funcional técnico |
| --- | --- |
|Nombre | Actualización de Datos|
|Descripción | El sistema permitirá actualización únicamente al administrador usuarios y contraseña para acceder al sistema.|
|Usuarios | Desarrollador| 


 
|RQFT006| Requisito funcional técnico |
| --- | --- |
|Nombre | Validacion de campos |
|Descripción | Al momento de registrarse los campos de de nombre y apellido acepta solo caracteres alfabéticos |
|Usuarios | Desarrollador |



|RQFT007| Requisito funcional técnico | 
| --- | --- |
|Nombre | Fecha y hora |
|Descripción | El campo de fecha y hora no se podrá editar o modificar por ningún motivo, esta es cargada por el sistema de manera automática y de acuerdo a la hora que está en el equipo|
|Usuarios | Desarrollador| 



### Diagramas Caso de uso 
https://lucid.app/lucidchart/61f2197f-83ea-4126-8dfe-26ceffd03eed/edit?shared=true&page=0_0#
### Diagramas de clases 
https://lucid.app/lucidchart/61f2197f-83ea-4126-8dfe-26ceffd03eed/edit?shared=true&page=omDnnrJVxypD#
### Digaramas de secuencia 
https://lucid.app/lucidchart/61f2197f-83ea-4126-8dfe-26ceffd03eed/edit?shared=true&page=irdoBUmjBE3D#
### Diagrama de componentes 
https://lucid.app/lucidchart/61f2197f-83ea-4126-8dfe-26ceffd03eed/edit?shared=true&page=n8uoVZ4LC33i#

## Mock-Ups

https://www.figma.com/file/YQQVD1zSVrWqUuDcJhtSPe/FourPawsCitiziens?node-id=0%3A1










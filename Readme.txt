Ejercicio puesto Goal Systems
-----------------------------

Para ejecutar la aplicaci�n s�lo es necesario cargarla en visual studio(en mi caso us� 2017 para crearla) y ejecutarla.
Antes es necesario modificar el Web.config del proyecto WebApiGestorInventario con un DataSource v�lido. No se ha utilizado
persistencia de datos, pero la librer�a Hangfire necesita la persistencia para trabajar correctamente. Se ha utilizado la librer�a 
Hangfire para crear un acci�n recurrente en la Web Api. Se ha utilizado la librer�a Web Push para el env�o de notificaciones a 
suscriptores. Por falta de tiempo no se ha creado persistencia para los datos del inventario. Tampoco se ha podido securizar la	
Api, una buena implementaci�n ser�a a trav�s de Token JWT. Tampoco se han creado test por falta de tiempo.
En la vista de Nuevo Producto habr�a que poner un datepicker en la Fecha de caducidad. He intentado poner el de MaterializeCss
pero no me ha funcionado a la primera. 
# myrepository

Repositorio para realización de prueba Sportradar.

La solución más simple y extensible que se me ha ocurrido ha sido la siguiente:

Creación de dos clases. 

Una llamada Game que almacenará el nombre del equipo local y el visitante, junto con sus resultados. 

Otra llamada Scoreboard que almacenara un listado de objetos de tipo Game.

La solución que he pensado para que los marcadores mas actualizados se impriman primero ha sido la siguiente:

Cuando se modifica un resultado, se elimina el objeto Game del Scoreboard y lo se añade con el nuevo resultado y en el metodo utilizado para imprimir marcadores imprimo la información del listado del ultimo al primero.

He ido construyendo el proyecto junto con las pruebas de ambas clases, siendo las pruebas de la clase Scoreboard la de mayor extensión.

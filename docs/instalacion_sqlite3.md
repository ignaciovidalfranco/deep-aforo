# Pasos

Nos aseguramos de tener el sistema actualizado.

> sudo apt-get update

Instalamos el paquete de SQLite3.

> sudo apt-get install sqlite3

Creamos un directorio para nuestra base de datos.

> mkdir mldata

Navegamos a nuestro nuevo directorio.

> cd mldata

Ejecutamos el cli de SQLite3 y creamos una base de datos.

> sqlite3 mldata.db 
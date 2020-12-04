### Título: Comandos necesarios en Liquibase.
***
- comando para mapear base de datos: 
##### liquibase generateChangeLog

- comando para actualizar la base de datos: 
##### liquibase update 

- comando para crear la documentacion de la bd: 
##### liquibase --changeLogFile=gestorproyectos.xml dbDoc changelogDocs

- comando para crear un snapshot de la bd formato json: 
##### liquibase --outputFile=myschemaSnapshot.json snapshot --snapshotFormat=json
***
### Autor:

[Daniel José Caballero Sánchez] (<danielcaballero796@gmail.com>).

[Daniel José Caballero Sánchez]: <https://www.linkedin.com/in/danielcaballero796>

# moment5.1

Detta repo innehåller alla filer för min backend skriven i PHP. 

Jag har tre mappar som innehåller följande:

1. api: Denna mapp innehåller min webtjänst som möjliggör CRUD-opertaioner.
2. classes: Denna mapp inehåller en klass som möjliggör att ett kursobjekt skapas. Här i finns också metoderna som möjliggör CRUD till databasen.
3.config: I denna mapp har jag min databaskoppling som jag gjort med hjälp av PDO. Samt en htacess fil som snyggar till adressfältet.

För att lagra data till databasen använder man webbtjänsten tilsammans med ett program som tex. Advanced Rest Client där man kan välja olika metoder för CRUD.

För att läsa ut ur databasen skriver man in https://yofal.se/egnaprojekt/api/read.php och väljer metoden GET

För att läsa ut ur specifik post i databasen skriver man in https://yofal.se/egnaprojekt/api/read_one.php +?id= + (id man vill läsa ut) och väljer metoden GET

För att skapa ny post i databasen skriver man in https://yofal.se/egnaprojekt/api/create.php och väljer metoden POST

För att radera post i databasen skriver man in https://yofal.se/egnaprojekt/api/delete.php +?id= + (id man vill radera) och väljer metoden DELETE

För att uppdatera post i databasen skriver man in https://yofal.se/egnaprojekt/api/delete.php +?id= + (id man vill uppdatera) och väljer metoden PUT


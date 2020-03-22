# CreatingDatabasesInVS
1. go to 'project' and add new item 
2. go to 'data' and click ADO.NET entity data model and rename the model
3. chooses empty EF designer 
4. right click and click 'add new' and then 'entity'
5. give the entity a name
6. right click on the entity and click 'add new' and then 'scalar property' and give the property a name (it will be a string om default)
7. add another entity. add another scalar property. you can now right click anywhere on the screen and 'add new' and 'association'
8. choose the type of relationship between the entities (many to many, many to one etc)
9. right click anywhere on the screen and click 'generate database from model'
10. make sure 'microsoft sql server database file (sql client is selected)
11. click browse and select where you want the file to be generated. name it and click 'open'
12. click 'ok' and 'yes' when the system asks you do you want to create the database
13. choose entity framework and wait a few moments for the DDL (database script to load)
14. click on the script and then hit the green play button above the script
15. choose MSSQLLocalDB and browse for your database file below and click 'connect'
16. go to the server explorer, to your databases and to tables and right click and click 'show table data'
17. add data as you wish
18. add a datagrid and name it 
19. declare your databse after the public partial class MainWindow : Window (check the name in app.confiq <connections>) 
20. write a quer to populate the datagrid with the rows of the database

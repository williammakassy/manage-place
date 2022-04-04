# manage-place
Hello there, this is manage-place api
<br>
Here are the steps to following so as you can be able to run this api crud application,
<br>
1. First you have install a web server, where I for one I have use Xampp web server,
<br>
2. After you have completed the installation of a web server, you will create a folder and name it place-api,
<br>
3. Then you will download the project from github and paste all the folders and files to the place-api folder,
<br>
4. After that you will run xampp web server where you are required to start Apache and MySQL,
<br>
5. And there you will open any web browser and type 'localhost' to the URL and then you will navigate to phpMyAdmin
<br>
6. There you will create a database, name it db_manageplaces and after that you are supposed to insert the database sql file from the place-api folder
<br>
7. the sql file name is db_manageplaces.sql,
<br>
8. after that you will open the project to any text editor, but I suggest to use visual studio code text editor in order to be able to run the project.
<br>
9. And then to test the API you will use Postman app, So you have to download and install postman for testing activities.
<br>
10. When you're done with installing Postman, you'll create a new workspace where you have to test all the operations there.
<br>
11. For testing urls you have to use the below urls:
<br>
12. http://127.0.0.1:8000/api/places - Here you will be able to see all the places. Note: You will select GET method 
<br>
13. http://127.0.0.1:8000/api/places/1 - Here you will be able to see one record by writing id on the url. Note: You will select GET METHOD
<br>
14. http://127.0.0.1:8000/api/updatePlace/1 - Here you will be able to edit, and you have to select PUT method.
<br>
15. http://127.0.0.1:8000/api/places - Here you have to select POST method so as to store data to the database
<br>
16. http://127.0.0.1:8000/api/places/1 - Here you will delete the record but to do so you have to select DELETE METHOD

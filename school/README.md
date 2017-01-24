# Primary School Website

This is a primary school website , which has login system implemented into it via php and SQL database at the backend, for the front end we have used bootstrap , html , css and js.

## How to get this website working ?
 
1. Download the Zip File extract the file. 
2. Now copy the extracted folder and place in your server path directory *eg : C://xampp/htdocs/* here paste it.
3. Import the database onto your local server *Preferably Xampp* .
4. Inside the folder school open the file *db_connect.php* now here *$conn = ("Your localhost name","username","password","primary"); here dont change the last attribute "primary".*
5. Once Above steps are done the go to database and check the student table for which you hav *sid's* don't try view results of those candidates whose *sid's* aren't there in student table.
6. After this you are ready to go and in the website admin login details *username : shiva password: prasad*.
7. Follow The steps and go through them again and check them once again.

##Limitations 

1. The Admin Can't Change the student table data through the web app he has to enter into the database and make changes though he can make changes to the marks via *sid(student id)*.
2. It doesn't provide more functionality to user apart from viewning results of their students and contacting the school.

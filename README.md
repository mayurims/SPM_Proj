# SPM_Proj



The Ports assigned for each of the Classes are the following ->
1. Courses.py -> 5001
2. Person.py -> 5002
3. Enrollment -> 5003
4. Quiz -> 5004


In order for the application to work, go to your Terminal, 
1. Load the SQL file 'g7t6_database.sql' into your Database
2. Change directory to flask 
   <br /> cd flask
3. Run the following codes in your terminal :-
   <br /> python Course.py
   <br /> python Person.py
   <br /> python Enrollment.py
   <br /> python Quiz.py

<br />
For MAC users, 
<br />
1. Replace for the following files -
   <br /> python Course.py
   <br /> python Person.py
   <br /> python Enrollment.py
   <br /> python Quiz.py
<br />
From (original file): 
<br />
 app.config['SQLALCHEMY_DATABASE_URI'] = 'mysql+mysqlconnector://root:''' + \
                                        '@localhost:3306/mydb'
                                        
                                        
<br />                                
To (MAC users):
<br />
app.config['SQLALCHEMY_DATABASE_URI'] = 'mysql+mysqlconnector://root:root' + \
                                        '@localhost:3306/mydb'
                                        
2. Change the directory to hr_pov
   <br /> cd UI
   <br /> cd hr_prov
   <br />
3. Look for the file 'action.php' and make the following edits.
  <br /> 
From(original file):
<br />
   $connect = new PDO("mysql:host=localhost;dbname=mydb","root", "");
<br />
To (MAC users):
<br />
   $connect = new PDO("mysql:host=localhost;dbname=mydb","root", "root");

               

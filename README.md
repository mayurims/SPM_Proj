# SPM_Proj



The Ports assigned for each of the Classes are the following ->
1. Courses.py -> 5001
2. Person.py -> 5002
3. Enrollment -> 5003
4. Quiz -> 5004


In order for the application to work, go to your Terminal, 
1. Load the SQL file 'g7t6_database.sql' into your Database
2. Change directory to flask 
   cd flask
3. Run the following codes in your terminal :-
    python Course.py__
    python Person.py__
    python Enrollment.py__
    python Quiz.py__


For MAC users, 

1. Replace for the following files -
    python Course.py,
    python Person.py,
    python Enrollment.py,
    python Quiz.py
    
From (original file): 
 app.config['SQLALCHEMY_DATABASE_URI'] = 'mysql+mysqlconnector://root:''' + \
                                        '@localhost:3306/mydb'
                                        
                                        
                                      
To (MAC users):
app.config['SQLALCHEMY_DATABASE_URI'] = 'mysql+mysqlconnector://root:root' + \
                                        '@localhost:3306/mydb'
                                        
2. Change the directory to hr_pov
   cd UI
   cd hr_prov
   
3. Look for the file 'action.php' and make the following edits.
   
From(original file):
   $connect = new PDO("mysql:host=localhost;dbname=mydb","root", "");
   
To (MAC users):
   $connect = new PDO("mysql:host=localhost;dbname=mydb","root", "root");

               

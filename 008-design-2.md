#Still need to edit this 

 #Software Design document
1.  What programming language(s) will you use? We will use HTML,CSS, and Javascript for connecting the database to the website. In addition, we will use PHP and SQL queries to develop and maintain the database. 
 
2.  What framework(s), if any, will you use? We will use CakePHP framework to facilitate the production of our database. 
 
3.  What other libraries or dependencies will you use? We will rely on Wordpress add-ons and its functionality, because our sponsors want the website to work with the database storing patient information. We will also use a MySQL server for our database.   
 
4.  Will you use different languages, frameworks, and/or libraries/dependencies for different parts of your application? 
    We will use PHP and  CakePHP for the server-side and for connecting the database to the Clinic in the Park  website. We will use SQL for developing and managing the database. 
 
5.  What is your overall architecture (e.g., MVC)? Our overall architecture is the client-server model, because most patients and staff accessing both the database and website will be accessing the server for information from their own side.
 
6.  What data will you need to store? We will need to store log-in and patient information, like check-ups or BMI of patients.  Overall information from events or clinics patients have attended under Clinic in the Park.  

7.  What is your database design (or other data storage scheme)?  The database itself will be based on database-centric architecture as information stored will be personal patient information.  The primary keys will be patient ID, clinics attended in Clinic in the Park, and check-ups. The check-ups key will have a relationship with another table that contains all the check-ups a patient has had from Clinic in the Park. 
 
8.  What are the other parts of your software? Our software will be accessed by the Clinic in the Park website and we will also develop a user interface for easier access. It will also be account restricted, meaning some accounts will have restriced access while others do not (e.g: staff accounts will be able to input patient information while patient accounts will not be allowed to edit that information.)

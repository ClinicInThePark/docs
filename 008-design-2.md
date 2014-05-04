
#Software Design Document
1.  What programming language(s) will you use? HTML, CSS, JavaScript, PHP/MySQL.
 
2.  What framework(s), if any, will you use? CakePHP 
 
3.  What other libraries or dependencies will you use? We will rely on Wordpress as our CMS for the website, plugins and its functionality, because our sponsors want the website to work with the database storing patient information. Our server will need to support MySQL for this project. For creating the database user interface, we will be using HTML/CSS and JavaScript, and will therefore be using the jQuery library as support. 
 
4.  Will you use different languages, frameworks, and/or libraries/dependencies for different parts of your application? 
    We will use HTML, CSS, and Javascript for creating the database user interface. We will use MySQL to create the database, and PHP (along with CakePHP) to facilitate interaction between the user and that database, as well as for connecting the database itself to the website.
 
5.  What is your overall architecture (e.g., MVC)? Our overall architecture is the client-server model. Most patients and staff accessing the database and website will be requesting information from the server from separate devices.
 
6.  What data will you need to store? We will need to store login credentials and visitor information, such as booths attended and health services received, ranging from general education to clinician-administered diagnoses and treatments.  

7.  What is your database design (or other data storage scheme)?  The database itself will be based on database-centric architecture, as information stored will be personal to the visitor. The primary keys will represent patient identification, clinics attended, booths attended, and health services received. The health services key will have a relationship with another table containing all previous services a given visitor has receved at Clinic in the Park. 
 
8.  What are the other parts of your software? Our software for the database will be accessible through a portal on the Clinic in the Park website. This portal will direct users to the database user interface, either directly within the website itself, or via link to an external address. Access will be based on account permission levels, meaning some accounts will be more restriced than others. For example, staff accounts will be able to input visitor information, while visitor accounts will not be allowed to edit that information.

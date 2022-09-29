# doodle-tutorial-project
# MVC Search Engine Project done with udemy course

This is the project Ive done with Udemy course - https://www.udemy.com/course/google-search-engine-clone/

# Summary
Here are my thoughts about the project, documentation of what Ive learned and brief summary: <br />
-Using PHP built-in DomDocument class to parse html (although Im aware of existence of external libraries that can do the same job) <br />
-Crawling websites (although Im aware of existence libraries like crawl that would do the same job as file_get_contents that can be even disabled to go to external websites on production - allow_url_fopen :)) <br />
-Writing OOP code and structuring the project <br />
-Using PDO and prepared statements to connect with the server (database) <br />
-Using PHP built-in functions to achieve a goal (for example, showing only links to websites) <br />

# Weaknesses
Weaknesses of the project:<br />
-Uses file_get_contents instead of curl<br />
-Does not use external libraries<br />
-Relies on initial link having links to other websites<br />

# Strengths:
-OOP classes<br />
-PDO prepared statements<br />
-Usage of php built-ins that are worth knowing but might be overlooked while learning (like DomDocument class)<br />
-Shows the idea and bluepring how to approach the task of creating search engine<br />
-Good code, Ive learned something useful<br />

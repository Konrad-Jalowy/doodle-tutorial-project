# doodle-tutorial-project
# MVC Search Engine Project done with udemy course

This is the project Ive done with Udemy course - https://www.udemy.com/course/google-search-engine-clone/

# Summary
Here are my thoughts about the project, documentation of what Ive learned and brief summary:
-Using PHP built-in DomDocument class to parse html (although Im aware of existence of external libraries that can do the same job)
-Crawling websites (although Im aware of existence libraries like crawl that would do the same job as file_get_contents that can be even disabled to go to external websites on production - allow_url_fopen :))
-Writing OOP code and structuring the project
-Using PDO and prepared statements to connect with the server (database)
-Using PHP built-in functions to achieve a goal (for example, showing only links to websites)

# Weaknesses
Weaknesses of the project:
-Uses file_get_contents instead of curl
-Does not use external libraries
-Relies on initial link having links to other websites

# Strengths:
-OOP classes
-PDO prepared statements
-Usage of php built-ins that are worth knowing but might be overlooked while learning (like DomDocument class)
-Shows the idea and bluepring how to approach the task of creating search engine
-Good code, Ive learned something useful

# byblios_160
# Small application for managing books and authors, using the Spring MVC framework and Thymeleaf
A small web application for managing books and titles, using the Spring MVC framework, a small MySQL database, and Thymeleaf for the front end.

The data model consists of seven tables: books, collections, authors, publishers, a short list of novel types, and two tables for the access authoring schema. The RDBM-ORM mapping is implemented with the Hibernate persistence framework, using adnotations. There should be Many2Many bi-directional dependency type between these objects, but this particular model only uses one-direction ManyToMany

It uses the Spring Boot container. No need to deploy in a Tomcat server

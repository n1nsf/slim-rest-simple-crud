# slim-rest-simple-crud


## Clone the project

To install [Git](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git), download it and install following the instructions : 

```sh
git clone https://github.com/nisaofee/slim-rest-simple-crud.git 
```

Go to the project directory : 

```sh
cd slim-rest-simple-crud
```


## Setup the project

1. Create a MySQL database name "cellar" in xampp phpmyadmin

2. import cellar.sql to create and populate the "wine" table

3. copy slim-rest-simple-crud to xampp htdocs directory

4. Open api/index.php. In the getConnection() function at the bottom of the page, make sure the connection parameters match your database configuration.

5. Access the application in your browser. For example: http://localhost/slim-rest-simple-crud

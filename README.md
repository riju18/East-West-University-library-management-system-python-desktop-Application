# info:
# database info:

    software: mysql workbench (https://dev.mysql.com/downloads/mysql/)

    mysql server login username: root

    mysql server login username: user own password

    database name: library_management

    number of tables: 7
# 'author' table:
  
    idauthor int(11) AI PK 

    author_name varchar(45)
  
 # 'book' table:
  
    id int(11) AI PK 

    book_name varchar(45) 

    book_description varchar(45)

    book_code varchar(45) 

    book_category varchar(45)

    book_author varchar(45)

    book_publisher varchar(45)

    book_price int(11)
    
# 'category' table:

    idcategory int(11) AI PK 
    category_name varchar(45)
    
# 'client' table:

    idclient int(11) AI PK 
    clientName varchar(45) 
    clientEmail varchar(45) 
    clientNid varchar(45)
    
# 'dayoperations' table:

    iddayoperations int(11) AI PK 
    bookname varchar(45) 
    type varchar(30) 
    days int(11) 
    fromDate datetime 
    toDate datetime 
    clientName varchar(45)
    
# 'publisher' table:

    idpublisher int(11) AI PK 
    publisher_name varchar(45)
    
# 'users' table:

    id_users int(11) AI PK 
    username varchar(45) 
    useremail varchar(45) 
    userspassword varchar(45)
# installation:

    pip install mysqlclient
    
    pip install MySQLdb 
    
    pip install pyqt5ac  (to convert .qrc file to .py)
# run:

    for conda : app.ipynb
    for python: app.py
    
# reminder:

    every time for the change of app_design.ui have to run the "convert_qrc_to_py.ipynb"(for conda), move the "icons_rc.py" to root folder from "generated folder" & then run the app.ipynb.
    
 # screenshots:
 ![mainWindow](https://user-images.githubusercontent.com/18087611/58745138-d2d5b280-846e-11e9-93e3-140770c202eb.JPG)
 ![userInfo](https://user-images.githubusercontent.com/18087611/58745139-d2d5b280-846e-11e9-8c27-a3a211a23fa0.JPG)
 ![loginWindow](https://user-images.githubusercontent.com/18087611/58745140-d36e4900-846e-11e9-8a23-7d6ef1de5106.JPG)

  

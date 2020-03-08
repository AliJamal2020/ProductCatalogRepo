# ProductCatalogRepo
add,edit,remove,view,search and export products with images 
-----------------------------------------------------------


1- extract the file
2- you find 2 folders "ProductCatalog" represent Back-end , "ProductCatalog-front" represent front-end
3- in back-end solution I Create Modal Class-library that represent Product Model and other models if exist
4- then Data.Access Class-library that Use Model as a reference , that represent Data access Layer includes EF core
5- then Core module that represent the business such as ProductManager 
6- finally Host Project that represent startup Project and mapping from dtos to Models and others
7- we need to run command update-database to Generate it "ProductCatalog.DataAccess" As a Default project and Build solution
8- in front-end project I Use angular 8 , I delete node_modules so please run this before  "npm i" then ng serve --o
9- I Used reactive forms , angular materials to build components 
10- I used asp.net core 3.1 version


-----------------------------------------

this solution help users to search by product name then view the products items and export them with the same search criteria 
and add ,edit ,delete any of them 

we can upload image to product in add mode then, it will display in view list 
also , can upload image to product in edit mode , it ovveride the old image then will display in view list 
in edit mode , "LastUpdated" property is updated with datetime.now

when export items , the images display in excl file that exported 

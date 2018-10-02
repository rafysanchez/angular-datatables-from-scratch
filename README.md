# Implementing jQuery Datatables in Angular 5 from scratch !
The code is very simple and only explains how to implements jQuery DataTables in Angular 5.

For the full tutorial, just see this Medium post : https://medium.com/apprendre-le-web-avec-lior/angular-5-and-jquery-datatables-fd1dd2d81d99

# Create the project (avoid this if you are implementing DataTables on an existing project)
ng new datatables

# When finishing go for Bootstrap 4 (use the strict 4.0.0-beta.2 or you will be in trouble with autoprefixer and other stuffs)
npm install bootstrap@4.0.0-beta.2 --save --save-exact

# Then DataTables core 
npm install datatables.net --save

# Then DataTables Bootstrap 4
npm install datatables.net-bs4 --save

# Finaly jQuery and it's types 
npm install jquery --save
npm install @types/jquery --save-dev


# intalacao de rxjs-compat
npm i rxjs-compat --save

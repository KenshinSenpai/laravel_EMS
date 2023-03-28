# laravel_EMS

Step 1:
  composer create-project laravel/laravel EMS
  
Step 2:
  create a new database
  
Step 3:
  replace the DB_DATABASE in env. file with the database you've created
  
  DB_DATABASE= <database name you've created>
  DB_USERNAME=root
  DB_PASSWORD=
  
Step 4:
  code .
  
Step 5:
  delete the migrations folder inside database folder
  
Step 6:
  paste the new migrations folder
  
Step 7:
  run php artisan migrate

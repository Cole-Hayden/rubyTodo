I used the Cloud9 ide which spins up your personal linux environment to run the ruby on rails application. 


Please use this url to access the application.

https://todopercipia-cwh8b4.c9users.io/lists


Creating the to do list in ruby on rails is very easy.  
To begin setting up the databse model you run the command

rails g scaffold lists description:string completed:boolean

Then you have to migrate your database model by running the command

rake db:migrate

After running the command rake routes, your routes are created and your to do list is completed.

In order to deploy on your own server, you would have to sign up for the cloud9 ide and then merge the code into your repo and run the application.

# README
### This is a base Rails api project using Postgres as a database.
Clone, cd into directory. Create a new directory called ".env", make sure you are in the "rails_api-postgres-base" folder.

Inside the .env folder create two files, backend and database.

Copy and paste this into the respective files to get started.

In backend copy this:

>DATABASE=postgres


In database copy this:

>POSTGRES_USER=postgres\
POSTGRES_PASSWORD=my_secure_password\
> Replace above with a good password!

Run:
>docker-compose up --build

If the build fails with an error "Your Ruby version is 3.1.x, but your Gemfile specified 3.1.1" You may need to change your Gemfile to the version you are running or set your local ruby version to the one specified in the Gemfile.

Navigate to localhost:3000 And you should see the Rails logo
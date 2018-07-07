# full-stack-go-
Torun the server on your system:

Make sure you have dep installed
Run dep ensure to install dependencies
Run go build to create the binary (blog_example__go_web_db)
Run the binary : ./blog_example__go_web_db
To run tests:

Run dep ensure to install dependencies
Run go test ./...
Create the birds table before running the application :

create table birds (
id serial primary key,
bird varchar(256),
description varchar(1024)
);
Before running the application, edit the connString variable inside the main function to specify your postgres database connection

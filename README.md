# full-stack-go-
Torun the server on your system:

Make sure you have dep installed
1. Run dep ensure to install dependencies
2. Run go build to create the binary (blog_example__go_web_db)
3. Run the binary : ./blog_example__go_web_db

To run tests:
1. Run dep ensure to install dependencies
2. Run go test ./...

Create the birds table before running the application :

```
create table birds (
  id serial primary key,
  species varchar(256),
  description varchar(1024)
);
```

Before running the application, edit the connString variable inside the main function to specify your postgres database connection

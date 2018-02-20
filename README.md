# Burger

BURGER is a burger logger with MySQL, Node, Express, Handlebars and a homemade ORM.  Heres the work flow:  View it here: [Burger App](https://powerful-depths-25126.herokuapp.com/)
  
* Used and implemented the MVC design pattern.
* Used Node and MySQL to query and route data in the app.
* Used a middleware ```Handlebars``` to generate HTML

---


Packages   |  Use
------------- | -------------
Express  |  standard server framework for Node.js
Body Parser  | a top-level middleware, which will parse the bodies of all incoming requests
Handle Bars| provides the power necessary to build semantic templates
MySQL  |relational database management system 

---

#### Directory structure

Here is how I structured my work:

```
.
├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   ├── assets
│   │   ├── css
│   │   │   └── burger_style.css
│   │   └── img
│   │       └── burger.png
│   └── test.html
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars
    ├── partials
        └── burger
            └── burger-block.handlebars
```

- - -

## GIF DEMO

![First Display](https://raw.githubusercontent.com/IamGiel/burger/master/views/images/burgers_galore.gif)





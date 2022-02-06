
```
   _____ _          __  __      _     _           
  / ____| |        / _|/ _|    | |   | |          
 | (___ | | ____ _| |_| |_ ___ | | __| | ___ _ __ 
  \___ \| |/ / _` |  _|  _/ _ \| |/ _` |/ _ \ '__|
  ____) |   < (_| | | | || (_) | | (_| |  __/ |   
 |_____/|_|\_\__,_|_| |_| \___/|_|\__,_|\___|_|     

  _____  _    _ _____  
 |  __ \| |  | |  __ \ 
 | |__) | |__| | |__) |
 |  ___/|  __  |  ___/ 
 | |    | |  | | |     
 |_|    |_|  |_|_|     

```

--------------
## START APPLICATION
--------------
* To launch the application start a local PHP server and a MySQL database.
* On database execute the SQL script `/api/db/NAME_DB_db_schema.sql`
* Put your project in root folder of your PHP server.
* Go to http://localhost

--------------
## CONFIGURE
--------------

* For PHP and database config edit `/api/properties.php`
* For AngularJS edit `properties.js`

--------------
## USING SKAFFOLDER-CLI
--------------

With Skaffolder-CLI you can easily manage your Skaffolder project from command line and customize your generator template from your IDE.

Install Skaffolder-CLI with
``` bash
$ yarn install -g skaffolder-cli
```

Login running the command
``` bash
$ sk login
```

Generate your project with the command
``` bash
$ sk generate
```

You can customize your generator template working with files in .skaffolder folder in your project root.

Please refer to https://skaffolder.com/#/documentation/skaffolder-cli for more information.


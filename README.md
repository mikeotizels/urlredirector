urlRedirector - A web based link redirecting plugin.
====================================================

Copyright (c) 2019 Michael Otieno. All rights reserved.
http://www.github.com/mikeotizels/urlredirector

Code distributed as part of Mikeotizels Developer project.
http://www.github.com/mikeotizels/developer 

For licensing, see LICENSE.md

urlRedirector is a link redirecting plugin to be used in websites to 
redirect to external URLs without leaking the Referer. It also logs
the redirection data in a TEXT file as well as in MySQL database. 
You can adjust the redirector to your needs and integrate it with  
your website or application.


Requirements
------------
1. Web Server  - A web server with PHP language and MySQL database like Apache
2. Web Browser - A web browser like Chrome, Firefox, Opera, Edge, e.t.c


Installation
------------

Installing urlRedirector is an easy task. Just follow these simple steps:

 1. **Download** the latest version from the author's github repository: 
      http://www.github.com/mikeotizels/urlredirector  
      You should have already completed this step, but be 
      sure you have the very latest version.

 2. **Unzip** all the urlredirector files on your computer.

 3. **Upload** all the files in the `redirector` folder to your web server.
      You can place the files in whichever directory you want, 
      on the root of your website.

 4. Define your MySQL server credentials in the dbconnect.inc.php file.

**Note:**
  - A database is only required if you want to insert the logs in MySQL server,
    or if your web server does not support PHP Files (Create, Open, Write, Close) 
    To create the tables, execute the SQL queries in the "db_tables.sql" file. 
    This can be done in PhpMyAdmin > SQL.

The redirector comes with a few documents to get you started with the application.
Take a look at the `samples` directory.

To test your installation, just call the following link at your website using a web browser:

    http://your-site-address/redirector-installation-path?s=source&r=referer&u=url


For example:

http://www.example.com/redirector?s=home-page&r=urlredirector-readme-file&u=http://www.mikeotizels.orgfree.com


## Upgrading

urlRedirector cannot really be "upgraded" - simply delete the old files on your 
web server, and follow the installation instructions above.

If you are using a database for logging, drop the old tables and create new ones.
Then execute the SQL queries in the "db_tables.sql" file. 


## Intergration

To integrate urlRedirector with other PHP Servers, Databases or CMS, follow the instructions
in the readme.txt files in the respective directories under `integration` folder.


## Contributing

Development    - Build plugins, extensions and more to be included in urlRedirector.       
Traslation     - Change the urlRedirector into other languages. 
Feedback       - Report bugs and other issues, provide helpful ideas. 
Donation       - Support the urlRedirector project.


Help
----
Refer to the files in `samples` folder.
If you need more help, please contact me:
Email:   mikeotizels@gmail.com
Website: http://www.mikeotizels.orgfree.com/contact?subject=urlRedirector


---------------------------------------------------------------------
*"Built by a Developer, for a Developer. Make it Bigger and Better!"*


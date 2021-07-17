Email Reader
------------

Why?
---

-  could not find any good email reader for automation purpose
-  fake smtp only displays last email and does not do rendering on top of it.


What?
----

Reader will target -

-  reading of email
-  clicking on the links randomly (chaos mode)

Approach?
---------

-  list all emails
-  open email on a tab on click
    -  Two modes
        -  mime message
        -  rendered version (long shot)

How?
----

-  server can listen on a directory for file addition
-  on add, pick the file and return to web (keep alive)
-  write web in react UI (and pull in all the amazing themes and templates provided by open source community)
-  deploy on localhost (because it is just another util)

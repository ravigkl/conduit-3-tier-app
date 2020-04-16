# conduit: An example application of The Kubernetes Guide
This application is 3 tier. It has frontend, api and backend database.

Vue is frontend, api is written into SpringBoot and database is MySQL.

Front is exposed at 80 port while api is on 8080 and db on 3306.

Only frontend would be exposed to the outside world while api and database would talk container to container locally.

There would be load balancer in front of every service - frontend, api and database.

# Rate-Limited-URL-Shortener
A URL Shortening service with Rate limiting for users to avoid server load.

A URL shortening application which also has rate limiting feature for shortening url like bit.ly .

Go project using go fiber modules and redis for url shortening service.

Technologies used: Go, Redis, Go fiber, Docker.

Description about technologies used:

The application uses Go fiber modules to shorten the url by parsing it as a string.

It aims at providing service to user only 10 times in 30 minutes, after which it will be reset to its normal value, 10. It is done to avoid DDoS attacks and server load.

Redis is used as an efficient Database for the project.

To start the project in your local:

-Start Redis server at port 6379.

-Do docker compose using terminal to load application in docker container.

-Use postman for fetching and retrieving data.

-Make sure your Redis server is up and running before starting the application.

Thanks.

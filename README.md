﻿# Movies API

 A REST-ful api created using SpringBoot and MongoDB 🍃

* GET Requests
  > `http://localhost:8080/api/v1/movies/` Gets All the movies
  >
  > `http://localhost:8080/api/v1/movies/<imdbId>` Gets Single movie for given imdbId

* POST Requests
  > `http://localhost:8080/api/v1/reviews/` Post Review for the given movie with imdbId
    > ```
    > {
    >       "reviewBody":<review>,
    >       "imdbId":<imdbId>
    > }
    >   ```

Looking forward to adding more functionality and security :)

# MoviesRestApi

> An IMDB Movie API

> This is a Java Spring Boot RESTful API that fetches movies and their details from IMDB. *The frontend for this project is served by Angular and is located in a different repository.*
--- 

Requirements
- Java 11
- Maven
- An IMDB API key

> Getting Started
1. Clone this repository.

2. Create a file called application.properties in the root of the project.

3. In the application.properties file, add the following property:

      *imdb.apikey=YOUR_IMDB_API_KEY*

4. Run the following command to build and start the application:

      *mvn spring-boot:run*

>> The application will start on port 8080. You can access the API at the following URL:
  http://localhost:8080/api/movies

---

API<br>

The API provides the following endpoints:

> /api/movies: Get a list of movies.
> 
> /api/movies/{id}: Get a movie by its ID.
> 
The /api/movies endpoint returns a JSON array of movies. Each movie object has the following properties:

> id: The movie ID.
> 
> title: The movie title.
> 
> year: The movie release year.
> 
> genres: The movie genres.
> 
> rating: The movie rating.
> 
> poster: The movie poster URL.


The /api/movies/{id} endpoint returns a JSON object for the movie with the specified ID.

Troubleshooting

If you are having trouble getting the application to start, please check the following:

> Make sure that you have Java 11 installed.
> 
> Make sure that you have Maven installed.
> 
> Make sure that you have an IMDB API key.
> 
> Make sure that you have added your IMDB API key to the application.properties file.

---




# MoviesDatabase API Integration

This project explores the MoviesDatabase API to understand how to fetch and interact with movie-related data. It demonstrates how to read API documentation, make authenticated requests, and handle responses effectively in a JavaScript or TypeScript project.

---

## API Overview

The **MoviesDatabase API** provides access to a large collection of movie, TV show, and actor data. It allows developers to search for movies, retrieve detailed information such as release dates, genres, cast, and crew, and explore trending titles. The API is ideal for building applications that need movie or TV metadata, such as streaming apps, recommendation systems, or entertainment dashboards.

---

## API Version

**Version:** 1.0  
*(Refer to the official MoviesDatabase API documentation for the latest updates.)*

---

## Available Endpoints

| Endpoint | Description |
|-----------|--------------|
| `/titles` | Retrieves a list of movies or TV shows based on filters like genre, year, or rating. |
| `/titles/{id}` | Fetches detailed information for a specific movie or show using its unique ID. |
| `/titles/search/title` | Searches for titles by name (e.g., “Inception” or “Breaking Bad”). |
| `/titles/random` | Returns a random movie or TV show entry. |
| `/actors/{id}` | Provides information about a specific actor, including filmography. |
| `/genres` | Lists all available genres supported by the database. |

---

## Request and Response Format

### Example Request
```http
GET https://moviesdatabase.p.rapidapi.com/titles/search/title?title=Inception
Headers:
  X-RapidAPI-Key: YOUR_API_KEY
  X-RapidAPI-Host: moviesdatabase.p.rapidapi.com

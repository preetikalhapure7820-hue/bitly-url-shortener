# Bitly-Style URL Shortener API

A scalable Bitly-style URL shortener backend built with Spring Boot,
designed as a reusable third-party API.

## Features
- Shorten long URLs
- Redirect to original URLs
- Custom alias support
- URL expiration
- Click analytics

## Tech Stack
- Java 17
- Spring Boot
- Spring Data JPA
- MySQL / PostgreSQL
- Maven

## API Overview
POST /api/v1/urls  
GET  /{shortCode}  
GET  /api/v1/urls/{shortCode}/analytics  

## Future Enhancements
- Redis caching
- Rate limiting
- Authentication & API keys

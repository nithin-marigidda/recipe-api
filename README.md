# Recipe API (Spring Boot + PostgreSQL)

## Overview
Parses `US_recipes.json`, stores recipes in PostgreSQL, and exposes REST APIs to list and search recipes. (Optional) React UI can consume the same APIs.

## Tech Stack
- Backend: Spring Boot 3, Java 17, Spring Data JPA
- DB: PostgreSQL
- Build: Maven

## Prerequisites
- Java 17+
- Maven 3.9+
- PostgreSQL 13+ with `psql` in PATH

## Database Setup
1) Create DB:
```bash
psql -U postgres -c "CREATE DATABASE recipe_db;"

# Cassandra Movie Database Project

This repository contains an assignment focused on using **Apache Cassandra** to create, manage, and query a movie database. It demonstrates the use of advanced Cassandra features such as collection types, TTL (time-to-live), and blob storage, integrated with Python for data insertion, update, and retrieval.

## Project Description

The project creates a `Movie` table within a Cassandra KeySpace and populates it with movie data including:
- Movie name
- Cast (as a map of roles to names)
- Poster image (stored as a BLOB)
- Timestamp of creation
- TTL (to expire certain entries automatically)

Python scripts are used to:
- Connect to the Cassandra database
- Insert movie data
- Update the movie posters from a folder of images
- Query movies by a specific actor or director
- Convert image files to and from blob format

## Technologies Used

- **Apache Cassandra**
- **Python**
- **Cassandra Driver (DataStax)**
- **BLOB and MAP data types**
- **TTL (Time-to-Live)**

##  Key Features

- Create KeySpace and Movie table with appropriate types
- Store cast information using `map<text, text>`
- Store and update movie posters using BLOBs
- Set TTL for automatic data expiration
- Query and filter movies based on cast members
- Convert image files to BLOBs and back for poster handling



---

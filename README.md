# Music Library System – OOP Lab
## Overview
This project implements a Song class using Object-Oriented Programming concepts in Python.

The system models individual songs while also maintaining global statistics about all created songs. These insights simulate features used in music streaming platforms such as:

Total number of songs
Unique artists
Unique genres
Song count per genre
Song count per artist

This lab demonstrates proper use of class attributes, class methods, and automatic state updates when new objects are created.

## Concepts Demonstrated
Class attributes
Class methods
Instance attributes
Automatic state updates on object creation
Data aggregation using dictionaries
Test-driven development with pytest

## Project Structure
```
PYTHON-MUSIC-LIBRARY-SYSTEM-LAB/
│
├── song.py
├── song_test.py
├── conftest.py
└── README.md
```



## Song Class Design
### Instance Attributes
Each Song object has:
name
artist
genre

### Class Attributes
The class tracks global data:
count → total number of songs created
genres → list of unique genres
artists → list of unique artists
genre_count → dictionary tracking songs per genre
Example:
```
{"Rap": 2, "Pop": 3}
```


artist_count → dictionary tracking songs per artist
Example:
```
{"Beyonce": 5, "Jay Z": 2}
```



### Class Methods
Each method is automatically triggered when a new Song is created:
add_song_to_count
add_to_genres
add_to_artists
add_to_genre_count
add_to_artist_count

## Running Tests
Install pytest:
```
python -m pip install pytest
```


Run tests:
```
pytest
```

All tests should pass successfully.

## Features Implemented
✔ Create Song objects
✔ Track total song count
✔ Store unique artists
✔ Store unique genres
✔ Count songs by genre
✔ Count songs by artist
✔ Fully tested with pytest

## Requirements
Python 3.12+
pytest
Check Python version:
python --version

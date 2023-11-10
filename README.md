# Music Song Records System 

## Table of Contents
- [Overview](#overview)
- [Feastures](#features)
- [Usage](#usage)
- [Testing](#testing)

## Overview 

This project is a Java-based music record system that allows users to manage, search, and delete music records efficiently using Binary Search Trees (BST). The system reads initial music records from a text file, and users can perform various operations through an interactive menu.

## Features 

1. **Song Object Class**:
    - A class is implemented to represent a song, with fields for song name, artist, ID, genre, and year.

3. **Search Functionality**:
    - Users can search for a song using the name, artist, or ID field individually.
    - Search and display all songs of a given genre.
    - Search for songs within a specified ID range.

4. **Interactive Menu**:
    - The program provides an interactive menu for users to easily navigate and perform operations.

5. **Binary Search Trees**:
    - Three BSTs are implemented based on song name, ID, and artist to efficiently index music records.
    - Each BST stores an index to help locate specific songs in an array, avoiding redundant storage of the entire song object.

6. **Insert and Delete Operations**:
    - Users can insert new songs with required fields.
    - Deletion of records is based solely on the ID field.

## Usage

1. **Insert Records**: Insert new songs with required fields using the interactive menu.
 
2. **Search Records**: Search for songs based on name, artist, or ID.
                       Display all songs of a specific genre.
                       Search for songs within a specified ID range.
   
3. **Delete Records**: Delete a song based on its ID.
   
## Testing 

1. **Read Records from File**: Read a few records from a text file using the program to build the BSTs.
   
2. **Perform Operations**: Apply various tasks mentioned in the project description on the generated BSTs.


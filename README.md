# Note-Taker
Express.js Challenge: Note Taker

Link to the website:

## Overview

Create an application called Note Taker that can be used to write and save notes. This application will use an Express.js back end and will save and retrieve note data from a JSON file.

## Features

The note-taking app is intuitive and efficient. Upon opening, a landing page leads to a note section. Here, existing notes are on the left, and a space for new notes is on the right. "Save" and "Clear" buttons appear when creating a note. Saved notes join the existing list, and selecting a note for editing is straightforward. A "New Note" button allows starting a new note easily, ensuring a streamlined note-taking experience.

## Technologies
- **Express.js:** Routing, Middleware Integration, and Handling API Requests and Responses.

- **Data Storage:** Utilize a db.json file for storing and retrieving notes. This will involve the fs (file system) module to handle read and write operations.

- **HTML Routes:** 
GET /notes should return the notes.html file, allowing users to access the note-taking interface.
GET * (a wildcard route) should direct users to index.html, typically the landing page.

- **API Routes:**
GET /api/notes for reading the db.json file and returning all saved notes in JSON format.
POST /api/notes for receiving new notes from the request body, adding them to the db.json file, and then returning the new note to the client. Implementing a method to assign unique IDs to each note is crucial for differentiation and retrieval. You might consider using npm packages like uuid for generating unique identifiers.

## License

This project is under the [MIT License](LICENSE).

![Note-Taker]
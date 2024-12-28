- Part 1 - Conceptual.md - Questions about PostgreSQL
- Part 2 - Queries.md - Questions about SQL Queries
______________________________________________________
- Part 3 - Database DJ Project
- ## Playlist-app

To get this application running, make sure you do the following in the Terminal:

1. `python3 -m venv venv`
2. `source venv/bin/activate`
3. `pip install -r requirements.txt`
4. `createdb playlist-app`
5. `flask run`

- The Database DJ Project Playlist App is a CRUD app that lets users create Playlist entries and add songs to that playlist.
- In iPython create your tables using db.create_all()
- Routes
    - GET / or /playlists - shows all playlists.
    - GET /songs - list of songs
    - GET /songs/<int:song_id> - shows specified song
    - GET /songs/add - Form to add a song
    - POST /songs/add - Submission to add
    - GET /playlists/<int:playlist_id> - Shows specified playlist
    - GET /playlists/add - Form to add playlist
    - POST /playlists/add - Submission of form to add playlist
    - GET /playlists/<int:playlist_id>/add-song - Form to add song to playlist
    - POST /playlists/<int:playlist_id>/add-song - Submission of form to add song to playlist

_______________________________________________________________________________________
- You will need Python, iPython, and Flask to run programs. Be sure to view the requirements.txt and install necessary packages to run files.
Hey Gökce

This is my interpretation of the playlist code, based around your template.


# Playlist:
-----------
A simple playlist manager using a *singly linked list*.  
This program reads a list of songs from a text file, allows manipulation of the playlist (insertion and deletion of tracks), and saves the updated playlist to a new file.

## Features:
------------

- Load playlist from a text file (`playlist.txt`)  
- Remove newline characters from track names automatically  
- Store playlist in a *singly linked list*  
- Delete a track at a given position  
- Insert a new track at a specific position  
- Save the updated playlist to a new file (`playlist-out.txt`)  
- Print the playlist to the console  

## Files:
---------

- `main.c` – main program and file handling  
- `singly_linked_list.h` – definition of Node and linked list functions  
- `singly_linked_list.c` – implementation of linked list functions  


The program will:

- Load tracks from playlist.txt

- Print the loaded tracks

- Delete the 4th track

- Insert a new track "Tarkan – Şımarık 💋" at position 3

- Save the updated playlist to playlist-out.txt

Example:
--------

Input (playlist.txt):

Bad Guy – Billie Eilish 👽
Bohemian Rhapsody - Queen 🎤
Billie Jean – Michael Jackson 🕺
Rolling in the Deep – Adele 🌊
Smells Like Teen Spirit – Nirvana 🤘


Output (playlist-out.txt):

Bad Guy – Billie Eilish 👽
Bohemian Rhapsody - Queen 🎤
Billie Jean – Michael Jackson 🕺
Tarkan – Şımarık 💋
Rolling in the Deep – Adele 🌊

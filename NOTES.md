## MODELS ##

Song
---
Title : string
artist_id : integer
genre_id : integer

Artist
---
name : string

artist has many songs

Genre
---
name : string


genre has many songs
# Movie-Trailer-Website

####Purpose:
A program that builds a webpage that lists a selection of movies and info about them, and allows users to watch their trailers. Movies are imported form a file.

Trailers and posters are retrieved online from youtube and from the web.

####Setup and run the code:
run the python prog: `movie_trailer_website_project_1.py`
Additional resources files:
* `tomatoes_squeezer.py` - html renderer
* `media.py` - class definitions
* `css/, images/, js/` folders

Requires internet connection.

####user requirements:
User must provide a `movie_info.txt` file with the selected movies data.
Each movie info field is in a separate line. And exactly the following order:

1. Title
2. Storyline
3. Year
4. IMDB rating
5. PG UK
6. PG US
7. Cast
8. Director
9. Genre
10. Poster_link
11. Trailer_link

an empty line must be used to separate movies' data.

####Program output:
The program creates the `movie_trailer_website.html` page.

Also opens the page in the default browser.


####Future development goals - all help is welcome :)
######Page and navigation
* nav bar, allowing for movie sections or genres
* a text-simple list view of the titles

######functionalities 
I have a film library of about 300 titles. It would take a lot of time to gather all movie info manually...
* fetch online imdb rating and pg rating
* find and fetch online trailer and poster




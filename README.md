# Search Project 0

## Table of Contents
1. [Description and Requirements](#description-and-requirements)
2. [Preview](#preview)
   - [Google Search](#google-search)
   - [Google Image Search](#google-image-search)
   - [Google Advanced Search](#google-advanced-search)
3. [Installation](#installation)

## Description and Requirements
Design a front-end for:
- **Google Search**: A basic search interface that allows users to input queries and view search results.
- **Google Image Search**: An interface for users to search for images based on keywords.
- **Google Advanced Search**: A more detailed search interface allowing users to specify additional parameters for their searches.

All requirements can be viewed [here](https://cs50.harvard.edu/web/2020/projects/0/search/).

A live version of the project can be viewed [here](http://cs50search.pythonanywhere.com/).

## Preview

### Google Search
This section allows users to perform a basic search query and view a list of search results.
![Google Search](https://github.com/suman154/Search/assets/119277749/19432d63-24dc-4032-855c-5505a214088c)

### Google Image Search
This section provides an interface for users to search for images based on keywords.
![Google Image Search](https://github.com/suman154/Search/assets/119277749/2da85461-084d-4b1d-b5b9-951c864984ce)


### Google Advanced Search
This section allows users to perform more refined searches with additional parameters such as:
- Exact phrase
- Exclude words
- Site/domain
- File type
  
![Google Advanced Search](https://github.com/suman154/Search/assets/119277749/7242e63f-e229-4566-b6e8-46873433b210)


### Watch on YouTube
[Click link to Watch the video](https://youtu.be/Jrdb3VjbRu0?si=08lnBDclNj9hTX0r)


## Installation
To set up this project on your computer:

1. **Download this project**
   ```sh
   git clone https://github.com/suman154/Search.git
2. Install all necessary dependencies
   ```sh
   pip install -r requirements.txt
3. Make migrations
   ```sh
   python manage.py makemigrations
4. Migrate
   ```sh
   python manage.py migrate
5. Run the server
   ```sh
   python manage.py runserver

Special thanks to Brian and the CS50 team for their invaluable support.

# clip-quiz
Simple front-end for a clip-based music quiz

## How it works
Having found a site that makes clips of music available for quizzing purposes, we simply set up a couple of buttons
to allow the user to preview a song to guess what it is, and then play a longer clip with the title and artist displayed to confirm the answer.

The HTML/JavaScript, such as it is, is mine. The songs are from [quizmasters](https://quizmasters.biz/) and hosted by them so that if they decide they need to add or remove a song from the collection, our code will be out of date.

The song list in the code is a simple web scrape from the original list with some regex magic to turn it into an array
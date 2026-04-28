# odin-dynasties
Basic HTML page about the Chinese dynasties using semantic HTML

Using tags like `<header>`, `<main>`, `<section>`, and `<article>` helps search engines and screen readers understand the structure of your content, rather than just seeing a bunch of generic `<div>` containers.

## Why this is "Semantic":

    `<main>`: Tells the browser that this is the primary content unique to this page (not the sidebar or navigation).

    `<section>`: Groups related content (all the dynasties).

    `<article>`: Used for each dynasty because a description of a dynasty could technically stand alone as a complete piece of information.

    `<time>`: This is a specific semantic tag used to help machines parse dates and times correctly.

    `<header>` & `<footer>`: Clearly defines the introduction and the "fine print" of the document.

## Extra
I added datetime="-0206" to the `<time>` tags. In HTML, years before the year 1 are represented with a minus sign (though many parsers handle "BCE" text just fine, the attribute makes it official!).

## Further ideas for this website:
* Add more of the previous Dynasties mentioned in the Accented Cinema video
* Add a "media from the x dynasty" link in each article/card
* Add individual pages for each dynasty
* In each individual dynasty page add some representative pictures, a list of movies/tv shows/videos/books/manhua that depicts that time, and a recipe from that time or that is inspired by it.
* Have the page be available in English and easy Mandarin Chinese
* Code the page as much as possible with just HTMl and CSS and later implement JavaScript (progressive enhacement of special effects a la Soueidan)
* Add a "Sources" page where all of my sources are listed
* Once I learn to draw, make an SVG for each dynasty's card to represent each dynasty in a cute responsive way
* Once I learn how to draw, draw my own version of the Shiba Inu in black to use as a logo for my pages
* Add information from the MIT OCW Chinese Dynasties course


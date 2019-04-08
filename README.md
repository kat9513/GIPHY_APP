# GIPHY_APP

https://kat9513.github.io/GIPHY_APP/

An application that uses the GIPHY API to make a dynamic web page that populates with gifs of famous artists. 

Makes a call to the GIPHY API and uses JavaScript and jQuery to change the HTML on the site.

The application uses an array of artists to dynamically create buttons in the HTML.

When the user clicks on a button, the page grabs static, non-animated gif images from the GIPHY API and place them on the page along with their rating (PG, G, etc).

When the user clicks one of the still GIPHY images, the gif becomes animated.

A form on the page takes a value from the user input box and adds it into the `artists` array. A function call takes each artist in the array and remakes the buttons on the page, to include the user's input.

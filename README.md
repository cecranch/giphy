# giphy

This application uses the GIPHY API to make a dynamic web page that populates with gifs of the user's choice. 
The application calls the GIPHY API and uses JavaScript and jQuery to change the HTML of the site.

I created a free giphy account @ API: https://developers.giphy.com/docs/sdk

The first step was to create an array of strings, each one related to a topic, and saving it to a variable called 'topics'.

The app takes the topics in this array and create buttons in the HTML (using append).

When the user clicks on a button, the page should grab 10 static, non-animated gif images from the GIPHY API and place them on the page.
When the user clicks one of the still GIPHY images, the gif should animate. If the user clicks the gif again, it should stop playing.

Under every gif, the rating will display(PG, G, so on). This data is provided by the GIPHY API.

Lastly, a form takes a value from the user input box and adds it to the topics array. A function call  takes each topic in the array and remakes the buttons on the page.

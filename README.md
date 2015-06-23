This is a working demo of the autocomplete rails 4 gem. This is intended to address some issues I had with the original documentation and to bundle together a few improvements other developers have described.


For a new developer there might be a few slight hiccups following the documentation. 
For me, following the routes example in the offical documentation did not work. However following the format of Yoni in his blogpost, I was able to make the autocomplete work.

http://www.yoniweisbrod.com/autocomplete-magic-with-rails/

2. You'd also want to change the CSS such that the results show up better. This has also been incorporated in the demo (see food.css). I obtained this from a gist, forgive me I don't remember who the author is at the moment. The change will highlight and change the color of the suggestion menu items.

3. Another of Yoni's improvements, you can click on a suggested item to submit the search, instead of having to click on the submit button after clicking on the item.

4. The autocomplete form is implemented in the context of a search form with a simple scope search(see the food model and controller). 

The live demo can be seen here
https://rocky-thicket-9286.herokuapp.com/




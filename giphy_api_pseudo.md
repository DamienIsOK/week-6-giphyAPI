#1. A user clicks on any of the buttons that contain topics
	* This should be a function that creates buttons
	* Create array called 'topics'
	* Create a new variable button

-	For #1:
	var topics = ["hey arnold!", "steven universe", "animaniacs", "adventure time"];
	var b = $("<button>");

#2. When the button is clicked, 10 gifs of said topic appear on the page
	* Use a loop that appends a button for each string in the array	
	* The click event listener takes in the text of the button clicked
	* Create a variable called 'url' that holds the api url
	* Set the data attr to be topics[i]
	* Create variable called 'img' that holds the image
	* Use string interpolation to add the text to 'url'


- 	For #2:
	This should be a function
	$(buttonDiv).click(*run function that has appending loop*)
		for(i....
		b.attr("data-name", topics[i])
		b.text(topics[i])
		$("#buttonsDiv").append(b);
		)

#3. Under every gif, display rating
	* Create variable called 'rating' that holds the rating
	* When button clicked, add rating to the html

-	For #3:
	$(imagesDiv).html(<div> + image + </div> + <p> + rating + </p>)

#4. Clicking on a static gif animates it

#5. Clicking on an animated gif pauses it

#6. The text entered in the search field is appended to the page as a button
	* Create a variable for the value of the form input
	* Push the variable to the array
	* Replace the html of gifDiv with topics[i]

- For 6:
	var newButton = $("#button-input").val()
	newButton.push(topics);
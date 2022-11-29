## SDSS Computing Studies Python Assignment
### Flask!

Objectives:
* To make/retrieve flask requests from an html client

### HTML Clients
We will be making POST requests from an HTML document today.  We will need to do 2 things:
1. retrieve data from an HTML page
2. make a post request with javascript/jquery
3. retrieve the response and parse it for use in html

We will be looking at the client.html document today to help us do some of the basic commands.  We will also need to make use of html <input> tags to help us get user data

### How it Works
1. We create an html document with input tags.  Each input tag is best if it includes a name and/or id.  These should be unique identifiers for ease of use, but they don't have to be. This is on lines 57-62
2. We create an event handler for retrieving data from the html page and storing it into an object (the JS version of a Dictionary) This occurs on lines 13-21
3. We make an AJAX request (asynchronous javascript and XML) to our API endpoint. Note the inclusion of a number of different parameters! lines 22-43
4. Lines 27 to 37. We retrieve a response and try to parse it as a json object.  Try..Catch is the JS equivalent of try...except
5. We add it to our webpage by modifying an existing html container by ID (line 29)

## Assignment
In Assignment 010 you created a database for a veterinarian to track his clients.  Today we will be making an HTML document that will allow you to add client information to this database.  Refer back to your first SQL assignment.
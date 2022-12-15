# Fetch-API

To run, open index.html and run live server (VS code extension).
The html will run the script.js.
The script uses the fetch API to grab or post (or CRUD) data from online.
The fetch() function needs parameters: at minimum, the URL of an API.
If no other options are specified, the fetch() function will use the GET method.
However this code uses the POST method which is explicitely defined as a parameter.

Make sure to use JSON.stringify({object}) in order to post data.

Also note, fetch() never fails unless there is something wrong with the API or network.
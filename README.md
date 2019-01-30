# Udacity-Feed-reader-Testing
This is a project to test a feedReader code in Jasmine.js

## How to run the app locally
### Quick start
The simple way is to clone or download this git repository to your local machine. Locate to the repository folder and open index.html, at this point you should be able to see the feeds load.

 ### Run the app on server
clone this repository to your project folder
ensure you've installed **_node.js_**. For more details, please refer to [node.js](https://nodejs.org/en/)
locate to the project folder root and open it using any code editor, from there you can **install http-server** from the terminal using **npm** command line: _npm install -g http-server_ or you can download any **live server** extension from your code editor.
At this point you can visit http://127.0.0.1:3000 to view your app

## Test each feeds
create a loop that check if the allFeeds has a defined URL and it's not empty and to the same for the name

### Test "The Menu"
Make a test that will check if the menu is hidden or not and the script on app.js will work fine with the click() event.

### Test Suite "Initial Entries"
Make a test that ensures when the **loadFeed** function is called.

### Test Write "New Feed Selection"
Make a test that ensures when a new feed is loaded by the **loadFeed** function that the content actually changes.

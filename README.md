Things to grill in the summer

I'm a vegan and wanted to create an app that allows users to give me some ideas on what to grill. Since people can be trolls I elected to require users to have an account before they could post. The results would be displayed on the screen and also in my database that's connected to the project.

Link to Project:

How it's made:
Tech used: HTML, CSS, Javascript, Node, Express, Mongo, Embedded Javascript, Passport

To control user login and signup I used the npm passport. After that I used Node and Express to create a server that my browser can connect to. After ensuring my server was up and running I created a form in Embedded Javascript that the user can input info to. After that I linked my Mongo database to the form so when information gets entered it also gets stored into the database.

Optimizations:
I haven't learned it yet but when I do I want to add the ability to login with facebook.

Lessons Learned: This project enabled me to use my database to delete things which I never did before. In testing the app out I realized my delete button to delete messages wasn't working, after I got it working I was able to delete comments but I wasn't able to delete the comments I initially posted in my testing stages. The only way to get rid of them was to delete them from the database. I didn't even know that was possible before this project.

Examples:
Take a look at these couple examples that I have in my own portfolio:















## Installation

1. Clone repo
2. run `npm install`

## Usage

1. run `node server.js`
2. Navigate to `localhost:8000`

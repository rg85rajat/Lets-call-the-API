# Calling External API
Result Form

# Installation
Clone the repository git clone https://github.com/rg85rajat/terriblytinytales.git

Change the directory cd terriblytinytales

Run: node index.js

The server is running at localhost:3000

# Defining Code Components

![Capture3](https://user-images.githubusercontent.com/72291911/112749764-28833380-8fe2-11eb-8ae3-b9ece87acc90.JPG)

Fetching  Roll No query from the url (External API) and passing the roll numbers seperated by comma.

split() is used for splitting the Roll Numbers. 

![Capture](https://user-images.githubusercontent.com/72291911/112749950-3d13fb80-8fe3-11eb-900d-f0d9f9ee8d2d.JPG)

Consists of the form through which values to the API is passed.

![Capture](https://user-images.githubusercontent.com/72291911/112751219-63896500-8fea-11eb-894f-ee63f21086ae.JPG)

Passed String of Roll Numbers will be displayed in a tabular form

![Capture5](https://user-images.githubusercontent.com/72291911/112750225-fe7f4080-8fe4-11eb-9d39-17ef9bd6c110.JPG)

Front-End 

After Clicking on Submit, Button will change into please wait and depending on the time taken by external API page will ask to wait.

![Capture7](https://user-images.githubusercontent.com/72291911/112750242-1d7dd280-8fe5-11eb-9565-37ee54ce3e30.JPG)

Output of the test case: 5,6,9,12,18,20,25,30,32,36,37,38,40,42,45,47,49,50 

http://localhost:3000/testAPI?rollNo=5,6,9,12,18,20,25,30,32,36,37,38,40,42,45,47,49,50

Click Directly to view: https://terriblytinytale.herokuapp.com/testAPI?rollNo=5,6,9,12,18,20,25,30,32,36,37,38,40,42,45,47,49,50

![Capture4](https://user-images.githubusercontent.com/72291911/112750379-ed82ff00-8fe5-11eb-9c82-93e491733379.JPG)

Output of the testcase: 27

http://localhost:3000/testAPI?rollNo=27

https://terriblytinytale.herokuapp.com/testAPI?rollNo=27

# Libraries and Plugins
Node.JS

body-parser

express

node-fetch

nodemon

pug


# Hosted on Heroku
# Website
https://terriblytinytale.herokuapp.com/














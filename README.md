Architecture 
The types of frontend development used in this full stack project was Express HTML, JavaScript and a single page application. The Express HTML file was pretty easy to construct since it I got to use HandleBars. This was new for me, but self explanatory with the constant like use a {{ title }} function to update for all title pages. 

Functionality
When constructing the database, I initially used JSON, to format all of the records, which took some time. It was much easier to switch the backend to NoSQL MongoDB database, because it is a non-relational database that does not require an exact key value pair for every record; however, the body of our database had records that all had to equal true. 

The main difference between JavaScript and JSON, is that a JSON Object is used for data and has to be fed into a variable as a string, then parsed into JavaScript. 
There was numerous times where I had to factor code. Specifically in the coursework, some of the formatting was outdated which is to be expected, because your average program releases a new version at least every three months, and the instruction videos were from two years ago. This led me to refactor a large amount of functions, settings, and initialized variables. The one most notable was the jsonwebtoken. The format was import jsonwebtoken = require('jwt'), but the updated documentation recommended a full scope of setting it as const { expressjwt: expressJwt } = require('express-jwt'); function auth() to avoid a bug. 

Testing
Some methods required from requesting and retrieving API endpoints include the use of token authorization and authentication in Postman.

This project really helped me reach my goal of establishing a full stack project that I can constantly update and build on because I love traveling. This will probably be one of my main side projects that I work on throughout my career. I know these skills that include working hard, researching every possible avenue, and staying in contact with my mentor when all else fails. 

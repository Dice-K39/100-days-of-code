# 100 Days Of Code - Log

## Day 1: Apr 22, 2021

**Today's Progress**: Learned about update and delete on the CRUD operations for MongoDB.

**Thoughts:** I thought it was pretty easy to learn about the CRUD operations for MongoDB. It was pretty similar to the CRUD operations using SQLite on Rails.

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/tree/main/task-manager)

## Day 2: Apr 23, 2021

**Today's Progress**: Installed and used Mongoose to create models and validate data.

**Thoughts:** Very easy and straightforward to create models and validate data. I see similarities between how Mongoose and Rails validate data. Having fun learning new things and wanting more of it!

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/tree/main/task-manager)

## Day 3: Apr 24, 2021

**Today's Progress**: Recap on REST API. Also installed and used Postman to test endpoints for task app.

**Thoughts:** At first had problems with creating documents into mongodb but found out that I didn't start it up. REST API was a recap. Using mongoose and express, I inserted documents into mongodb database. Having fun learning new and old things.

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/tree/main/task-manager)

## Day 4: Apr 25, 2021

**Today's Progress**: In Node.js, used REST API to read documents from mongodb database. Also learned about promise chaining and its syntax.

**Thoughts:** REST API part was easy since I went through them so many times in class and projects. Promise chaining was something new to me and it made code look so much cleaner than nesting promises so many levels deep. I enjoy just programming!

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/tree/main/task-manager)

## Day 5: Apr 26, 2021

**Today's Progress**: Learned about async and await.

**Thoughts:** Async and await made the code cleaner because of less callbacks in the task app routes. I know that I can use these keywords to clean up my projects from school using promises. So much to refactoring to do, so little time!

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/blob/main/task-manager/src/index.js)

## Day 6: Apr 27, 2021

**Today's Progress**: Recap on the U and D of CRUD operation. Also separated route files in my task app.

**Thoughts:** The update as usual is complex. Will have to come back to the update operation to understand it more. It was nice to have separation of concerns for the routes because of how long the index file was getting on the task app.

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/blob/main/task-manager/)

## Day 7: Apr 28, 2021

**Today's Progress**: Used bcryptjs to hash passwords of users.

**Thoughts:** A recap from my Rails days except how to use in JavaScript. Also used the pre hook middlware to hash passwords before saving.

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/blob/main/task-manager/src/)

## Day 8: Apr 29, 2021

**Today's Progress**: Learned about JWT (JSON Web Token). Also disabled routes in my task app by using express middleware.

**Thoughts:** JWT authentication is pretty new to me. I am used to using HTTP cookies to authenticate users. Must delve deeper into JWT. I finally understand how middleware works with the use of express routes.

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/blob/main/task-manager/src/)

## Day 9: Apr 30, 2021

**Today's Progress**: Learned about accepting authentication tokens for creating and logging in users. Also learned about advanced Postman techniques such as setting environmental variables for the url. Also learned about logging out the user by clearing the authentication tokens.

**Thoughts:** Learning about accepting JWT authentication tokens was challenging. I am used to session cookies to authenticate. I see the benefit of using JWT authentication because these tokens are saved in the client side. Session cookies uses server memory so if many users logs in the server may slow down. Better techniques in Postman helped me streamline the process so that I don't have to do redundant tasks such as setting the url with minor differences for each REST route.

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/blob/main/task-manager/src/)

## Day 10: May 1, 2021

**Today's Progress**: Learned a little more about authenticating users with JWT.

**Thoughts:** Understanding authentication and authorization is important because of so much is riding on technology these days. I need to study more about authentication.

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/blob/main/task-manager/src/)

## Day 11: May 2, 2021

**Today's Progress**: Learned how to setup relationships in Node.js. With that, also setup task app to only display a user's tasks than displaying everyone's tasks. This lets the current user only modify their own tasks.

**Thoughts:** Setting up relationship in Node.js is confusing. Task belongs-to User relationship requires a property within the Task model and the User has-many Tasks relationship requires a virtual property to the User model (not in the curly braces of the User model but a separate property). The virtual property is only a reference to the task data that is stored in a separate collection.

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/blob/main/task-manager/src/)

## Day 12: May 3, 2021

**Today's Progress**: Learned how to put timestamps onto data that has been created. Also added options to filter, paginate, and sort data.

**Thoughts:** The way NodeJS add timestamps and filter, paginate, and sort reminds me how easy it was to do that in Rails. JavaScript feels a bit manual work but that makes it more worthwhile to program in JavaScript. It's fun!

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/blob/main/task-manager/src/)

## Day 13: May 4, 2021

**Today's Progress**: Used a new npm package called multer to upload files. Validated those files using regex.

**Thoughts:** Multer is easy to use to upload files.

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/blob/main/task-manager/src/)

## Day 14: May 5, 2021

**Today's Progress**: Learned how to handle express errors, adding images to user profiles in database instead of a folder in the project, fetching images, and using sharp to auto-crop and format an image.

**Thoughts:** Formatting an image is straightforward. I need to go through npm packages if I start making an app because of so much resources that is available to programmers.

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/blob/main/task-manager/src/)

## Day 15: May 6, 2021

**Today's Progress**: Learned about SendGrid and nodemailer. Sent welcome and cancelation emails to myself for creating and canceling accounts on my task app.

**Epilogue**: Had to mess with git because I pushed sensitive data to github. Took me awhile to figure it out and remove the data. Need to study git!

**Thoughts:** It was pretty exciting creating and sending emails to myself for account creation and cancelation for my task app. Bad that SendGrid had to temporarily restrict my account because of suspicious activity which is only using their service to learn about creating emails. At least I learned about nodemailer too.

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/blob/main/task-manager/src/)

## Day 16: May 7, 2021

**Today's Progress**: Learned how to use MongoDB Atlas and Compass so that I am able to host my task app on heroku.

**Thoughts:** Pushing to heroku is cumbersome because of how much more I have to do to get it hosted on the console. It is a good feeling that my app is in production on heroku.

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/blob/main/task-manager/src/)

## Day 17: May 8, 2021

**Today's Progress**: Installed jest and learned how to create test cases for example code. Also learned how to create asynchronous code tests.

**Thoughts:** Jest made creating test for code easy. I knew I needed to learn how to code tests for my code one day.

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/blob/main/task-manager/src/)

## Day 18: May 9, 2021

**Today's Progress**: Learned how to test express application using npm package called supertest. Also learned about jest lifecycle methods that runs before and after each test case.

**Thoughts:** Although I haven't tested my code through school, I am starting to like Jest because of how easy it is to use. I will have to learn more about it so that I can learn more advanced testing cases.

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/blob/main/task-manager/src/)

## Day 19: May 10, 2021

**Today's Progress**: Learned how to authenticate test user and how to assert a user. Also learned about mocking libraries.

**Thoughts:** Authentication is still a bit confusing but learning how to assert a user is useful because it means that the code is connecting to the database properly. Also mocking is useful because resources does not have to be wasted just to run test cases such as creating users which sends an email automatically to the user's email.

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/blob/main/task-manager/src/)

## Day 20: May 11, 2021

**Today's Progress**: Created test cases for task in my task app.

**Thoughts:** Testing with jest is getting simpler as I do more. Some parts I need to review but for the most part I think I will be able to test my code using jest.

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/blob/main/task-manager/src/)

## Day 21: May 12, 2021

**Today's Progress**: Created test cases for task app.

**Thoughts:** Took a break from regular course work and worked on extra test cases on my task app. Creating test cases is getting easier but the HTTP code I need to study.

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/blob/main/task-manager/src/)

## Day 22: May 13, 2021

**Today's Progress**: Started creating a chat app. Learned about WebSockets.

**Thoughts:**

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/blob/main/task-manager/src/)

## Day 23: May 14, 2021

**Today's Progress**: Learned how to send a message to all clients connected to server (testing using a couple of browser windows open and printing message to console).

**Thoughts:** So cool that a message is sent to all clients connected to server! Oddly excited lol.

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/tree/main/chat-app)

## Day 24: May 15, 2021

**Today's Progress**: Learned how to broadcast messages, sharing location, and acknowledging data has been received.

**Thoughts:** Socket.io is easy to learn and oddly fun to code with.

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/tree/main/chat-app)

## Day 25: May 16, 2021

**Today's Progress**: Made some user interface enhancements to my chat app.

**Thoughts:** Not much of a progress today. Had so much to do before starting.

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/tree/main/chat-app)

## Day 26: May 17, 2021

**Today's Progress**: Learned how to use mustache.

**Thoughts:** Mustache was easy to use.

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/tree/main/chat-app)

## Day 27: May 18, 2021

**Today's Progress**: Learned how to create rooms using socket.io.

**Thoughts:** I am learning so many new things from the Node.js course from Udemy. I just hope I can retain the knowledge and use it at a job.

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/tree/main/chat-app)

## Day 28: May 19, 2021

**Today's Progress**: Learned how to store usernames, retrieving them, and removing them for my chat app.

**Thoughts:** Basic array manipulation. Easy!

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/tree/main/chat-app)

## Day 29: May 20, 2021

**Today's Progress**: Finished chat app. Added functionality of tracking users joining and leaving, sending messages to a room, rendering a user list and room name in sidebar, and autoscroll feature when user is viewing the latest message.

**Thoughts:** I had fun creating the chat app. I was more excited creating this than the other apps. Also pushed to Heroku and works just as it works locally.

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/tree/main/chat-app)

## Day 30: May 21, 2021

**Today's Progress**: Started on iOS Development course on Udemy.

**Thoughts:** Been contemplating on what to learn next. I thought about the general idea why I want to code. The only reason is that I love to code. Then I thought about what specific technology I want to code for and I realized I love to do mobile development. It is mostly because of a game I started playing a few years ago which had graphics on par with a desktop computer. So I decided on doing iOS development and once done go into Unity with C# development.

## Day 31: May 22, 2021

**Today's Progress**: Did a walkthrough of creating a simple iOS app.

**Thoughts:** Very simple to do. I think I have done this when I was learning Visual Basic a long time ago.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/I%20am%20Rich)

## Day 32: May 23, 2021

**Today's Progress**: Started coding a cloned app.

**Thoughts:** Still new to the way Swift is coded. Excited!

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/Dicee-iOS13)

## Day 33: May 24, 2021

**Today's Progress**: Completed cloned app.

**Thoughts:** Able to make a simple app that shows two die with random numbers. Randomization and syntax was simple. Nothing out of the way of my experience with other languages.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/Dicee-iOS13)

## Day 34: May 25, 2021

**Today's Progress**: Cloned another app and completed it.

**Thoughts:** Cloned another repo and worked on it. Had an error but fixed it by relinking the UI element to the code that it belongs to. Still new but this is getting interesting!

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/Magic-8-Ball-iOS1)

## Day 35: May 26, 2021

**Today's Progress**: Learned about auto layout and responsive UI.

**Thoughts:** Getting the layout to be what you want is pretty hard. Must work on it!

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/AutoLayout-iOS13)

## Day 36: May 27, 2021

**Today's Progress**: Created functions with arguments in Swift.

**Thoughts:** I thought creating variables was the same as other languages but when it was time to create argument variables, I was wrong. The variable name comes first and then a colon and then the data type. Hard to break my habit of creating a variable with data type in the front of the variable name.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/Xylophone-iOS13)

## Day 37: May 28, 2021

**Today's Progress**: Finished an app where it counts down to 0. Learned about optionals and Timer.

**Thoughts:** Very tedious to create a Timer. The selector property does not take a method with an argument so the argument had to be set as a global variable and changed through the method.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/EggTimer-iOS13)

## Day 38: May 29, 2021

**Today's Progress**: Learned how to create structs and functions with return types and recap on MVC design pattern.

**Thoughts:** MVC design pattern was a recap since Ruby on Rails was all about the pattern. Creating structs and functions with return types was somewhat new to me since I started programming from C++. Structs was similar to C++ but returning a value from a function was a bit new. Use a -> with what data type it is returning.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/Quizzler-iOS13)

## Day 39: May 30, 2021

**Today's Progress**: Working on a challenge with MVC design pattern with a cloned project in Swift.

**Thoughts:** I still have some hiccups on how to code in the MVC pattern but I am understanding it little by little.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/Destini-iOS13)

## Day 40: May 31, 2021

**Today's Progress**: Completed challenge from yesterday about MVC design pattern.

**Thoughts:** Practicing the MVC design pattern helps me understand the concept better. I know this will help me retain the knowledge better and be a better programmer.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/Destini-iOS13)

## Day 41: June 1, 2021

**Today's Progress**: Cloned and completed majority of a Swift project that calculates the user's BMI from two sliders, one for height and another for weight.

**Thoughts:** Retrieving values is becoming easier as I practice doing them in Swift. Everything is just practice!

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/BMI-Calculator-iOS13)

## Day 42: June 2, 2021

**Today's Progress**: Learned about how to create UI by code and using segues to navigate multi-screen apps.

**Thoughts:** Segues is a new concept that I need to review. Listening to the instructor makes it hard to make any sense.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/BMI-Calculator-iOS13)

## Day 43: June 3, 2021

**Today's Progress**: Learned more about optionals since JavaScript.

**Thoughts:** The concept of optionals is easy to understand but putting it into practice is tough. Another thing I have to work on.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/BMI-Calculator-iOS13)

## Day 44: June 4, 2021

**Today's Progress**: Cloned a tip calculating app project and created IBActions and IBOutlets for calculator and results screen. Also button functionality for tip labels.

**Thoughts:** General setup is pretty easy, linking outlets and actions. Coding the functionality gets a little bit tricky but starting to understand from me trying and viewing how the instructor done it.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/Tipsy-iOS13)

## Day 45: June 5, 2021

**Today's Progress**: Completed tip calculating app project.

**Thoughts:** Segues still give me problems but understanding it a bit more. Still need to work on it

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/Tipsy-iOS13)

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

**Thoughts:** Segues still give me problems but understanding it a bit more. Still need to work on it.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/Tipsy-iOS13)

## Day 46: June 6, 2021

**Today's Progress**: Cloned a new project for lesson and learned about dark mode and vector assets.

**Thoughts:** Spent majority of time on fixing my git repository so not much progress in Swift. I did learn plenty of new things like how XCode handles dark mode and using vector assets.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Clima-iOS13)

## Day 47: June 7, 2021

**Today's Progress**: Learned about delegate methods and protocols.

**Thoughts:** Swift protocols are like Java interface. Need to implement if given to a class.

**Link to work:** [Project GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Clima-iOS13)

[Protocol Demo](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Protocol%20Demo)

## Day 48: June 8, 2021

**Today's Progress**: Learned more about protocols and delegates.

**Thoughts:** Protocols and delegates goes hand in hand. Delegate classes receives the call from a class to perform a method that needs to be implemented (protocol).

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Protocols%20and%20Delagates)

## Day 49: June 9, 2021

**Today's Progress**: Started using URLSession to fetch data from OpenWeather API.

**Thoughts:** Using URLSession is different from using fetch in JavaScript. Need to create a URLSession and use dataTask to handle the incoming data from the API. resume() will start the task.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Clima-iOS13)

## Day 50: June 10, 2021

**Today's Progress**: Learned about Swift closures.

**Thoughts:** Closures seems like a straightforward concept. An anonymous function that is the last argument in a function's parameter list. Seems different than JavaScript closure. Need to look into it.

## Day 51: June 11, 2021

**Today's Progress**: Decoded JSON from OpenWeather API in Swift.

**Thoughts:** Decoding JSON is a bit tedious in Swift because a struct need to be created to decode the JSON properly.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Clima-iOS13)

## Day 52: June 12, 2021

**Today's Progress**: Created WeatherModel and learned about computed properties.

**Thoughts:** The WeatherModel is a struct that stores the weather information from the API. A computed property called conditionName will compute the id from the API and return the proper image for the weather.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Clima-iOS13)

## Day 53: June 13, 2021

**Today's Progress**: Found an example of typealias and practice protocols and delegates.

**Thoughts:** Protocols and delegates is still challenging to me. Thinking of redoing this section to understand the concept fully.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Clima-iOS13)

## Day 54: June 14, 2021

**Today's Progress**: Reviewed UITextField.

**Thoughts:** Decided to start reviewing a few topics that I vaguely understand.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Clima-iOS13)

## Day 55: June 15, 2021

**Today's Progress**: Reviewed Swift protocols.

**Thoughts:** Protocols is the same as Java interface. It is abstract, contains abstract properties and methods, a class can implement multiple protocols, and any class using the protocol has to define the method in the class that is using it.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Clima-iOS13)

## Day 56: June 16, 2021

**Today's Progress**: Reviewed the delegate design pattern.

**Thoughts:** The delegate design pattern is where a class implements a protocol that is used in an element such as an UITextField. Any class that implements the protocol written under that element can use that element for any purpose that the app is for.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Clima-iOS13)

## Day 57: June 17, 2021

**Today's Progress**: Reviewed how protocols and delegates are used.

**Thoughts:** The class that designates itself as the delegate will do the biding of the class that calls the delegate. The calling class does not care about who is doing the action.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Clima-iOS13)

## Day 58: June 18, 2021

**Today's Progress**: Reviewed URLSession.

**Thoughts:** Steps to requesting data from an API is to create a url, create a URLSession, give the session a task, and then start the task. The steps of this is littered with optional chaining because one part of the step may not exist.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Clima-iOS13)

## Day 59: June 19, 2021

**Today's Progress**: Reviewed closures.

**Thoughts:** Closures are functions that are passed into a function as input. I am amazed that a multi-lined function can be reduced to a one line call to a function using the closure as input.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Closures.playground)

## Day 60: June 20, 2021

**Today's Progress**: Reviewed how to decode JSON to Swift Objects.

**Thoughts:** I finally understand why I created structs for JSON. Swift does not have a way to decode JSON directly so I have to create structs to unpack the JSON objects into Swift objects. Tedious indeed.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Clima-iOS13)

## Day 61: June 21, 2021

**Today's Progress**: Reviewed computed properties.

**Thoughts:** Computed properties are always changing so must be declared using the var keyword. AFter that, it is the same as declaring a variable except that it has a sort of function body for computation purposes.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Clima-iOS13)

## Day 62: June 22, 2021

**Today's Progress**: Learned that Swift has an external and internal parameter names.

**Thoughts:** External parameter names are used when calling the function. Internal parameter names are used inside the function with the passed in data as the internal parameter name. Another option in calling the function is that the external parameter name can be completely omitted if the function itself is defined with an underscore before the internal parameter name (func myFunc(_ name: Type)).

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Clima-iOS13)

## Day 63: June 23, 2021

**Today's Progress**: Learned about Swift error handling and updating UI with DispatchQueue.

**Thoughts:** Used protocol and delegate to error handle. Used DispatchQueue to update UI. Updating UI is not possible in a completion handler because data is not available to update until it came back from the server.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Clima-iOS13)

## Day 64: June 24, 2021

**Today's Progress**: Learned about extensions.

**Thoughts:** Extensions helps in implementing functionality after an app is rolled off to production. Also helps in giving any protocol implementing struct or class a default implementation.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Extensions.playground)

## Day 65: June 25, 2021

**Today's Progress**: Learned about CoreLocation in Swift.

**Thoughts:** Process of retrieving location data is done by importing CoreLocation.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Clima-iOS13)

## Day 66: June 26, 2021

**Today's Progress**: Fixed bugs in weather app.

**Thoughts:** Kept on getting the weather of London even when typing in a different location. Problem was the url contained a query for London so the returned data was always London.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Clima-iOS13)

## Day 67: June 27, 2021

**Today's Progress**: Started a project that fetch bitcoin price from coinapi.io.

**Thoughts:** Able to fetch data from the api. Also found a way to not enter API key everytime I want to test the code (same as every other languange): assign API key to a variable and put in a separate file and then use .gitignore. Use the variable instead of the actual key so that it will remove the mundane task of placing and removing API key to test code.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/ByteCoin-iOS13/ByteCoin)

## Day 68: June 28, 2021

**Today's Progress**: Completed bitcoin app project.

**Thoughts:** Not bad but I still had some trouble with how to parse the data into a Swift object.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/ByteCoin-iOS13/ByteCoin)

## Day 69: June 29, 2021

**Today's Progress**: Cloned new project and started with adding a navigation controller and segues to each page.

**Thoughts:** Navigation controller added a back button on each page except the first page of app. Also added segues for path to each page.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Flash-Chat-iOS13)

## Day 70: June 30, 2021

**Today's Progress**: Installed Cocoapods and fixed errors.

**Thoughts:** Installed Cocoapods and fixed errors pertaining to versions.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Flash-Chat-iOS13)

## Day 71: July 1, 2021

**Today's Progress**: Made CLTypingLabel work and installed Firebase.

**Thoughts:** Feels good that one line of code makes CLTypingLabel work instead of having over 10 lines of code for the same functionality. Firebase installation takes time.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Flash-Chat-iOS13)

## Day 72: July 2, 2021

**Today's Progress**: Learned how to use Firebase to sign up and log in user.

**Thoughts:** Firebase was easy to implement into the project. Google described the steps in a simple way that first time users would understand how to implement it.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Flash-Chat-iOS13)

## Day 73: July 3, 2021

**Today's Progress**: Finished with logout function on Swift app and redirects user all the way back to the title screen.

**Thoughts:** Able to finish logout function with ease with Google's documentation. Logout function will redirect user to the title screen of the app.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Flash-Chat-iOS13)

## Day 74: July 4, 2021

**Today's Progress**: Used a file to store each string used in Swift app to a variable.

**Thoughts:** Using a file to store each non-changing string to a variable would reduce misspelling mistakes that may waste time debugging.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Flash-Chat-iOS13)

## Day 75: July 5, 2021

**Today's Progress**: Used an UITableView and customized the way message cells looks with a xib file.

**Thoughts:** UITableView is a container for cells that shows certain data in a table. It will be used to display cells that have messages for the user in the chat app. Also used a xib file to customize how a cell is displayed so that it would look much like an authentic chat app.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Flash-Chat-iOS13)

## Day 76: July 6, 2021

**Today's Progress**: Learned about different keywords for typecasting (as, as?, as!, is).

**Thoughts:** is keyword is for comparing, as? and as! keywords are for downcasting from superclass to subclass, and as keyword is for upcasting from subclass to superclass.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Class.playground)

## Day 77: July 7, 2021

**Today's Progress**: Created a Firestore database and implemented code that sends to the database.

**Thoughts:** With the documentation's help, I was able to implement the code to send data from the chat app to Firebase database. As always, easy to do.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Flash-Chat-iOS13)

## Day 78: July 8, 2021

**Today's Progress**: Learned how to retrieve data from Firestore and update messages on the fly by listening for changes.

**Thoughts:** Retrieving data from the FIrestore was full of optionals. Just to retrieve data, had to go 3 levels deep in optionals. Used optional binding. It is understandable but just feels messy.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Flash-Chat-iOS13)

## Day 79: July 9, 2021

**Today's Progress**: Sorted data coming from Firestore and used another package using Swift Package Manager.

**Thoughts:** Data in Firestore is sorted by collection id. To have it sorted, used date that was based on when each data was sent to the database. When retrieving the data, the app sorts data by its date.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Flash-Chat-iOS13)

## Day 80: July 10, 2021

**Today's Progress**: Finished with UI on the chat app.

**Thoughts:** Worked on UI improvements such as scrolling to the latest message, differentiating from sender and receipient of a message by coloring, emptying text bar once send is pressed, and showing the navigation bar in appropriate places. Touched on lifecycle methods.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Flash-Chat-iOS13)

## Day 81: July 11, 2021

**Today's Progress**: Learned more about ViewController and App lifecycle methods.

**Thoughts:** Lifecycle methods runs in the background unless explicitly overrided with custom code in the body. Useful for doing things before, during, after, and being destroyed.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/AppLifecycle)

## Day 82: July 12, 2021

**Today's Progress**: Learned about shortcuts that can be used in terminal.

**Thoughts:** Nice to know that there are shortcuts that can be used to quickly do what I need to do in terminal. I usually use the keyboard to do what I need to do. Didn't know that Alt plus the mouse I can click anywhere on the command text to go to that point.

## Day 83: July 13, 2021

**Today's Progress**: Learned about SwiftUI.

**Thoughts:** SwiftUI made creating an app simpler by just click and dragging elements from the Object Library.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/I%20Am%20Rich%202)

## Day 84: July 14, 2021

**Today's Progress**: Used SwiftUI to make a demo business card app using complex designs and layout.

**Thoughts:** Less code and a complex design app. Very neat.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Dice-KCard)

## Day 85: July 15, 2021

**Today's Progress**: Used SwiftUI to create an app with functionality.

**Thoughts:** The laziness of programmers are showing using SwiftUI. Apps can be easily created. The only hard part is designing the looks of the app.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Dicee-SwiftUI)

## Day 86: July 16, 2021

**Today's Progress**: Used SwiftUI to create a news app that uses an API from algolia.com.

**Thoughts:** Learning the basics was fundamental in learning SwiftUI. If I started on SwiftUI, I would have given up quickly if I had to do the same thing through writing pages of code to do the same thing.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/H4XOR%20News)

## Day 87: July 17, 2021

**Today's Progress**: Started on a to do list app.

**Thoughts:** Getting used to UITableViewController. Forgotten some methods used to display data in a table.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Todoey-iOS13)

## Day 88: July 18, 2021

**Today's Progress**: Learned about UserDefaults.

**Thoughts:** UserDefaults is not a database. It is a place that saves, for example, configuration settings for apps. Do not abuse as a database or the app will slowdown.

**Link to work:** [App](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Todoey-iOS13)
[UserDefaults](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/UserDefaults.playground)

## Day 89: July 19, 2021

**Today's Progress**: Learned about singletons.

**Thoughts:** Only creates one instance per app run.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Singleton.playground)

## Day 90: July 20, 2021

**Today's Progress**: Created a data model to easily create todo list tasks and used ternary operator to check and uncheck tasks.

**Thoughts:** Nothing too hard. Using an assignment operator for the condition threw me off guard though.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Todoey-iOS13)

## Day 91: July 21, 2021

**Today's Progress**: Used NSCoder to save and load data.

**Thoughts:** Better than using UserDefaults.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Todoey-iOS13)

## Day 92: July 22, 2021

**Today's Progress**: Setup to-do app to use CoreData.

**Thoughts:** CoreData interfaces with SQLite, which I have used in the past with Rails. Would be nice to get some brush ups with SQLite.

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Todoey-iOS13)

## Day 93: July 23, 2021

**Today's Progress**: Went through CRUD using CoreData.

**Thoughts:** Learning how to do the CRUD operations using CoreData was simple enough. 

**Link to work:** [GitHub](https://github.com/Dice-K39/Swift/tree/main/iOS%20%26%20Swift%20-%20The%20Complete%20iOS%20App%20Development%20Bootcamp/Projects/Todoey-iOS13)

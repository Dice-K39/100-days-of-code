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

**Thoughts:** It was pretty exciting creating and sending emails to myself for account creation and cancelation for my task app. Bad that SendGrid had to temporarily restrict my account because of suspicious activity which is only using their service to learn about creating emails. At least I learned about nodemailer too.

**Link to work:** [GitHub](https://github.com/Dice-K39/Node.js/blob/main/task-manager/src/)

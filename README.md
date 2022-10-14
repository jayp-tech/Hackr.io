# Hackr.io


## Aim of the project

- Target millions of potentials users to use and engage with our app

- Users could be anyone.. who finds a course, video or articles online... likes it and wants to share

- The links they share will also be available in their dashboard for update/delete

- A user could be someone who is a content creator like me... instructors, youtubers, blog and tutorial writers, book authors etc

- Users will signup/signin to our app to post/share/like the links/urls

- Users will do this to get free traffic... to get people's attention... sharing links for free

## Overview of the project

- Login/Register System

- Need a MongoDB that scale infinitely. We will use Mongo Atlas for this requirement.

- Need a massive storage system that scale infinitely to store user uploaded image files. We will use AWS S3 (Simple Storage Service) for this requirement.

- You never have to worry about how to manage millions of user uploaded files... let AWS take care of that! S3 pricing is the lowest in the market for storing infinite amount of data that is readily available worldwide throughout AWS data centers globally.

- Need robust email service for sending emails for hundreds of thousands of users. We will use AWS SES (Simple Email Service) for this requirement.

- You never have to worry about how to send email to millions and pay higher price ... let AWS take care of that! their rate of SES is the lowest in the market.

- We have used using AWS EC2 (Elastic Compute Cloud) for hosting our backend NodeJS API and React/Next JS frontend, all within one instance.

- Keep the cost as low as possible by using AWS services for storage, email and hosting.

- The biggest issues of scaling web apps are storage and database scaling. That part will be handled by AWS. So we as a developer don't have to worry.Our aim is to enable just 1 or 2 developer to maintain the entire project and continuously grow in future.

## Clean simple and easy to maintain project architecture

- Extremely simple architecture that is easy to maintain and scale

- Separate backend API and frontend built with react/nextjs for easy development, code maintenance and deployment

- Keep the frontend as simple as possible

- Scenario 1 > You create a page in react to do certain task. For example it fetch the data from your API/Server and put that data on the web page for user to see. Job done.

- Scenario 2 > You create admin page to create a new post. For example to post the data to your API/Server and show the returned response of either success or error. Job done.

- Keep the backend API as simple as possible

- Scenario 1 > You have a GET route. For example '/api/posts'. You will receive a request from react/frontend for getting all posts from database.

- You pass this request to a controller method. Controller method/function will make a query to database, get all posts and return back to react/frontend. Job done.

- Scenario 2 > You have a POST route. For example '/api/create/post'. You will receive data from react/frontend to create a new post. You pass that data to a controller method.

- Controller method/function will save that data in database and return the success response, which will be sent back to react. Job done.

- This is the logic of our app or basically any web app out there. The cycle of requests/responses. Request from frontend, Response from server.


## Project Images


<img width="500" alt="image" src="https://user-images.githubusercontent.com/82361158/195748312-6a2c71ec-6adc-4a02-8b88-8d3bf99fad0e.png">
<img width="500" alt="image" src="https://user-images.githubusercontent.com/82361158/195748705-4899d1e7-55ed-4ebe-afc1-57edbbdcfebb.png">
<img width="500" alt="image" src="https://user-images.githubusercontent.com/82361158/195749365-1914d7f0-8423-4c83-a6d8-3d450bef211e.png">
<img width="500" alt="image" src="https://user-images.githubusercontent.com/82361158/195749416-bcfbdfc5-68d9-4a40-9864-62258ae4f715.png">


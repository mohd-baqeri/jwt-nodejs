# jwt-nodejs

We have two separate servers:
  1. For Authentication & Authorization (localhost:4000)
      - npm run authDevStart
      - npm run devStart
  3. For Viewing the Posts (localhost:3000)

The project includes a file called: request.rest that you can test the project with...

in VSCode download an extension called REST CLIENT for testing your request.rest file

Create a .env file and put these values in that:
- ACCESS_SECRET_TOKEN=myAccessToken
- REFRESH_SECRET_TOKEN=myRefreshToken

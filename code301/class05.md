## Heroku
Heroku is a cloud platform as a service supporting several programming languages. One of the first cloud platforms, Heroku has been in development since June 2007, when it supported only the Ruby programming language, but now supports Java, Node.js, Scala, Clojure, Python, PHP, and Go.

### Set up
heroku login
This command opens your web browser to the Heroku login page. If your browser is already logged in to Heroku, simply click the Log in button displayed on the page.


- node --version
v12.20.0



- npm --version
7.5.3


### Prepare the app
git clone https://github.com/heroku/node-js-getting-started.git
cd node-js-getting-started


- Deploy the app
heroku create

- git push heroku master
heroku ps:scale web=1

- heroku open
View logs
heroku logs --tail

- Create a server
we will create a file called server.js with the following code:
node server.js
Make it worldwide
Works fine. But it works locally. WWW is for "World Wide Web" and we will turn your local server into a world wide server.

- We'll use Heroku cloud application platform for this. Heroku is a cloud platform as a service

- It allows you to deploy your web server, so everyone could see how awesome you are as a web developer.
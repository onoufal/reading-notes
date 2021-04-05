# Node.js & Heroku

* Node.js is an open source, cross-platform runtime environment, which allows you to build server-side and networking applications.

## Heroku Setup

### Instaling
1. Install the Heroku Command Line Interface (CLI)

2. Use the heroku login command to log in to the Heroku CLI.

### Prepare the app

1. To clone a local version of the sample application that you can then deploy to Heroku, execute the following commands in your local command shell or terminal:

```bash
$ git clone https://github.com/heroku/node-js-getting-started.git
$ cd node-js-getting-started
```

### Deploy the app

1. Create an app on Heroku, which prepares Heroku to receive your source code.
`heroku create`.

2. Now deploy your code:
`git push heroku main`

3. open the website 
`heroku open`

### View logs

1. View information about your running app using one of the logging commands. `heroku logs --tail`

### Define a Procfile

`web: npm start`

### Scale the app
1. You can check how many dynos are running using the ps command: `heroku ps`

2. Scale the number of web dynos to one:
`heroku ps:scale web=1`

### Declare app dependencies
1. you can create `package.json` by running `npm init --yes`

2. preparing your system for running the app locally:
`npm install`


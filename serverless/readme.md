# Running a Serverless App

**Step 1:** Go to Katacoda

`https://katacoda.com/courses/ubuntu/playground`

**Step 2:** Install the Serverless CLI

`npm install serverless --global`

**Step 3:** Login

You'll be redirected to the serverless.com website to enter your access credentials

`serverless login`

**Step 4:** Create your app

`serverless --org reselbob --app my-cool-app`

You'll get a message:

`Serverless: No project detected. Do you want to create a new one? (Y/n)`

Answer, `Y`

`cd my-cool-app`

*Step 5:** Deploy your app

`serverless deploy`

# Express Boilerplate!

This is a boilerplate project used for starting new express servers.

## Set up

Complete the following steps to start a new project (NEW-PROJECT-NAME):

1. Clone this repository to your local machine `git clone BOILERPLATE-REPO-URL NEW-PROJECT-NAME`
2. `cd` into the cloned repository
3. Make a fresh start of the git history for this project with `rm -rf .git && git init`
4. Install the node dependencies `npm i`
5. Move the example Environment file to `.env` that will be ignored by git and read by the express server `mv example.env .env`
6. Edit the contents of the `package.json` to use `"name": "NEW-PROJECT-NAME"` instead of `"name": "express-boilerplate",`

### Abridged version: 
1. Pick a project name, `PROJECT-NAME-HERE`
2. `projectname=PROJECT-NAME-HERE && git clone git@github.com:jamesjenkinsjr/express-boilerplate.git $projectname && cd $_ && rm -rf .git && git init && npm i && mv example.env .env && vim package.json && git add -A && git commit -m "initial server commit"` (NOTE: You will be prompted to use vim to edit package.json project name)

## Scripts

Start the application `npm start`

Start nodemon for the application `npm run dev`

Run the tests (mocha/chai) `npm test`

## Deploying

When your new project is ready for deployment, add a new Heroku application with `heroku create`. This will make a new git remote called "heroku" and you can then `npm run deploy` which will push to this remote's master branch.

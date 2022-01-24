# starting_react
tic-tac-toe game tutorial on react website

First commit for React on github.

Completing the tutorial on https://reactjs.org/tutorial/tutorial.html#setup-for-the-tutorial

This link was useful for learning how to push using PAT:
https://techglimpse.com/git-push-github-token-based-passwordless/

Make sure to npm start in the directory.
Reference below if npm start is causing problems.
https://stackoverflow.com/questions/55932106/react-missing-script-start

Namely (for starting a new app):
npm uninstall -g create-react-app
sudo npm install -g npm@latest
npx create-react-app yout-app-name


Git steps:
git add -A
git commit -m "Comment"
git push https://TOKEN_HERE@github.com/sandole/starting_react.git

Git tools:
git status
git log

To kill process on port 3000 (npm already running) first find PID then kill:
sudo lsof -i :3000
kill -9 <PID>


1. I am gonna take notes here of certain actions and techniques I take
to make this new version of the page.
2. I will include my command-line commands.

/* ran this command to install Sass for node
3. npm install node-sass --save-dev
*/

/* Ran this command to install live-server for live-updates
4.npm install live-server --save-dev
*/

/* -this package is similar to the "concurrently" npm package
5. npm install npm-run-all --save-dev
*/

/*
6. Copied these npm commands into my package.json
"scripts": {
  "watch:sass": "node-sass sass/main.scss css/style.css -w",
  "devserver": "live-server",
  "start": "npm-run-all --parallel devserver watch:sass",
*/
Note: 1st will update sass-files on changes, 2nd will run live-server, 3rd runs them in parallel kinda like concurrently


7. I will worry about things like compression and prefixing later.

8. Created a SASS directory with a main.scss and create index.html and css/style.css

9. lets add a CSS reset to all the html. Let's also use Open sans again.

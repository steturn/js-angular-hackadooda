#JS/Angular Hackadooda

## Eyup!
This is an example 'Todo' app to help you get starting with NodeJS, AngularJS, Common JS JavaScript and using GitHub.

## Getting Started
1. Install [NodeJS](http://nodejs.org)
2. Clone this repository `git clone https://github.com/CascadeHR/js-angular-hackadooda.git`
3. Install the dependencies `cd js-angular-hackadooda && npm install`
4. Work through [these issues](https://github.com/CascadeHR/js-angular-hackadooda/issues).

To resolve an issue do the following:

1. Fork the repository using the fork button at the top right of the repository main screen.
2. Pull the repository down, fix the issue and commit the code in git.
3. Push the code up to GitHub, this should then show a button on the main screen of your forked repo that allows you to submit a pull request.
4. Submit the pull request. You can refrence the issue you are fixing by saying 'Fixes #{issue number}' in your comment.
5. Me or Scoop will then review the work and merge it or or suggest some changes in the comments.

### Running / Building
- Run the application: `npm start`, then open a browser and go to http://localhost:8888
- Build the application: `npm run build`
- Test and lint the application: `npm run test`
- Watch the files and build on any changes: `npm run watch`

### Additional Info
- The Angular JavaScript code is in the `lib` folder.
- The code is written using CommonJS
    - a file is representative of a module
    - `require('../path/to/my/code')` is how to pull in other modules of code
    - `module.exports = function () { ... }` is how you expose code in a module
    - http://webpack.github.io/docs/commonjs.html
- CSS is done using SASS in the `sass` folder, for the most part this is just the same as CSS so you don't need to wory too much
    - http://sass-lang.com/guide

# Plant babies!

Is an exploration to deploying seedling plants onto the web (i.e. using github actions to facilitate a continous integration pipeline).
This repository contains some github workflows which will 
- Trigger a build of the app every time ´main´ is pushed to
- Store the built assets and commit them to the ´website-build´ when  there are changes

On Netlify we then setup a site which will montior the ´website-build´ branch, and deploy the contents when a commit is pushed.

## Roadmap of features
- [x] Create basic React app
- [x] Setup GitHub actions to build the site on changes to main
- [x] Upload production assets to this repo & test with Netlify
- [ ] Run react's tests as part of the build pipeline
- [ ] Integrate data stored in a separate repository
- [ ] Run the results though a static site generator

# The underlying react app

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

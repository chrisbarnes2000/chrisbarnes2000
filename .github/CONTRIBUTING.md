# **Contributing.md** needs to be updated by the **`YOUR-ORGANIZATION`**


<!-- 
    # Contributing to YOUR-ORGANIZATION

    ## How to contribute

    You can contribute to Minerva Facilities in various ways, including:

    - [Reporting bugs or issues](https://github.com/YOUR-ORGANIZATION/YOUR-REPO/issues/new) on GitHub. Please make sure to include fill in all the details in the issue template to make sure the issue can be addressed as quickly as possible.
    <!-- - [Submitting improvements to the documentation](). Updates, enhancements, new guides, spelling fixes... ->
    <!-- - Helping other people on the [forums](). ->
    - Looking at existing [issues](https://github.com/YOUR-ORGANIZATION/YOUR-REPO/issues) and adding more information, particularly helping to reproduce the issues.
    - [Submitting a pull request](https://github.com/YOUR-ORGANIZATION/YOUR-REPO/blob/master/CONTRIBUTING.md#submitting-a-pull-request) with a bug fix or an improvement.

    <!-- ### Branches

The `master` branch of the repository should be kept releasable at any time. This way we can continuously deploy fixes and improvements without costly managing of different branches and issues will be noticed and fixed quickly. This also ensures other contributors can check out the latest version from GitHub and work on it with minimal disruption from other features in progress.

Keeping the `master` releasable means that changes merged to it need to be:

<!-- - **Backwards compatible**: Expo CLI should work with every currently supported Expo SDK version. If the code you're adding depends on a feature only present in newer or unreleased SDK versions, it needs to check which SDK version is being used and not assume the latest version is being used. ->
- **Non-breaking**: If code that is unreleasable or fails the test suite ends up in master, it should be reverted.
- **Tested**: Always include a test plan in pull requests. Do not merge code that doesn't pass all automated tests.

### Please read [Steps to Contribute](https://www.dataschool.io/how-to-contribute-on-github/#gettingstarted) & [Understanding Good Commit Message](https://chris.beams.io/posts/git-commit/)

### Setting up the repository for development

<!-- (Existing contributors can create feature branches without forking. Prefix the branch name with `@your-github-username/`.) ->
1. Fork the [repository](https://github.com/YOUR-ORGANIZATION/YOUR-REPO) and create a feature branch.
2. Clone the **Forked** Repository.
3. You can then run `yarn install && yarn start` in the root folder to start watching and automatically re-building packages when there are new changes.

### Submitting a pull request

To submit a pull request:

1. Write the description of your pull request. Make sure to include a test plan and test your changes.
2. Make sure all tests pass on -TESTING PLATFORM-.  <!-- CircleCI. ->
3. Wait for a review and adjust the code if necessary.

<!-- ## Publishing a release -->

<!-- To publish a new release, run this command (you must have two-factor authentication enabled for npm):

``` terminal
node ./scripts/publish.js
```

The command will bump the versions of all packages with changes since the previous release and publish them in the correct order. For each changed package, it will ask, if the changes require a new _major_ version (breaking changes), _minor_ version (new backwards compatible functionality) or just a _patch_ version (backwards compatible bug fixes).

### Canary release

If you wish to publish a canary version, please run:

``` terminal
yarn run publish --canary
``` -->

<!-- Adapted From: -->
<!-- https://github.com/expo/create-react-native-app/blob/master/CONTRIBUTING.md ->

---

## Available Scripts

In the project directory, you can run:

### [`yarn install`](https://yarnpkg.com/lang/en/docs/cli/install/#:~:text=yarn%20install%20is%20used%20to,you%20need%20to%20pick%20up.)

Used to install all dependencies for a project. \
This is most commonly used when you have just checked out code for a project, or when another developer on the project has added a new dependency that you need to pick up.

### [`yarn add <package...>`](https://classic.yarnpkg.com/en/docs/cli/add/)

This will install one or more packages in your dependencies.\
This will also update your `package.json` and your `yarn.lock` so that other developers working on the project will get the same dependencies as you when they run `yarn` or `yarn install`.

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

<!-- 
### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

### Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)
->

## :rocket: Deployment

### [`yarn deploy`](https://facebook.github.io/create-react-app/docs/deployment)

This section has moved [here](https://facebook.github.io/create-react-app/docs/deployment)

<!-- 
### `yarn build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify) ->

-->
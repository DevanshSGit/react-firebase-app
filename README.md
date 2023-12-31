# Firebase Authentication in React App

This is a React application that uses Firebase Authentication to allow users to sign up, log in, and navigate through different components. The app includes four components: Home, Login, Signup and UsersList.
The Signup component is the first component displayed when the app is loaded in the browser. React-Router is used to facilitate navigation between these components.

## Authentication Components
### Signup
When a user signs up with valid credentials, they are redirected to the Login page.

![Signup](https://github.com/DevanshSGit/devansh-wevois-project/assets/65933707/47e7bf52-1452-4293-8ff9-a8ffc69c8cba)


### Login
After providing correct email and password, users are redirected to the Home page.

![Login](https://github.com/DevanshSGit/devansh-wevois-project/assets/65933707/66d681d4-bdda-4d32-89eb-f4e642217033)



## Application Components
### Home
Displays a welcome message and user details, including name and email. It also has a "See all Users" option that redirects users to the UsersList page component.

![Home](https://github.com/DevanshSGit/devansh-wevois-project/assets/65933707/0ea206c8-65c1-4471-86b9-21abb06b07d3)


### UsersList
Displays currently present users in a tabular format. Usernames and their ages are shown. Users can be sorted based on alphabetical order of names or ages by clicking "Filter by Name" and "Filter by Age" buttons.

![UsersList](https://github.com/DevanshSGit/devansh-wevois-project/assets/65933707/14bcd02a-9c10-4735-b3c5-7d07d65fd7a7)


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

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

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

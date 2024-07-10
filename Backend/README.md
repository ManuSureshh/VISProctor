# Proctor: Full Stack Application
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
# FrontEnd
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


# BackEnd

# MonitorApplication
2 TABLES
ipPort entities ip_address , portno
userDetails entities email , tokenid, ip_port_id(one to one) mapped with ipPort TABLE ,
HENCE SAME IPADDRESS AND PORT NO IS ADDED IN BOTH TABLES WITH SAME ID

Scheduler = 1 sec

JSON BODY 
Eg: /adddetails

{
  "token_id": "abcdefghijk1234567",
  "email": "meganitish@gmail.com",
  "ipPort": {
  "ipAddress": "172.16.3.250" ,
    "port": 6969
  }
}

## Check out some snapshots of the application running in production below:

<br>

![capture_20240708110711](https://github.com/ManuSureshh/VISProctor/assets/155379347/fb920c23-5db1-48b4-9c9c-9d2db8170cdf)

<br>

![capture_20240708110725](https://github.com/ManuSureshh/VISProctor/assets/155379347/f25e17f1-0ffd-4b20-972a-5d3d363f08ad)

<br>

![capture_20240708110754](https://github.com/ManuSureshh/VISProctor/assets/155379347/97003479-cef9-4fe9-be3e-2ff8cc2cde3f)

<br>

![capture_20240708110805](https://github.com/ManuSureshh/VISProctor/assets/155379347/5670d2cd-1790-4651-914a-b8628b02adff)

<br>

![capture_20240708110859](https://github.com/ManuSureshh/VISProctor/assets/155379347/adc1f96a-a70c-447f-a97d-74f62af3fe51)

<br>

![capture_20240708110930](https://github.com/ManuSureshh/VISProctor/assets/155379347/a63ab71f-1e07-4ed5-a22c-80e02fdc25ee)

<br>



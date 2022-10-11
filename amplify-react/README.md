# Cognito-SDK-Examples

### amplify-react
### Amplify SDK with React example


Usage:
- Download Example
- navigate to the amplify-react folder
- run 'npm install'
- then 'npm start'

[New components added]
![APP UI](UI.jpg?raw=true "Title")

To use the Cognito react HOC instead, uncomment line 54 in App.js and comment out line 55:
Example:
 ~~~
export default withAuthenticator(App, false);
//export default App
~~~

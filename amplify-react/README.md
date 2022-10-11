# Cognito-SDK-Examples

### amplify-react
### Amplify SDK with React example


Usage:
- Download Example
- navigate to the amplify-react folder
- run 'npm install'
- Run `amplify add auth` for [adding auth resource](https://docs.amplify.aws/lib/auth/getting-started/q/platform/js/#create-authentication-service) or Run `amplify import auth` followed by `amplify push` to [import existing auth resources](https://docs.amplify.aws/cli/auth/import/). 
- then 'npm start'

![APP UI](UI.jpg?raw=true "Title")

To use the Cognito react HOC instead, uncomment line 54 in App.js and comment out line 55:
Example:
 ~~~
export default withAuthenticator(App, false);
//export default App
~~~

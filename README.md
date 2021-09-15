### How to install the project

* Clone the project on your machine
* Create a vars.js file at the root of the project
* Write the following code in the previously created file :
```javascript
var tokens = {
  auth : "insert access token"
};

export{tokens};
```
* Get you access token from https://github.com/settings/tokens
* Copy the token token and replace the auth value in vars.js file
* Start an apache server (laragon or else) and open the project via localhost
* You're done !

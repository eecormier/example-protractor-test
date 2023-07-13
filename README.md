# example-protractor-test

Use to rep selenium bug after setting up selenium in docker container: https://github.com/eecormier/selenium-bug/blob/main/README.md 
Rep Steps:
1. Install protractor globally if you haven't already: `npm install -g protractor`
2. Run the tests: `protractor conf.js`
3. The session should time out after 30 seconds with error "Could not start a new session. New session request timed out"

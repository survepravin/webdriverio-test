## To run the automated tests
This automation framework is using *WebdriverIO* tool with *Cucumber*. To run the tests on your machine hit following npm commands.

#### Pre-requisites before running task
##### _setup :_
1. Create `.env` file in main project folder
2. Copy paste in above file 
```
URL=https://www.saucedemo.com/
USER_NAME=standard_user
PASS_WORD=secret_sauce
```

Note: env values can be changes on the go e.g. $env:USER_NAME="new_user"

#### Run the tests
Open new terminal and run below command.
`npm test`
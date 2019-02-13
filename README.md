![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## Lab 37: Login & Auth

### Author: Becca Lee
Paired with Brent Woodward and Heather Cherewaty

### Links and Resources
* [repo](https://codesandbox.io/s/mq3kvy68oj)
* [url](https://mq3kvy68oj.codesandbox.io/)

### Modules
- `index.js` renders the main app
- `store/index.js` sets the store
- `components/if/index.js` creates conditional statement components
- `components/cms/actions.js` contains all actions for the app
- `components/cms/cms.js` contains the CMS class to render the CMS components (Models, Records, Record)
- `components/cms/cms.scss` contains the styling for the app
- `components/cms/models.js` contains the models class and corresponding functionality
- `components/cms/record.js` contains the record class and corresponding functionality for an individual record
- `components/cms/records.js` contains the records class and corresponding functionality for all records
- `components/cms/reducers.js` contains the reducers in a switch case
- `components/auth/auth.js` sets up the auth functionality that allows users to take certain actions based on their assigned capabilities
- `components/auth/context.js` sets context for logins
- `components/auth.login.js` contains the login form component
- `__tests__/` contains the testing suite

#### Running the app
* The app can be run using the url linked above.
* To sign in, choose one of the following login combos:
  * username: user, pw: USER - this login has read capabilities only
  * username: editor, pw: EDITOR - this login has read, create, and update capabilities
  * username: admin, pw: ADMI - this login has has read, create, update and delete capabilities
  
* If you wish to work with the code, simply fork the repo and jump right in
  
#### Tests
Actions tests are currently complete, but records tests are in-progress. Hoping to add testing for login functionality. 

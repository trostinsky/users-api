# users-api
### How use this api?
You have few endpoints: 

#### GET https://test-users-api.herokuapp.com/users/ 
Show your all created users. No parameters.

#### GET https://test-users-api.herokuapp.com/users/:id
Show your only one user by id. No parameters.

#### POST https://test-users-api.herokuapp.com/users/ 
Creating new user. Required parameters: name -> String, age -> Number;

#### PUT https://test-users-api.herokuapp.com/users/:id
Editing user by ID, sending in URL. Avialible parameters: name -> String, age -> Number

#### DELETE #### GET https://test-users-api.herokuapp.com/users/:id
Deleting user by ID, sending in URL. No parameters.

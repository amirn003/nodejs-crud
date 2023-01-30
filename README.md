# Node.js

1°) Install all the packages required

    npm install

2°) Start the express server
    
    npm start
    
3°) Run with authentication
    
    npm run start_auth

Example of curl requests:

curl --request POST 'localhost:5000/login?user=toto&id=1'

curl --request GET 'localhost:5000/user/johnwick@gamil.com'

curl --request PUT 'localhost:5000/user/johnsmith@gamil.com?DOB=1/1/1971'

curl --request DELETE 'localhost:5000/user/johnsmith@gamil.com'

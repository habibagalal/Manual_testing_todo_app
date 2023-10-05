
### Hello and welcome to this Project.
This is a simple Manual testing project in React Web application 

### The manual testing scope :
  ##Overview:
  This project involves manual testing of a Todo application. The application allows users to manage their tasks effectively. It provides features to add, update, delete, and view tasks. The application uses MongoDB as its database.

  ## Objective:
  The objective of this project is to ensure that the Todo application is functioning as expected and provides a seamless user experience. This involves validating all the features of the application and ensuring data integrity with MongoDB.

  ## Scope:
  The scope of testing includes but is not limited to:
    # Functionality Testing: To verify that each function of the software application behaves as specified in the requirement document.
    # User Interface Testing: To validate the user interface and ensure it is user-friendly, efficient, and intuitive.
    # Database Testing: To check the integrity of data in MongoDB, validate queries for data retrieval, and ensure optimal performance.
  ## Test cases link and bug tracking on jira zepher scale tool:
  https://shorturl.at/iqE17
  

## Prerequisites:
This app is using mongodb as the databse, you will need to create a new mongo atlas clustor to be able to run the app. To do that you can find many videos on youtube just search for `create new mongo clustor on atlas`


## Run the App locally:
* Clone the repository.
* Download all the dependencies using `npm i` or `yarn install`
* Create .env file in the route folder.
* Add the below: 
```shell
MONGO_DB_URL=Your Mongo URL
TOKEN_SECRET=sahgjasbdasd
```
* To start the server `npm run start:server`
* To start the frontend `npm run start`

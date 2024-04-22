------------------------------------------------------------------------------------------------------
                                     EXPRESS JS - NODE JS FRAMEWORK
------------------------------------------------------------------------------------------------------
   

   - Steps to build express server
     1. Create a folder for server
     2. Create package.json file : npm init -y
     3. Update scripts in package.json file as "start" : "node index.js" instead of "test"
     4. Install external packages to build server
          - express(server creation),cors(Cross Origin Resourse Sharing ,sharing data between two database),dotenv(Load contents of .env file to process .env)
          - npm i express cors dotenv
    5. Create .env file to add environmental variable (used to store secret data regarding the app)
    6. Create .gitignore file to add files to be ignored
        - node_modules,.env
    7. Create index.js file : define server
         - import dotenv,cors,express
         - create express server
         - use cors in express server
         - use express.json() middleware in server to parse json data in  
         - Set up port where we have to run server
         - Run the server to listen client request
         - To resolve http request using express
              -express-server.httprequest(path,callback)
         - To setup independent routes for each request in express server
              - Create routes folder : to set up path for each http request
                   - inside routes folder create router.js file tom define route/path for resolving each request
                   - import express
                   - create object for router class of express to set up routes 
                   - export router and use it in server app
              - Create controller folder to define logic to resolve request
                   - Inside folder, create js file
    8. To run server app : node index.js / nodemon index.js

--------------------------------------------------------------------------------------------------------------------------
                                MONGODB - DATABASE
--------------------------------------------------------------------------------------------------------------------------

  - Databases are used to store and manipulate data permanently
  - NOSQL Database : Structureless DB 
  - Data stored as document 
         - document is similar as JSON 
  - Collection : collection of documents
  - Multiple collections be hold in single db
  














--------------------------------------------------------------------------------------------------------------------------
                              MONGOOSE - ODM (Object Data Model for MongoDB to Node.js)
--------------------------------------------------------------------------------------------------------------------------

    1. Install mongoose : npm install mongoose
    2. Connect db wuth node.js
        - Create a DB folder for defining db connection and create connection js file
        - import mongoose
        - connect db via mongoose
        - Schema : structure of data / document to be started in db
                - create object for mongoose.Schema class
                - Schema types
        - Model : collection of documents
                - mongoose.model(model-name,schema)








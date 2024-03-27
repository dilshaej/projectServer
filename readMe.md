------------------------------------------------------------------------------------------------------
                                     EXPRESS JS - NODE JS FRAMEWORK
------------------------------------------------------------------------------------------------------
   

   - Steps to build express server
     1. Create a folder for server
     2. Create package.json file : npm init -y
     3. Update scripts in package.json file as "start" : "node index.js" instead of "test"
     4. Install external packages to build server
          - express(server creation),cors(sharing data between two database),dotenv
          - npm i express cors dotenv
    5. Create .env file to add environmental variable
    6. Create .gitignore file to add files to be ignored
        - node_modules,.env
    7. Create index.js file : define server
         - import dotenv,cors,express
         - create express server
         - use cors in express server
         - Set up port where we have to run server
         - Run the server to listen client request
         - To resolve http request using express
              -express-server.httprequest(path,callback)
         - To setup independent routes for each request in express server
              - Create routes folder
                   - inside routes folder create router.js file tom define route/path for resolving each request
                   - import express
                   - 
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
  










  
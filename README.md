# goodreads-gql-server

GraphQL server that communicates with the Good Reads API to grab books based on author or book title.  
Uses the Googe Translate API for book titles that are not in English.  Must generate your own API key for 
the two API's and either create a '.env' file matching the naming scheme used in the 'schema.js' file, or
just replace the 'process.env' placeholders with the actual key value.  

# To Get Started:
- Clone down to local machine
- In terminal, 'npm install' for dependencies
- After generating API keys and entering them, enter 'npm start' into the terminal
- Go to 'localhost:4000/graphql to access the server

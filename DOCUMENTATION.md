CRUD APIs:

Create - https://www.example.com/api/  make an API request with the create operation

      The reqired Object has two type string values with the name value requred and value as optional
      ie. { 
      "name":"***",
      "value":"***"  #optional
      }
      The response returns a similar object plus the id which you`ll need to perform other operations
       { 
       "_id":"**"
      "name":"***",
      "value":"***"  #optional
      }

Get, Put/Update, Delete - https://www.example.com/api/user_id make an API call to perform the listed operations depending on the request operation making the call

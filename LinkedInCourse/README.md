###  Introducing Postman

See LinkedIn course [Introducing Postman](https://www.linkedin.com/learning/introducing-postman/)

### Application

- run the sample API from the API folder
- the sample API is a rudimentary ticket tracking system
    It is implemented as a self contained node JS application, and simulates many common API scenarios including multiple routes, methods, query strings, and authentication. 
    At a high level it is divided into four areas:
        
    * tickets which represent to do items,
    * boards which provide a mechanism for grouping tickets, 
    * users to manage boards and tickets,
    * authentication to establish user context.
    
```bash
$ pwd
~/postman/api/node
$ npm i
$ npm run start-mac
```
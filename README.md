# GraphQL-Apollo
 A simple graphql-apollo server with redis demo

## Technologies
- [Graphql](https://graphql.org/)
- [Tutorial](https://www.howtographql.com/)
- [Apollo-server](https://www.apollographql.com/docs/apollo-server/)
- [Keynote-Slide](https://drive.google.com/file/d/14YaiklIK9QogeizLav9Q9-BsAjyTSV0i/view)

## Getting Started
Clone this repository
```
$ git clone git@github.com:cxchan1/graphql-apollo.git
```
Run the npm install:
```
$ npm install
```
Start docker-redis:
```
$ cd docker && docker-compose up -d
```
Start the graphql server:
```
$ node src/server.js
```
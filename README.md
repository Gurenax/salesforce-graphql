
<h1 align="center">Salesforce + GraphQL</h1>
<p align="center">☁︎ Building APIs with GraphQL and Salesforce</p>
<p align="center"><a href="https://travis-ci.com/Gurenax/salesforce-graphql/"><img src="https://travis-ci.com/Gurenax/salesforce-graphql.svg?branch=master"/></a>
</p>

---

## Blogs
- [Part 1: Building APIs with GraphQL and Salesforce](https://www.mav3rik.com/blog/salesforce-graphql)
- [Part 2: Building APIs with GraphQL and Salesforce](https://www.mav3rik.com/blog/salesforce-graphql-1)

## Major Update
- The project is now using [jsforce](https://github.com/jsforce/jsforce) instead of nForce
- Added CRUDs for multiple account records.

## Preview
![](/docs/images/graphql.png)

---

## Getting Started
1. Download the project
```
git clone https://github.com/wearemav3rik/salesforce-graphql.git
```

2. Install the packages
```
yarn install
```

3. Start the GraphQL server
```
yarn start
```

4. Go to your browser and open `http://localhost:4000/graphql`

---

## Objectives
- ~~Use `nForce` to integrate and perform queries with Salesforce~~
- ~~Utilise existing patterns in the project: [Node nForce](https://github.com/Gurenax/node-nforce)~~
- Use `jsforce` to integrate and perform queries with Salesforce
- Create an easy to use pattern for GraphQL and Salesforce
- Utilise these patterns as back-end for React and React Native salesforce projects


## Dependencies
### Environment Variables
- Use a .env file in your application's directory
```
CONSUMER_KEY = 
CONSUMER_SECRET = 
SALESFORCE_USERNAME = 
SALESFORCE_PASSWORD = 
SALESFORCE_SECURITY_TOKEN = 
```

### Libraries
- Run `yarn install` to install these dependencies:
  - [jsforce](https://github.com/jsforce/jsforce)
  - [nforce](https://github.com/kevinohara80/nforce)
  - [node-nforce](https://github.com/Gurenax/node-nforce)
  - [GraphQl](https://github.com/graphql/graphql-js)
  - [Express GraphQL](https://github.com/graphql/express-graphql)
  - [dotenv](https://github.com/motdotla/dotenv)
  - [nodemon](https://github.com/remy/nodemon)
  - [jshint](https://github.com/jshint/jshint)

## Contributing
### Todos
- Add more mutations
  - ~~Create multiple accounts~~
  - ~~Update multiple accounts~~
  - ~~Delete multiple accounts~~
  - ~~Upsert multiple accounts~~
- Fill up GraphiQL documentation
  - ~~queries~~
  - mutation
- Use facebook dataloader to improve query scalability
# graphql-ts-server-boilerplate

A GraphQL Server boilerplate made with Typescript, PostgreSQL, and Redis

## Installation

1. Install dependencies 
```
yarn
```
2. Start PostgreSQL server
3. Create database called `graphql_ts_server_boilerplate`
```
createdb graphql-ts-server-boilerplate
```
4. Create a test database called `graphql_ts_server_boilerplate_test`
```
createdb graphql_ts_server_boilerplate_test
```
5. Create User in Postgre 
6. Upadate ormconfig.json with the user name
7. Install and start Redis

## Usage

You can start the server with `yarn start` then navigate to `http://localhost:4000` to use GraphQL Playground.

## Features

* Register - Send confirmation email
* Login
* Forgot Password
* Logout  
* Cookies
* Authentication middleware
* Rate limiting
* Locking accounts
* Testing (probably Jest)

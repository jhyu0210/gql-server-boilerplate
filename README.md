# Awesome Project Build with TypeORM
        
Steps to run this project:

1. Run `npm i` command
2. Setup database settings inside `ormconfig.json` file
3. Run `npm start` command

# Project

1. typeorm init --name gql-ts-server-boilerplate --database postgres
2. npm i -g npm-check-updates for using "ncu"
3. ncu -u : upgrades all dependencies in package.json
4. yarn to install
5. ormconfig edit
6. sql shell : Database: postgres, Username: postgres password: "my-password"
7. createdb graphql-ts-boilerplate at postgres=# prompt
8. show db : \l
9. tsconfig.json copy from github by benawad
10. yarn add -D tslint tslint-config-prettier
11. yarn add graphql-yoga
12. add graphql-yoga example in the index.ts file
13. add nodemon in devdependencies
14. add script package.json "start": "nodemon --exec ts-node src/index.ts"
   
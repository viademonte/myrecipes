Create new myrecipes app

Minitest

Layout of the application

Integration Testing

Model Tests - unit testing

TDD (Test Driven Development) - design the app functionality based on a test first approach
Write the test for the functionality
Build minimum code necessary to make each test pass

Re-factor the code - *code doesn't smell - clean code, confidence

----------------
Database and 1:m associations

- Relational Databases
- SQL - Structured Query Language
- ActiveRecord - abstraction - Ruby - translated to SQL

Database layer, Associations

1:m, m:m

Object Relational Mapper - ORM

Relational Database

Recipe -
- recipe should be valid
- name should be present
- description should be present
- chef_id should be present **
- maximum length for name and description, maybe a minimum for description

Chef -
- chefname should be present
- email should be present
- size restrictions on email and chefname
- email address should be valid format
- email should be unique, case insensitive

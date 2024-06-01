# DJANGO UDEMY TDD

## 1. Introduction

- Run using Docker and docker compose
- Apply changes by docker-compose build
- Run something by docker-compose run --rm app sh -c "command"
- docker compose up (starts the services)

## 2. Github actions

- if the code is required, use the checkout action


## 3. Tests

- Tests using a db create a new db for each test, no need to worry about cleaning up and mixing data
- SimpleTestCase - test a function, not a db
- TestCase - test a function, with a db
- Mock the test if you dont want to perform ceratin actions (e.g. sending an email)
- test functions has to start with test_
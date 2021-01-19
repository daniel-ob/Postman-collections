# My practice REST API testing Postman collections

These collections are my solutions to exercises of the course:
[Postman: The Complete Guide - REST API Testing](https://www.udemy.com/course/postman-the-complete-guide/)

## GitHub

What this collection does:

- Create a new Github repository (random name)
- Retrieve repository
- Create a new issue inside the repository
- Retrieve issue
- Delete repository
- Try to fetch just deleted repository

Tests are implemented on each request.

In order to use it, please create an Environment with following variables:
```
url = https://api.github.com
token = your_github_token
```

## Trello

What this collection does:

- Create a board
- Creat two lists: TODO and DONE
- Create a new card inside TODO
- Move the card to DONE
- Delete the board

Tests are implemented on each request.

In order to use it, please create an Environment with following variables:
```
trellokey = trello_api_key
trellotoken = your_trello_token
```
Trello API key can be obtained here: [https://trello.com/app-key](https://trello.com/app-key) (must be logged-in)

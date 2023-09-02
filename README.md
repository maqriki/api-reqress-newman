
# Take home test API

repository take home test API reqress

This is repository for API testing with Postman, using API from https://reqres.in/
1. Create user
2. Get user
3. Update user
4. Delete delete


**Notes:** The 'get user', 'update user', and 'delete user' endpoint can't use the ID from the 'create user' response, so I have decided to use a static ID.



## Installation

Clone the project

```bash
  git clone https://github.com/maqriki/api-reqress-newman.git
```

Go to the project directory

```bash
  cd api-reqress-newman
```

Install dependencies

```bash
  npm install -g newman
  npm install -g newman-reporter-html
```


## Running Tests

### To run tests with html report, run the following command

```bash
  newman run moduit-take-home-test.postman_collection.json -e moduit-env-api.postman_environment.json -r html
```
you can access report html in newman directory

### To run tests with cli report

```bash
  newman run moduit-take-home-test.postman_collection.json -e moduit-env-api.postman_environment.json
```

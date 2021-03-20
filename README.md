# Task-Manager-API
Task Manager App API

### Deployed here (http://aditya-task-manager.herokuapp.com)

## API 

To register/signup a user: 
```POST /users```

To login a user:
`POST /users/login`

To logout current user:
`POST /users/me`

To get current user profile data:
`GET /users/me`

To update current user profile data:
`PATCH /users/me`

To delete user profile:
`DELETE /users/me`

To add current user profile image:
`POST /users/me/avatar`

To delete current user profile image:
`DELETE /users/me/avatar`

To get current user profile image:
`GET /users/me/avatar`

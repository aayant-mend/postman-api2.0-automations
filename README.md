# postman-api2.0-automations

## Two Options:
1. Add the contents of `Mend APITest` into the `Mend API` folder's tests section to apply to all requests. This will catch any 401 response and automatically login and set auth tokens in your environment. (Reccomended)
2. Add the contents of `Login Test` into the `Login` API's tests section. This will simply set the response variables in the environment after manually logging in, you will need to resend the Login request every 30 minutes.

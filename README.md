Tutorial-
https://sandydev.medium.com/how-to-implement-otp-verification-in-authentication-system-with-express-js-and-mongodb-c4f1c1314aed

APIs-
POST -
localhost:8080/api/v1/sendotp
{ "email": "user@gmail.com" }

localhost:8080/api/v1/signup
{ "name": "user",  
 "email": "user@gmail.com",
"password": "password123",
"role": "Student",
"otp": "846008"
}

localhost:8080/api/v1/login
{
"email": "user@gmail.com",
"password": "password123",
}

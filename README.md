# spring-security-demo
A Spring course project that is supposed to demonstrate the usage od Spring Security.
For dependancies it uses Maven, Pages are made of jsp files using jstl. Cofiguration is done in Java files, with an additionl properties file. Passwords are encrypted in bcrypt. The used database is MySQL.
Login page returns a "Invalid password", and "Logout" message. After logging different content is show depending on the logged users role. 

![screenshot1](https://github.com/WojciechWarchol/spring-security-demo/blob/master/screenshots/app1.jpg?raw=true) ![screenshot2](https://github.com/WojciechWarchol/spring-security-demo/blob/master/screenshots/app2.jpg?raw=true)

Logged in as employee:
![screenshot3](https://github.com/WojciechWarchol/spring-security-demo/blob/master/screenshots/app3.jpg?raw=true)

Logged in as manager:
![screenshot4](https://github.com/WojciechWarchol/spring-security-demo/blob/master/screenshots/app4.jpg?raw=true)

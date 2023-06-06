# Java Security Template

This template is meant to be a simple way to start any Java backend project that utilizes Spring and Spring boot and requires Spring security. 

In order to have this work properly, make sure to follow the instructions below, otherwise you will encounter Spring errors that are very annoying to debug.


Make sure to check all the Todos before using this code:

1. set your sql file to point to the correct database and add the tables in the correct place. 
2. Set your application.properties file to communicate with the correct database.
3. Set your issuer in the JwtConverter class. 
4. Add necessary permissions to all endpoints in securityConfig class.
# Secrets

[Click Here!](https://aqueous-ravine-15860.herokuapp.com/")

Its a **Social Media** websites where people can share their views and thoughts.<br>
This Webpage lets user Register via thier Mail ids and password, later they can log in with thier crediantels.Uses cookies to keep the user loggedin in .The crediantels are stored safe in the Database after being Hashed and Salted for protection and privacy .
## WorkFlow
<img src="https://github.com/kitarp29/Secrets/blob/master/Secrets.png" height="400" width="450">
## Tech-Stack</h3>
- **NodeJS**- For rendering the Server side handling of GET and POST requests and connecting to DB
- **MongoDB**- The User data (Password ,id ,views,etc) are saved in a Mongo Database deployed on AWS Bucket-S3 via MongoDB
- **ExpressJS**- For passing the dta from user to DB and vice versa.
- **EJS**- For rendering the data from user to DB and vice versa on the webpages.
- **npm Packages**- Various other NPM packages like Body-Parser,PassportJS etc

## Running locally
- Clone the Repo
- Move to the Dir
- ```npm i```
- Create a .env file and connect your Mongo DB 
- ```node app.js```
- Project is served on http://localhost:3000/
<br>
*Note- There is a Google Auth setup but never used

<h1>Secrets</h1>

<i>Link</i>- <a href="https://aqueous-ravine-15860.herokuapp.com/">Click Here!</a>

Its a <b>Social Media</b> websites where people can share their views and thoughts.<br>
This Webpage lets user Register via thier Mail ids and password, later they can log in with thier crediantels.Uses cookies to keep the user loggedin in .The crediantels are stored safe in the Database after being Hashed and Salted for protection and privacy .

<h3>Tech-Stack</h3>
<li><b>NodeJS</b>- For rendering the Server side handling of GET and POST requests and connecting to DB</li>
<li><b>MongoDB</b>- The User data (Password ,id ,views,etc) are saved in a Mongo Database deployed on AWS Bucket-S3 via MongoDB</li>
<li><b>ExpressJS</b>- For passing the dta from user to DB and vice versa.</li>
<li><b>EJS</b>- For rendering the data from user to DB and vice versa on the webpages.</li>
<li><b>NPM Packages</b>- Various other NPM packages like Body-Parser,PassportJS etc</li>

<h3>Running locally</h3>
<li>Clone the Repo</li>
<li>Move to the Dir</li>
<li>>npm i</li>
<li>Create a .env file and connect your Mongo DB </li>
<li>>node app.js</li>
<li>Project is served on http://localhost:3000/</li>
<br>
*Note- There is a Google Auth setup but never used

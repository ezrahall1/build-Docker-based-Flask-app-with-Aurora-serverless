<h1>How to build Docker based Flask app with Aurora Serverless</h1>

<h2>Description</h2>

In this project I will demonstrate how I set up a flask based docker application that interacts with Amazon Aurora serverless using the data api
<br />


<h2>Services Used</h2>

- <b>RDS</b> 
- <b>Secrets Manager</b>
- <b>IAM</b>



<h2>Environments Used </h2>

- <b>AWS</b>
- <b>Putty</b>

<h2>YouTube Demonstration </h2>

[How to build Docker based Flask app with Aurora Serverless - video walk-through guide](https://youtu.be/DBxDYXgn-vs)


<h2>Program walk-through:</h2> 
<H3>Step 1 - RDS</H3>
Once I had configured my app files in Visual Studio, I went to the RDS section in AWS to create the database.

<img src="https://i.imgur.com/LokNBMZ.png" height="80%" width="80%" alt="Image 1"/>


<H3>Step 2 – Secrets Manager</H3>
In this section I created a secret key in order to store credentials.

<img src="https://i.imgur.com/UzVNQMg.png" height="80%" width="80%" alt="Image 1"/>


<H3>Step 3 – Connect to database</H3>
In this section I used the query editor to test whether my Secrets Manager is working correctly.


<img src="https://i.imgur.com/oCWhkqD.png" width="80%" alt="Image 3"/>


<H3>Step 4 – IAM</H3>
I created a user that has full access to RDS.
<img src="https://i.imgur.com/O88BBjh.png" height="80%" width="80%" alt="Image 4"/>


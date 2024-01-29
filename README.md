<h1>How to build Docker based Flask app with Aurora Serverless</h1>

<h2>Description</h2>
This project will showcase the setup and deployment of a Flask-based Docker application, specifically designed to interact seamlessly with Amazon Aurora Serverless using the Data API. The demonstration will delve into the step-by-step process of configuring and connecting the Flask application to the serverless database, highlighting the utilization of Docker for containerization. By emphasizing the integration with Amazon Aurora Serverless Data API, the project aims to provide a comprehensive guide on developing and deploying applications that leverage serverless database capabilities, enhancing flexibility and scalability within a Flask-based environment.
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
In this section I used the query editor to test whether my Secrets Manager was working correctly.


<img src="https://i.imgur.com/oCWhkqD.png" width="80%" alt="Image 3"/>


<H3>Step 4 – IAM</H3>
In this section I created a user that had full access to RDS.
<img src="https://i.imgur.com/O88BBjh.png" height="80%" width="80%" alt="Image 4"/>


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

<img src="https://i.imgur.com/fdVAGzB.png" height="80%" width="80%" alt="Image 1"/>


<H3>Step 2 – Secrets Manager</H3>
Once the EC2 instance was in a running state I connected to it, by right clicking and selecting connect.

<img src="https://i.imgur.com/kaoMGqH.png" height="80%" width="80%" alt="Image 2"/>

<H3>Step 3 – Connect to database</H3>
The final step is creating the the bash script name for example testscript.sh and creating the variables in a text editor using this command <b>nano testscript.sh</b>.

<img src="https://i.imgur.com/WtDE4tp.png" height="80%" width="80%" alt="Image 6"/>


<H3>Step 4 – IAM</H3>

<img src="https://i.imgur.com/WtDE4tp.png" height="80%" width="80%" alt="Image 6"/>


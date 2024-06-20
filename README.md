<h1>AWS Cloud Resume Challenge</h1>



<h2>Description</h2>
The AWS Cloud Resume Challenge is a hands-on project designed to help individuals gain practical experience with a variety of AWS cloud services. This project involves building and deploying a professional online resume that leverages cloud technologies to showcase your skills and knowledge.<br />


<h2>Technologies Used</h2>

- <b>Amazon S3: For hosting the static website.</b>
- <b>Amazon Route 53: For domain registration and DNS management.</b>
- <b>Amazon CloudFront: For CDN and enhanced security.</b>
- <b>Amazon API Gateway: For creating APIs.</b>
- <b>AWS Lambda: For serverless functions.</b>
- <b>Amazon DynamoDB: For NoSQL database.</b>


<h2>Project Setup</h2>

<p align="center">
Created an S3 bucket: <br/>
<img src="https://i.imgur.com/gfA23kO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Upload the files in the bucket:  <br/>
<img src="https://i.imgur.com/QX0wPUH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
CloudFront is used to distribute the static website globally, ensuring faster load times and enhanced security: <br/>
<img src="https://i.imgur.com/BY1WxNc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Updating S3 bucket policy to allow access only from CloudFront distribution:  <br/>
<img src="https://i.imgur.com/L05lVyg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Testing the cloud front distribution using CloudFront domain name:  <br/>
<img src="https://i.imgur.com/s9hXqh0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Providing the custome domain name using Route53:  <br/>
<img src="https://i.imgur.com/LOCbInw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Testing custome domain name:  <br/>
<img src="https://i.imgur.com/E4P0qua.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Using Dynamo DB to store viewers count in the table:  <br/>
<img src="https://i.imgur.com/kwxZ593.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
Using Lambda function to fetch Dynamo DB values :  <br/>
<img src="https://i.imgur.com/KD2ScCJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
Using IAM roles to allow access to the Dynamo DB table:  <br/>
<img src="https://i.imgur.com/xQjw4fs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
Configure API endpoint in API Gateway that integrates with the Lambda function:  <br/>
<img src="https://i.imgur.com/jYK9YD1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
configration:  <br/>
<img src="https://i.imgur.com/znYLZKm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
Testing the API call:  <br/>
<img src="https://i.imgur.com/hAf838q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
Successfully printing the views on the wesite:  <br/>
<img src="https://i.imgur.com/PFF8jS6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

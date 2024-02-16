Functionalites Deployed

1. Amazon S3 - To host the frontend
2. Amazon Lex - To create the bot
3. API Gateway - To set up the API
4. Amazon SQS - to store user requests on a first-come bases
5. ElasticSearch Service - To quickly get restaurant ids based on the user preferences of cuisine collected from SQS
6. DynamoDB - To store the restaurant data collected using Yelp API
7. Amazon SES - to send restaurant suggestions to users through email
8. Lambda - To send data from the frontend to API and API to Lex, validation, collecting restaurant data, sending suggestions using SNS.
9. Yelp API - To get suggestions for food


Procedure :

1. Build and deploy the frontend of the application
  a. Implement a chat user interface, where the user can write messages and get responses back. You can use open source libraries and frameworks that give you this UI UX out of the box.
  b. Host your frontend in an AWS S3 bucket i. Set the bucket up for website hosting ii. https://docs.aws.amazon.com/AmazonS3/latest/dev/HostingWebsiteOnS3Setup.html

2. Build the API for your cloud application.
3. Build a Dining chatbot using Amazon Lex. 
  a. Create a new bot using the Amazon Lex service. Read up the documentation on all things Lex, for more information:                                                               https://docs.aws.amazon.com/lex/latest/dg/getting-started.html

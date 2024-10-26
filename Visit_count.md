# Visit Count on Digital Resume

Implemented API Gateway and Lambda to track the number of visits to the portal:

- Created a DynamoDB table to store the visit count.
- Developed a Lambda function in Python to increment the counter and retrieve the latest count.
- Set up API Gateway to trigger the Lambda function.
- Updated CORS settings to enable access to the API Gateway.
- Configured the API Gateway to be called each time the website is loaded.

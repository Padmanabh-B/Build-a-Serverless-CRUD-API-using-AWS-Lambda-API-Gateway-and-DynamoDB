# CRUD Serverless API with AWS Lambda, API Gateway, and DynamoDB

This project demonstrates how to build a serverless API with AWS Lambda, API Gateway, and DynamoDB, allowing you to perform CRUD (Create, Read, Update, Delete) operations on a database.

## Prerequisites

Before starting, make sure you have the following prerequisites:

- An AWS account with appropriate permissions to create Lambda functions, API Gateway, and DynamoDB.
- AWS CLI installed and configured with your AWS credentials.
- Node.js installed locally for writing Lambda function code.

## Steps to Build the API

Follow these steps to build the CRUD serverless API:

1. **Set up DynamoDB Table:**
   - Go to the AWS Management Console and open the DynamoDB service.
   - Create a new table with the desired name and primary key configuration.
   - Configure any additional settings as per your requirements.

2. **Create Lambda Functions:**
   - Go to the AWS Management Console and open the Lambda service.
   - Create a new Lambda function for each CRUD operation (create, read, update, delete).
   - Configure the function's runtime and permissions to access DynamoDB.

3. **Implement Lambda Function Code:**
   - Write the code for each Lambda function, implementing the respective CRUD operation.
   - Use the provided code snippets as a starting point and modify them according to your table structure.

4. **Create API Gateway:**
   - Go to the AWS Management Console and open the API Gateway service.
   - Create a new REST API.
   - Configure API Gateway resources and methods for each CRUD operation.
   - Integrate the methods with the corresponding Lambda functions.

5. **Deploy API:**
   - Deploy the API in API Gateway to make it accessible.
   - Test the API endpoints using the provided URL.

## Folder Structure

This repository follows the following folder structure:

```
├── create-lambda-function.js
├── read-lambda-function.js
├── update-lambda-function.js
├── delete-lambda-function.js
├── README.md
```

- Each Lambda function file contains the code for the respective CRUD operation.
- Modify the files as needed, adding additional functions or making changes to the existing code.

## Conclusion

Congratulations! You have successfully built a CRUD serverless API using AWS Lambda, API Gateway, and DynamoDB. You can now perform create, read, update, and delete operations on your DynamoDB database using the API endpoints.

Remember to follow best practices for securing your API and handling errors. Additionally, feel free to enhance the functionality or customize the code to meet your specific requirements.


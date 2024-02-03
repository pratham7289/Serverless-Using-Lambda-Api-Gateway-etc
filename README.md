# Simplified AWS Web Application Setup

## Overview
This guide provides step-by-step instructions to create a basic web application using AWS services such as Lambda, API Gateway, DynamoDB, and Amplify. The application allows users to perform mathematical calculations.

## Prerequisites
Before starting, ensure you have:
- A text editor.
- An AWS account with console access.
- Basic knowledge of AWS services.

## Step-by-Step Guide

### 1. Set Up Web Page with Amplify
1. Create a new HTML file.
2. Copy and paste the HTML code.
3. Save the file and zip it.
4. Deploy the web page using AWS Amplify.

### 2. Create Lambda Function for Math Operations
1. Open the AWS Lambda console.
2. Create a new Lambda function in Python 3.9.
3. Replace the function code.
4. Save and deploy the Lambda function.

### 3. Set Up API Gateway
1. Open the AWS API Gateway console.
2. Create a new REST API.
3. Add a resource and method (POST).
4. Connect the method to the Lambda function.
5. Enable CORS for the POST method.
6. Deploy the API and note the invoke URL.

### 4. Set Up DynamoDB for Results Storage
1. Open the AWS DynamoDB console.
2. Create a new table with a primary key.
3. Note the ARN of the DynamoDB table.

### 5. Update Lambda Function to Write to DynamoDB
1. Open the Lambda function.
2. Replace the function code.
3. Update the DynamoDB table name and ARN.
4. Save and deploy the Lambda function.

### 6. Update Web Page to Call API Gateway
1. Open the HTML file.
2. Replace the script with the provided JavaScript code.
3. Update the API Gateway URL.
4. Save the file and zip it.
5. Redeploy the web page using AWS Amplify.

## How to Run
1. Set up AWS resources as per the instructions.
2. Open the web page using the provided Amplify URL.
3. Enter base and exponent numbers, click "Calculate," and view the result.

## Additional Notes
- Delete resources after testing to avoid charges.
- Customize the application based on your needs.
- Adjust AWS service configurations as required.
- Explore and enhance the application further.

Enjoy building and experimenting with AWS services!
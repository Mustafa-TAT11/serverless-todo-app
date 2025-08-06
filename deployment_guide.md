// deployment_guide.md
# Deployment Guide

## Step 1: Set Up DynamoDB
- Create a table `Tasks` with `taskId` as the primary key.

## Step 2: Create Lambda Functions
- Add the code in backend/ to AWS Lambda functions.

## Step 3: Set Up API Gateway
- Create REST API endpoints for each Lambda.

## Step 4: Deploy Frontend
- Upload frontend/ to an S3 bucket and enable static hosting.

## Step 5: Connect Frontend to API Gateway
- Use JavaScript `fetch()` to call your API endpoints.

# Serverless Computing - Hello World

## Introduction
This project demonstrates the basic concept
of serverless computing using AWS Lambda.

## Objective
- Understand serverless computing.
- Learn about AWS Lambda.
- Write a simple Python function.
- Display Hello World output.

## Technology Used
- AWS Lambda
- Python
- GitHub

## Python Code
def lambda_handler(event, context):
    return {
        'statusCode': 200,
        'body': 'Hello World!'
    }

## Expected Output
Hello World!

## Conclusion
This project explains how AWS Lambda
can execute code without managing servers.

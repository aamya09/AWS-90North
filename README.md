# ** AWS Lambda - Add Two Numbers**

This repository contains an AWS Lambda function that takes two numbers as input and returns the sum of the two numbers.

# Features

1)Accepts two numbers (num1 and num2) from an event input.

2)Returns the sum of the two numbers as the output.

# Pre-requisites

To use this Lambda function, you need:

1)AWS Account with access to Lambda.

2)Basic knowledge of AWS Lambda and AWS Console.

# Setup Instructions

Follow these steps to set up the AddTwoNumbers Lambda function:

# 1. Create a New Lambda Function:-
Go to the AWS Management Console and navigate to Lambda.

Click on Create function.

Choose Author from scratch.

Set the function name (e.g., AddTwoNumbers).

Choose the runtime as Python 3.x (since the function is written in Python).

Click Create function.

# 2. Copy the Code to the Lambda Function:-

Once your Lambda function is created, you'll need to copy the code from this repository:

In the Lambda function console, scroll down to the Function code section.

In the code editor, paste the following Python code:

# 3.  Set Up Test Event:-

Now, you'll need to configure a test event to invoke the Lambda function with the two numbers.

In the Test section, click on Create a new test event.

Replace the default event with the following JSON:

{
    "num1": 5,
    "num2": 10
}

This event sends two numbers, 5 and 10, to the Lambda function.

Click Save changes.

# 4. Invoke the Lambda Function:-

After saving the test event, click Test to invoke the Lambda function.

The Lambda function will process the event and return the sum of the two numbers.

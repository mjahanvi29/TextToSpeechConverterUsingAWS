# Text-to-Speech Web Application

This is a simple web application that converts text input into speech using Amazon Polly and allows users to listen to the generated audio.

## Features

- Convert text to speech with different voices available.
- Display the converted audio with playback controls.
- View the status of the conversion process.
- Get a unique post ID for each conversion.

## Technologies Used

- Frontend: HTML, CSS, JavaScript, jQuery
- Backend: AWS Lambda, Amazon Polly, Amazon DynamoDB
- Deployment: AWS API Gateway, AWS S3

## Prerequisites

- AWS account with appropriate permissions to access Lambda, Polly, DynamoDB, and API Gateway services.
- Node.js and npm installed locally.
- Basic knowledge of AWS services, JavaScript, and web development.

## Setup

1. Clone this repository to your local machine.
2. Set up your AWS environment with Lambda, Polly, DynamoDB, and API Gateway.
3. Update the `API_ENDPOINT` variable in `script.js` with your API Gateway endpoint URL.
4. Deploy your frontend files to an S3 bucket or any static hosting service.
5. Test the application in your web browser.

## Usage

1. Enter text in the input field.
2. Select a voice from the dropdown menu (optional).
3. Click the "Say It" button to convert the text to speech.
4. Listen to the generated audio.
5. Use the "Search" button to retrieve and display previous conversions by post ID.



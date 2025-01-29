#Face Detection with Amazon Rekognition and AWS Lambda

🚀 This project automatically detects faces in images using Amazon Rekognition and AWS Lambda. When an image is uploaded to an S3 bucket, a Lambda function is triggered to analyze the image, count the number of faces, and send an email notification.

![Architectural Diagram](https://github.com/user-attachments/assets/c99c26fa-4813-4bbc-ad5e-2e398bf501bf)


📌 Features
✔ Automatic face detection using Amazon Rekognition
✔ Event-driven processing with AWS Lambda
✔ Serverless architecture (no servers to manage)
✔ Email notifications with detected face count

🛠️ Technologies Used
Amazon S3 – Stores uploaded images
AWS Lambda – Processes the images
Amazon Rekognition – Detects faces
Amazon SNS – Sends email notifications

🚀 How It Works
Upload an image to the S3 bucket
The upload event triggers AWS Lambda
Amazon Rekognition analyzes the image
Amazon SNS sends an email with face count


🔗 Medium Article:(https://ifeloludavid.medium.com/face-detection-with-amazon-rekognition-and-aws-lambda-43bf6b61842b)
🔗 Youtube video walkthrough: https://youtu.be/oSLluwD40iM

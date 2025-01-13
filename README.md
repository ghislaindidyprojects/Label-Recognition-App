# Label-Recognition-App
How to create a label Recognition App using AWS Rekognition

# Project Overview
This project demonstrates how to use AWS Rekognition to detect labels and bounding boxes in images stored in an S3 bucket. It uses Python, the AWS SDK (`boto3`), and visualization libraries like Matplotlib and Pillow to display detected objects with bounding boxes.
###  Prerequisites
- **AWS Account**: Ensure you have an AWS account with access to Rekognition and S3 services.
- **Python**: Python 3.7 or higher installed on your system.
- **AWS CLI**: Install the [AWS CLI](https://aws.amazon.com/cli/)

**Setup**:

  1. AWS S3 Bucket and Image Upload

Create an S3 bucket.
Upload the image(s) you want to analyze to this bucket.

  2. Create an IAM user
     
   - Attach Policies directly
   - Under Permissions policies: Check AdministratorAccess
   - Create User and generate access keys
   - Download keys and store in safe folder to allow you to acess IAM through your cmd prompt

  4. Open your computer terminal and Configure CLI Access
      - Type the command: AWS configure
      - Copy and paste your Access Key ID, and Secret Access Key

  5. Install dependencies
       - in your command prompt type: pip install boto3
       - next: pip install matplotlib

  6. Create a python file in your IDE (Eg: Visio Code)
     -Copy my code
     - replace in def (main) Photo = 'your own photo you uploaded'
     - replace in def (main) bucket = 'your own bucket name'

    6. Last Step: Running your app
    - open terminal and navigate to your python code directory
    -run the command: python pythonfile.py


  
    

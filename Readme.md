In this project I use the following technologies:
- [Python](https://www.python.org/)
- AWS(Lmabda,Api Gateway,IAM,SSM)
- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

<<<<<<< HEAD
- HandModule is used to create a docker image and run the container.

- By showing finger to the camera, the program will recognize the gesture and send the command to the AWS Lambda function.
- The Lambda function will send the command to the AWS SSM and the SSM will send the command to the EC2 instance.
- The EC2 instance will execute the command and send the result to the SSM.
- The SSM will send the result to the Lambda function.
- The Lambda function will send the result to the client.
- The client will show the result on the screen.
=======
HandModule is used to create a docker image and run the container.

 By showing finger to the camera, the program will recognize the gesture and send the command to the AWS Lambda function.
 
The Lambda function will send the command to the AWS SSM and the SSM will send the command to the EC2 instance.

The EC2 instance will execute the command and send the result to the SSM.

The SSM will send the result to the Lambda function.

The Lambda function will send the result to the client.

The client will show the result on the screen.
>>>>>>> 20fa417281256011010dc397b90c76e30556e59d

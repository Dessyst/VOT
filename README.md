# VOT
# AWS 
I chose AWS because it offers a platform where developers can concentrate on building the core of their applications, while it takes care of the underlying infrastructure, scalability, and security aspects.

# The process of creating the application
- The process began with creating and hosting my website, which was accomplished with the assistance of the Amplify server that deployed my site. 

- Subsequently, I created my Lambda function using the AWS-provided Lambda service, which is instrumental in making the application serverless. I then utilized the API Gateway to establish a public endpoint, which is crucial as it eliminates the necessity for users to interface with the AWS console directly. The API Gateway facilitates the creation, publication, security, and management of APIs (Application Programming Interfaces) for the application. It serves as a bridge or proxy between the internet and the backend services, easing the exposure and management of my APIs. 

- To grant the necessary permissions to the Lambda function and the database, I used IAM as the final service. IAM allows the adjustment and addition of permissions to roles, groups, and various AWS services and resources.

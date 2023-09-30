
Local Development with Git

Start development on your local system.
Use Git for version control to track changes.
Angular Web App

Develop your web app using Angular.
Frontend-Backend Connection

Inside your Angular project, maintain a 'deploy' folder.
This folder connects the frontend to an Express backend server running on port 3000.
GitHub Repository

Push your code to a GitHub repository named 'awswebapp' for centralized version control.
AWS CodeBuild

Configure AWS CodeBuild.
Set GitHub as the source for your builds.
Create a buildspec.yml file to define build, post-build, and artifact storage actions.
Build and Artifact Storage

AWS CodeBuild compiles your code successfully.
The resulting 'dist' folder contains the build artifacts.
These artifacts are packaged and stored in an S3 storage bucket.
Deployment Environment

Create a deployment environment using AWS Elastic Beanstalk.
AWS CodePipeline Integration

Integrate Git, AWS CodeBuild, and AWS Elastic Beanstalk using AWS CodePipeline.
Changes in your local Git repository trigger the CodePipeline.
Automated Deployment

When changes occur, CodePipeline builds the app using CodeBuild.
The updated application is then deployed to the Elastic Beanstalk environment.
Continuous Integration

Achieve a fully automated flow for Angular web app development.
Changes made to your local Git repository are automatically reflected in the deployed application.
This flow ensures efficient development, version control, and automated deployment of your Angular web application. It's a well-structured process for collaborative and continuous development.





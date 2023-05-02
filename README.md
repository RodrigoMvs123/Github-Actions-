# Github-Actions-



GitHub Actions Tutorial - Basic Concepts and CI/CD Pipeline with Docker


Github Actions 

What are Github actions?
Developer workflow use cases
Basic Concepts: Github Events and Actions 

How Github Actions automates those workflows ?

CI/CD pipeline with Github Actions!
Benefits of Github Actions CI/CD
Demo
Syntax 

Java App with Gradle / Build Artifact
Docker Image / Build Image
Private Repository Push Docker Repository

What are Github Actions ?
Platform to automate developer workflows
Github Actions / CI/CD tool 

CI/CD tool - is one of many workflows 

What are those workflows?
Github ( Platform for open-source projects ) 
Publically available to use and contribute to the project  
add new contributors 
pull requests are created 

Organizational Tasks

Java Library ( Contributors / Users )
 
Workflows 
 
New Issue 
Is it minor/major ?
Is it reproducible ? 
Assign to a contributor ?

Pull Request 
Review Pull Request 
Is the bug fixed ? 
Merge to master branch 

Merged Code 

CI/CD Pipeline 
Test code 
Build 
Deployment 

Prepare release notes
Update version number  

Github Actions 
When something happens IN or TO your repository 
Automate ACTIONS are executed in response 

( Github Events )  
Pull Request Created 
Issue Created 
Pull Request Merged 
Contributor Joined 

Listen to Event 
Issue Created 

           Github Actions 
    
Sort 
Label
Assign it 
Reproduce
CI/CD with Github Actions 

Most common workflow for your repository 

Commit Code 
Test
Build
Push 
Deploy

Pipeline 

NodeJs App
Build Docker Image
Push to Nexus Repository
Deploy to DigitalOcean Server 

Pipeline 

Java App with Maven
Integration Tests - Linux and Windows
Build Docker Image 
Push to AWS Repository 
Deploy to AWS EKS 

CI/CD Demo 

Java App with Grandle 
Build Docker Image 
Push to Private Repository Docker Hub 

Create 
New Repository - GitHub Actions Tutorial - Basic Concepts and CI/CD Pipeline with Docker

Terminal 
[java-app (master)]$ git push 
https://github.com/nanuchi/my-project 

Github Actions 
https://github.com/RodrigoMvs123/Git-and-GitHub-/actions/new
https://github.com/RodrigoMvs123/Git-and-GitHub-/new/main?filename=.github%2Fworkflows%2Fgradle-publish.yml&workflow_template=ci%2Fgradle-publish

Syntax of Workflow File 


GithubActions
Checkoout 
action.yml 
https://github.com/actions/checkout/blob/main/action.yml

Docker Hub
https://hub.docker.com/repository/docker/rodrigomvs123/githubactions/general

https://github.com/marketplace/actions/docker-build-and-push



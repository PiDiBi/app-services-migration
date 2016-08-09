## Continuous Deployment using GitHub

Visual Studio offers built-in tooling for deploying applications to Microsoft Azure App Services. However, having someone manually deploy doesn't give you continuous deployment. In addition, you might be using a different tool, such as Visual Studio Code or Sublime, which doesn't offer such capabilities.

Fortunately,  App Services allows you to deploy code from most common repositories, including TFS, Git, Bitbucket, and GitHub. By configuring App Services to deploy from a repository, you're able to enable Continuous Deployment.

In addition, App Services, through Hybrid Connections, allows you to access local resources, such as MongoDB. This offers you the flexibility to deploy your applicaiton in stages, 

### Overview

In this lab, you will take a Node.JS application deployed to GitHub and configure continuous deployment. You'll also examine how you can roll back changes as needed.

In this lab, you'll perform the following tasks:

1. Create a web app in App Services
1. Enable Hybrid Connections to connect to MongoDB
1. Fork the **node-invoicing** application
1. Configure App Services to pull the code from your repository, and perform the initial deployment
1. Configure the connection string for your applicaiton
1. 

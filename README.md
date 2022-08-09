# My-Udagram-Project

The essence of this project is to demonstrate how flexible and expedient applications can easily be deployed to the cloud without having to deal with the heavy lifting involved when provisioning and managing virtual servers (EC2 instances, as in the case of AWS).
AWS PaaS offering; Elastic Beanstalk is the service that simplifies and achieves the objective of deploying applications without having to manually spin up servers,installing operating systems,patching,and other related system jobs to prepare an instance for its workload in the cloud. This affords any organization or business entity to dedicate its resources and time on what distinguishes its business and increase productivity rather than performing repetitive infrastructural jobs that do not add to the value of its

# Getting Started

The source code for this project can be found on the development branch(dev) of this repository. 

A.Setup Node Environment
  
You'll need to create a new node server. Open a new terminal within the project directory and run:

1.Initialize a new project: npm i

2.run the development server with npm run dev


B. Create a new endpoint in the server.ts file
There is an endpoint in ./src/server.ts which uses query parameter to download an image from a public URL, filter the image, and return the result.

3. Deploying your system
Follow the process described in the course to eb init a new application and eb create a new environment to deploy your image-filter service! Don't forget you can use eb deploy to push changes.



http://wonder-image-filter-dev-dev2.us-west-2.elasticbeanstalk.com/filteredimage?image_url=https://onlinejpgtools.com/images/examples-onlinejpgtools/sunflower.jpg

The link above points to an endpoint url of a running elastic beanstalk deployment of the project

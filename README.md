# My-Udagram-Project

# Getting Started
A.Setup Node Environment
  The source code for this project can be found on the development branch(dev) of this repository. 

You'll need to create a new node server. Open a new terminal within the project directory and run:

1.Initialize a new project: npm i

2.run the development server with npm run dev


B. Create a new endpoint in the server.ts file
There is an endpoint in ./src/server.ts which uses query parameter to download an image from a public URL, filter the image, and return the result.

3. Deploying your system
Follow the process described in the course to eb init a new application and eb create a new environment to deploy your image-filter service! Don't forget you can use eb deploy to push changes.



http://wonder-image-filter-dev-dev2.us-west-2.elasticbeanstalk.com/filteredimage?image_url=https://onlinejpgtools.com/images/examples-onlinejpgtools/sunflower.jpg

The link above points to an endpoint url of a running elastic beanstalk deployment of the project

# Udagram Image Filtering Microservice

This is a simple cloud application developed alongside the Udacity Cloud Developer Nanodegree. It allows users to process photos using an image filtering microservice.
It is a Node-Express application which runs a simple script to process images.

## Project Details

### Engineering Process and Quality

* The project demonstrates an understanding of a good cloud git process

All project code is stored in a GitHub repository. There are two branches - one for development (dev, development) and one master. 

* The project demonstrates an ability to use typescript and Nodejs

Any variables use typescript typing wherever possible, variable and function names are clear, endpoints are logically named. Good coding practices are followed.

### Development Server

* The project demonstrates the ability to develop using the NodeJS framework

Open a new terminal within the project directory and run:
  1. Initialize a new project: `npm i`
  2. run the development server with `npm run dev`

* The project demonstrates an understanding of RESTFUL design

The image filtering microservice is available at http://localhost:{{PORT}}/filteredimage?image_url=<url_to_image>

Example: http://localhost:{{PORT}}/filteredimage?image_url=https://upload.wikimedia.org/wikipedia/commons/b/bd/Golden_tabby_and_white_kitten_n01.jpg

* The project demonstrates an understanding of HTTP status codes

Successful responses have a 200 code, at least one error code for caught errors (i.e. 422)

### AWS Elastic Beanstalk Deployment

* The project demonstrates the ability to create functional cloud deployments

Endpoint URL: http://udagram-image-filt-microservice-prod.ap-south-1.elasticbeanstalk.com/

Example: http://udagram-image-filt-microservice-prod.ap-south-1.elasticbeanstalk.com/filteredimage?image_url=https://upload.wikimedia.org/wikipedia/commons/b/bd/Golden_tabby_and_white_kitten_n01.jpg

Requires: Authorization Header with Bearer Token. Token is included in the Postman collection in the project directory.

* The project demonstrates an understanding of AWS Elastic Beanstalk’s CLI and Console Dashboard

The project was deployed using the AWS Elastic Beanstalk CLI eb init, eb create, and eb deploy commands.
A screenshot of the elastic beanstalk application dashboard is included in a deployment_screenshot directory.

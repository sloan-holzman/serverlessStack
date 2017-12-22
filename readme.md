# Serverless - using AWS Lambda, Cognito, DynamoDB, S3, Node.js, and React.js #


## Why did you choose this subject? ##
- I wanted to get some experience deploying to AWS, as it's where most sites run and I thought it'd be fun to user the cutting edge approach to deployment

## How were you first made aware of it? ##
- Zakk mentioned it to me yesterday when I asked him for ideas

## What problem does it solve? ##
- Servers are expensive and difficult to run.  

## How does it solve the problem (conceptually)? ##
- Serverless allows us to build applications where we simply hand the cloud provider (AWS, Azure, or Google Cloud) our code and it runs it for us. It also allocates the appropriate amount of resources to respond to the usage.

## Why does one use it? ##
- To save time and energy on servers.  Also, the system works well with AWS's other Backend as a Services (including DBs and authentication), allowing users to export some of the security and authorization functionality to a trusted provider (AWS)

## What are the alternatives? ##
- Traditional AWS or other virtual servers.  Plus, there are a lot of authentication tools, like Devise or Passport, which we are doing through AWS's Cognito

## What is it similar to, if anything? ##
- Not sure.  Obviously it's replacing traditional AWS or other virtual server environments

## What is the history of this technology? ##
- AWS Lambda was launched in 2014-2015, but the idea of Function as a Service (FaaS) was first mentioned in 2012

## Who built it and why? ##
- The main platform was built by Amazon- to lower server costs and simplify hosting

## Who is maintaining it? ##
- AWS

## What is your opinion on the technology after having built something with it? ##
- It's hard for me to say, as I don't have much experience working with traditional servers.  But, it wasn't radically more difficult to set up simple paths and authorization than it did using standard express.  So, if this approach is much cheaper and makes hosting easier, then it seems like a great technology.

## What are the biggest conceptual hurdles (if any) you encountered when researching this? ##
- AWS is just not very intuitive.  There are so many different ways to set things up, it is very difficult to do it correctly without a guide

## What resources do you recommend for interested students? ##
- I followed a great tutorial- https://serverless-stack.com/.  But, it's very long.  There are likely shorter, simpler ones out there.

## What article or forum was most helpful to you in learning this? ##
- here's a good article, outlining some of the pros and cons: http://www.iheavy.com/2017/04/15/top-amazon-lambda-questions-hiring-serverless-expert-interview/

## What are 3 interview questions one might be asked about this technology? ##
- What is serverless?
- What are the pros?
- What are the cons?

## Run your example. ##
- Unfortunately, running my example will be really difficult...SORRY!  I should have chosen something simpler, but it's kind of inherent to the exercise to be complicated...
- ...you need to set up an AWS account, including Cognito, DynamoDB, S3, and IAM in order to do the tutorial that I did.
- You also have to npm install all the dependendies in the backend app (notes-app-api) and in the frontend (notes-app-client)

## Use your subject. ##
- There are alternatives to Lambda, but if you use Lambda, you need to set up an AWS account, configure your backend API to interact with the AWS account, and then set up your frontend to call the backend API

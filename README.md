# Akka Serverless Beta Exercises

Thank you for participating in the Akka Serverless Closed Beta! We want Akka Serverless to be easy to learn and use. We realize that your time is valuable. To help you get the most out of working with Akka Serverless, we’ve created some “_Getting Started Exercises._” 

NOTE: If you’re participating in our User Experience study, please jump to [User Experience Participant Exercises](#user-experience-participant-exercises)

## Exercises for those not participating in the User Experience study. 

We've provided three main exercises, but we realize that it is possible that some will not be able to complete all three. We are interested in your feedback regardless of how far you get. Please answer our [short survey](https://lightbend.qualtrics.com/jfe/form/SV_1CkcF7hvg40BLmu) when you are done.

### Exercise One 
*Try out the Akka Serverless console*

_First we’ll focus on the developer experience of the Akka Serverless Console. All of the tasks can be done through your web browser._

Imagine that you’re a developer working for ACME Sunglasses. Your team has built a few services that you need to deploy. A colleague has invited you to join his Akka Serverless Project.


1. Follow the link in the email invitation to log into Akka Serverless Console.
2. Click on the project and a tutorial will guide you through deployment of a shopping cart service. At the end it will provide a link to a UI you can use to connect to the service.
3. [Open the UI in a new tab](https://static.akkaserverless.com/js-shopping-cart/index.html) connect it to the new service using the hostname of the route you exposed. 
4. In the UI, enter a user name and add and remove items from the cart.
5. View the log.


### Exercise Two
*Try out the Akka Serverless Command Line Interface (CLI)*

_Next, we’ll focus on the developer experience of the Akka Serverless `akkasls` CLI. All the tasks can be done using the CLI._

As a developer working for ACME Sunglasses, your team has built a different shopping cart service that you need to deploy. 


1. Install the CLI as described at: https://developer.lightbend.com/docs/akka-serverless/getting-started/set-up-development-env.html.
2. Using the previous project, deploy the new service from this container image on Docker Hub: https://hub.docker.com/r/retgits/acmesunglasses-warehouse/tags?page=1&ordering=last_updated, make sure that the service will be exposed for internet access.
3. Update the container with a new version from this container image: <please add link to image 2> 
4. Add environment variables.
4. Check whether the service has started.
5. View the log.


### Exercise Three
*Building Apps to deploy on Akka Serverless*

_Finally, we’ll focus on building applications. The tasks will cover using your preferred IDE, Docker, and either the Akka Serverless Console or the Akka Serverless CLI._

Imagine that you have transferred to ACME Wireless, the parent company of ACME Sunglasses. Your team has been tasked with building and deploying a wireless mesh app on Akka Serverless. To build and deploy the app, you can choose:


*   [The Java version of the application](https://github.com/lightbend-labs/akkaserverless-wirelessmesh-java)
*   [The JavaScript version of the application](https://github.com/lightbend-labs/akkaserverless-wirelessmesh-javascript) 

1. Follow the README in the repository of your choice to build the container (_you can skip the step for Google Cloud Pub/Sub_). You can deploy using the Console or the CLI.

2. Follow the documentation to learn about the main functionality of the Java example: https://developer.lightbend.com/docs/akka-serverless/tutorial/iotexample-learn.html

3. Modify the example. The `AssignRoom` rpc method returns an empty response. Change it to return the incoming message. 

Thank you, please do not forget to fill out the [short survey](https://lightbend.qualtrics.com/jfe/form/SV_1CkcF7hvg40BLmu).


## User Experience Participant Exercises

Our team will walk you through these exercises. Feel free to think out loud and so that we see your first impression. Remember we are testing Akka Serverless, not you, so any problem you encounter is welcome and valuable to us.

### Exercise - Working with projects and services

An Akka Serverless project is a collection of services and configuration that comprise your application. Each Akka Serverless project runs in its own Kubernetes namespace. Projects support team collaboration: Multiple people can work on a single project, and each person can be a member of many projects.

For your first task, log in to Akka Serverless. You will need to create an account if you don't have one.

1. Create a new project. After we approve it, you will receive an email confirmation.
2. Click the approved project. A tutorial will guide you through deployment of a shopping cart service. Click Finish to dismiss the tutorial for now. 
2. Add a new member to your project so that you can collaborate. We’ll provide you with an email address for the invitee. 
3. Your newly invited colleague has created a new version of the shopping cart and published it at: https://hub.docker.com/r/retgits/acmesunglasses-warehouse/tags?page=1&ordering=last_updated. Redeploy the service and add an environment variable to it.
4. Suppose that your company decides to use a private Docker Hub account to store container images. How would you go about making sure you can deploy a container from a private registry?

### Exercise - Learning about development

Imagine that you are a JavaScript developer joining the team that created the shopping cart. The team has documented how they created the service. Follow their directions: [https://docs.lbcs.dev/tutorial/shopping-cart-node.html](https://docs.lbcs.dev/tutorial/shopping-cart-node.html)

Note: We know that we have limited time, so you will likely not finish during the screen share.

If you have time and the desire, feel free to try [Exercise Two](#exercise-two) and [Exercise Three](#exercise-three). If you are able to work with Akka Serverless more, please  fill out the [short survey](https://lightbend.qualtrics.com/jfe/form/SV_1CkcF7hvg40BLmu).

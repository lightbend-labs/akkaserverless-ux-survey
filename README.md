# Akka Serverless Beta Exercises

Thank you for participating in the Akka Serverless Private Beta! We want Akka Serverless to be easy to learn and use. We realize that your time is valuable. To help you get the most out of working with Akka Serverless, we’ve created some “_Getting Started Exercises_”. You can either do these exercises on your own and provide us feedback using a [short survey](https://lightbend.qualtrics.com/jfe/form/SV_1CkcF7hvg40BLmu) or you can follow the interactive route using Paircast. Each of the exercises below has a "_Record Paircast_" button that will walk you through the same exercise, but recording it using [Paircast](https://paircast.io).


### Akka Serverless :: Console

<a href="https://app.paircast.io/intro?key=fce7be36-e30a-4078-8471-58ec2dacc8d4"><img src="https://app.paircast.io/images/share-your-build.png" alt="Share with Paircast"></a>

For this exercise, imagine that you’re a developer working for ACME Sunglasses. Your team has built a few services that you need to deploy. A colleague has invited you to join his Akka Serverless Project. We'd like you to deploy a shopping cart service. You can do that in two ways:

1. Using the tutorial in the Akka Serverless Console
2. Deploy a new service yourself(you can use `lightbend-docker-registry.bintray.io/cloudstate-samples/shopping-cart-javascript` as the docker container)

In both cases, the goal is to make the image publicly available (public endpoint), connect it to the [static frontend](https://static.akkaserverless.com/js-shopping-cart/index.html), and see the logs after putting some sunglasses in your cart.


### Akka Serverless :: CLI

<a href="https://app.paircast.io/intro?key=b8ddf958-622f-4340-a4e6-04f775066869"><img src="https://app.paircast.io/images/share-your-build.png" alt="Share with Paircast"></a>

For this exercise, imagine that you’re a developer working for ACME Sunglasses. Your team has built a few services that you need to deploy. A colleague has invited you to join his Akka Serverless Project. We'd like you to deploy a warehouse inventory service using the CLI. The steps you'll need to follow are:

* Download and install the Akka Serverless CLI
* Deploy the warehouse inventory service (you can use the container image `docker.io/retgits/acmesunglasses-warehouse:2.0.0`) with an environment variable called `MSG` (you can choose the value for it yourself)
* Check whether the service has started and view the logs


### Akka Serverless :: Building Apps in Java

<a href="https://app.paircast.io/intro?key=7fee1872-2e8f-41e1-859f-f3afe3b4b582"><img src="https://app.paircast.io/images/share-your-build.png" alt="Share with Paircast"></a>

For this exercise, imagine that you've transferred to ACME Wireless (part of the same group of companies as ACME Sunglasses). Your team has been tasked with building and deploying a wireless mesh app on Akka Serverless using Java. We would like you to:

* Follow the README in the [GitHub repository](https://github.com/lightbend-labs/akkaserverless-wirelessmesh-java) to build and deploy the application to Akka Serverless (to deploy the application you can use the Akka Serverless Console or CLI)
* Modify the `AssignRoom` rpc method, which now returns an empty response, to return the incoming message

The documentation of how this example application was built is available [here](https://developer.lightbend.com/docs/akka-serverless/tutorial/iotexample-learn.html)

### Akka Serverless :: Building Apps in JavaScript

<a href="https://app.paircast.io/intro?key=6425fdaf-2265-4c81-9d05-8d27baa6c5ba"><img src="https://app.paircast.io/images/share-your-build.png" alt="Share with Paircast"></a>

For this exercise, imagine that you've transferred to ACME Wireless (part of the same group of companies as ACME Sunglasses). Your team has been tasked with building and deploying a wireless mesh app on Akka Serverless using Node.js. We would like you to:

* Follow the README in the [GitHub repository](https://github.com/lightbend-labs/akkaserverless-wirelessmesh-javascript) to build and deploy the application to Akka Serverless (to deploy the application you can use the Akka Serverless Console or CLI)
* Modify the `AssignRoom` rpc method, which now returns an empty response, to return the incoming message

The documentation of how this example application was built is available [here](https://developer.lightbend.com/docs/akka-serverless/tutorial/iotexample-learn.html)

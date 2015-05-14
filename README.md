# Bluemix Object Storage application

This sample application illustrates the usage of the OpenStack Swift Object Storage service by an application deployed to the IBM Bluemix Platform-as-a-Service.


## Steps

Follow these steps to set up a Bluemix account, provision an instance of the Swift Object Storage, and deploy a Node.js application that provides a user interface for uploading and sharing files.

* Sign up for [IBM Bluemix](http://bluemix.net/).

* Create an instance of the Object Store service through the Bluemix catalog UI (v1, not v2). Name the service 'object-store' so that it matches the manifest file and leave it unbound.

![Object Storage in the Bluemix catalog](https://github.com/krook/bluemix-object-storage/blob/master/public/img/object-storage-tile.png)
![Configuring the Object Storage](https://github.com/krook/bluemix-object-storage/blob/master/public/img/configuration.png)

* Sign up for the [IBM DevOps Service](http://hub.jazz.net/).

* Fork the [bluemix-object-storage](http://github.com/krook/bluemix-object-storage) repository to get the application code (make it a public project, uncheck add scrum features, check create Bluemix project).

* Deploy the application to Bluemix using the Deploy button.

* Access the application via the URL to upload / view / delete any text, image, and PDF files.

* Scale the front end and provide a blue/green deployment process.

* Binding to other services.

# Kitchen Inventory Tracking

## Introduction

This is a model application to demonstrate how you can keep a track of your kitchen's inventory. By leveraging IoT, you can sense the weight of kitchen storage containers and hook them to the cloud which can enable smart decision making when it comes to tracking consmuption patterns and getting timely alerts for replenishment and expiry.

## Setup

This application comprises of a hardware setup, a cloud hosted server application and a mobile app. 

The hardware is based on Linkit ONE and HM-10 BLE module. Load cells are used to sense the weight of the containers. Refer this [link](HwBuildAndInstall.md) for setting up and programming the hardware.

The server application is hosted on IBM Bluemix. Refer this [link](Deploy.md) for instructions on how to deploy the server application on Bluemix.

The Mobile app is a cordova based android app used to track the inventory and provide some basic analytics. Refer this [link](AppBuild.md) for instructions on how to build th app.

This application relies on PubNub data stream network for the underlying messaging between the hardware, the server and app. Ensure that the same set of PubNub keys are used across all the components while configuring and building the application software.  



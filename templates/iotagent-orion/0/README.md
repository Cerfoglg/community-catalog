# IoTA json stack

### Info:

This template deploys a collection of FIWARE generic enablers and external services which are required by them.

In this catalog item, the following technologies are used:

* [IoTA json](https://github.com/telefonicaid/iotagent-json)
* [Orion](https://github.com/telefonicaid/fiware-orion) 
* [MongoDB](https://github.com/mongodb/mongo) 
* [Mosquitto](https://github.com/eclipse/mosquitto)

Note that **IoTA json** docker image can be deployed in multiple system architectures, currently supporting **amd64** and **arm64**.

## Deployment:
1. Select IoTA json stack from the community catalog.
2. Click deploy.

## Usage
* IoTA will be available on port 4041. For more information about this generic enabler and a step by step guide [click here](https://github.com/telefonicaid/iotagent-json/blob/master/docs/stepbystep.md).
* Orion will be available on port 1026. For more information about this generic enabler [click here](https://fiware-orion.readthedocs.io/en/master/).
* Mosquitto server will be available on port 1883. For more info about this external service [click here](https://mosquitto.org/).
* Note that this catalog item is only intended to deploy each of these services - in order to send and store information in Orion please follow the IoTA step by step mentioned above. 

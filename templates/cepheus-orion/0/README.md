# Cepheus + Orion stack

### Info:

This template deploys a collection of FIWARE generic enablers and external services which are required by them.

In this catalog item, the following technologies are used:

* [Cepheus](https://github.com/Orange-OpenSource/fiware-cepheus)
* [Orion](https://github.com/telefonicaid/fiware-orion)
* [MongoDB](https://github.com/mongodb/mongo)

Note that **Cepheus** docker image can be deployed in multiple system architectures, currently supporting **amd64** and **arm64**.

## Deployment:
1. Select Cepheus + Orion stack from the community catalog.
2. Click deploy.

## Usage
* Cepheus will be available on port 8080 and 8081. For more information about this generic enabler and a step by step guide [click here](https://github.com/Orange-OpenSource/fiware-cepheus/tree/master/doc/examples). 
* Orion will be available on port 1026. For more information about this generic enabler [click here](https://fiware-orion.readthedocs.io/en/master/).
* Note that this catalog item is only intended to deploy each of these services - in order to send and store information in Orion please follow the step by step mentioned above. 

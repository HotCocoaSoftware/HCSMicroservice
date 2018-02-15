# HCSMicroservice

This is a demo project for understanding microservices in Golang. 
Making use of protobuf and gRPC as the underlying transport protocol and containerizing services using Docker.

Following services has been created:
* Compartment
* Vessels

The stack used are: golang, mongodb, grpc, docker, go-micro
Steps to run locally 

* docker-compose pull
- pulls pre-built images from docker repo requires in out project e.g postgres,mongo

* docker-compose pull
- pulls pre-built images from docker repo requires in out project e.g postgres,mongo

* docker-compose run consignment - to run consignment service
* docker-compose run vessel-service - to run vessel service
* docker-compose run consignment-cli - cli service to see output of creating a consignment using consignment service 
   and while creating consignment, vessel service is communicated using grpc.
   
   

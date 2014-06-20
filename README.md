Go-Lab Smart Device Metadata Specification - Draft
==================================================

**Status:** Draft

This repository contains the specification of the metadata format for the Go-Lab Smart Device. The
aim of the metadata specification is to declare the services a Smart device provides and the data
needed to communicate with external services. The specification is making use of [Swagger](https://github.com/wordnik/swagger-spec/blob/master/versions/1.2.md)
to define the smart device APIs.

The specification is split in separate files:

- `spec/resource-listing.json`: This is the main specification that provides an overview of all APIs.
- `spec/client-declaration.json`: This file provides the detailed specification and data models
for the API to retrieve the client applications of the smart device.
- `spec/sensor-declaration.json`: This file provides the detailed specification and data models
for the API to retrieve sensor metadata and data.
- `spec/actuator-declaration.json`: This file provides the detailed specification and data models
for the API to retrieve actuator metadata and data.
- `spec/logging-declaration.json`: This file provides the detailed specification and data models
for the API to retrieve user activity and lab logging information.

Furthermore, some examples of how the specification is used can be found in the `examples` folder.

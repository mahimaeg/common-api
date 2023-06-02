# Common API Module 
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)  ![branch parameter](https://github.com/PSMRI/Common-API/actions/workflows/sast-and-package.yml/badge.svg)

Common API is a microservice whch acts as a gateway for AMRIT.There are 15 APIs that are exposed by Common-API.

### Primary Features
* Beneficiary Registration
* Call handling - 107,1097-mcts
* 
* Email Service
* SMS service

* Feedback service
* Beneficiary Medical History maintenance
* 
* Finding Institutions()master service
* KM file management
* Getting data from POCT

### Patient Visit Category
* Ante natal care (ANC)
* Post natal care (PNC)
* Neonatal and infant health care services
* Childhood and adolescent health care services including immunisation
* Family planning, contraceptive services and other reproductive health care
* Care for acute simple illnesses and minor ailments 
* Management of communicable diseases
* National health programs (General OPD)
* Prevention, screening and management of non communicable diseases (NCD)

## Building From Source
This microservice is built on Java, Spring boot framework and MySQL DB.

### Prerequisites 
* JDK 1.8
* Maven 

$ ./mvn clean install

## Installation
This service has been tested on Wildfly as the application server.

### Prerequisites 
* Wildfly (or any compatible app server)
* Redis
* MySQL Database

## Integrations
* Video Consultation

## Usage
All features have been exposed as REST endpoints. Refer to the SWAGGER API specification for details.s

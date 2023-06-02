# Common API Module 
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)  ![branch parameter](https://github.com/PSMRI/Common-API/actions/workflows/sast-and-package.yml/badge.svg)
Common API is one of the comprehensive applications of AMRIT designed to capture details of 7 Service packages as per guidelines which should be available at Health and Wellness centre.0

### Primary Features
* Beneficiary Registration
* Call handling
* Create Order
* Email Service
* Door to door
* Feedback service
* Beneficiary Medical History
* Honeywell Service
* Finding Institutions
* KM file management
* Getting data from POCT devices

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

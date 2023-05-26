# MBSE-Capella-Autonomous
This repo is for modelling an MBSE project done on Capella using the Arcadia method. 

## Functional Architecture for Steer Collaboration in ADAS

This project presents a detailed model of the functional architecture of an Advanced Driver Assistance System. The system under focus for development is an SAE Level 3 Autonomy system - namely being Conditionally automated.

To briefly describe a level 3 Autonomy system:
* This Automated Driving system is self monitoring
* Within a stipulated lead time, the driver needs to take back the Driving task in this system.

## Steer Collaboration
In this project, the concept of Steer collaboration is being set and the development chain involving a 9 layer abstraction has been designed.
Steer collaboration is a highway / road safety concept similar to industry LKA and LDW systems.
The concept can be described as a system involving the belief in driver intervention and cooperation. The driver at anytime can temporarily participate in the engagement of the steering wheel to change path. The vehicle is expected to re-engage Automated Driving once the HOD system detections that the driver has taken hands off the wheel.

The driver always remains informed about the autonomous path and as a result the steering effort becomes a function of human path deviation signals only.

## Architecture Modelling
The modelling process has broadly been classified into:
* Operational Analysis - Define Stakeholder Needs
* System Analysis - Formalize System Requirements
* Logical Architecture - Develop System Architectural Design
* Physical Architecture - Develop System Architectural Design
* Formalize Components Requirement

In relation to the above, the following models were modelled:
 * For defining operational entities and capabilities
  * Operational Entity Breakdown Diagram
  * Operational Capabilities Diagram
  * Operational Activity Interaction Diagram

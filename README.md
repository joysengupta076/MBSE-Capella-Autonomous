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
  * System Architecture Diagram
  * Logical Architecture Diagram
  * Functional Dataflow Bank Diagram
  * Functional Breakdown Diagram
  * Physical Architecture Diagram

### Operational Entity Breakdown - OEBD
Diagram giving a heirarchical relationship between the entities and actors involved in the scenario. The Ego vehicle involves conceptual entities of its own such as Motion Planning, perception etc. The Physical entity in the ODD coming under the umbrella of the Road system along with other non-ego actors such as Pedestrians and the Driver.

### Operational Capabilities - OCB
Depiction of the features or capabilites and the entities facilitating said features. Here, the capability of enhancing the driver's comfort is facilitated by All the entities shown in the diagram.

### Operational Activity Interaction - OAIB
The activites are explained in the form of a process flowchart where for example, here the driver intervenes after monitoring the environment to change the path. Hence the corresponding process is the request for temporary handover for steering, acceleration and braking from the autonomous control.

### System Architecture - SAB
Detailed architecture diagram in this case, the motion control system. 

### Logical Architecture - LAB
Detailed logical relationship for the processes with each function, for example here the Motion Control System.

### Functional Data Flow - LDFB
Diagram of data flow between sub-functions or functions in resolution of outports and inports. Here the lateral control functions and its sub functions are shown involving the exchange between the autonomous steering control and cooperative handover.

### Functional Breakdown - LFBD
Diagram showing heirarchical breakdown of Lateral Control functionality and the sub-functions.

### Physical Layer Architecture - PAB
Diagram showing where the elements of the architecture such as electronic control units, actuators, interlinking CAN buses etc. are physically located with respect to the vehicle. The blue boxes represent the functionalities being deployed by these elements. On overlay of a sedan has been used to depict approximate locations of the components.

### Physical Data Flow - PDFB
To facilitate communications and links between the elements in the physical layer, a representation diagram involving the functions and the design for the communication links.

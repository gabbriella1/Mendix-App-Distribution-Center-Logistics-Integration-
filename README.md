# Mendix-App-Distribution-Center-Logistics-Integration-

A logistics and business process integration solution developed in Mendix simulating the coordination between a Distribution Center (DC), Transport Companies (TCs), and a Control Tower (CT) for efficient order delivery.

---

## Project Overview

This project models and simulates a real-world logistics case for the fictional supplier Uniprocterlevergamble, which manages deliveries to supermarkets. It focuses on:

- Receiving customer orders  
- Requesting transport quotes from TCs  
- Managing truck movement and loading inside the DC  
- Coordinating with external stakeholders via APIs and services

The business logic and integration were implemented using **Mendix**, with real-time communication through REST APIs and OData.

---

## Objectives

- Simulate logistics processes across multiple stakeholders  
- Model business logic using BPMN  
- Create Mendix apps for internal and external systems  
- Enable real-time truck and order tracking via REST & OData

---

## Business Process Model

The full supply chain process was modeled using BPMN. It includes quote requests, truck coordination, order staging, location tracking, and delivery confirmation. [BPMN Diagram](./BPMN%20of%20the%20whole%20business%20process%20(1).png)

---

## Technologies Used

- **Mendix** (low-code app development)  
- **REST APIs** (for real-time truck orders and status updates)  
- **OData Protocol** (truck ETA visibility for Control Tower)  
- **Postman** (API testing and validation)  
- **WorldTimeAPI** (time synchronization)  
- **Draw.io** (BPMN process modeling)

---

## Key Features

- Request and evaluate transport quotes from multiple TCs  
- Dynamic truck load assignment (partial/full)  
- Internal logistics handling: staging area, queues, loading  
- External communication via REST and OData services  
- Integration with real-time clock service for timestamp accuracy  

---

## Integration & APIs

- Implemented REST APIs for:
  - Submitting truck ETAs  
  - Notifying when trucks are ready for departure  
- Used OData services to expose live truck updates  
- Connected to WorldTimeAPI for synchronized order handling  
- All APIs tested via **Postman** and fully integrated with Control Tower.

---

## Testing & Collaboration

- Extensive testing using Postman for all endpoints  
- Collaboration with Control Tower Group for full integration  
- Validated business flow: quote handling -> truck assignment -> order dispatch  
- Covered edge cases including partial loads and transport reassignments

---

## Project Files

- `CT_dummy_App.mpk` – Control Tower Mendix App  
- `DistributionCenterBIT_2.mpk` – Main Distribution Center App  

---

## Report

Refer to the full report for a more detailed explanation:  [`report`](./report.pdf)

---

## Project Contributors
Dani Mahaini
Alan Nessipbayev
Gabriela Todorova
Miglena Pavlova

---

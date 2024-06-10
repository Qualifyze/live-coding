<br />
<br />

<p align="center">
  <img src=".images/video-call.png" alt="qualifyze live coding challenge" width="80" height="80">
</p>


<h1 align="center">
  <b>
    Qualifyze Live Coding Challenge
  </b>
  <br />
  <h4 align="center"><small>Auditor Assignment System</small></h4>
</h1>

<br />

### Context

We are developing a system to manage and schedule audits for various suppliers, ensuring efficient use of our auditors and adherence to different client subscription levels. This solution aims to address typical scenarios where companies require timely and fair distribution of audit resources.

### Project Overview

The system will handle the scheduling of audits for a supplier company, "Supplier 4 Live," with the following requirements and constraints:

1. **Auditor Availability:**
    - An auditor can audit only one site per day.
    - We aim to distribute the audits proportionally among auditors to ensure fairness.

2. **Subscription Levels:**
    - Clients pay for different subscription levels, each with distinct commitments for audit report delivery:
        - **Essentials:** Report available no earlier than 4 weeks after the request, with a maximum wait time of 4 months.
        - **Advanced:** Report available no earlier than 3 weeks after the request, with a maximum wait time of 2 months.
        - **Premium:** Report published as soon as it is ready, with a maximum wait time of 4 weeks.

3. **Performance Considerations:**
    - Ensure the system can handle concurrent audit requests efficiently.
    - The audit assignment logic should balance the load among auditors while adhering to subscription-level constraints.

### Challenge Description

You have been provided with the problem statement a few days in advance to familiarize yourself with the requirements and constraints. During the live coding session, which will last 90 minutes, your task is to design and implement a part of this system, focusing on:

1. **System Design:**
    - Design an architecture that supports the requirements above, using principles of hexagonal architecture and Domain-Driven Design (DDD).
    - Ensure the system can manage auditor availability, client subscriptions, and audit scheduling.

2. **Implementation:**
    - Implement a function to assign auditors to sites, ensuring that:
        - Each auditor audits only one site per day.
        - Audits are distributed proportionally among auditors.
        - Adherence to subscription-level constraints for report delivery.

3. **Additional Complexity:**
    - Implement a basic event management system to handle notifications for audit assignments and report deliveries.
    - Consider concurrency issues that might arise from multiple audit requests and provide solutions to handle them efficiently.

### Example Scenario

- **Client:** "Farma World Champion SLU"
- **Supplier:** "Supplier 4 Live"
- **Subscription Levels:** Essentials, Advanced, Premium

The system should schedule audits as per the subscription level constraints and assign auditors proportionally while ensuring that no auditor is double-booked on any given day.

#### Key Points to Address

- **Architecture Design:**
    - Explain how you would organize the system using hexagonal architecture and DDD.
    - Identify key aggregates, entities, and value objects.

- **Event Management:**
    - Describe how you would implement event handling for notifications.

- **Concurrency and Performance:**
    - Discuss how you would manage concurrency in audit assignments.
    - Outline strategies to optimize system performance.

#### Preparation

Before the live coding session, review the problem statement and prepare any questions you may have. During the session, you will start directly with the design and implementation tasks, given the limited time of 90 minutes.

By tackling this challenge, you will demonstrate your ability to design scalable systems, manage concurrency, and implement efficient solutions for complex scheduling problems.

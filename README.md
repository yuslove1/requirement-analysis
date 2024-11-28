# Requirement Analysis in Software Development

This repository is dedicated to documenting the requirement analysis phase of a software development project.  Requirement analysis is a crucial process that involves eliciting, analyzing, specifying, and validating the needs and constraints of stakeholders for a software system. This repository will serve as a central hub for all requirement-related artifacts, including functional and non-functional requirements, use cases, diagrams, and acceptance criteria.  The goal is to provide a clear and comprehensive understanding of the system's intended behavior and ensure that the development process aligns with stakeholder expectations.


## What is Requirement Analysis?

Requirement analysis is a crucial phase in the Software Development Life Cycle (SDLC),where the project team gathers, analyzes, and defines the requirements of the software product to be developed. This process ensures that all stakeholders have a clear and mutual understanding of what the system should do, how it should perform and what limitations it must operate within. 

The process typically includes the following activities:

* **Requirements Gathering:** Gathering information from stakeholders (users, clients, business analysts, etc.) through interviews, surveys, workshops, and document analysis.
* **Requirements Elicitation:** Generating idea and gathering requirement through brainstorming and creating prototypes to help stakeholders visualize the system and refine their requirements.
* **Requirements Analysis:** Organizing, prioritizing, and modeling the gathered information to identify inconsistencies, ambiguities, and missing details.
* **Requirements Documentation:** Documenting the requirements in a clear, concise, and unambiguous manner, often using use cases, user stories, or formal specifications.
* **Requirements Validation:** Ensuring that the documented requirements accurately reflect the stakeholders' needs and are feasible to implement.

**Importance in the SDLC:**

Requirement analysis is crucial for software project success. It reduces development costs by minimizing rework, improves communication between stakeholders and developers, enhances software quality by meeting user needs, manages scope creep, and increases the likelihood of on-time and within-budget project completion.


## Why is Requirement Analysis Important?

Requirement analysis is a cornerstone of successful software development.  Here are four key reasons highlighting its importance:

* **Clarity and Understanding:** It helps in understanding what the stakeholders expect from the software, reducing ambiguity.
* **Scope Definition:** Clearly defines the scope of the project, which helps in preventing scope creep.
* **Cost and Time Estimation:** Facilitates accurate estimation of project cost, resources, and time.
* **Quality Assurance:** Ensures that the final product meets the specified requirements, leading to higher customer satisfaction.

## Key Activities in Requirement Analysis.

**1. Requirement Gathering**
* Interviews: Conducting interviews with stakeholders to gather detailed information about their needs and expectations.
Surveys/Questionnaires: Distributing surveys to collect requirements from a larger audience.
* Workshops: Organizing workshops with stakeholders to discuss and gather requirements.
* Observation: Observing end-users in their working environment to understand their needs.
* Document Analysis: Reviewing existing documentation and systems to understand current functionalities and requirements.

**2. Requirement Elicitation**
* Brainstorming: Conducting brainstorming sessions to generate ideas and gather requirements.
* Focus Groups: Holding focus group discussions with selected stakeholders to gather detailed requirements.
* Prototyping: Creating prototypes to help stakeholders visualize the system and refine their requirements.

**3. Requirement Documentation**
* Requirement Specification Document: Creating a detailed document that lists all functional and non-functional requirements.
* User Stories: Writing user stories to describe functionalities from the user’s perspective.
* Use Cases: Creating use case diagrams to show interactions between users and the system.

**4. Requirement Analysis and Modeling**
* Requirement Prioritization: Prioritizing requirements based on their importance and impact on the project.
* Feasibility Analysis: Assessing the feasibility of requirements in terms of technical, financial, and time constraints.
* Modeling: Creating models (e.g., data flow diagrams, entity-relationship diagrams) to visualize and analyze requirements.

**5. Requirement Validation**
* Review and Approval: Reviewing the documented requirements with stakeholders to ensure accuracy and completeness.
* Acceptance Criteria: Defining clear acceptance criteria for each requirement to ensure they meet the expected standards.
* Traceability: Establishing traceability matrices to ensure all requirements are addressed during development and testing.

## Types of Requirements

Requirements are broadly categorized into functional and non-functional requirements.  Understanding the distinction between these two types is crucial for effective requirement analysis.

### Functional Requirements

Functional requirements define *what* a system should do. They describe the specific functionalities and features the system must provide to meet the user's needs.  These requirements are often expressed as actions or behaviors the system should perform.

**Examples for a Booking Management System (based on the provided case study):**

* **Search Functionality:** Users should be able to search for available hotels based on location, date range, number of guests, and other criteria.
* **Booking Functionality:** Users should be able to book a selected hotel room and receive a booking confirmation.
* **Payment Processing:** The system should integrate with a payment gateway to process online payments securely.
* **Hotel Management Portal:** Hotel managers should be able to manage their hotel listings, including updating availability, pricing, and room details.
* **User Authentication:** Users should be able to register, log in, and manage their profiles.
* **Booking Management:** Users should be able to view, modify, or cancel their bookings.
* **Notification System:** The system should send notifications to users and hotel managers regarding booking confirmations, updates, and cancellations.


### Non-Functional Requirements

Non-functional requirements define *how* a system should perform. They describe the qualities and constraints that the system must adhere to, such as performance, security, usability, and scalability.  These requirements are often expressed as constraints or targets.

**Examples for a Booking Management System (based on the provided case study):**

* **Performance:**  The system should respond to user requests within 2 seconds.
* **Security:** User data and transactions should be protected using secure encryption and authentication mechanisms.
* **Scalability:** The system should be able to handle a large number of concurrent users and bookings without performance degradation.
* **Usability:** The system should have a user-friendly interface that is easy to navigate and use.
* **Reliability:** The system should have a high uptime (e.g., 99.9%) and be resilient to failures.
* **Data Archival:**  Older booking data should be archived efficiently (using Cassandra as mentioned in the case study).
* **Caching:**  The system should utilize caching (Redis as mentioned in the case study) to improve performance and reduce database load.


## Use Case Diagrams

A Use Case Diagram is a visual representation of the interactions between actors (users or external systems) and a system to achieve specific goals.  It provides a high-level overview of the system's functionality from the user's perspective.

**Benefits of Use Case Diagrams:**

* **Clarify System Functionality:**  Use case diagrams help to clearly define the scope of the system and the different functionalities it provides.
* **Identify Actors and Their Interactions:** They visually represent the actors involved with the system and how they interact with it.
* **Facilitate Communication:** Use case diagrams serve as a communication tool between stakeholders and the development team, ensuring a shared understanding of the system's behavior.
* **Simplify Requirements Elicitation:**  They can be used to elicit requirements from stakeholders by visually representing different scenarios and use cases.
* **Aid in System Design and Testing:** Use case diagrams provide a foundation for system design and testing by outlining the different functionalities that need to be implemented and tested.

**Use Case Diagram for the Booking System:**

The following diagram illustrates the use cases for the booking management system:

alx-booking-uc.png

**Explanation of Actors and Use Cases:**

* **Customer:**  Can search for hotels, make bookings, manage bookings (modify/cancel), and view booking details.
* **Hotel Manager:** Can manage hotel listings (add/update/remove), view booking details, and receive notifications.
* **Payment System:** An external system that processes payments.

* **Search for Hotel:** Allows the customer to search for available hotels based on various criteria.
* **Make Booking:** Enables the customer to book a selected hotel room.
* **Manage Booking:** Allows the customer to modify or cancel an existing booking.
* **View Booking Details:** Allows both customers and hotel managers to view details of a specific booking.
* **Manage Hotel Listing:** Enables the hotel manager to manage their hotel listings.
* **Process Payment:**  Interaction with the payment system to process payments.
* **Send Notification:**  Sends notifications to customers and hotel managers.

## Acceptance Criteria

Acceptance criteria are specific conditions that must be met for a user story or feature to be considered complete and acceptable by the stakeholders.  They define the boundaries of a feature and provide a clear definition of "done."

**Importance of Acceptance Criteria:**

* **Provide Clarity and Shared Understanding:** Acceptance criteria ensure that everyone involved (developers, testers, stakeholders) has a shared understanding of what needs to be built and how it should function.
* **Facilitate Testing and Verification:**  They provide a basis for creating test cases and verifying that the implemented feature meets the requirements.
* **Prevent Scope Creep:**  Clearly defined acceptance criteria help prevent scope creep by setting boundaries for the feature's functionality.
* **Improve Product Quality:** By focusing on specific criteria, acceptance criteria help ensure that the delivered feature is of high quality and meets user expectations.
* **Streamline the Acceptance Process:**  Well-defined acceptance criteria make the acceptance process smoother and more efficient.

**Example Acceptance Criteria for the Checkout Feature:**

Let's consider the "Checkout" feature in the booking management system. Here are some examples of acceptance criteria:

* **Functional:**
   * The user must be able to enter valid payment information (card number, expiry date, CVV).
   * The system must validate the payment information and display appropriate error messages for invalid input.
   * The system must integrate with the payment gateway to process the payment securely.
   * Upon successful payment, the system must generate a booking confirmation and send it to the user via email.
   * The system must update the booking status to "Confirmed" after successful payment.

* **Non-Functional:**
   * The checkout process should be completed within 3 seconds under normal network conditions.
   * The payment information should be encrypted during transmission and storage.
   * The checkout page should be accessible on different devices (desktop, mobile, tablet).
   * The checkout process should be user-friendly and intuitive.
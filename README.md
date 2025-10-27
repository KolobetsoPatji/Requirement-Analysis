# Requirement Analysis in Software Development

This repository contains a project focused on the requirement analysis phase of the Software Development Life Cycle (SDLC). Its purpose is to structure requirements for a booking management system. The work in this repository simulates real-world software planning and ensures clarity accuracy before the development stage begins.

## What is Requirement Analysis?

Requirement analysis is the systematic process of discovering, documenting, validating, and managing the needs and constraints of stakeholders for a software system. It transforms often-ambiguous business goals and user needs into clear, actionable specifications that guide design, development, and verification activities.

Key activities in requirement analysis include:
- **Elicitation:** Gathering information from stakeholders through interviews, workshops, surveys, observation, and document reviews.
- **Analysis and Modeling:** Organizing and refining gathered information into structured artifacts such as use cases, user stories, process flows, data models, and diagrams.
- **Specification and Documentation:** Writing clear, testable functional and non-functional requirements, acceptance criteria, and interface descriptions that become part of the Software Requirements Specification (SRS).
- **Validation and Verification:** Reviewing requirements with stakeholders to ensure they are complete, consistent, feasible, and aligned with business objectives.
- **Prioritization and Traceability:** Ranking requirements for incremental delivery (e.g., MoSCoW) and maintaining mappings betwwen requireents, designs, and tests to track coverage and changes.

### Importance in the SDLC

Requirement analysis is foundational to the Software Development Life Cycle (SDLC). Its importance includes: 
- **Reduces rework and cost:** Clear, validated requirements prevent misunderstandings that lead to expensive rework later in the project.
- **Aligns stakeholders:** It creates a shared understanding among users, product owners, developers, and testers, ensuring the delivered product meets actual needs.
- **Improves planning and estimation:** Well-defined requirements enable more accurate effort estimates, scope control, and risk assessment.
- **Enables testability and quality assurance:** Documented acceptance criteria and traceability allow testers to verify that requirements are satisfied and to detect defects earlier.
- **Supports maintainability and scalabilty:** Requirements captured with future growth and non-functional concerns in mind produce systems that are easier to extend and operate under load.
- **Provides a clear handoff:** A complete SRS and associated diagrams (ERD, component and context diagrams, UI flows) serve as a professional handoff to design and development teams.

In short, requirement analysis turns ideas into a dependable blueprint. When done well, it makes development faster, cheaper, and more likely to succeed.

## Why is Requirement Analysis Important?

Requirement Analysis plays a critical role in the Software Development Life Cycle, because it ensure that the final product trul meets the needs and expectations of its users. Without this phase, teams risk building the wrong solution, wasting time, effort, and resources.

Here are three key reasons why requirement analysis is essential:

### 1. Prevents Miscommunication and Rework
It establishes a shared understanding between developers, stakeholders, and users. Clear and validated requirements reduce the chances of misunderstandings and prevent costly rework later in the project.

### 2. Guides Accurate Project Planning
Well-defined requirements enable better estimates for timelines, budget, workload, and resources. This leads to improved planning, scheduling, and risk management throughout the development process.

### 3. Ensures Product Quality and User Satisfaction
By defining detailed acceptance criteria and tracaeability, requirement analysis ensures that testing and validation activities confirm that the delivered software works as expected and satisfies user needs. This leads to higher-quality sstems and happier users.

## Key Activities in Requirement Analysis

The requirement analysis phase involves several essential steps that ensure the project is grounded in accurate and complete understanding of stakeholder needs. These activities include: 

- **Requirement Gathering**
  - Collecting initial information from stakeholders through surveys, interviews, meetings, and research to capture needs and expectations.

- **Requirement Elicitation**
  -Engaging with stakeholders to uncover hidden needs, clarify assumptions, and expand on the details of the requirements.

- **Requirement Documentation**
  - Converting gathered requirements into structured artifacts such as requirement specifications, user stories, and diagrams.

- **Requirement Analysis and Modeling**
  -Evaluating and breaking down requirements to ensure they are feasible, relevant, unambiguous, consistent, and complete. This includes modeling the system using tools like ERD and use case diagrams.

- **Requirement Validation**
  -Reviewing documented requirements with stakeholders to confirm accuracy, alignment with business goals, and that they address the identified problems effectively.

  ## Types of Requirements

  Software requirements are generally classified into two categories: **Functional Requirements** and **Non-Functional Requirements**.

  ### Functional Requirements
  These describe what the system should do. They define specific behaviors and functionalities that enable users to accomplish their goals.

  **Examples for the Booking Management system:**
  -Users can search available rooms based on location, check-in and check-out dates.
  -Users can create bookings and receive confirmation notifications.
  -Service providers can update room availability and pricing.
  -The system stores booking details for future reference.

  ### Non-Functional Requirements
  These define the quality attributes and constraints of the system. They describe how well the system performs tasks rather than what it does.

  **Examples for the Booking Management System:**
  - The system should handle up to 10,000 concurrent booking requests during peak times.
  - Responses should load within 2 seconds under normal usage.
  - All user data should be encrypted in transit and at rest.
  - The system must be available 99,5 percent of the year with minimal downtime.

  ## Use Case Diagrams

  A use diagram provides a visual representation of how users interact with a system. It highlights key user (actors) and the major functions ( use cases)

  ### Actors
  -Customer
  -Service Provider
  -Admin

  ### Use Cases
  - Register & Login
  - Search for rooms
  - Book a room
  - Cancel booking
  - Manage availability (Provider)
  - Send notifications (System)

  Below is an example of the use case diagram for the Booking Management System:

  <img width="10104" height="1488" alt="image" src="https://github.com/user-attachments/assets/d4c21d92-ec7b-4f67-b935-c8291b2584c6" />

 ## Acceptance Criteria

 Acceptance criteria are predefined conditions that a system feature must meet to be considered complete and acceptable to stakeholders. They ensure clarity by explaining exactly what success looks like for each requirement. Acceptance criteria also supports testing, helping teams verify that a delivery satisfies user needs.

 ### Example: Checkout Feature (Booking Management System)

 - Given a user has selected a room and provided valid payment information, when they confirm the booking, then the system processes the payment securely and records the booking.
 - The user should receive a confirmation message on-screen and via email after a successful checkout.
 - If the payment fails, the system must notify the user and not create a booking.
 - The system must display the booking summary before final confirmation to allow users to make changes if needed.

  

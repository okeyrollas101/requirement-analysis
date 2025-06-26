# Requirement Analysis in Software Development

Welcome to my Requirement Analysis project- a real-world simulation of documenting and analysing the foundational needs of a software system before development begins.

## Purpose Of This Repository

This repository serves as a structured space to capture the complete requirement analysis process for a **Booking Management System**. It focuses on creating industry-standard documentation that clearly defines:

- Project scope and stakeholder needs
- Functional and non-functional requirements
- Visual system representations using diagrams
- Use case definitions and acceptance criteria

Through this project, we aim to demonstrate the critical thinking and planning required in the **Requirement Analysis phase of the SDLC**, ensuring that systems are built on clarity, structure, and user-aligned expectations.

> "Well defined requirements are the blueprint a great software"

## What is Requirement Analysis?

**Requirement Analysis** is a critical phase in the Software Development Life Cycle (SDLC) where the needs, expectations, and constraints of stakeholders are gathered, interpreted, and documented to define the scope of a software project.

This process ensures that development is aligned with business goals, user expectations, and technical feasibility, reducing the risk of costly rework and scope creep later in the project.

### 🎯 Key Objectives of Requirement Analysis:

- Understand what the client or end-user truly needs
- Identify and resolve ambiguities or contradictions
- Translate abstract needs into clear, actionable requirements
- Lay the foundation for design, development, and testing

Requirement Analysis plays a foundational role in the success of any software project. Here's why it’s indispensable:

- 🧭 **Direction and Clarity**
 
    Clearly defined requirements ensure that the development team builds the right solution, not just a solution.

- 💸 **Cost and Time Efficiency**
  
    Catching unclear or conflicting requirements early reduces the need for revisions during the development or testing phases.

- 🧩 **Design and Architecture Alignment**
  
    Well-structured requirements guide technical design decisions, allowing developers to build scalable and maintainable systems.

- 📐 **Testability and Validation**

    Requirements serve as a benchmark for validating and verifying software functionality through test cases and user acceptance testing (UAT).

- 🤝 **Stakeholder Satisfaction**

    Continuous engagement with stakeholders during this phase ensures alignment between what is needed and what is delivered.

## Why is Requirement Analysis Important?

Requirement Analysis is not just the starting point of software development — it’s the strategic compass that guides the rigorous journey of software development.

Below are three key detailed reasons why Requirement Analysis is vital in the Software Development Life Cycle (SDLC):

### 1️⃣ Reduces Costly Rework and Scope Creep

Misunderstood or poorly documented requirements often lead to unnecessary revisions, missed features, or functionality that doesn’t align with user expectations.
**Clear, early analysis saves time, budget, and engineering effort**.

> Studies show that fixing a requirement defect after development can cost up to 100x more than fixing it during the analysis phase.

### 2️⃣ Aligns Business Goals with Technical Execution

Requirement Analysis ensures that development efforts stay focused on delivering business value.
By translating stakeholder goals into technical objectives, teams avoid building features that are irrelevant or redundant.

> A system that meets technical specs but fails to solve user problems is still a failed product.

### 3️⃣ Enables Accurate Planning and Prioritisation

With a solid understanding of all functional and non-functional requirements, teams can estimate timeframes, allocate resources, and define realistic milestones.
This leads to better **project scoping, risk management, and delivery timelines**.

> Good requirements = better roadmaps, sprints, and stakeholder trust.

> “You can’t build what you don’t understand — and Requirement Analysis ensures you do.”

## 🔍 Key Activities in Requirement Analysis

Requirement Analysis is a multi-step process that transforms initial project ideas into a structured foundation for software design and development. Below are the five core activities that define this process:

### 1. Requirement Gathering

- Collect information from stakeholders, end-users, clients, and subject matter experts
- Understand the business context, problems, and goals
- Identify stakeholders' needs, expectations, and pain points
- Tools used: interviews, questionnaires, workshops, observation

### 2. Requirement Elicitation

- Go beyond surface-level needs to uncover implicit and hidden requirements
- Use techniques like brainstorming, use case development, and scenario analysis
- Encourage stakeholder collaboration and clarify conflicting requirements
- Ensures that needs are not just heard, but deeply understood

### 3. Requirement Documentation

- Convert gathered insights into formal, structured documentation
- Clearly distinguish between functional and non-functional requirements
- Maintain version-controlled and traceable documentation using tools like markdown, spreadsheets, or requirement management software
- Serves as the “source of truth” for all future development stages

### 4. Requirement Analysis and Modelling

- Organise and structure requirements logically
- Identify dependencies, constraints, and priorities
- Use diagrams (e.g. use case diagrams, context diagrams) to model the system
- Translate business requirements into technical understanding

### 5. Requirement Validation

- Review requirements with stakeholders to ensure accuracy and completeness
- Identify gaps, ambiguities, or conflicts
- Verify that each requirement is testable and aligns with business objectives
- Use acceptance criteria or formal validation checklists

> These activities are iterative and collaborative, ensuring the foundation of development is stable, scalable, and aligned with user needs.

## 🧾 Types of Requirements

In the context of the Booking Management System, requirements can be divided into two main categories: **Functional Requirements and Non-functional Requirements**. Both are essential for defining what the system should do and how it should perform.

### ⚙️ Functional Requirements

Functional requirements describe the specific behaviours, functions, and features the system must perform. These define what the system should do to fulfil business and user needs.

**Examples for the Booking Management System:**

- Users must be able to **register and log** in to the platform.
- Users should be able to **search for available rooms** by date, location, or category.
- The system must allow **booking confirmation with payment integration**.
- Admins should be able to **view, add, update, and delete bookings**.
- Users must receive **booking confirmation via email**.
- The system should allow customers to **view their booking history**.

> Functional requirements define the actions or services the system must deliver.

### 📈 Non-functional Requirements

Non-functional requirements specify the **quality attributes, performance constraints, and operational standards** the system must meet. These ensure that the functional features are usable, reliable, and scalable.

**Examples for the Booking Management System:**

- The platform should be **accessible on both desktop and mobile devices**.
- The system should handle up to **1,000 concurrent users without degradation**.
- **Booking confirmation emails** must be delivered within **10 seconds** of a successful transaction.
- The system must be available **99.9% of the time** during business hours.
- User data must be **encrypted and securely stored** in compliance with data protection laws.
- The user interface must load **within 2 seconds** for 90% of users on 4G connections.

> Non-functional requirements define the quality, constraints, and standards under which the system operates.

> Both types of requirements are critical- functional tells us what to build, while non-functional tells us how well it must work.

## Use Case Diagrams

A **Use Case Diagram** is a visual representation of the interactions between different actors (users or systems) and the functionalities (use cases) of a system.

It helps stakeholders quickly understand:

- Who will use the system
- What actions each user can perform
- The system's scope and expected behaviours

This form of modelling supports requirement validation and system planning by capturing functional interactions in a clear and concise way.

### 📌 Use Case Diagram for Booking Management System

The diagram below illustrates the main actors and their interactions with the core functionalities of the Booking Management System:

![alx-booking-uc](https://github.com/user-attachments/assets/d7ac487f-a498-4bbf-a3fd-ce7ddeb9bce0)

> 🎭 Actors like customers and administrators interact with use cases such as booking rooms, managing reservations, and handling user accounts.

## Acceptance Criteria

**Acceptance Criteria** are predefined conditions that a software feature or user story must meet to be considered complete and acceptable by stakeholders. They serve as the **quality gate** that aligns developers, testers, and product owners around clear expectations.

### Why Acceptance Criteria Matter

- **Clarity**: Eliminates ambiguity by translating requirements into testable outcomes.
- **Validation**: Ensures that features meet user needs and business goals.
- **Testability**: Enables QA teams to create accurate and automated test cases.
- **Agile Alignment**: Supports iterative development by providing a “definition of done” for each feature.

### Example: Checkout Feature – Acceptance Criteria

Feature: **Booking Checkout Process**

**Given**:

- A user has selected a room and chosen booking dates

**When**:

- The user clicks the “Checkout” button

**Then**:

- The system should display a summary of the booking (room, dates, total cost)
- The user should be able to enter payment details and submit the form securely
- Upon successful payment, the system should:
 i. Save the booking to the database
 ii. Send a confirmation email to the user
iii. Redirect the user to a “Booking Successful” page
- If payment fails:
i. An error message should be shown
ii. The user should not be charged
iii. The user should remain on the checkout page

> 🧠 This example follows the “Given–When–Then” format commonly used in Behaviour-Driven Development (BDD).

> ✨ Acceptance Criteria transform “just code” into working, validated software that delivers real value.






## What is Requirement Analysis?

Requirement Analysis is a foundational phase in the Software Development Life Cycle (SDLC). It involves gathering, understanding, analyzing, and documenting the needs and expectations of stakeholders for a software system. The goal is to ensure the software meets user and business needs before development begins.

### Why is it important?

- ✅ It defines the scope and boundaries of the project.
- ✅ It prevents misunderstandings between developers and clients.
- ✅ It minimizes costly revisions during development.
- ✅ It ensures that the delivered system meets user expectations.
- ✅ It helps in estimating resources, time, and cost accurately.

Without proper requirement analysis, software projects are more likely to fail due to unmet expectations or overlooked features.
## Why is Requirement Analysis Important?
Requirement Analysis plays a critical role in the success of any software project. It serves as the foundation for design, development, and deployment. Below are three key reasons why it is important in the Software Development Life Cycle (SDLC):
### 1. Clarity of Project Scope
Requirement analysis helps clearly define what needs to be built. It prevents scope creep and ensures all stakeholders have a shared understanding of the project goals, features, and limitations.
### 2. Reduces Development Errors
By identifying the functional and non-functional requirements early, development teams can avoid costly mistakes and misunderstandings that often occur later in the project lifecycle.
### 3. Saves Time and Cost
Well-documented requirements allow for better planning, accurate estimation of resources, and early identification of risks — leading to faster development cycles and reduced project costs.
## Key Activities in Requirement Analysis

Requirement Analysis consists of several essential activities that ensure the software product aligns with stakeholder expectations and technical feasibility. Below are the five key activities:

- **Requirement Gathering**  
  Collecting information from stakeholders to understand their needs, expectations, and constraints. This includes interviews, questionnaires, observations, and document reviews.

- **Requirement Elicitation**  
  Engaging stakeholders to clarify, explore, and discover requirements through workshops, brainstorming sessions, use case discussions, and prototyping.

- **Requirement Documentation**  
  Structuring and recording the gathered requirements in a clear and organized format, such as Software Requirement Specifications (SRS), user stories, or requirement traceability matrices.

- **Requirement Analysis and Modeling**  
  Evaluating requirements for feasibility, consistency, and completeness. This may include creating diagrams (e.g., data flow diagrams, use case models) to visualize system behavior and relationships.

- **Requirement Validation**  
  Ensuring the documented requirements accurately reflect stakeholder needs and are agreed upon. Techniques include walkthroughs, reviews, and validation meetings with stakeholders.
  
  ## Types of Requirements

In software engineering, requirements are broadly categorized into two types: functional and non-functional. Understanding both is essential for designing robust and user-centered systems.

### Functional Requirements

Functional requirements describe **what the system should do** — the specific behavior or functions of the software.

These are features that define how the system responds to input, processes data, and produces output.

**Examples for a Booking Management System:**
- Users should be able to **search for available properties** based on location, price, and dates.
- Guests can **book a property** by selecting check-in and check-out dates.
- Hosts can **add, update, or delete their listings**.
- The system should **send confirmation emails** after a successful booking.
- Users should be able to **register, log in, and manage their profiles**.

### Non-functional Requirements

Non-functional requirements define **how the system should perform**. These include quality attributes such as performance, security, usability, and scalability.

They do not specify actions but set constraints on how the system functions.

**Examples for a Booking Management System:**
- The application should **load search results within 2 seconds**.
- The system should be available **24/7 with 99.9% uptime**.
- User data must be **encrypted and stored securely**.
- The app must be **responsive and mobile-friendly**.
- The system should support **up to 100,000 concurrent users** during peak seasons.

## Use Case Diagrams

Use Case Diagrams are visual models that represent the interactions between users (actors) and the system. These diagrams help stakeholders and developers understand what the system should do by illustrating system functionality from a user's point of view.

### Benefits of Use Case Diagrams

- Help visualize the system’s scope and boundaries
- Simplify communication between technical and non-technical stakeholders
- Highlight core system functionality at a glance
- Serve as a basis for identifying functional requirements

### Use Case Diagram for Booking Management System

The diagram below illustrates the primary interactions between actors and the booking system.

**Actors:**
- Guest (User)
- Host
- Admin

**Use Cases:**
- Register / Login
- Search for Properties
- Book Property
- Make Payment
- Add or Manage Listings
- Approve Listings
- Manage Users
## Acceptance Criteria

Acceptance Criteria are conditions that a software product must satisfy to be accepted by the end user, customer, or stakeholders. These are used to confirm that a feature or functionality meets the requirements and performs as expected.

### Why Acceptance Criteria are Important

- ✅ Define clear expectations for a feature's behavior and scope
- ✅ Help avoid misunderstandings between developers, testers, and stakeholders
- ✅ Serve as the basis for test cases and quality assurance
- ✅ Ensure traceability between requirements and delivered features

### Example: Acceptance Criteria for the Checkout Feature

**Feature:** Checkout Page for Booking

**Acceptance Criteria:**

- ✅ User must be logged in to access the checkout page
- ✅ User must see a summary of selected property, dates, and pricing
- ✅ User must be able to enter or select a saved payment method
- ✅ Booking confirmation must be displayed upon successful payment
- ✅ System should validate expired or invalid cards and display error messages
- ✅ A booking confirmation email must be sent after successful transaction
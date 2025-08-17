# Requirement Analysis in Software Development.
The Requirement Analysis Project focuses on crafting a comprehensive foundation for software development by documenting, analyzing, and structuring requirements. Through a series of well-defined tasks, learners will create a detailed blueprint of the requirement analysis phase for a booking management system. This project simulates a real-world development scenario, emphasizing clarity, precision, and structure in defining requirements to set the stage for successful project execution.


## What is Requirement Analysis?
📌 Requirement Analysis in Software Development Lifecycle (SDLC)
🔎 What is Requirement Analysis?

Requirement Analysis is the first and one of the most crucial phases of the Software Development Life Cycle (SDLC).
It involves gathering, analyzing, documenting, and validating the needs and expectations of stakeholders (clients, users, business managers, developers, etc.) for a software system.

The primary goal is to clearly define what the system should do (functional requirements) and how well it should perform (non-functional requirements), so developers can design and build a system that meets user needs.

## 📌 Key Activities in Requirement Analysis

* Requirement Gathering

Collecting needs from stakeholders using interviews, surveys, observation, questionnaires, brainstorming sessions, or workshops.

* Requirement Elicitation

Digging deeper into the requirements to uncover hidden, conflicting, or unclear needs.

* Requirement Analysis & Prioritization

Reviewing requirements for feasibility, consistency, and prioritizing them based on importance and constraints (budget, time, resources).

* Requirement Documentation (SRS – Software Requirement Specification)

Creating a formal document called the SRS that lists all functional and non-functional requirements.

This serves as a blueprint for design, development, and testing teams.

* Requirement Validation

Ensuring the documented requirements accurately reflect stakeholder needs and are complete, realistic, and testable.

## 🏗️ Types of Requirements

* Functional Requirements

Describe what the system should do.

Example: “The system must allow users to log in with a username and password.”

* Non-Functional Requirements

Define how the system should perform.

Example: “The system should respond to user requests within 2 seconds.”

## Why is Requirement Analysis Important?
### 🌍 Importance of Requirement Analysis in SDLC

* Foundation for Development

Provides a clear roadmap for developers, reducing ambiguity and misunderstandings.

* Reduces Rework and Costs

Errors in requirements, if discovered later (in design or testing), are very expensive to fix. Proper analysis prevents costly mistakes.

* Improves Communication

Serves as a bridge between stakeholders and the technical team, ensuring everyone is on the same page.

* Ensures User Satisfaction

Captures the actual needs of end-users, leading to a product that solves their problems effectively.

* Basis for Testing

Test cases are designed based on the requirements. If requirements are unclear, testing will also be flawed.

* Supports Project Planning

Helps estimate time, cost, and resources needed for development.

### ✅ Example in Practice

Imagine building an e-commerce website:

Functional Requirement: Users should be able to add products to a shopping cart and proceed to checkout.

Non-Functional Requirement: The system should handle 10,000 concurrent users during peak sales without crashing.

If these are not clearly analyzed and documented, developers might build a system that works for basic needs but fails under real-world conditions.

## Key Activities in Requirement Analysis.
*Some key activities in requirement analysis are:*
### Requirement Gathering

   * Definition: The initial step where requirements are collected from stakeholders (clients, users, managers, etc.).
    
   * Goal: Understand stakeholder expectations clearly.
    
   * Methods: Interviews, surveys, brainstorming, questionnaires.
    
   * Importance: Poor gathering leads to incomplete or unclear requirements.
    
   * Example: Asking users of an e-commerce site if they need product search, shopping cart, and order tracking.

### Requirement Elicitation

  * Definition: Goes beyond gathering by extracting hidden or unclear requirements.
    
  * Goal: Ensure no critical requirement is missed.
    
  * Methods: Workshops, prototyping, observation, role-playing.
    
  * Importance: Stakeholders may not always express what they really need.
    
  * Example: User says “fast login” → elicitation uncovers they actually want Google or Facebook login options.

### Requirement Documentation

  * Definition: Recording requirements in a structured format for reference.
    
  * Goal: Create a single source of truth for developers, testers, and stakeholders.
    
  * Deliverable: Software Requirement Specification (SRS), user stories, or backlog items.
    
  * Importance: Prevents miscommunication and scope creep.
    
  * Example: Documenting that “The system shall allow users to reset passwords via email.”

### Requirement Analysis and Modeling

  * Definition: Examining requirements for feasibility, consistency, and completeness, then modeling system behavior.
    
  * Goal: Ensure requirements are practical and achievable.
    
  * Techniques: Use-case diagrams, data flow diagrams (DFDs), UML models.
    
  * Importance: Helps identify conflicts or technical challenges early.
    
  * Example: Drawing a use-case diagram showing how a customer interacts with an online booking system.

### Requirement Validation

  * Definition: Checking that requirements truly reflect stakeholder needs.
    
  * Goal: Confirm correctness and alignment with business objectives.
    
  * Methods: Reviews, walkthroughs, stakeholder feedback, prototyping.
    
  * Importance: Catches mistakes early, reducing costly fixes later.
    
  * Example: Showing a working prototype of a booking system to stakeholders before coding begins.

  ### In Summary:  

   * Requirement Gathering → Collect what stakeholders want.
    
   * Requirement Elicitation → Uncover hidden/implicit needs.
    
   * Requirement Documentation → Record requirements clearly (SRS).
    
   * Requirement Analysis & Modeling → Check feasibility & model system behavior.
    
   * Requirement Validation → Confirm requirements are correct before coding.

### Use Case Diagrams  

**What are Use Case Diagrams?**  
Use Case Diagrams are part of UML (Unified Modeling Language) used in **Requirement Analysis** to visually represent the interaction between **actors (users or systems)** and the **functionalities (use cases)** of a system.  

**Benefits of Use Case Diagrams:**  
- Provide a **clear visual understanding** of system functionality.  
- Help in identifying **actors and their roles** in the system.  
- Act as a **communication tool** between stakeholders, analysts, and developers.  
- Ensure that **requirements are captured correctly** before moving to design and development.  
- Serve as a **blueprint for test case creation** during validation.  

---

#### Conclusion

Requirement Analysis is the cornerstone of successful software development. It ensures that software is built right the first time, aligns with stakeholder expectations, minimizes risks, and optimizes cost and time.
Without a thorough requirement analysis, projects are highly likely to face scope creep, budget overruns, delays, and dissatisfied users.

## Acceptance Criteria  

**Acceptance Criteria** are the conditions that a software product must satisfy to be accepted by the user, customer, or other stakeholders. They are written in clear, simple language and define the boundaries of a user story or requirement.  

### Importance of Acceptance Criteria in Requirement Analysis  
- **Clarity of Scope**: Clearly defines what is “done,” reducing ambiguity.  
- **Alignment**: Ensures developers, testers, and stakeholders have the same understanding of a feature.  
- **Testability**: Provides a basis for creating test cases and verifying functionality.  
- **Quality Assurance**: Helps ensure the product meets user needs before release.  
- **Traceability**: Links business needs with system functionality, aiding requirement validation.  

### Example – Checkout Feature (Booking Management System)  

**User Story**:  
_As a customer, I want to complete my booking through a checkout process so that I can confirm my reservation and make payment._  

**Acceptance Criteria:**  
- ✅ The system should display a summary of selected booking details (dates, property, price, taxes).  
- ✅ The customer should be able to select a payment method (credit card, PayPal, etc.).  
- ✅ The system must validate payment details before processing.  
- ✅ An error message should appear if payment fails or details are invalid.  
- ✅ On successful payment, the system should generate a booking confirmation number.  
- ✅ A confirmation email must be sent to the customer with booking details.  
- ✅ The booking record should be stored in the system for future reference.  

---


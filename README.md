# requirement-analysis
# What is Requirement Analysis?

**Requirement Analysis** is the process of gathering, examining, documenting, and validating the needs and expectations of stakeholders for a software system. It turns ideas, business goals, and user needs into clear, verifiable, and prioritized requirements that guide design, development, and testing.

### Key Activities
- **Elicitation:** Collect information from stakeholders using interviews, workshops, surveys, observation, and prototyping.
- **Analysis & Refinement:** Clarify and resolve ambiguities, identify conflicts or gaps, and refine requirements into actionable items.
- **Specification:** Produce formal artifacts such as a System Requirements Specification (SRS), user stories, use cases, and acceptance criteria.
- **Validation:** Confirm requirements with stakeholders to ensure they reflect real needs and are feasible.
- **Requirement Management:** Track changes, maintain traceability, and prioritize requirements throughout the project lifecycle.

### Types of Requirements
- **Functional Requirements:** Describe specific behaviors or functions (e.g., “Users can search listings by location and price”).
- **Non-Functional Requirements:** Describe system qualities like performance, security, usability, scalability, and reliability.
- **Business & Domain Rules:** Constraints and rules specific to the domain (e.g., cancellation policy, tax rules).

### Deliverables
- System Requirements Specification (SRS)
- User stories with acceptance criteria
- Use case diagrams and flowcharts
- Prioritized backlog / requirement list
- Traceability matrix

### Importance in the Software Development Lifecycle (SDLC)
1. **Aligns Stakeholders:** Ensures everyone — users, business owners, and developers — shares a common understanding of what will be built.
2. **Reduces Cost & Risk:** Finding and fixing requirement issues early prevents expensive rework later in design, development, or testing.
3. **Guides Architecture & Design:** Well-defined requirements inform technical decisions and architecture choices.
4. **Improves Testability & Quality:** Clear, testable requirements make it easier to create acceptance tests and QA plans, raising product quality.
5. **Supports Prioritization & Planning:** Helps Product Owners and teams focus on high-value features first, enabling incremental delivery and faster feedback.
6. **Enables Change Control:** Documented and traceable requirements simplify impact analysis when change requests arrive.

### Best Practices
- Involve real users and stakeholders early and continuously.
- Write requirements in clear, unambiguous, and testable language.
- Add acceptance criteria for each requirement.
- Distinguish “must-have” from “nice-to-have.”
- Maintain traceability from requirements → design → implementation → tests.

> Requirement analysis is the foundation of a successful software project — it defines *what* should be built, *why*, and *how success will be measured*.

## Why is Requirement Analysis Important?

Requirement Analysis plays a vital role in the **Software Development Lifecycle (SDLC)** because it lays the foundation for all subsequent phases. Without a clear understanding of what needs to be built, projects often face delays, cost overruns, or failure to meet user expectations.

Here are three key reasons why it’s critical:

1. **Prevents Miscommunication and Scope Creep**  
   Clearly defined and documented requirements ensure that all stakeholders — clients, developers, testers, and project managers — share the same understanding of the project goals. This alignment helps prevent misunderstandings, reduces scope creep, and ensures the final product matches expectations.

2. **Saves Time and Reduces Cost**  
   Identifying and resolving requirement issues early in the development process is significantly cheaper and faster than fixing them later in design, coding, or testing. Proper requirement analysis helps detect potential risks early, streamlining development and minimizing rework.

3. **Improves Quality and User Satisfaction**  
   When requirements are complete, consistent, and testable, developers can create solutions that meet real user needs. This results in higher product quality, better usability, and increased satisfaction among users and stakeholders.

> In essence, Requirement Analysis serves as the **blueprint** for software development — ensuring every feature, function, and user interaction is intentional, validated, and aligned with business goals.

## Key Activities in Requirement Analysis

Requirement Analysis involves several structured activities that ensure software requirements are clearly understood, documented, and validated before development begins. These activities help bridge the gap between stakeholder expectations and the technical implementation.

Here are the five key activities involved:

- **1. Requirement Gathering**  
  This involves collecting information about the system to be developed from various sources such as clients, end-users, and domain experts. Techniques like interviews, questionnaires, surveys, and document analysis are used to gather data about business needs and system goals.

- **2. Requirement Elicitation**  
  Elicitation focuses on understanding stakeholder needs and expectations in depth. It includes identifying the stakeholders, engaging them through brainstorming sessions, workshops, prototyping, or use cases, and clarifying unclear or conflicting requirements.

- **3. Requirement Documentation**  
  After gathering and eliciting requirements, they are documented in an organized and detailed manner. This documentation may take the form of a Software Requirement Specification (SRS), user stories, or use case diagrams — serving as a reference for developers, testers, and clients.

- **4. Requirement Analysis and Modeling**  
  This activity involves examining and structuring the gathered requirements to identify dependencies, conflicts, and priorities. Modeling techniques such as data flow diagrams (DFDs), entity-relationship diagrams (ERDs), and use case models help visualize system behavior and interactions.

- **5. Requirement Validation**  
  The final step ensures that all documented requirements are complete, consistent, and aligned with stakeholder needs. Validation may include reviews, walkthroughs, or prototyping to confirm that requirements are realistic, achievable, and testable before implementation begins.

> These activities collectively ensure that the software being developed meets user expectations, adheres to business goals, and provides a strong foundation for the rest of the SDLC.

## Types of Requirements

In software engineering, requirements are generally classified into two main types: **Functional** and **Non-functional**.  
Both are essential for defining what the system should do and how it should perform. Below are examples based on the **Booking Management Project** case study.

---

### 🧩 Functional Requirements

Functional requirements describe **what the system should do** — the specific behaviors, features, and functions that enable users to achieve their goals. These define the system’s **core functionality**.

**Examples for the Booking Management Project:**
- The system shall allow users to **create an account** and **log in** securely.
- The system shall enable users to **search for available properties** by location, date, and price range.
- The system shall allow hosts to **list new properties**, including images, descriptions, and pricing details.
- The system shall enable users to **book a property** and receive an automated confirmation message.
- The system shall allow users to **cancel a booking** and process refunds according to the cancellation policy.
- The system shall send **email or SMS notifications** for booking confirmations, cancellations, and reminders.
- The system shall allow administrators to **manage users, bookings, and property listings** through a dashboard.

Functional requirements are the **"actions"** of the system — what it must be capable of doing to meet user needs.

---

### ⚙️ Non-functional Requirements

Non-functional requirements define **how the system performs** its functions. They describe quality attributes such as performance, reliability, security, and usability that determine user satisfaction and system efficiency.

**Examples for the Booking Management Project:**
- **Performance:** The system should load search results within **3 seconds** under normal network conditions.
- **Scalability:** The system should support at least **10,000 concurrent users** without performance degradation.
- **Security:** All sensitive user data (e.g., passwords, payment details) must be **encrypted** in storage and during transmission.
- **Availability:** The system should have **99.9% uptime** to ensure reliable access to booking services.
- **Usability:** The interface should be **intuitive and responsive**, allowing users to complete a booking in **less than five steps**.
- **Compatibility:** The platform should be accessible on **both mobile and desktop browsers**.
- **Maintainability:** The codebase should follow **modular design principles**, making it easy to update or add new features.

Non-functional requirements focus on the **system’s quality and constraints** — how well it performs its tasks rather than what tasks it performs.

---

> Together, functional and non-functional requirements provide a complete understanding of both **what the system must do** and **how it must behave**, ensuring the product is both effective and user-friendly.

## Use Case Diagrams

A **Use Case Diagram** is a visual representation of how different users (**actors**) interact with a system to achieve specific goals.  
It helps in identifying **who** will use the system and **what** functionalities they will perform.  

Use Case Diagrams are an essential part of **Requirement Analysis** as they help in understanding the **functional scope** of a system and serve as a communication bridge between stakeholders and developers.

---

### 🎯 Benefits of Use Case Diagrams

- Provide a **high-level overview** of system interactions.
- Help stakeholders and developers **understand system functionality** clearly.
- Serve as a **foundation for writing detailed functional requirements**.
- Support **identification of primary actors and their goals**.
- Enhance **communication and collaboration** within the development team.

---

### 🧑‍💻 Use Case Diagram for Booking Management System

Below is the Use Case Diagram for the **Booking Management System**, showing the interactions between users (actors) and the main system features.

**Actors:**
- **Guest/User** – searches, books, cancels, and reviews properties.
- **Host** – lists, updates, and manages property listings.
- **Administrator** – oversees user accounts, bookings, and platform management.

**Use Cases:**
- Create Account / Login  
- Search for Properties  
- View Property Details  
- Book Property  
- Cancel Booking  
- Make Payment  
- Manage Listings (Host)  
- Manage Users and Bookings (Admin)  
- View Booking History  

---

### 🖼️ Use Case Diagram

![Use Case Diagram for Booking System](alx-booking-uc.png)



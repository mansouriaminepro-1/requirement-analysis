## The Requirement Analysis Project:
provides a structured approach to understanding and documenting software requirements. Through this project, learners will create a detailed blueprint of the requirement analysis phase for a booking management system. The focus is on clarity, organization, and precision, simulating real-world software development practices to lay a strong foundation for successful project execution.

## What is Requirement Analysis?

**Requirement Analysis** is the process of gathering, examining, and defining the needs and expectations for a software system. It identifies what the system should do, how it should behave, and under what constraints it must operate. This phase transforms stakeholder ideas and business needs into clear, testable, and prioritized requirements that guide design, development, and testing.

### Importance in the Software Development Lifecycle (SDLC)
Requirement Analysis is crucial because it:

- **Ensures clarity and understanding:** Aligns developers, stakeholders, and users on what the system should deliver.
- **Defines scope:** Prevents misunderstandings and scope creep by setting clear boundaries.
- **Saves time and cost:** Detects issues early, reducing expensive fixes later in the development process.
- **Supports quality assurance:** Provides the foundation for testing and verifying the software.
- **Reduces risk:** Identifies conflicts, ambiguities, and feasibility concerns early.
- **Aligns with business goals:** Ensures the final software meets user needs and organizational objectives.

## Why is Requirement Analysis Important?

Requirement Analysis plays a vital role in the Software Development Life Cycle (SDLC). Here are three key reasons why it is critical:

1. **Clarity and Shared Understanding**  
   By clearly defining what the software should do, requirement analysis ensures that developers, stakeholders, and users are all aligned. This reduces misunderstandings and sets a common vision for the project.

2. **Scope Management and Cost Efficiency**  
   Well-documented requirements help define the project’s boundaries and prevent scope creep. Catching errors or missing requirements early in the analysis phase reduces costly rework during later stages of development.

3. **Improved Quality and Risk Reduction**  
   Detailed and verified requirements provide a foundation for testing and quality assurance. They help identify potential conflicts, ambiguities, or feasibility issues early, reducing the risk of project delays or failure.

## Key Activities in Requirement Analysis

Requirement Analysis involves several essential activities to ensure that software requirements are accurate, complete, and actionable. The five key activities are:

- **Requirement Gathering**  
  Collect information about what the users, stakeholders, and business need from the system. This can involve interviews, surveys, questionnaires, and reviewing existing documentation.

- **Requirement Elicitation**  
  Engage with stakeholders to uncover their actual needs and expectations. Techniques include workshops, brainstorming sessions, observation, and prototyping to understand functional and non-functional requirements.

- **Requirement Documentation**  
  Clearly record all gathered and elicited requirements in a structured format. Common outputs include Software Requirements Specifications (SRS), user stories, and use case diagrams, making requirements understandable and traceable.

- **Requirement Analysis and Modeling**  
  Examine requirements for feasibility, consistency, and completeness. Use modeling techniques such as data flow diagrams, entity-relationship diagrams, and UML diagrams to visualize and organize requirements.

- **Requirement Validation**  
  Ensure that documented requirements accurately reflect stakeholder needs and business goals. This involves reviews, walkthroughs, inspections, and sign-offs to confirm correctness and readiness for the next SDLC phase.

## Types of Requirements

In the context of the hotel booking management system, requirements are categorized into two main types: **Functional Requirements** and **Non-Functional Requirements**. Each type ensures the system meets both user needs and quality standards.

### Functional Requirements

Functional requirements define the core features and actions the system must support. For the hotel booking management system, examples include:

- **User Registration and Authentication:** Users can create accounts, log in securely, and manage their profiles.  
- **Room Search and Filtering:** Users can search for hotels and rooms based on location, price, dates, ratings, and amenities.  
- **Booking Management:** Users can make new bookings, modify existing reservations, and cancel bookings, with real-time updates to room availability.  
- **Payment Processing:** The system supports multiple payment methods, including credit/debit cards, wallets, and online payment gateways.  
- **Review and Rating System:** Users can submit reviews and ratings for hotels after their stay.  
- **Admin Dashboard:** Administrators can manage hotels, rooms, bookings, payments, and generate operational reports.  

### Non-Functional Requirements

Non-functional requirements describe **how** the system performs its functions, focusing on quality, performance, and user experience. Examples specific to a hotel booking system include:

- **Performance:** Search results and booking confirmations should be returned within 2 seconds, even under high user load.  
- **Scalability:** The system must handle growth in users, hotels, and bookings, allowing easy horizontal scaling of servers.  
- **Security:** All user data, including personal details and payment information, must be encrypted and secured against unauthorized access.  
- **Reliability & Availability:** The system should be available 24/7 with minimal downtime, ensuring users can book or modify reservations at any time.  
- **Usability:** The interface should be intuitive, responsive, and accessible across web and mobile devices for a smooth booking experience.  
- **Maintainability:** The system should allow updates, bug fixes, and new features without disrupting ongoing bookings or data integrity.  
- **Compliance:** The system must comply with data privacy regulations (e.g., GDPR) and payment industry standards (e.g., PCI-DSS).  

## Use Case Diagrams

**Use Case Diagrams** are visual representations of the interactions between users (actors) and a system.  
They illustrate the functionality the system provides and how different users engage with it.  

In this project, the Use Case Diagram focuses on the **Booking Management System**, showing the main actors (Customer, Admin/Manager, and Payment System) and their interactions with the system.  

### Benefits of Use Case Diagrams
- **Visual clarity:** Provides a simple overview of how users interact with the system.  
- **Requirement validation:** Ensures all necessary system functionalities are identified.  
- **Improved communication:** Bridges understanding between developers, stakeholders, and end users.  
- **Project planning:** Defines scope and priorities by mapping core interactions.  

### Booking System Use Case Diagram
You can view the diagram here: [Booking System Use Case Diagram](https://drive.google.com/file/d/1OmXCtU5BmnmwEe95mbf3TesRUWMzx6p_/view?usp=sharing](https://drive.google.com/file/d/1ZMuTCD6Xk7Jyb69cPXV-J0jTv9YhhQSM/view?usp=sharing))


# Acceptance Criteria

### What Are Acceptance Criteria?

Acceptance criteria are specific conditions that a feature must fulfill for stakeholders to consider it complete. They are crucial in Requirement Analysis because they:

- Provide a clear understanding of expected functionality.
- Make features measurable and testable.
- Include both functional and non-functional requirements.
- Serve as a reference for quality assurance and validation.

### Example: Checkout Feature in Booking Management System

**Checkout Acceptance Criteria**

1. **Successful Checkout**  
   Guest provides valid information → Payment completed → Booking confirmed → Confirmation email delivered.

2. **Invalid Payment Details**  
   Expired or incorrect card → Display error message → Allow guest to retry payment.

3. **Payment Declined**  
   Card declined or insufficient funds → Notify guest → Provide retry option.

4. **Property Unavailable**  
   Selected property already booked → Prevent checkout → Show “Unavailable” message.

5. **Payment Gateway Failure**  
   Gateway timeout or error → Display appropriate message → Enable safe retry without duplicate charge.

6. **Refund Handling**  
   Booking canceled within the allowed refund period → Initiate refund → Notify guest of refund status.


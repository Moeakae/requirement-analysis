# requirement-analysis
This is for documenting, analysing and structuring requirements for software development
### What is Requirement Analysis?
-Focuses on crafting a comprehensive foundation for software development by documenting, analyzing, and structuring requirements
### Why is Requirement Analysis Important?
| Keys                      | Description
|---------------------------|------------------------------------------------------------------------------------------
| Requirement Gathering     | the process of identifying, documenting, managing the needs and expectations of system
| Requirement Documentation | a crucial process of creating a detailed and agreed-upon specification of what a software system should do and how it should perform
| Requirement Validation    | the process of ensuring that the software requirements, as documented in a SRS
### Key Activities in Requirement Analysis
| Keys                      | Activities
|---------------------------|-----------------------------------------------
| Requirement Gathering     | UNCOVERING ALL STAKEHOLDERS, CURRENT PROCESS MAPPING and UNDERSTANDING THE IMPACT
| Requirement Elicitation   | PREPARATION, NEGOTIATIONS and VERYFICATION
| Requirement Documantation | CREATING, COST EFFICACY, and EXECUTIVE SUMMERY
| Requirement Analysis AND Modeling| LISTING SECURITY, PRIVACY AND COMPLIANCE
| Requirenent Validation    | DEVELOPING, PERFORMING and IDENTIFYING
### Types of Requirements
|Fuctional Requirements                             |Non-fuctional Requirements
-defines what a system should do                    | -defines how the system should do

## Use Case Diagrams
Use Case Diagrams are part of the Unified Modeling Language (UML) and are used in requirement analysis to visually represent how users (actors) interact with a system. These diagrams help stakeholders understand the functional requirements of the system by showing the relationships between users and the various use cases (tasks) the system performs.
###  Benefits of Use Case Diagrams
- **Clarity**: Makes system behavior easy to understand.
- **Communication**: Helps bridge the gap between technical and non-technical stakeholders.
- **Scope Definition**: Defines the boundaries of the system and expected user interactions.
- **Requirement Validation**: Ensures all user needs are captured.

###  Use Case Diagram for ALX Booking System

Below is the use case diagram showing the main actors and their interactions with the booking system:

![https://drive.google.com/file/d/1jYlxe14qaM7pKcQHTrOG8b8W7MMB-n2X/view?usp=sharing](./alx-booking-uc.png)

#### 👤 Actors:
- **Guest**: Can search listings, view listing details, make bookings, and leave reviews.
- **Host**: Can create listings, manage bookings, and respond to reviews.
- **Admin**: Manages users, handles disputes, and oversees the system.

#### 🛠 Use Cases:
- **Search Listings**
- **View Listing Details**
- **Book Property**
- **Cancel Booking**
- **Leave Review**
- **Create Listing**
- **Edit Listing**
- **Manage Bookings**
- **Moderate Content**
- **Resolve Disputes**

## Acceptance Criteria
Acceptance Criteria are predefined conditions that a software product must meet to be accepted by the user, customer, or other stakeholders. These criteria are used during requirement analysis and are typically written in plain, non-technical language to ensure mutual understanding between developers and stakeholders.

###  Importance of Acceptance Criteria
- **Clarifies requirements**: Ensures the development team understands what is expected.
- **Defines scope**: Sets clear boundaries for what should and shouldn’t be developed.
- **Guides testing**: Provides a basis for writing test cases and validating features.
- **Reduces ambiguity**: Avoids misinterpretation of requirements by using measurable outcomes.

###  Example: Acceptance Criteria for Checkout Feature

**Feature**: Checkout Functionality for Booking System

**User Story**:  
As a guest, I want to complete my booking through a secure and user-friendly checkout process so that I can confirm my reservation.

**Acceptance Criteria**:
1. ✅ The user must be able to view a summary of their booking before payment.
2. ✅ The system must validate availability before proceeding to payment.
3. ✅ Payment methods must include at least credit card and PayPal.
4. ✅ An error message should display if payment fails.
5. ✅ The user receives an email confirmation after successful payment.
6. ✅ The booking is marked as “confirmed” in the database upon successful checkout.
7. ✅ The total cost must include all applicable fees and taxes.

These criteria will be used to validate the implementation of the checkout feature during development and testing.

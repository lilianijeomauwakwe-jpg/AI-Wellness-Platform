# User Stories & Acceptance Criteria

## AI Wellness Platform

### Translating Product Requirements into Deliverable Work

This document demonstrates how product requirements were translated into structured Agile work through user stories, acceptance criteria, estimation and sprint planning.

---

## User Story Framework

The product backlog was structured using standard Agile user stories:

> **As a [user], I want [capability], so that [benefit].**

This format helped connect product requirements with user outcomes and provided a consistent structure for backlog refinement and sprint planning.

---

## Backlog Structure

The initial product backlog contained **24 user stories** organized across five product epics:

| Epic | Product Area |
|---|---|
| 01 | User Onboarding |
| 02 | AI Diagnostics |
| 03 | Provider Directory |
| 04 | Appointment Booking |
| 05 | Notifications |

---

## Representative User Stories

The following examples demonstrate the type of requirements represented in the documented backlog. They are representative portfolio examples rather than verbatim copies of internal project tickets.

### User Onboarding

**User Story**

> As a user, I want to complete my onboarding information so that I can begin using the platform.

**Acceptance Criteria**

- Required onboarding information can be entered
- Required fields are validated
- The user can complete the onboarding flow
- Successful completion moves the user to the next stage of the experience

---

### AI Diagnostics

**User Story**

> As a user, I want to provide information about my symptoms so that I can receive an AI-assisted preliminary assessment.

**Acceptance Criteria**

- The user can provide the required symptom information
- The submitted information is processed by the relevant AI functionality
- The resulting response is presented clearly
- The experience provides appropriate next-step guidance

> This represents the documented product scope around an AI-powered preliminary diagnostic experience. It does not describe proprietary model architecture or clinical decision logic.

---

### Provider Directory

**User Story**

> As a user, I want to browse available healthcare providers so that I can identify an appropriate provider.

**Acceptance Criteria**

- Provider information can be displayed
- Users can browse the available provider directory
- Relevant provider information is presented clearly
- The user can proceed toward the appointment workflow

---

### Appointment Booking

**User Story**

> As a user, I want to book an appointment so that I can connect with a healthcare provider.

**Acceptance Criteria**

- The user can select an available provider
- Required appointment information can be provided
- The booking request can be submitted
- The user receives confirmation of the booking action

---

### Notifications

**User Story**

> As a user, I want to receive relevant notifications so that I remain informed about important activity.

**Acceptance Criteria**

- Relevant notification events are triggered
- Notifications contain appropriate information
- The notification experience is understandable to the user
- The notification workflow supports the intended user journey

---

## Acceptance Criteria

Acceptance criteria were used to establish a shared understanding between Product, Design, Engineering and QA.

They helped define:

- Expected functionality
- Completion conditions
- Validation requirements
- User outcomes
- QA expectations

For Sprint 2, detailed acceptance criteria were added across the sprint backlog to improve clarity and delivery readiness.

---

## Definition of Done

A Definition of Done was established as a shared standard for completed work.

The purpose was to ensure that a story was not considered complete simply because development activity had finished.

The Definition of Done supported alignment across:

- Development
- Design
- QA
- Product
- Project delivery

---

## Estimation

The team used **Fibonacci story-point estimation** supported by Planning Poker.

Story points represented relative effort and complexity and were used during sprint planning to help determine the work that could reasonably be committed to.

---

## Sprint Selection

### Sprint 1

**Goal:**

> Complete the user onboarding flow and core AI symptom-checker MVP.

**Planned effort:** 12 story points

### Sprint 2

**Goal:**

> Complete the provider directory, appointment booking flow, and push notification system.

**Planned effort:** 14 story points

---

## Requirements Traceability

The delivery flow connected user needs to completed work:

```text
User Need
   ↓
Product Requirement
   ↓
Epic
   ↓
User Story
   ↓
Acceptance Criteria
   ↓
Story Point
   ↓
Sprint
   ↓
Development
   ↓
QA / Validation
   ↓
Accepted Work

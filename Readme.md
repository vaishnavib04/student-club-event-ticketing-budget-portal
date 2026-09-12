# Student Club Event Ticketing & Budget Portal

A Software Engineering project for managing student club events, budget approval workflows, event registration, and QR-based ticket validation.

## Project Overview

The Student Club Event Ticketing & Budget Portal is designed to streamline the process of proposing and approving student club events, registering attendees, generating QR-based tickets, and validating tickets at the event venue.

The system supports different user roles and provides a structured multi-stage budget approval workflow.

## Key Features

- Event proposal creation and submission
- Event budget management
- Multi-stage budget approval
  - Faculty Coordinator
  - Finance Officer
  - Dean
- Proposal status tracking
- Revision and resubmission of proposals
- Event registration
- Unique QR ticket generation
- QR ticket validation at the venue
- Role-Based Access Control (RBAC)
- Notifications for budget proposal status changes
- Fast QR validation

## User Roles

The system involves the following roles:

- **Club Lead** – Creates and submits event proposals and manages event-related information.
- **Faculty Coordinator** – Reviews and approves or requests revisions to proposals.
- **Finance Officer** – Reviews and approves the financial aspects of proposals.
- **Dean** – Provides the final approval for the event budget.
- **Attendee / Student** – Registers for approved events and receives a QR ticket.
- **Campus Admin** – Validates QR tickets at the event venue.

## Budget Approval Workflow

The budget approval process follows a multi-stage workflow:

```text
Club Lead
    ↓
Faculty Coordinator
    ↓
Finance Officer
    ↓
Dean
    ↓
Approved
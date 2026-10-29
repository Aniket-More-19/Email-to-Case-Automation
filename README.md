
# Salesforce Email-to-Case Automation

## Overview

A Salesforce automation project that captures incoming customer emails as Cases, routes them to the appropriate support queue, and sends automated acknowledgment emails using Record-Triggered Flows.

The automation improves case intake, ensures customers receive confirmation with their Case Number, and provides fault handling for troubleshooting flow errors.

## Features

- **Email-to-Case:** Automatically creates Salesforce Cases from incoming customer emails.
- **Queue-Based Routing:** Assigns incoming Cases to the Product Issues queue.
- **Automated Acknowledgment:** Sends customers an email confirming receipt of their request and providing the Case Number.
- **Email Templates:** Uses Salesforce email templates to maintain consistent acknowledgment messages.
- **Fault Handling:** Captures flow errors and logs relevant details to support troubleshooting.

## Technologies Used

- Salesforce Email-to-Case
- Record-Triggered Flows
- Salesforce Email Templates
- Queues
- Flow Fault Paths and Error Logging

## Workflow

1. A customer sends an email to the configured support email address.
2. Salesforce Email-to-Case creates a Case from the incoming email.
3. The Case is routed to the **Product Issues** queue.
4. A Record-Triggered Flow runs when the Case is created.
5. The Flow sends an acknowledgment email containing the Case Number.
6. If an error occurs, the fault path captures error details for troubleshooting.

## Implementation

<img width="1470" height="888" alt="Screenshot 2026-10-29 at 5 04 00 PM" src="https://github.com/user-attachments/assets/c50d69b5-05e4-4fb3-a444-eb3dec1214d2" />

<img width="1470" height="889" alt="Screenshot 2026-10-29 at 5 04 45 PM" src="https://github.com/user-attachments/assets/d9d9dd36-60df-4636-b44f-0d3dccd809d5" />

<img width="1469" height="810" alt="Screenshot 2026-10-29 at 5 13 22 PM" src="https://github.com/user-attachments/assets/0fe5e8a3-e3cf-4e26-9976-58b1fd44b6ce" />

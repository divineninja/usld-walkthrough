# docs-uslocal-directory

## Introduction

This repository contains comprehensive documentation for the USLOCAL walkthrough project. The project demonstrates a complete workflow for registering listing information with two flexible payment processing options:

1. **Agent-Registered Payment**: The agent directly registers the customer's credit card information
2. **Customer-Self Payment**: The agent sends a secure payment link allowing customers to register their own card details

The documentation includes detailed step-by-step walkthroughs for both agent and customer workflows, complete with screenshots and instructions.

## Documentation Overview

### [Agent Walkthrough](./Agent.md)
Detailed guide for agents registering listing information, including:
- Login and dashboard navigation
- Listing registration process
- Customer information entry
- Payment option selection (direct registration or payment link)
- Real-time customer activity monitoring

### [Customer Onboarding Walkthrough](./Customer.md)
Complete customer registration and onboarding process, including:
- Introduction and service agreements
- ID verification and document upload
- Authorization and confirmation steps
- Welcome materials and access instructions

### [Customer Payment Link Walkthrough](./Customer%20Payment%20Link.md)
Customer workflow for self-registering payment information via secure link:
- Receiving and accessing the payment link
- Entering credit card details securely
- Confirmation and completion of registration

### [Agent Registration — New Flow Walkthrough](./Agent%20Registration%20-%20new%20flow.md)
Updated agent registration workflow using the unified 4-step wizard, including:
- 4-step registration wizard (Listing Information, Schedule, Customer Information, Summary)
- Payment plan selection during registration
- Real-time Payment Link Monitor with activity timeline
- Service agreement signing and payment authorization
- Credit card registration with billing information and authorization form
- Confirmation and welcome email sequence

## Summary

This documentation provides end-to-end guidance for implementing a secure, user-friendly listing registration system with multiple payment pathways. The walkthroughs ensure both agents and customers have clear, visual instructions for each step of the process, promoting efficient and compliant operations.

## Converting Markdown to DOCX

To convert the Markdown files to DOCX format, use [Pandoc](https://pandoc.org/installing.html). Run each command from the repository root.

```bash
# Agent walkthrough (original flow)
pandoc -o Docx/Agent.docx -f markdown -t docx Agent.md

# Agent Registration — New Flow
pandoc -o "Docx/Agent Registration - new flow.docx" -f markdown -t docx "Agent Registration - new flow.md"

# Customer onboarding
pandoc -o Docx/Customer.docx -f markdown -t docx Customer.md

# Customer payment link
pandoc -o "Docx/Customer Payment Link.docx" -f markdown -t docx "Customer Payment Link.md"
```

> **Note:** Pandoc does not embed local images by default. To include images in the DOCX output, ensure the working directory is the repository root when running the commands above, or use the `--resource-path` flag:
> ```bash
> pandoc -o "Docx/Agent Registration - new flow.docx" -f markdown -t docx \
>   --resource-path=. \
>   "Agent Registration - new flow.md"
> ```

---

*Last Updated: April 7, 2026*

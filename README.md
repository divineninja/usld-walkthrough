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

## Summary

This documentation provides end-to-end guidance for implementing a secure, user-friendly listing registration system with multiple payment pathways. The walkthroughs ensure both agents and customers have clear, visual instructions for each step of the process, promoting efficient and compliant operations.

## Converting Markdown to DOCX

To convert the Markdown files to DOCX format, use Pandoc. For example, to convert `Agent.md` to `Docx/Agent.docx`:

```bash
pandoc -o Docx/Agent.docx -f markdown -t docx Agent.md
pandoc -o Docx/Customer.docx -f markdown -t docx Customer.md
pandoc -o Docx/Customer Payment Link.docx -f markdown -t docx Customer Payment Link.md
```

Repeat this command for other Markdown files as needed, replacing `Agent.md` with the appropriate filename.

---

*Last Updated: February 25, 2026*

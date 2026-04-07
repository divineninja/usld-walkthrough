# Agent Registration - New Flow Walkthrough Guide

This guide walks through the updated agent workflow for registering listing information. The new flow uses a unified 4-step registration wizard followed by the payment process. Two payment options are available: the agent can send a payment link to the customer, or the agent can register the customer's credit card directly.

[Agent Login Page](https://dashboard.uslocaldirectory.com/agent)

---

## Part 1: Registration Wizard

### Step 1: Listing Information
![Listing Information](./Agent%20Registration%20-%20new%20flow/1.2%20registration-listing-information.png){width=600px}

**Context:** The agent begins the registration process by filling out the business listing details. The stepper at the top displays the four stages: Listing Information, Listing Schedule, Customer Information, and Summary.

**Key Elements:**
- 4-step progress stepper (01 Listing Information → 02 Listing Schedule → 03 Customer Information → 04 Summary)
- Business Name, Company email, and Phone number fields
- Categories & Services section (Category, Sub category, Tags, Services Offered)
- Address section (Street, City, State, Zip)
- Rich-text Description editor
- "Next" button to advance to the schedule step

**Instructions:**
1. Enter the business name, company email, and phone number.
2. Select the appropriate Category and Sub category from the dropdowns.
3. Add relevant Tags and Services Offered for the listing.
4. Fill in the full business address (Street, City, State, Zip).
5. Write a business description using the rich-text editor.
6. Click "Next" to proceed to the listing schedule.

---

### Step 2: Listing Schedule
![Listing Schedule](./Agent%20Registration%20-%20new%20flow/1.2%20registration-schedule.png){width=600px}

**Context:** The agent sets the business hours for the listing by configuring schedule entries for each day of the week.

**Key Elements:**
- Individual schedule cards for each day of the week (Monday through Sunday)
- Day selector dropdown per entry
- Time From and Time Till (HH:MM) pickers
- Delete icon to remove a day's schedule entry
- "Back" and "Next" navigation buttons

**Instructions:**
1. Review the pre-populated schedule entries for all seven days.
2. Adjust the Time From and Time Till values for each day as needed.
3. Remove any days the business is closed by clicking the delete icon on that card.
4. Click "Next" to proceed to the customer information step.

---

### Step 3: Customer Information
![Customer Information](./Agent%20Registration%20-%20new%20flow/1.3%20registration-customer-information.png){width=600px}

**Context:** The agent enters the customer's personal details and selects the appropriate payment plan for the listing subscription.

**Key Elements:**
- First name and Last name fields
- Email address field
- Language dropdown selector
- Payment Plan selector with available plan options (Free, PREMIUM, TRIAL, starter, Pro Premium, elite)
- "Back" and "Next" navigation buttons

**Instructions:**
1. Enter the customer's first name, last name, and email address.
2. Select the customer's preferred language from the dropdown.
3. Choose the appropriate Payment Plan by clicking the desired plan button.
4. Click "Next" to review the full summary.

---

### Step 4: Summary
![Summary](./Agent%20Registration%20-%20new%20flow/1.4%20registration-summary.png){width=600px}

**Context:** The agent reviews a consolidated summary of all entered information before proceeding to the payment step. Both the customer information and listing information are displayed together for final verification.

**Key Elements:**
- Customer information summary (name, email, language, selected payment plan)
- Listing information summary (business name, email, phone, categories, address, description)
- "Back" button to revise any information
- "Proceed to payment" button to advance to the payment step

**Instructions:**
1. Review all customer information for accuracy (name, email, language, payment plan).
2. Verify all listing details (business name, contact info, categories, address, description).
3. Click "Back" to return and correct any information if needed.
4. Once confirmed, click "Proceed to payment" to continue.

---

## Part 2: Payment Process — Payment Link to Customer

### Step 5: Payment Link Monitor
![Payment Link Monitor](./Agent%20Registration%20-%20new%20flow/2.%20payment-process-monitor.png){width=600px}

**Context:** After proceeding to payment and selecting the payment link option, the agent is taken to the Payment Link Monitor. This page displays the customer's information, current listing status, and an Activity Timeline that updates in real time as the customer interacts with the payment link.

**Key Elements:**
- Customer Information panel showing customer name, email, business name, and status
- Status indicator (initially shows "Pending")
- Activity Timeline with real-time event tracking
- "Send Introduction Email" and "Save" action buttons

**Instructions:**
1. Confirm the customer information displayed is correct.
2. Note the initial "Pending" status and the first activity entry "Listing Created" in the timeline.
3. Use "Send Introduction Email" to dispatch the introduction email to the customer.
4. Monitor this page for real-time activity updates as the customer interacts with the link.

---

### Step 5.1: Introduction Email Sent to Customer
![Introduction Email](./Agent%20Registration%20-%20new%20flow/2.1%20Email%20-%20Unlock%20Premium%20Visibility%20for%20your%20Business%20-%20Only%2050%24%3AMonth.png){width=600px}

**Context:** The system sends an introduction email to the customer's registered email address. The email outlines the US Local Directory Pro Premium Services, subscription benefits, and prompts the customer to review and sign the Service Agreement before any charges are processed.

**Key Elements:**
- Personalized greeting with the customer's name
- Description of Pro Premium Services and monthly rate ($50.00/month)
- List of included benefits (landing page, logo design, SEO, premium listing, photo gallery, review section, and more)
- Disclaimer that US Local Directory is not affiliated with 411locals, Yelp, Township, Ad IQ, or similar providers
- "Read Service Agreement" button (green) to proceed
- "Decline" button (red) to opt out

**Instructions:**
1. Confirm the email has been sent by checking the Activity Timeline on the Payment Link Monitor.
2. Advise the customer to check their inbox and review the email content.
3. Instruct the customer to click "Read Service Agreement" to proceed with registration.
4. The customer may click "Decline" to opt out; the agent will be notified via the Activity Timeline.

---

### Step 5.2: Real-time Activity — Introduction Link Opened
![Introduction Link Opened - Monitor Update](./Agent%20Registration%20-%20new%20flow/2.3%20Introduction-link-open.png){width=600px}

**Context:** As the customer interacts with the introduction email and proceeds through the service agreement, the Payment Link Monitor updates in real time. The agent can observe each action the customer takes, with timestamped events logged in the Activity Timeline. The status advances to "Pending Account Setup" once the service agreement is signed.

**Key Elements:**
- Updated status: "Pending Account Setup"
- Activity Timeline events (newest first):
  - **Service Agreement Signed** — includes page, viewed by, IP address, and message
  - **Service Agreement Link Clicked** — logs when the customer opens the agreement link
  - **Listing Created** — the original listing creation event
- "Creditcard Registration" button — becomes available once the service agreement is signed
- "Send Introduction Email" and "Save" buttons remain accessible

**Instructions:**
1. Monitor the Activity Timeline for real-time updates as the customer acts on the email.
2. Confirm the "Service Agreement Link Clicked" and "Service Agreement Signed" events appear.
3. Verify the status has advanced to "Pending Account Setup".
4. Once the service agreement is signed, click "Creditcard Registration" to proceed with card registration on behalf of the customer, or allow the customer to complete it via the link.

---

### Step 5.3: Customer View — Service Agreement
![Service Agreement](./Agent%20Registration%20-%20new%20flow/4.1%20Authorization-image-upload-and-signature.png){width=600px}

**Context:** After clicking "Read Service Agreement" in the introduction email, the customer is presented with the full Service Agreement. The customer must upload a valid government-issued ID, provide a digital signature, and accept the agreement before proceeding.

**Key Elements:**
- Full Service Agreement with all terms (subscription fee, automatic renewal, cancellation policy, disputes & chargebacks, refund policy, governing law)
- Signature section with customer full name, business name, email, billing frequency, and minimum term details
- Identity Verification section with ID document upload field
- Digital signature canvas
- "Accept Service Agreement" button (primary) and "Decline" button

**Instructions:**
1. The customer reads the complete Service Agreement carefully.
2. The customer uploads a valid government-issued ID (driver's license or state-issued ID).
3. The customer provides a digital signature in the signature canvas.
4. The customer clicks "Accept Service Agreement" to proceed.

> **Example Signed Document:** [Hollee_Bradford-Signed Service Agreement.pdf](./Agent%20Registration%20-%20new%20flow/Hollee_Bradford-Signed%20Service%20Agreement.pdf) *(example only)*

---

### Step 5.4: Customer View — Payment Authorization
![Payment Authorization Popup](./Agent%20Registration%20-%20new%20flow/4.2%20Authorization%20-%20popup%20for%20squareup.png){width=600px}

**Context:** After the customer signs the service agreement, a payment authorization popup appears prompting the customer to authorize the payment method. This step connects the signed agreement to the payment gateway (Square) before final submission.

**Key Elements:**
- "Payment authorization required" modal dialog
- Instructional text: "Click authorization button to proceed"
- "Authorize" button to confirm the payment authorization
- Underlying page still visible (service agreement with ID upload and signature)

**Instructions:**
1. The customer clicks "Authorize" on the popup to complete the payment authorization.
2. The authorization links the signed service agreement to the payment gateway.
3. Upon confirmation, the customer is redirected to the Thank You page.

---

### Step 5.5: Customer View — Thank You Page
![Thank You Page](./Agent%20Registration%20-%20new%20flow/2.4%20Thankyou-page.png){width=600px}

**Context:** After successfully signing the service agreement and authorizing the payment, the customer is shown a confirmation page acknowledging that the service agreement has been signed.

**Key Elements:**
- "Thank You!" heading
- Confirmation message: "We appreciate you using US Local Directory."
- Status message: "Service agreement signed successfully."

**Instructions:**
1. The customer sees the confirmation that their service agreement has been signed.
2. The agent's Payment Link Monitor updates to "Pending Account Setup" at this point.
3. The customer should expect a confirmation email with next steps.

---

## Part 3: Credit Card Registration

### Step 6: Credit Card Registration
![Credit Card Registration](./Agent%20Registration%20-%20new%20flow/3.1%20Payment-credit-card-registration.png){width=600px}

**Context:** The agent (or customer via the payment link) proceeds to register the credit card. This form accepts the cardholder name and card details for verification. A $1 hold is charged to the card for verification purposes and is refunded immediately.

**Key Elements:**
- "Name on Card" field
- Integrated card input row: card number, expiration date (MM/YY), CVV, and ZIP code
- "Register Card" button
- Note: "This will charge $1 to customer card for verification, and will be refunded right away."

**Instructions:**
1. Enter the cardholder's name exactly as it appears on the card.
2. Input the card number, expiration date, CVV, and ZIP code in the card details row.
3. Inform the customer that a $1 verification charge will be applied and immediately refunded.
4. Click "Register Card" to proceed.

---

### Step 6.1: Billing Information
![Billing Information](./Agent%20Registration%20-%20new%20flow/3.2%20credit-card-registration-billing-information.png){width=600px}

**Context:** The agent or customer fills in the complete billing information associated with the payment method. This information is required to complete the payment page and finalize the subscription.

**Key Elements:**
- Position / Title field
- First Name and Last Name fields
- Email address field
- Billing Phone Number field
- Billing Street Address, City, and Billing State fields
- "Continue" button at the bottom

**Instructions:**
1. Enter the cardholder's position/title within the company.
2. Provide the first and last name as it should appear on billing records.
3. Enter a valid email address for billing correspondence.
4. Fill in the billing phone number and complete billing address (street, city, state).
5. Click "Continue" to proceed to the final authorization form.

---

### Step 6.2: Credit Card Authorization Form
![Credit Card Authorization Form](./Agent%20Registration%20-%20new%20flow/3.3%20credit-card-registration.png){width=600px}

**Context:** The final step of the credit card registration displays the complete Credit Card Authorization Form. This form consolidates the business information, payment method details, authorization terms, identity verification, and customer signature for the agent's records.

**Key Elements:**
- Business Information section (business name, phone, email, address)
- Payment Method Information (cardholder name, position, masked card number, card type, expiration)
- Authorization Terms (amount, billing frequency, minimum commitment, and full terms)
- Identity Verification section with ID document upload
- Signature & Consent section with digital signature canvas
- Cardholder full name and date displayed below the signature
- "SUBMIT" button

**Instructions:**
1. Verify business information and payment method details are correct.
2. Review the Authorization Terms with the customer before proceeding.
3. Upload a valid government-issued ID document for identity verification.
4. Obtain and capture the customer's digital signature in the signature canvas.
5. Click "SUBMIT" to complete the credit card authorization.

> **Example Signed Document:** [Hollee_Bradford-Signed Credit Card Authorization.pdf](./Agent%20Registration%20-%20new%20flow/Hollee_Bradford-Signed%20Credit%20Card%20Authorization.pdf) *(example only)*

---

### Step 6.3: Confirmation Email
![Confirmation Email](./Agent%20Registration%20-%20new%20flow/3.4%20Email%20-%20confirmation-email.png){width=600px}

**Context:** After the credit card is registered and the service agreement is signed, the customer receives a confirmation email summarizing their subscription details. The email also requests identity verification before the account is fully activated.

**Key Elements:**
- Personalized greeting confirming receipt of signed documents
- Subscription Summary (Plan, Monthly Rate, Billing Frequency, Minimum Term, Start Date)
- "Action Required — Identity Verification" notice
- "Confirm Registration" button linking to the ID upload portal
- Contact information for support

**Instructions:**
1. Confirm the customer has received the email at their registered address.
2. Instruct the customer to review the subscription summary for accuracy.
3. Direct the customer to click "Confirm Registration" to complete the identity verification step.
4. Advise the customer to contact support@uslocaldirectory.com for any questions.

---

## Part 4: Account Activation

### Step 7: Welcome Email
![Welcome Email](./Agent%20Registration%20-%20new%20flow/4.3%20Email%20-%20Welcome%20Email.png){width=600px}

**Context:** Upon successful completion of the signed service agreement, credit card authorization, and identity verification, the customer receives a Welcome Email confirming their account is fully active. This email outlines what happens next and provides the customer's subscription details for reference.

**Key Elements:**
- Warm welcome confirming the account is now fully active
- Confirmation that signed documents and ID verification have been received
- "What Happens Next" section listing deliverables:
  - Custom landing page on usld.biz subdomain
  - Logo design and business branding
  - Premium directory listing and detailed listing page
  - SEO optimization for local search visibility
  - Photo gallery, review section, and interactive map
  - Full hosting and technical support
- Subscription Details (Plan, Rate, Billing, Minimum Term)
- Invitation to send additional assets (photos, descriptions, special offers)
- Signed documents attached for the customer's reference

**Instructions:**
1. Confirm the customer has received the Welcome Email.
2. Encourage the customer to send any assets they would like included on their listing page.
3. Let the customer know they will receive a follow-up notification when the landing page and live listing link are ready.
4. Provide the customer with the support contact (support@uslocaldirectory.com) for any questions or change requests.

---

## Workflow Summary

The new agent registration flow consolidates the listing setup into a structured 4-step wizard followed by a clear payment and authorization process:

1. **Listing Information** — Agent enters complete business details including categories, services, and address
2. **Listing Schedule** — Agent configures business hours for each day of the week
3. **Customer Information** — Agent enters customer details and selects the subscription Payment Plan
4. **Summary** — Agent reviews all information before proceeding to payment
5. **Payment Link Monitor** — Agent monitors the customer's real-time interactions with the payment link
6. **Introduction Email** — Customer receives and reviews the service introduction and agreement
7. **Service Agreement** — Customer reviews, signs, and authorizes the agreement
8. **Credit Card Registration** — Card details, billing information, and CC authorization form are completed
9. **Confirmation Email** — Customer receives subscription summary and ID verification request
10. **Welcome Email** — Customer account is activated and onboarding deliverables are confirmed

## Notes

- All screenshots represent the updated registration interface with the unified 4-step stepper.
- The Payment Plan selection is now part of the Customer Information step (Step 3) rather than a separate step.
- The Payment Link Monitor provides real-time activity tracking, allowing the agent to observe each customer interaction as it happens.
- The "Creditcard Registration" button on the monitor becomes available only after the customer has signed the service agreement.
- A $1 verification charge is applied during credit card registration and is immediately refunded.
- Signed documents (Service Agreement and Credit Card Authorization Form) are automatically generated and emailed to the customer upon completion.

## For Developers

When implementing or modifying this workflow:
- Ensure the 4-step stepper state persists across page refreshes
- Real-time monitor updates should use WebSocket or polling with appropriate fallback
- Payment Plan options displayed in Step 3 should be dynamically fetched and reflect current available plans
- The "Creditcard Registration" button on the monitor must only be enabled after confirming the service agreement is signed
- All signed PDF documents should be generated server-side and stored securely before emailing
- Implement proper validation on all form fields, especially card details and ID uploads

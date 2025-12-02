**Automated Lead Confirmation via Retell AI**

**Description: An outbound automation designed to reduce no-show rates for events. It triggers an AI phone call when a lead reaches a specific stage in the CRM.**

Key Features:

CRM Integration: Fetches contact details (Name, Phone, Event Time) from Kommo CRM.

API Orchestration: Sends a payload to the Retell AI API to initiate a phone call using a specific Agent ID and dynamic variables (LLM injection).

Pipeline Management: Automatically moves the lead to a "Processing" stage while the call is being attempted.

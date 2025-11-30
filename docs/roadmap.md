# Roadmap

## Week 1
-   Set up core project repository (frontend/backend).
-   Implement basic User Authentication (gym owner login/logout, registration).
-   Design and develop the Centralized Lead Inbox/Dashboard UI.
-   Create mock data service for leads.
-   Display mock leads in the Lead Inbox, showing name, source, and current status.
-   Implement a basic "View Lead Profile" page, displaying mock details (name, contact).
-   Add functionality to manually update a lead's status (e.g., "New" to "Contacted") for a clickable demo.
-   Integrate a placeholder for incoming messages (e.g., a simple form to simulate a WhatsApp/Instagram lead).

## Weeks 2-4
-   **Lead Ingestion & Integration Module:**
    -   Implement full WhatsApp Business API integration for receiving messages and sending replies.
    -   Implement full Instagram DM integration for receiving messages and sending replies.
    -   Ensure automated lead creation upon new inbound messages from integrated channels.
-   **Lead Management & CRM Module:**
    -   Complete Lead Profile Management: allow editing/viewing name, contact details, source, notes, and communication history.
    -   Develop customizable Lead Status Tracking: enable gym owners to define/reorder statuses (e.g., New, Contacted, Follow-up, Converted, Lost).
    -   Implement Manual Lead Addition for offline inquiries with all relevant fields.
-   **Notification & Reminder Engine Module:**
    -   Develop Automated Follow-up Reminders based on lead status (e.g., "Lead is 'Contacted' for 3 days, no activity - remind to follow up") or custom schedule.
-   **Dashboard & Reporting Module:**
    -   Enhance Centralized Lead Inbox with filtering (by status, source) and search capabilities.
    -   Implement Basic Reporting features: "Leads by Source" chart, "Conversion Rate" metric, and a "Lead Pipeline Overview" table/chart.
-   **User & Account Management Module:**
    -   Refine User Authentication and Authorization for a single gym owner account, ensuring security best practices.
-   **ML Service (future integration point):**
    -   Prepare data models and API endpoints for future ML integration (e.g., storing communication history, lead attributes) - *No ML implementation yet in this phase.*

## Month 2-3
-   **Infrastructure & Stability:**
    -   Implement robust error handling and logging across all modules.
    -   Optimize database queries and API endpoints for performance.
    -   Set up automated testing (unit, integration, end-to-end tests).
    -   Configure continuous integration/continuous deployment (CI/CD) pipeline.
    -   Implement basic security measures: input validation, secure API keys management, data encryption in transit/at rest.
-   **Polishing & User Experience:**
    -   Conduct comprehensive UI/UX review and implement improvements based on feedback.
    -   Ensure mobile responsiveness for the dashboard and lead management interfaces.
    -   Add user onboarding flows and in-app tooltips for key features.
    -   Implement toast notifications or similar for user feedback (e.g., "Lead saved successfully").
-   **Sellable Features & Initial Analytics:**
    -   Implement Automated Message Templates for quick responses within WhatsApp/Instagram communication.
    -   Develop an internal admin dashboard for monitoring system health and usage metrics.
    -   Prepare initial documentation for users and support.
    -   Refine reporting module to allow basic customization of date ranges for reports.

## Task Backlog
-   ML-driven Lead Prioritization (hot, warm, cold)
-   ML-driven Conversion Probability Score for each lead
-   Calendar Integration for booking trial sessions or appointments
-   Team Collaboration features (assign leads, internal notes)
-   Payment Gateway Integration for membership sign-ups
-   Advanced Analytics with custom report generation
-   SMS/Email integration for broader communication
-   Member Management (post-conversion tracking)
-   Two-factor authentication (2FA) for user accounts
-   Export lead data functionality (CSV, Excel)
-   Audit trail for lead activity
-   Dark mode UI option
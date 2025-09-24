**[Phase 7: Integration & External Access -- Real Estate
CRM]{.underline}**

1\. Named Credentials

-   Store Property Listing API or Government Land Registry API
    credentials securely for safe integrations.

2\. External Services

-   Connect with Mortgage/Loan Verification Services or Property
    Valuation APIs.

3\. Web Services (REST/SOAP)

-   REST callout: Fetch latest property valuation or ownership details
    from an external registry.

-   SOAP callout: Verify legal documents of a property.

4\. Callouts

-   Triggered when:

    -   A new Property is added → call external API to verify property
        details.

    -   A Deal is created → trigger loan/mortgage eligibility check.

5\. Platform Events

-   Publish event if:

    -   A Property Status changes (e.g., Available → Booked → Sold).

    -   A Site Visit is canceled and notify external
        calendar/integration system.

6\. Change Data Capture (CDC)

-   If Property details (price, availability) or Deal status (Pending →
    Closed) is updated → notify connected portals or partner systems.

7\. Salesforce Connect

-   Connect to external Property Management Databases if real estate
    listings are maintained outside Salesforce.

8\. API Limits

-   Monitor API calls/day especially when syncing with:

    -   Multiple Property Portals

    -   Bank Loan/Mortgage services

    -   Government verification systems

9\. OAuth & Authentication

-   If clients log in via a Real Estate Customer Portal, use OAuth for
    secure authentication.

-   Enable partner brokers to securely access shared property data.

10\. Remote Site Settings

-   Allow callouts to:

    -   External listing portals

    -   Government property verification domains

    -   Bank/Mortgage APIs

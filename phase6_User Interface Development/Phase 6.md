**[Phase 6: User Interface Development -- Real Estate CRM]{.underline}**

1.Lightning App Builder

-   Create a "Real Estate CRM" app to manage properties, clients, deals,
    and site visits.

2\. Record Pages

-   Property Page → Display key details (location, price, availability,
    property type).

-   Show related lists: Enquiries and Site Visits linked to the
    property.

-   Client Page → List of enquiries, visits, and deals related to the
    client.

3\. Tabs

-   Add Properties, Clients, Enquiries, Site Visits, and Deals tabs for
    easy navigation.

4\. Home Page Layouts

-   Dashboard with:

    -   Total Active Properties

    -   Upcoming Site Visits

    -   Conversion Funnel (Enquiries → Visits → Deals)

    -   Top Performing Agents

5\. Utility Bar

-   Quick actions:

    -   "New Enquiry" (fast client entry form).

    -   "Schedule Site Visit" shortcut.

6\. Lightning Web Component (LWC)

-   Component: Search Properties by filters (location, budget, property
    type, availability).

-   Display search results in a datatable with actions like *View
    Details*, *Book Visit*.

7\. Apex with LWC

-   Imperative Apex call → create new Enquiry or Site Visit record when
    a client shows interest in a property.

8\. Events in LWC

-   Child component (Search Form) → passes search criteria (budget,
    location) to parent.

-   Parent component (Results) → displays matching properties
    dynamically.

9\. Wire Adapters

-   Wire available Property records from Salesforce to display real-time
    listings in the UI.

10\. Imperative Apex Calls

-   On "Book Site Visit" → call Apex method to create a Site Visit
    record linked to property & client.

11\. Navigation Service

-   After booking a visit or finalizing a deal → navigate directly to
    the related Enquiry / Deal record page for seamless workflow.

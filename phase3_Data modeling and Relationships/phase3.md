**Data Modeling and Relationships phase**

1. Standard & Custom Objects
   1. Standard: Contact (buyers, sellers, agents).
   1. Custom: Property, Visit/Appointment, Deal.

2. Fields
   1. Property: Location, Price, Size (sq ft), Status (Available, Sold, Under Negotiation).
   1. Visit/Appointment: Date, Time, Notes.
   1. Deal: Deal Value, Closing Date, Deal Status.

3. Record Types
   1. Property: “Residential” vs “Commercial.”
   1. Deal: “Rent” vs “Sale.”

4. Page Layouts
   1. Property page: Shows related visits and deals.
   1. Deal page: Shows related property and customer details.
   1. Contact page: Shows properties visited, deals closed.

5. Compact Layouts
   1. Mobile (Property): Location, Price, Status.
   1. Mobile (Deal): Deal Value, Closing Date, Status.

6. Schema Builder
   1. Used to visualize relationships among Property, Deal, Contact, Visit.

7. Lookup vs Master-Detail
   1. Property ↔ Deal → Lookup (a deal is associated with a property, but property can exist without a deal).
   1. Deal ↔ Contact → Lookup (a deal links to a buyer/seller).
   1. Visit ↔ Property → Lookup (a visit relates to a property, but property exists independently).


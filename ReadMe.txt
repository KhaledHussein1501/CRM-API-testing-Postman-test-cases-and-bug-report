
Hello

this is the swagger link
https://qa-assignment.sortcrm.com/swagger/index.html

Testing Process:
1. Navigate to API Link.
2. Each endpoint is well documented, make sure to read the API documentation
carefully.
3. Register an account using your own email Under Account/Register endpoint.
4. Use the login endpoint to login and obtain a token so you can start testing.
5. Use the token to authorize swagger, before entering the value to swagger add a
prefix to it like this: Bearer $APIKEYVALUE
a. For example, if the token value was: 123435564664664
i. add it like this in the blue value box: Bearer 123435564664664


CRM Module User Stories:
A- Manage Contacts:
As an Employee I want to manage my contacts by creating, viewing, updating,
and deleting them, as well as adjusting their balance, so that I can maintain
accurate and up-to-date information for my business interactions.
Acceptance Criteria:

o View all my contacts with optional pagination and search
parameters.
o Request a contact using its unique ID.
o Create new contacts
o Update information for an existing contact.
o Remove contacts.
o Add a specific amount to a contact's balance.

B- Manage Invoices:
As an Employee I want to manage my invoices by creating, viewing, returning,
and paying them, so that I can maintain accurate financial records and handle
billing efficiently.
Acceptance Criteria:
o View a list of invoices associated with my account.
o I should receive the detailed information of any invoice if it exists.
o When I provide valid invoice details and submit a creation request for a
specific contact, then a new invoice should be created, associated with the
specified contact, and my contact's balance should be appropriately
adjusted, and the total profit of the invoice should be calculated.
o When I submit a request to return an existing invoice, Then the invoice
should be marked as returned, and the contact's balance should be
adjusted accordingly. Additionally, I should no longer be able to pay the
returned invoice.
o When I submit a payment request for a specific invoice with a valid
amount, Then the invoice should be marked as paid, and the payment
amount should be added to the contact's balance.
# Municipality-Management-System-Backend
A system for managing basic municipal services such as electricity, water, bills, complaints, maintenance, and licenses, in a flexible manner that makes it easier for citizens and the municipality.

# Technologies Used
Node.js

Express.js

MongoDB with Mongoose

Postman (for API testing)

JWT (Authentication & Authorization)

Multer (File Uploads)

Nodemailer (Emailing invoices)

xlsx (Handling Excel file imports)


# Roles:
1-citizen 

2-supervisor 

3-admin 

4-Municipality Accountant


# Each role has specific permissions:
**Citizen

Register and log in.

Submit maintenance requests.

Track the status of maintenance requests.

Submit complaints.

Track the status of complaints.

View and interact with other citizens' complaints.

Submit permit applications (building, commercial, etc.).

Upload the required documents for permits.

Track the status of permit applications.

Receive invoices via email.

View a list of their invoices with the status (paid/unpaid).

**Municipal Supervisor

Log in.

View all maintenance requests.

Update the status of maintenance requests (pending/in progress/completed).

View all permit applications.

Respond to permit applications with (done, missing documents, rejected).

**Municipal Accountant

Log in.

Add monthly invoices by uploading monthly Excel files for automatic invoice entry.

Update the status of invoices (paid/unpaid).

Send invoices to citizens via email.

View a list of invoices for all citizens.

**System Administrator

Log in.

View all maintenance requests.

View all complaints and suggestions.

Respond to complaints.

View all license applications and their status.

View and browse all invoices and reports.

View invoices for a specific user by ID number.

# **Functional Documentation**

This section explains how the system works from the point of view of both Employee and Admin users.

### **Employee**

#### Login / Register
- User logs in using username and password.
- After login, they see their dashboard (list of trips).
- JWT token is used to authenticate API calls.

#### Create Trip
- Click "Add Trip".
- Enter trip details: title, description, start date, end date.
- Trip is saved with status = Draft.
- Trips can be edited or deleted before submission.

#### Add Transactions
- Each trip can have multiple transactions (expenses).
- Each transaction includes:
  - Title  
  - Date & Time  
  - Category (Food, Transport, Lodging, Other)  
  - Amount  
  - Description (optional)
- User can edit or delete transactions while trip is still Draft.

#### Submit Trip
- When all transactions are added, user clicks Submit.
- Trip status becomes Submitted.
- Editing is locked after submission.
- Admin sees in dashboard.
- Admin updates trip status


### **Employee Flow Overview**

![Employee Reimbursement Flowchart](assets/images/emp-flow.svg){ width="50%" style="display:block; margin-left:auto; margin-right:auto;" }

---

### **Admin User**

#### Login
- Admin logs in to view dashboard.

#### View Submitted Trips
- All employee trips appear with status (Draft, Submitted, Approved, Rejected).
- Admin can open each trip to view its details and transactions.

#### Approve / Reject
- Admin can click Approve or Reject.
- On approval, trip status changes to Approved.
- On rejection, status changes to Rejected.


### **Admin Flow Overview**

![Admin Reimbursement Flowchart](assets/images/admin-flow.svg){ width="60%" style="display:block; margin-left:auto; margin-right:auto;"}

---

**Next:** [Business Use Cases](bus-sys-use.md)

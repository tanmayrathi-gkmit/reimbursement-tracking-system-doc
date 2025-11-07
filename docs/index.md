# **Overview**

Welcome to the documentation for the Reimbursement Tracking System.  


## **Introduction**
The Reimbursement Tracking System helps employees record their trip expenses and submit them for admin approval.  
Admins can review these expenses, approve or reject them, and the system keeps track of everything digitally.

#### **It mainly demonstrates**
- Basic CRUD operations
- Authentication and Authorization
- Clean API development using Django REST Framework
- A simple frontend (HTML, CSS, JavaScript)
- PWA setup for mobile compatibility


#### **Requirements**
- Login & Signup (User authentication)
- Roles: Employee and Admin
- Employees can create trips and add transactions (expenses)
- Admins can review and approve/reject submissions
- CRUD for trips and transactions
- Basic responsive frontend
- PWA for mobile usability


#### **Users**
| Role | Description | Access |
|------|--------------|--------|
| Employee | Regular user who creates trips and logs expenses. | Can create, edit, delete their trips and transactions, submit trips for approval. |
| Admin | Reviewer who approves or rejects trip reimbursements. | Can view all trips, approve or reject them, and manage users. |


#### **Tech Stack**
| Component | Technology Used |
|------------|-----------------|
| Backend | Django REST Framework |
| Frontend | HTML, CSS, JavaScript |
| Auth | JWT Authentication |
| Database | PostgreSQL |
| PWA | Manifest + Service Worker |

#### **Future Scope**
- Add **email notifications** so that when an employee submits a reimbursement, the admin gets an alert. Similarly, when the admin approves or rejects a request, an email notification is sent back to the employee.  
- Add a **receipt upload option** for employees when submitting expenses. These uploaded receipts can be stored securely using **AWS S3** for better scalability.
<!-- 
### **Quick Overview**
1. The employee starts by creating a trip and adding all their transactions or expenses related to it. They can view or edit the trip anytime before submitting it for approval.
2. The admin then checks the submitted trip and either approves or rejects the reimbursement request based on the details.
3. Both sides can view trip history anytime. -->
---

**Next:** [Functional Overview](functional.md)

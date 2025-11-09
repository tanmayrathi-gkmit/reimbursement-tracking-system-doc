# **Overview**

Welcome to the documentation for the Reimbursement Tracking System.  


## **Introduction**
The Reimbursement Tracking System helps employees record their reimbursement request and submit them for admin approval.  
Admins can review these reimbursement requests, approve or reject them, and the system keeps track of everything digitally.

#### **It mainly demonstrates**
- Basic CRUD operations
- Authentication and Authorization
- Clean API development using Django REST Framework
- A simple frontend (HTML, CSS, JavaScript)
- PWA setup for mobile compatibility


#### **Requirements**
- Login & Signup (User authentication)
- Roles: Employee and Admin
- Employees can create reimbursement requests and add expenses
- Admins can review and approve/reject submissions
- CRUD for trips and transactions
- Basic responsive frontend
- PWA for mobile usability


#### **Users**
| Role | Description | Access |
|------|--------------|--------|
| Employee | Regular user who creates reimbursement requests and logs expenses. | Can create, edit, delete their reimbursement request and expenses, submit reimbursement request for approval. |
| Admin | Reviewer who approves or rejects reimbursement request. | Can view all reimbursement requests, approve or reject them, and manage users. |


#### **Tech Stack**
| Component | Technology Used |
|------------|-----------------|
| Backend | Django REST Framework |
| Frontend | HTML, CSS, JavaScript |
| Auth | JWT Authentication |
| Database | PostgreSQL |
| PWA | Manifest + Service Worker |

#### **Future Scope**
- Add **email notifications** so that when an employee submits a reimbursement request, the admin gets an alert. Similarly, when the admin approves or rejects a request, an email notification is sent back to the employee.  
- Add a **receipt upload option** for employees when submitting expenses. These uploaded receipts can be stored securely using **AWS S3** for better scalability.
---

**Next:** [Functional Overview](functional.md)

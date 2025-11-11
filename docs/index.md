# **Reimbursement Tracking System – Overview**
Welcome to the documentation for the Reimbursement Tracking System.  
## **Introduction**
The Reimbursement Tracking System (RTS) is a digital platform designed to simplify and organize the reimbursement process within an organization. It enables employees to create, manage, and submit reimbursement requests for their expenses, while allowing administrators to review, approve, or reject these requests efficiently. By maintaining all data in a centralized system, the platform ensures transparency, accountability, and easier record-keeping of all reimbursement activities.

## **Problem Statement**
At present, Google Forms are used to manage reimbursement claims. This method has proven to be inefficient and disorganized. Employees are unable to view or edit their forms after submission, which leads to errors and a lack of flexibility. Moreover, Google Forms impose several limitations that make it difficult to record detailed expense information. On the administrative side, reviewing, approving, and tracking reimbursement requests is a cumbersome and time-consuming task. The lack of a centralized digital solution also complicates the auditing process, making it challenging to maintain a clear and accurate record of all reimbursement-related activities.

## **Proposed Solution**
To address these challenges, the Reimbursement Tracking System offers a fully digital and structured workflow for managing reimbursements. Employees can easily create reimbursement requests, record detailed expense information, and modify their requests while they remain in draft status. Once a request is submitted, it becomes available for the administrator to review and either approve or reject. The entire process is recorded within the system, ensuring that all requests and decisions are traceable and readily available for auditing. This not only simplifies the workflow for both employees and administrators but also enhances transparency, efficiency, and accountability throughout the reimbursement lifecycle.

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
- Implement email notifications to enhance communication between employees and admins. When an employee submits a reimbursement request, the admin will automatically receive an alert. Likewise, when the admin approves or rejects a request, the employee will be notified via email, ensuring timely updates and better workflow transparency. 
- Add an option for employees to upload supporting proofs or documents when submitting expenses. These files can be securely stored and managed using AWS S3, providing scalable storage, easy access, and improved auditing and verification capabilities.
---

**Next:** [Functional Documentation](functional.md)
